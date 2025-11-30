# Single Sign-On (SSO): The Master Key for Your Apps

## What is Single Sign-On?

Imagine if you had a different key for your house, your car, your office, and your mailbox. It would be a pain to carry them all around and remember which key opens which lock. Single Sign-On (SSO) is like having a single master key that securely unlocks everything you need.

In the digital world, SSO allows you to log in *once* with a single username and password and then gain access to multiple different applications and services without having to log in to each one separately.

## How it Works in Simple Terms

When you use SSO, you log into a central service first. This service then acts as a trusted gatekeeper. When you try to access another application:

1.  That application sees you haven't logged in, so it sends you back to the central SSO service.
2.  The SSO service sees that you've already authenticated and tells the application, "Yes, this person is legitimate. You can let them in."
3.  The application grants you access without ever asking for another password.

This is not only more convenient for you, but it's also more secure because it reduces the number of passwords you need to manage (and potentially forget or write down).

## The Microsoft Technology Involved

**Microsoft Azure Active Directory (Azure AD)** provides robust Single Sign-On capabilities. It acts as that central, trusted service. Once you sign in with your Azure AD account, you can get seamless access to:

-   Microsoft 365 services (Outlook, Teams, SharePoint).
-   Thousands of popular third-party cloud applications like Salesforce, ServiceNow, and Slack.
-   Internal company applications.

This creates a smooth and secure user experience across the entire organization.
