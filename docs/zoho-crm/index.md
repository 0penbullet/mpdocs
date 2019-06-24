# Zoho CRM

## Overview

Zoho CRM or Customer Relationship Management software is a cloud-based CRM service that helps you store and segment your customer data into different groups throughout the customer's journey. [Mageplaza Zoho CRM extension](https://www.mageplaza.com/magento-2-zoho-crm/) will help you integrate seamlessly with Zoho CRM to connect and synchronize data from Magento including **Customer, Product, Order, Invoice, Catalog Rules** to Zoho CRM with **Accounts, Contacts, Leads, Sales Orders, Invoices, Products, Campaigns** and vice versa. That will help create a smooth flow to maintain customer relationships and organize your business well. Also, data to Zoho CRM can be sent manually or automatically synchronized whenever there is any update. 


## How to download and install

- [Download Mageplaza Zoho CRM](https://www.mageplaza.com/magento-2-zoho-crm/)
- [How to Install](https://www.mageplaza.com/install-magento-2-extension/)


## How to use


**Zoho CRM**:

To **register** a Zoho CRM account, visit the [this link](https://www.zoho.com/crm/).

After registering an account, visit [this link](https://accounts.zoho.com/developerconsole) to get your **Zoho API** login information when clicking **Add Client ID**. There provided with **Client Id** information, **Client Secret** you need be able to connect with Zoho CRM.



Fill in the information below to **Create Zoho Client ID**.















After click **Create** button, you get the Zoho API including **Client Id, Client Secret**, you need to save this information so you can connect to Zoho CRM.



## How to Configure
### 1. Configuration

Login to the Magento Admin, choose `System > Zoho CRM Integration > Configuration`.

#### 1.1. General Configuration

- **Enabledv: Select **Yes** to activate the module and use the feature to support data synchronization from the Magento Objects to Zoho CRM.
- **Client Id**:
  - Enter the obtained ID in Zoho CRM into the **Client Id field** to connect to Magento.
  - If left blank or incorrectly entered Id, it will not synchronize data with Zoho CRM.
- **Client Secret**:
  - Enter the Client Secret obtained in Zoho CRM.
  - If left blank or fill incorrectly in the Client Secret, it will not synchronize data with Zoho CRM.
- **Get Access Token**: Admin can get Access Token to check the connection with Zoho CRM by clicking **Get Access Token** button. After that, you will see a successful notification and remind the admin to save configuration to apply change.


#### 1.2. Queue Schedule



- **Delete Queue Log After**:
   - Enter number of day in this field. System will delete Queue Log after the selected number of days. Example: You enter 5 days, then after 5 days. Queue Log will be deleted.
  - If empty, Log will no longer be deleted. 
  
- **Schedule**: Select the time to automatically send data to Zoho Module. Any Magento objects changes will be sent to Zoho Module, otherwise the unchnaged data will not be sent to Zoho Module anymore.

- **Number of Object Send per time**:
  - Enter the number of objects limit each time sending data to Zoho Module. Any pre-added queues will be prioritized to be sent to the  Zoho Module first.
  - If left blank, unlimited objects will be sent each time.
  
### 2. Manage Sync Rules

Login to the Magento Admin, choose `System > Zoho CRM Integration > Manage Sync Rules`.


#### 2.1. Grid

- Here, the Sync Rules information includes the **Name, Magento Object, Zoho Module, Website, Pending Queue fields, etc.**
- Click **Add new** button to create a new rule. After creating rules, you can choose **Edit** to edit rules. Also admin can **delete rules, change change status (Enable / Disable), filter, and so on.**
- Select **Add Data to Queue** if you want to add more data to Queue.


#### 2.2. Create Sync Rule

- **Please select Magento Object**: Select **Magento Object** to allow sending that object data to Zoho CRM.
- **Please select Zoho Module**: Here will display the **Zoho Module** corresponding to the selected **Magento Object**. For example: Magento Object is **Customer**, so the information corresponds from Zoho Module is **Account**.
- **Please select Website**: Select Website from which to get Magento Object data sending to Zoho Module. 
- After selecting the object, click **Next** to start filling at **Form create/ edit Sync Rule**


##### 2.2.1. General

- **Name**:
  - Enter the name of Sync rules
  - This is a required field
- **Status**: Select **Active** to rule active and synchronize data to Zoho Module.
- Data of Magento Object schools, Zoho Module, Website are taken according to the object information above before creating sync rules and can only change information when admin changes object information before creating.
2.2.2. Conditions






2.2.3. Mapping Fields

Zoho Contact Fields: Displays the fields managed by Zoho for this Module according to the selected Magento Object.
Magento Customer Fields:
Enter the fields of the corresponding magento object with the fields of Zoho Module.
Leaving this column blank will get the Default Value field applied to Zoho Module.
Description: Enter a description in the Description field. This section is only for admin note information with this rule, there is no value when processing data.
Insert Variables: Select the fields of the Magento object corresponding to the fields of Zoho Module. Here you can select multiple display field values ​​at the same time.
2.2.4. Queue Report
Here record Queu information




3. Manage Queue

This section records the information of Queue including Object information, Sync Rule, Magento Object, Zoho Module, .....
Here admin can Sync All or Sync with Zoho Modules such as Sync Account, Campaign Sync, Sync Contact, Sync Lead, Sync Order, Sync Invoice, Sync Product.
When you click on View, it will display Popup View Queue to see all information of each Queue. Select Delete to delete Queue and Resend to Resend Queue.
