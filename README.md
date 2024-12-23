# Microsoft Entra External ID Extension for Visual Studio Code

Integrating authentication into consumer and business applications is essential for securing resources and data. The Microsoft Entra External ID extension for Visual Studio Code simplifies this process by enabling you to create external tenants, configure sign-in experiences, and set up sample applications directly from Visual Studio Code.

## Features
- Create external tenants.
- Configure customized sign-in experiences for users.
- Bootstrap projects with preconfigured sample applications.
- Streamlined setup with automatic configuration of tenant and application IDs.

## Prerequisites
- [Visual Studio Code](https://code.visualstudio.com/)
- Microsoft Entra External ID extension ([Install it from the Marketplace](https://aka.ms/vscodequickstart/marketplace))

---

## Getting Started

### 1. Install the Extension
1. Download and install [Visual Studio Code](https://code.visualstudio.com/).
2. Open Visual Studio Code and navigate to the [Microsoft Entra External ID Extension](https://aka.ms/vscodequickstart/marketplace).
3. Install the extension.
4. Access the extension via the activity bar or from the Welcome page under **Help > Welcome > Walkthroughs > Get started with Microsoft Entra External ID**.

---

### 2. Set Up Your External ID
#### **Option 1: Set up a Free Trial**
1. From the extension, select **Set up a free trial**.
2. Sign in using a Microsoft account (MSA), personal account, or GitHub account.
3. Choose a location for your tenant data.
4. Provide a unique name for the tenant.
5. Monitor tenant creation progress in **View > Output**. The setup may take up to 30 minutes.

#### **Option 2: Use an Existing Subscription**
1. Select **Use my subscription**.
2. Choose a directory (tenant) associated with your Azure account.
3. Sign in and select a subscription and resource group.
4. Choose a location for tenant data and provide a unique tenant name.
5. Monitor progress in **View > Output**.

---

### 3. Set Up Sign-In for Your Users
1. Select **Set up sign-in and branding** in the extension walkthrough.
2. Sign in to the new tenant and select your sign-in method:
   - **Email and password**
   - **Email and one-time passcode**
3. Customize the sign-in layout:
   - Center-aligned or right-aligned
   - Background color
   - Company logo (245 x 36 px, max 50 KB, PNG/JPEG)

---

### 4. Try Out Your Sign-In Experience
1. Click **Run it now** in the walkthrough.
2. Use the browser tab to sign in or create a user account.
3. Sign-in attempts redirect to `JWT.ms`, where the token contents are displayed.
4. Verify created users in the Microsoft Entra admin center.

---

### 5. Set Up and Run a Sample App
1. In the extension, select **Set up sample app**.
2. Choose an app type (e.g., React, Node.js, ASP.NET Core, etc.).
3. Select a folder to download the sample repository.
4. Open the project in Visual Studio Code and build it:
   - **Run > Run without debugging** from the top menu.
5. The Microsoft Authentication Library (MSAL) configuration is pre-set to your tenant.

#### **Run the App**
1. Open the local host redirect URI from the app's `README.md` file in a browser.
2. Test the sign-in experience with the application.

---

### 6. Use the Explorer View
The Explorer view allows you to manage resources, access documentation, and explore configuration options.

#### **Manage Resources**
- View and manage tenants, applications, user flows, and branding.
- Right-click on resources to open them in the Microsoft Entra admin center.

#### **Getting Started**
- Access documentation or configuration pages directly from the extension's **Getting Started** section.

---

## Notes
- Tenant data location cannot be changed after setup.
- Logo file requirements:
  - Image size: 245 x 36 px
  - Max size: 50 KB
  - File type: PNG or JPEG
- Tenant creation may take up to 30 minutes.

---

## Resources
- [Visual Studio Code](https://code.visualstudio.com/)
- [Microsoft Entra External ID Extension](https://aka.ms/vscodequickstart/marketplace)
- [Microsoft Entra Admin Center](https://entra.microsoft.com/)

---

## Feedback and Support
If you encounter issues, use the **Help and Feedback** section in the extension or open an issue on this repository.

---
