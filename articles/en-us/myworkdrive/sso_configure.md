## Prerequisites

To configure Azure AD integration with MyWorkDrive, you need the following items:

- An Azure AD subscription
- A MyWorkDrive single sign-on enabled subscription

> **Note:**
> To test the steps in this tutorial, we do not recommend using a production environment.

To test the steps in this tutorial, you should follow these recommendations:

- Do not use your production environment, unless it is necessary.
- If you don't have an Azure AD trial environment, you can [get a one-month trial](https://azure.microsoft.com/pricing/free-trial/).

### Configuring MyWorkDrive for single sign-on

To configure single sign-on on MyWorkDrive side, download the **[Download Azure AD Signing Certifcate (Base64 encoded)](%metadata:certificateDownloadBase64Url%)**, **Azure AD Sign Out URL** : %metadata:singleSignOutServiceUrl%, **Azure AD SAML Entity ID** : %metadata:IssuerUri%, and **Azure AD Single Sign-On Service URL** : %metadata:singleSignOnServiceUrl% and configure them manually on MyWorkDrive server or copy and paste the Azure **App Federation Metadata URL** into your MyWorkDrive Server Admin Panel SAML Azure AD configuration screen. For additional information contact [MyWorkDrive support team](mailto:support@myworkdrive.com).

## Quick Reference

* **Azure AD Single Sign-On Service URL** : %metadata:singleSignOnServiceUrl%

* **Azure AD Sign Out URL** : %metadata:singleSignOutServiceUrl%

* **Azure AD SAML Entity ID** : %metadata:IssuerUri%

* **[Download Azure AD Signing Certifcate (Base64 encoded)](%metadata:certificateDownloadBase64Url%)**

## Additional Resources

* [How to integrate MyWorkDrive with Azure Active Directory](https://docs.microsoft.com/azure/active-directory/saas-apps/myworkdrive-tutorial)
