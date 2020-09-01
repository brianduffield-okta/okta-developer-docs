---
title: Create your Okta organization
---

You built an awesome app and you want to add user authentication to it. Let’s get you set up and working with Okta.

To start, you're going to need a free Okta developer edition org. An org is a private data space Okta creates for you, to hold all the resources you create to handle user authentication.

An org is free, and you can use it to handle authentication for up to 1,000 users. Later, if you need more capacity, you can upgrade to a paid org.

#### Create your org

<StackSelector snippet="create-org" />

#### Activate your org

After creating your org, check your email, and complete the following steps:

1. You receive an email to activate your account. The email gives you a temporary password and your Okta domain.

	Your Okta domain is important: It’s the base URL you use to access your org.  Authorization requests for users will be directed to an endpoint that has this as its base, and any Okta API endpoints you call will also have this as their base.

	Record your domain and your temporary password. Click the **Activate your account** button in the email.

2. You're prompted to sign in to your org. Supply your email address and the temporary password that was provided in the email.

3. You're prompted to change your password and to choose a security question to use if you forget your password. You're also prompted to choose a security image. The image is displayed whenever Okta prompts you to sign in, providing some assurance that it’s Okta asking.

#### Next steps

Your org is now created and usable. There's a survey you’re prompted to fill out about your role, goal, and software stack, which can help us support you.

A wizard launches to help you through basic setup for a few commons scenarios. You can choose to exit the wizard by clicking **Dashboard**.

In the next sections of this quick start, we won’t use the wizard, but rather the regular Developer Console menus that you could use on an ongoing basis to complete tasks.

The URL to access your org's Developer Console consists of your Okta domain plus `-admin`, e.g., `https://dev-133337-admin.okta.com`, but the domain itself doesn’t have the “-admin” part, e.g., `https://dev-133337.okta.com`.

You now have an org. You can create additional orgs at any time, and it's often useful to do so, to support separate development environments, for example, separating Development and Production.
