## Prerequisites

To configure Azure AD integration with Linkedin Lookup, you need the following items:

- An Azure AD subscription
- A Linkedin Lookup single-sign on enabled subscription

> **Note:**
> To test the steps in this tutorial, we do not recommend using a production environment.

To test the steps in this tutorial, you should follow these recommendations:

- Do not use your production environment, unless it is necessary.
- If you don't have an Azure AD trial environment, you can get a one-month trial [here](https://azure.microsoft.com/pricing/free-trial/).

### Configuring Linkedin Lookup for single sign-on

1. Go to **LinkedIn Admin Settings** section. Upload the XML file you downloaded from the Azure portal by clicking the **Upload XML file** option.

	![Configure Single Sign-On](./media/tutorial_linkedin_metadata_03.png)

2. Click **On** to enable SSO. SSO status changes from **Not Connected** to **Connected**

	![Configure Single Sign-On](./media/tutorial_linkedin_admin_05.png)

## Quick Reference

* **Azure AD Single Sign-On Service URL**: %metadata:singleSignOnServiceUrl%

* **Azure AD SAML Entity ID**: %metadata:IssuerUri%

* **[Download SAML Metadata file](%metadata:metadataDownloadUrl%)**


## Additional Resources

* [How to integrate Linkedin Lookup with Azure Active Directory](active-directory-saas-linkedinlookup-tutorial.md)

