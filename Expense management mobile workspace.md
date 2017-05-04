Expense management mobile workspace
-----------------------------------

### Overview of the Expense management mobile workspace

Many organizations require that a copy of a receipt be attached to a
travel-related or business-related expense report that an employee submits for
reimbursement. The **Expense management** mobile workspace lets users quickly
create new expense lines on the mobile device of their choice by using an
attached photo of a receipt. Alternatively, users can capture a photo of a
receipt and then attach it to an expense report later.

Specifically, the **Expense management** mobile workspace enables a user to:

-   Take a photo of a receipt, and upload it to Microsoft Dynamics 365 for
    Finance and Operations, Enterprise edition July 2017. A user can then attach
    that phot to an expense report later.

-   Upload a file as a captured receipt. A user can then attach that file to an
    expense report later.

-   Create a new expense line by using an attached receipt. A user can then add
    the line item to an expense report later, and submit for approval and
    reimbursement.

### Prerequisites

| **Prerequisite**                                                                                                                                                                                           | **Role**             | **Description**                                                                                                                                                                                                                                                   |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Microsoft Dynamics 365 for Finance and Operations, Enterprise edition July 2017 OR Microsoft Dynamics 365 for Operations version 1611 with platform update 3 or later                                      | System administrator | If you don’t already have Dynamics 365 for Operations deployed in your organization, your system administrator should see [Deploy a Microsoft Dynamics 365 for Operations demo environment](http://ax.help.dynamics.com/en/wiki/deploy-an-ax7-demo-environment/). |
| For **Microsoft Dynamics 365 for Operations version 1611**, KB 4019015 must be implemented. This KB is not needed for **Microsoft Dynamics 365 for Finance and Operations, Enterprise edition July 2017**. | System administrator | KB 4019015 (an X++ update or metadata hotfix) contains the **Expense management** mobile workspace. To implement KB 4019015, your system administrator must follow these steps:                                                                                   |
| The **Expense management** mobile workspace must be published to the Microsoft Dynamics 365 for Finance and Operations, Enterprise edition July 2017 or Microsoft Dynamics 365 for Operations mobile app.  | System administrator | Start Microsoft Dynamics 365 for Finance and Operations, Enterprise edition July 2017 or Microsoft Dynamics 365 for Operations in your browser.                                                                                                                   |

1.  Download KB 4019015 from Microsoft Dynamics lifecycle Services (LCS).

2.  [Install the metadata
    hotfix](https://ax.help.dynamics.com/en/wiki/configuring-and-installing-a-metadata-hotfix-package/).

3.  [Create a deployable
    package](https://ax.help.dynamics.com/en/wiki/create-and-apply-a-deployable-package/)
    that contains the **ApplicationSuite** and **ExpenseMobile** model, and then
    upload the deployable package to LCS.

4.  [Apply the deployable
    package](https://ax.help.dynamics.com/en/wiki/apply-a-deployable-package-on-a-dynamics-ax-system/)
    to your Dynamics 365 for Operations system.

5.  On the **System parameters** page, select **Manage mobile workspaces**.

6.  Select the **Expense management** workspace.

7.  Click **Publish mobile workspace**.

### Download and install the Microsoft Dynamics 365 for Operations mobile app

Download and install the Dynamics 365 for Operations mobile app from your mobile
app store.

-   For Android: [Dynamics 365 for Operations on the Google Play
    Store](https://play.google.com/store/apps/details?id=com.microsoft.dynamics365.operations.mobile)

-   For iPhone: [Dynamics 365 for Operations on the iTunes apps
    store](https://itunes.apple.com/us/app/dynamics-365-for-operations/id1180836730?mt=8)

### Sign in to the Microsoft Dynamics 365 for Operations mobile app

1.  Start the app on your mobile device.

2.  Enter your Microsoft Dynamics 365 for Finance and Operations, Enterprise
    edition July 2017 or Microsoft Dynamics 365 for Operations URL.

3.  Enter the company to sign in to. For example, enter **USMF**.

4.  The first time that you sign in, you’re prompted for the user name and
    password for your Microsoft Dynamics 365 for Finance and Operations,
    Enterprise edition July 2017 or Microsoft Dynamics 365 for Operations
    account. Enter your credentials.

5.  After you sign in, you see the available workspaces for your company. Note
    that if your system administrator publishes a new workspace later, you can
    pull to refresh the list of mobile workspaces.

### Capture a receipt by using the Expense management mobile workspace

1.  On your mobile device, select the **Expense management** workspace.

2.  Select **Capture receipt**.

3.  Select **Take photo** or **Choose image**.

4.  If you selected **Take photo**, follow these steps:

    1.  You’re taken to the camera on your mobile device, so that you can take a
        photo of the receipt. When you’ve finished taking a photo, click **OK**
        to accept the photo.

    2.  Optional: Enter a name for the photo, and enter any notes.

>   \-or-

>   If you selected **Choose image**, follow these steps:

1.  Select an image in the list.

2.  Optional: Enter a name for the image, and enter any notes.

3.  Select **Done**.

### Quick expense entry by using the Expense management mobile workspace

1.  On our mobile device, select the **Expense management** workspace.

2.  Select **Quick expense entry**.

3.  Select the category for the expense. You see a list of expense categories
    that are loaded into your app for offline use. By default, up to 50 items
    are loaded, but a developer can change this number. For more information,
    developers should see [Dynamics 365 for Operations mobile
    platform](http://ax.help.dynamics.com/en/wiki/mobile-development-handbook/).

>   If your category isn’t in the list, select **Search** to do an online search
>   in Microsoft Dynamics 365 for Finance and Operations, Enterprise edition
>   July 2017 or Microsoft Dynamics 365 for Operations. Search by expense
>   category, or switch to search by expense type.

1.  Enter the transaction date of the expense.

2.  Optional: Enter the merchant for the expense.

3.  Enter the amount of the expense.

4.  Select the currency of the expense. You see a list of the currency codes
    that are loaded into your app for offline use. By default, up to 400
    currencies are loaded, but a developer can change this number. For more
    information, developers should see [Dynamics 365 for Operations mobile
    platform](http://ax.help.dynamics.com/en/wiki/mobile-development-handbook/).

    If your currency isn’t in the list, select **Search** to do an online search
    in Microsoft Dynamics 365 for Finance and Operations, Enterprise edition
    July 2017 or Microsoft Dynamics 365 for Operations. Search by currency, or
    switch to search by name.

5.  Select to **Take photo** or **Choose image**.

6.  If you selected **Take photo**, you’re taken to the camera on your mobile
    device, so that you can take a photo of the receipt. When you’ve finished
    taking a photo, click **OK** to accept the photo.

>   \-or-

>   If you selected **Choose image**, select an image in the list.

1.  Select **Done**.
