---
title: 'Tutorial: Azure Active Directory integration with Projectplace | Microsoft Docs'
description: Learn how to configure single sign-on between Azure Active Directory and Projectplace.
services: active-directory
documentationCenter: na
author: jeevansd
manager: mtillman

ms.assetid: 298059ca-b652-4577-916a-c31393d53d7a
ms.service: active-directory
ms.component: saas-app-tutorial
ms.workload: identity
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.date: 06/29/2017
ms.author: jeedes

---
# Tutorial: Azure Active Directory integration with Projectplace

In this tutorial, you learn how to integrate Projectplace with Azure Active Directory (Azure AD).

Integrating Projectplace with Azure AD provides you with the following benefits:

- You can control in Azure AD who has access to Projectplace
- You can enable your users to automatically get signed-on to Projectplace (Single Sign-On) with their Azure AD accounts
- You can manage your accounts in one central location - the Azure portal

If you want to know more details about SaaS app integration with Azure AD, see [what is application access and single sign-on with Azure Active Directory](../manage-apps/what-is-single-sign-on.md).

## Prerequisites

To configure Azure AD integration with Projectplace, you need the following items:

- An Azure AD subscription
- A Projectplace single sign-on enabled subscription

> [!NOTE]
> To test the steps in this tutorial, we do not recommend using a production environment.

To test the steps in this tutorial, you should follow these recommendations:

- Do not use your production environment, unless it is necessary.
- If you don't have an Azure AD trial environment, you can get a one-month trial [here](https://azure.microsoft.com/pricing/free-trial/).

## Scenario description
In this tutorial, you test Azure AD single sign-on in a test environment. 
The scenario outlined in this tutorial consists of two main building blocks:

1. Adding Projectplace from the gallery
2. Configuring and testing Azure AD single sign-on

## Adding Projectplace from the gallery
To configure the integration of Projectplace into Azure AD, you need to add Projectplace from the gallery to your list of managed SaaS apps.

**To add Projectplace from the gallery, perform the following steps:**

1. In the **[Azure portal](https://portal.azure.com)**, on the left navigation panel, click **Azure Active Directory** icon. 

	![Active Directory][1]

2. Navigate to **Enterprise applications**. Then go to **All applications**.

	![Applications][2]
	
3. To add new application, click **New application** button on the top of dialog.

	![Applications][3]

4. In the search box, type **Projectplace**.

	![Creating an Azure AD test user](./media/projectplace-tutorial/tutorial_projectplace_search.png)

5. In the results panel, select **Projectplace**, and then click **Add** button to add the application.

	![Creating an Azure AD test user](./media/projectplace-tutorial/tutorial_projectplace_addfromgallery.png)

##  Configuring and testing Azure AD single sign-on
In this section, you configure and test Azure AD single sign-on with Projectplace based on a test user called "Britta Simon".

For single sign-on to work, Azure AD needs to know what the counterpart user in Projectplace is to a user in Azure AD. In other words, a link relationship between an Azure AD user and the related user in Projectplace needs to be established.

In Projectplace, assign the value of the **user name** in Azure AD as the value of the **Username** to establish the link relationship.

To configure and test Azure AD single sign-on with Projectplace, you need to complete the following building blocks:

1. **[Configuring Azure AD Single Sign-On](#configuring-azure-ad-single-sign-on)** - to enable your users to use this feature.
2. **[Creating an Azure AD test user](#creating-an-azure-ad-test-user)** - to test Azure AD single sign-on with Britta Simon.
3. **[Creating a Projectplace test user](#creating-a-projectplace-test-user)** - to have a counterpart of Britta Simon in Projectplace that is linked to the Azure AD representation of user.
4. **[Assigning the Azure AD test user](#assigning-the-azure-ad-test-user)** - to enable Britta Simon to use Azure AD single sign-on.
5. **[Testing Single Sign-On](#testing-single-sign-on)** - to verify whether the configuration works.

### Configuring Azure AD single sign-on

In this section, you enable Azure AD single sign-on in the Azure portal and configure single sign-on in your Projectplace application.

**To configure Azure AD single sign-on with Projectplace, perform the following steps:**

1. In the Azure portal, on the **Projectplace** application integration page, click **Single sign-on**.

	![Configure Single Sign-On][4]

2. On the **Single sign-on** dialog, select **Mode** as	**SAML-based Sign-on** to enable single sign-on.
 
	![Configure Single Sign-On](./media/projectplace-tutorial/tutorial_projectplace_samlbase.png)

3. On the **Projectplace Domain and URLs** section, perform the following steps:

	![Configure Single Sign-On](./media/projectplace-tutorial/tutorial_projectplace_url.png)

    In the **Sign-on URL** textbox, type a URL using the following pattern: `https://<company>.projectplace.com`

	> [!NOTE] 
	> This value is not real. Update this value with the actual Sign-On URL. Contact [Projectplace Client support team](https://success.planview.com/Projectplace/Support) to get this value. 
 
4. On the **SAML Signing Certificate** section, click **Metadata XML** and then save the metadata file on your computer.

	![Configure Single Sign-On](./media/projectplace-tutorial/tutorial_projectplace_certificate.png) 

5. Click **Save** button.

	![Configure Single Sign-On](./media/projectplace-tutorial/tutorial_general_400.png)

7. To configure single sign-on on **Projectplace** side, you need to send the downloaded **Metadata XML** to [Projectplace support team](https://success.planview.com/Projectplace/Support). They set this setting to have the SAML SSO connection set properly on both sides.

>[!NOTE]
>The single sign-on configuration has to be performed by the [Projectplace support team](https://success.planview.com/Projectplace/Support). You will get a notification as soon as the configuration has been completed.

> [!TIP]
> You can now read a concise version of these instructions inside the [Azure portal](https://portal.azure.com), while you are setting up the app!  After adding this app from the **Active Directory > Enterprise Applications** section, simply click the **Single Sign-On** tab and access the embedded documentation through the **Configuration** section at the bottom. You can read more about the embedded documentation feature here: [Azure AD embedded documentation]( https://go.microsoft.com/fwlink/?linkid=845985)

### Creating an Azure AD test user
The objective of this section is to create a test user in the Azure portal called Britta Simon.

![Create Azure AD User][100]

**To create a test user in Azure AD, perform the following steps:**

1. In the **Azure portal**, on the left navigation pane, click **Azure Active Directory** icon.

	![Creating an Azure AD test user](./media/projectplace-tutorial/create_aaduser_01.png) 

2. To display the list of users, go to **Users and groups** and click **All users**.
	
	![Creating an Azure AD test user](./media/projectplace-tutorial/create_aaduser_02.png) 

3. To open the **User** dialog, click **Add** on the top of the dialog.
 
	![Creating an Azure AD test user](./media/projectplace-tutorial/create_aaduser_03.png) 

4. On the **User** dialog page, perform the following steps:
 
	![Creating an Azure AD test user](./media/projectplace-tutorial/create_aaduser_04.png) 

    a. In the **Name** textbox, type **BrittaSimon**.

    b. In the **User name** textbox, type the **email address** of BrittaSimon.

	c. Select **Show Password** and write down the value of the **Password**.

    d. Click **Create**.
 
### Creating a Projectplace test user

In order to enable Azure AD users to log into Projectplace, they must be provisioned into Projectplace. In the case of Projectplace, provisioning is a manual task.

**To provision a user account, perform the following steps:**

1. Log in to your **Projectplace** company site as an administrator.

2. Go to **People**, and then click **Members**.
   
    ![People](./media/projectplace-tutorial/ic790228.png "People")

3. Click **Add Member**.
   
    ![Add Members](./media/projectplace-tutorial/ic790232.png "Add Members")

4. In the **Add Member** section, perform the following steps:
   
    ![New Members](./media/projectplace-tutorial/ic790233.png "New Members")
   
    a. In the **New Members** textbox, type the email address of a valid AAD account you want to provision into the related textboxes.
   
    b. Click **Send**.

   An email including a link to confirm the account before it becomes active is sent to the Azure Active Directory account holder.

>[!NOTE]
>You can use any other Projectplace user account creation tools or APIs provided by Projectplace to provision AAD user accounts.

### Assigning the Azure AD test user

In this section, you enable Britta Simon to use Azure single sign-on by granting access to Projectplace.

![Assign User][200] 

**To assign Britta Simon to Projectplace, perform the following steps:**

1. In the Azure portal, open the applications view, and then navigate to the directory view and go to **Enterprise applications** then click **All applications**.

	![Assign User][201] 

2. In the applications list, select **Projectplace**.

	![Configure Single Sign-On](./media/projectplace-tutorial/tutorial_projectplace_app.png) 

3. In the menu on the left, click **Users and groups**.

	![Assign User][202] 

4. Click **Add** button. Then select **Users and groups** on **Add Assignment** dialog.

	![Assign User][203]

5. On **Users and groups** dialog, select **Britta Simon** in the Users list.

6. Click **Select** button on **Users and groups** dialog.

7. Click **Assign** button on **Add Assignment** dialog.
	
### Testing single sign-on

In this section, you test your Azure AD single sign-on configuration using the Access Panel.

When you click the Projectplace tile in the Access Panel, you should get automatically signed-on to your Projectplace application.
For more information about the Access Panel, see [Introduction to the Access Panel](../user-help/active-directory-saas-access-panel-introduction.md).

## Additional resources

* [List of Tutorials on How to Integrate SaaS Apps with Azure Active Directory](tutorial-list.md)
* [What is application access and single sign-on with Azure Active Directory?](../manage-apps/what-is-single-sign-on.md)



<!--Image references-->

[1]: ./media/projectplace-tutorial/tutorial_general_01.png
[2]: ./media/projectplace-tutorial/tutorial_general_02.png
[3]: ./media/projectplace-tutorial/tutorial_general_03.png
[4]: ./media/projectplace-tutorial/tutorial_general_04.png

[100]: ./media/projectplace-tutorial/tutorial_general_100.png

[200]: ./media/projectplace-tutorial/tutorial_general_200.png
[201]: ./media/projectplace-tutorial/tutorial_general_201.png
[202]: ./media/projectplace-tutorial/tutorial_general_202.png
[203]: ./media/projectplace-tutorial/tutorial_general_203.png

