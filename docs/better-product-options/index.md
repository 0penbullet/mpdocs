# Better Product Options

## Overview

Adding custom product options is one of the great ways to make stores more profitable and can serve customers on your store in a better way. With [Mageplaza Better Product Options Extension](https://www.mageplaza.com/magento-2-better-product-options/), you can create more options for any product via Customize Option. This extension allows the admin to easily create Customize Options Template for options such as **Quantity, Advanced Pricing, Weight, Image, Tooltips Description, Depend Option** for products while the current Core Magento only allows setting **Title, Price and SKU** for the product. Also, you can perform **Assign Customize Option** at the template with Product ID/ SKU. 

This extension is compatible with [Mass Product Action](https://www.mageplaza.com/magento-2-mass-product-actions/), [Mageplaza Quick View](https://www.mageplaza.com/magento-2-quick-view/) and [Configurable Products Preselect](https://www.mageplaza.com/magento-2-configurable-preselect/).


## How to download and install

- [Download Mageplaza Better Product Options](https://www.mageplaza.com/magento-2-better-product-options/)
- [How to Install](https://www.mageplaza.com/install-magento-2-extension/)

## How to Configure

From the Admin Panel, go to `Stores > Configuration > Mageplaza > Better Product Options > Configuration`

![](https://i.imgur.com/fj30IoU.gif)

### 1. General Configuration 
From the Admin Panel, go to `Stores > Configuration > Mageplaza Extensions > Better Product Options > General Configuration`

![](https://i.imgur.com/wnQzNYp.png)

- **Enable**: Select **Yes** to enable the **Better Product Options** module
- **Link Options by Default**:
  - If **Yes** is selected, the options will be default linked to the template. Admin can only change the option on the template, then it will apply to all products assigned with those options.
  - If **No** is selected, by default the options will not link to the template.
- **Result after removing template**:
  - If **Delete the linked products options** is selected, when the template is deleted, the options in the products linked to this template are also deleted
  - If you select **Unlink the current linked products options**, when the template is deleted, the options in the products linked to this template before will not be linked with that template anymore.


### 2. Product Option Templates Grid

From Admin Panel, go to `Stores > Product Options > Manage Product Options Templates`

![](https://i.imgur.com/JY0klue.png)

- Here shown all the **Product Options Templates**
- From **Product Options Templates Grid**, admin can capture basic information of **Product Options Templates** such as **ID, Name, Status, Number of Products, Number of Options, Created Date, Action**
- **Action**:
  - **Delete**: Delete Product Options Templates created
  - **Change Status**: Change the Status of **Product Options Template**. There are 2 template states that are **Enable** and **Disable**
  - **Edit**: Navigate to the Product Options Templates information page created earlier.
  - Also, admin can **Filter, Sort, Search** for Product Options Templates.

### 3. Create New/ Edit Template

From Admin Panel, go to `Stores > Product Options > Manage Product Options Templates > Create New Template/ Edit Template`

#### 3.1. General Tab

![](https://i.imgur.com/PVniRJg.png)

- **Name**: Set a name for template. This is a required field.
- **Description**: Add a description for the template.
- **Status**:
  - **Yes**: Active the template
  - **No**: Disable the template, then the options for this template will be hidden at the frontend/ cart.

#### 3.2. Customizable Tab Options

![](https://i.imgur.com/sSzIpVc.png)

- Admin can create multiple Options in the same template by selecting **Add Option**
- **Option Title**: Enter a title for the Option. This is a required field.
- **Option Type**: Select Option Type. This is a required field. There are many different Option Types as shown below:

![](https://i.imgur.com/Sob7xS1.gif)

- ***Option Type = Text (Field/ Area)***

![](https://i.imgur.com/5dJxMGB.png)

- ***Option Type = File***

![](https://i.imgur.com/PyDyJB3.png)

- ***Option Type = Date (Date & Time/ Date/ Time)***

![](https://i.imgur.com/JWBc0kl.png)
 
- ***Option Type = Select (Drop-down/ Radio Buttons/ Multiple Select/ Checkbox/ Visual Swatch/Text Swatch)***

![](https://i.imgur.com/GvIUef4.png)

- **Sort Order**: Present the priority of options showing of a product. Option with smaller sort order will be displayed first. This is a required field. 
- **Required**: Tick this checkbox so that this option is required. Otherwise, do not select.
- **Disable**:
  - Tick **Disable**, the option will be disabled and not displayed at the frontend/ cart.
  - If not tick **Disable**, the option is used and displayed normally.
- **Default Value**: Select the default value for this option.
- **Visual Swatch**: You can choose a color or an image to represent the value in the option. This field only appears when **Option Type = Visual Swatch/Text Swatch**.
- **Title**: Set the title for the values in each option.
- **Price**: Set a price for each value. There are 2 price types as **Fixed** and **Percent**.
- **SKU**: Set the SKU for each option/ value of the option.
- **Qty**: Set the limit number for each value in the option.
- **Weight**: Set the weight for each value in the option.
- After completing the fields above, click on the icon ![](https://i.imgur.com/vbxk6Wf.png) at the right of each option to open **Popup Configuration**, this popup contains all the information you need to configure for that option.
  - **Visibility Tab**:
  ![](https://i.imgur.com/KYrArun.png)
    - **Customer Group (s)**: Only selected customer groups can see this option.
    - **Store View (s)**: Only Store View(s) selected can display this option.
  - **Title Tab**:
  ![](https://i.imgur.com/gIVt9oT.png)
    - This tab only appears when the popup template is turned on.
    - Set title for option in each Store View. If left blank, the default title will be displayed.
  - **Tooltip Description Tab**:
  ![](https://i.imgur.com/JuqQAEN.png)
    - **Tooltips Description**: This is the tool for admin to enter the description for Tooltip of this option.
    - **Store View**: Select "Yes" to set the Tooltips Description for certain storeview. Select "No", it will display Tooltips Description by default.

  - **Dependency Tab**:
  ![](https://i.imgur.com/26iIUko.png)
    - **Dependency Type**: Select the dependency type for this option. There are two choices: **One of below options is filled** and **All of below options are filled**
    - **Dependency Options**: The display of this option will depend on the **Options, Operation and Values** configured.
    
    
- For options with **Type = Select Option (Drop-down/ Radio Buttons/ Multiple Select/ Checkbox/ Visual Swatch/ Text Swatch)**, you can click on the icon ![](https://i.imgur.com/vbxk6Wf.png) at the right of each option to open **Popup Configuration** which contains all the information you need to configure for that option.

![](https://i.imgur.com/0Nfx5K8.png)
![](https://i.imgur.com/HV9WoyO.png)
![](https://i.imgur.com/jAYofcs.png)

- **Title Tab**: Set title by each Store View for each option. If left blank, it will display the default title of this option.
- **Image Tab**: This is the place to customize images for each option.
- **Alt Text**: Enter Alt Text for the image
- **Update Product Preview Image**: Select "Yes" to update the image of the product when selecting this option. If you dont' want to pdate images, select "No".
- **Display along with Option Value**: Select the display position of the image associated with Option Value. This field is only displayed when **Option Type = Radio Buttons/ Checkbox**.
- **Display Tooltip when hover Option**: Select **Yes** to show the tooltip image when hovering over this option. This field only appears when **Option Type = Radio Buttons/ Checkbox/ Visual Swatch/ Text Swatch**.
- **Advanced Pricing**: This tab is for advanced price settings of this sub-option. Here admin can give a special price for the option, and set the applying date as well as set the option price for specific customer group.
- **Option Dependency**: This tab is used to configure the dependency of this sub-option on other options. The display of this Option will depend on the **Options, Operation and Values** configured. It is similar to the **Option Dependency** section of the Father Option.

#### 3.3. Manage Assign Products Tab

![](https://i.imgur.com/Em4J3qt.png)

- **Assign By**: Select one of two assignment types: **Product SKUs or Product IDs**
- **Product SKUs/ Product IDs**: The name of this field depends on the **Assign By** field. Enter one or more Product SKUs/ IDs, separated by commas. Then click **Preview** to see the list of products to assign.

#### 3.4. Edit Product Form
- From the Admin Panel, go to `Products > Catalog > choose a Product> Customizable Tab Options`

![](https://i.imgur.com/d3iKyGm.png)

- **Import Options**: Clicking on this link, you are redirected to a new page to import options from other products into the current product.

![](https://i.imgur.com/hMhNjK1.png)

- **Add Option**: When you click here, you will see a form to create a new option.

![](https://i.imgur.com/009VEoG.png)

- **Add Option From Template**: Clicking here will appear a popup to add options from the product options template chosen into this product.
  - In the options are taken from **Product Options Template**, there are some differences compared with the options created at the Product page as follows:

    ![](https://i.imgur.com/m766vud.png)
    - **Template**: This is name of the template which will be assigned to this option.
    - **Link Template**: Link this option to the template taken from **Better Options Template**.
      - If the template has many options, all options will be linked to template and vice versa.
      - If ticked this **Link Template** checkbox, all field of this option(s) will be disabled and unedited.
      - Unticked, it can be edited normally.
      
- **SKU Display Type**: Select the display type of the product SKU when viewing order details. There are 3 options as shown below.

![](https://i.imgur.com/LKyxjxn.png)
  - **Parent SKU**: Only display the SKU of the product, not the SKU of the option.
  - **Custom Option SKU**: Display only SKUs configured for each option.
  - **Both**: Display the selected SKUs of the product and the selected SKUs of the option.
  
![](https://i.imgur.com/jhdEmWJ.png)

#### 3.5. Mass action at the Product Grid

- In addition to assigning the **Product Options Template** to products right after editing/ create template, we can perform the assignment of templates for the product at the **Product Grid** as follows:
- From the Admin Panel, go to `Products > Catalog` then select one or more Product then choose `Actions> Assign Product Options Templates`

![](https://i.imgur.com/5MjWKSN.gif)

### 4. Import/Export Template
#### 4.1. Import
#### 4.2. Export


## Frontend

- Image of ***Option Type = Text*** on Product View Detail page

![](https://i.imgur.com/CbRLd3I.png)

- Image of ***Option Type = File*** on Product View Detail page

![](https://i.imgur.com/aHcQYLt.png)

- Image of ***Option Type = Select*** on Product View Detail page

![](https://i.imgur.com/RrAgxs4.png)

- Image of ***Option Type = Date Time*** on Product View Detail page

![](https://i.imgur.com/V883rOc.png)

- **Show image with option value**

![](https://i.imgur.com/1S3YZPa.png)
