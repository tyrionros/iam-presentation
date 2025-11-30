# Authorization: What You Are Allowed to Do

## What is Authorization?

Once you've proven who you are (authentication), authorization determines what you have permission to do. Think of it this way: after the security guard checks your ID, they give you a keycard. Authorization is about which doors that keycard can open. You might be allowed into the main office area, but not into the CEO's office or the server room.

## How it Works in Simple Terms

In the digital world, authorization ensures that users can only access the specific files, applications, and data they need for their job, and nothing more. This is also known as the "principle of least privilege."

-   A sales representative can access customer relationship management (CRM) software but cannot access financial reports.
-   An accountant can view and edit financial records but cannot modify the company's website.

This prevents both accidental mistakes and intentional misuse of sensitive information.

## The Microsoft Technology Involved

**Microsoft Azure Active Directory (Azure AD)** is also central to authorization on Microsoft's platform. It controls permissions through several features, most notably:

-   **Role-Based Access Control (RBAC):** Administrators don't assign permissions to each person individually. Instead, they create roles (like "Salesperson," "Manager," or "Accountant") with specific sets of permissions. When you are assigned a role, you automatically get all the permissions associated with it. This makes managing access across a large organization much more efficient and secure.
