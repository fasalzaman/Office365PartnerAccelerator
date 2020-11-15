## Identity Workshop

In this lab we are going to learn:


• Microsoft Secure Score : Microsoft Secure Score is a measurement of an organization's security posture, with a higher number indicating more improvement actions taken. It can be found at https://security.microsoft.com/securescore in the Microsoft 365 security center.
Following the Secure Score recommendations can protect your organization from threats. From a centralized dashboard in the Microsoft 365 security center, organizations can monitor and work on the security of their Microsoft 365 identities, data, apps, devices, and infrastructure.

Secure Score helps organizations to:

Report on the current state of the organization's security posture.
Improve their security posture by providing discoverability, visibility, guidance, and control.
Compare with benchmarks and establish key performance indicators (KPIs).

•	Self-Service Password Reset (SSPR) – As the Microsoft 365 admin, you can let people use the self-service password reset tool so you don't have to reset passwords for them. Less work for you!

•	Multifactor Authentication (MFA) – To provide an additional level of security for sign-ins, you must use multi-factor authentication (MFA), which uses both a password, which should be strong, and an additional verification method based on:
    * Something you have with you that is not easily duplicated, such as a smart phone.
    * Something you uniquely and biologically have, such as your fingerprints, face, or other biometric attribute.
The additional verification method is not employed until after the user's password has been verified. With MFA, even if a strong user password is compromised, the attacker does not have your smart phone or your fingerprint to complete the sign-in.

•	Conditional Access (CA) - The modern security perimeter now extends beyond an organization's network to include user and device identity. Organizations can utilize these identity signals as part of their access control decisions.
Conditional Access is the tool used by Azure Active Directory to bring signals together, to make decisions, and enforce organizational policies. Conditional Access is at the heart of the new identity driven control plane.

•	Azure AD Application Management (SHA and SSO) - Azure Active Directory is an Identity and Access Management (IAM) system. It provides a single place to store information about digital identities. You can configure your software applications to use Azure AD as the place where user information is stored.
Azure AD must be configured to integrate with an application. In other words, it needs to know what applications are using it as an identity system. The process of keeping Azure AD aware of these applications, and how it should handle them, is known as application management.
You manage applications on the Enterprise applications blade located in the Manage section of the Azure Active Directory portal.

## Check Microsoft Secure Score 

Navigate to https://security.microsoft.com and login with the admin credentials provided to you.

<kbd>![](images/security.jpg)</kbd>

Once you successfully login, select **Security Score** in the menu bar availabe in the left hand side to see all the Security Score related details of your tenant.

<kbd>![](images/securescore.jpg)</kbd>

After exploring all the details provided in the **overview** tab, select **Improvement actions** tab to see all the available options for improving our security score.

<kbd>![](images/actions.jpg)</kbd>

Now we are going to implement couple of these improvemnt actions.

## Configure Self-Service Password Reset (SSPR)

Follow the below steps to turn on self-service password reset for everyone in your Organization.

Navigate to https://admin.microsoft.com to open **Microsoft 365 Admin Center** and login with the admin credentials provided to you.

In the admin center, go to the **Settings** > **Org settings** page.

At the top of the Org settings page, select the **Security & Privacy** tab.

Select **Self-service Password Reset**.

<kbd>![](images/sspr.jpg)</kbd>

Under Self-service password reset, select **Go to the Azure portal to turn on self-service password reset**.

In the left navigation pane, select **User**s, and then, on the **Users | All users** page, select **Password reset**.

On the Properties page, **select All** to enable it for everyone in your business, and then select **Save**.

When your users sign in, they will be prompted to enter additional contact information that will help them reset their password in the future.

## Configure Multi-factor Authentiacation 


