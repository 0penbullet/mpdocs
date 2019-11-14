# Free Gifts

## Overview

[Mageplaza Free Gift Extension](https://mageplaza.com/magento-2-free-gifts/) helps store owners set up special promotions by offer free gifts when customers purchase the products on their stores. Admins not only can easily set up conditions for free gifts, they alsp could customize these rules with discount products, customer groups, quantity restrictions, etc. Therefore, customers are interested in shopping in your Magento store.

## Download and Install

- [Download Free Gift extension](https://mageplaza.com/magento-2-free-gifts/)
- [Installation guide](https://www.mageplaza.com/install-magento-2-extension/)


## How to Use

### Free Gift is auto-added if the product customer adds to the cart is qualified for conditions.

![Imgur](https://i.imgur.com/yQf5YO5.png)

### Customer can change the desired gift in the Gift list that the admin offer

![Imgur](https://i.imgur.com/WE3NDiv.png)

### Customer can add gift to cart right at Product Detail Page

![Imgur](https://i.imgur.com/HxFDR2B.png)

### When a product with free gift promotion is removed from the cart, their free gifts are removed as well

## How to Configure

From the Admin panel, go to `Marketing > Free Gifts`

![Imgur](https://i.imgur.com/0PncUVj.png)

### 1. Configuration

From the Admin panel, go to `Marketing > Free Gifts > Configuration`

![Imgur](https://i.imgur.com/dcYnvf8.png)

#### 1.1 General Configuration

![Imgur](https://i.imgur.com/BvDuZZt.png)

- **Enable**: Select **Yes** to make the extension active
- **Gift Layout**: Set how to show gift list in Frontend. There are 3 ways:
  - **List**
  ![Imgur](https://i.imgur.com/OhtAeeK.png)

  - **Grid**
  ![Imgur](https://i.imgur.com/sgQdx5C.gifv)

  - **Slider**
  ![Imgur](https://i.imgur.com/V1kUZW7.gifv)

- **Show Notice For Gift**:
  - Select **Yes** so that notice is displayed with the gift. Thereby, customer can easily distinguish gift from other products
  - Notice is displayed in minicart and **View Cart Page**
- **Notice Content**: Enter the notice content
- **Allow Customers to hide gift notification**: On the **View Cart Page**, there is a general notice for all gifts. Select **Yes** sto allow customer to turn off this notice
- **Gift Icon**:
  - Uploaded image will be used as Gift Icon and displayed in Frontend
  - Accept image files in jpg, png, gif, svg, etc.
  - If the admin does not upload the icon, there will be no Gift Icon displayed
  - We recommend using a 20x20 px icon
  
  
#### 1.2 Button Display

![Imgur](https://i.imgur.com/wg8ftHu.png)

- **Show At Cart Page**: applies to auto cart rules
  - Click **Yes** to display the add gift button on the **View Cart Page**
  - If **No** is selected, the gift is automatically added following the rule, and the customer cannot change to another Gift
- **Show At Cart Item**: applies to manual item rules
- Select **Yes** to display the **add gift** button on the **View Cart Page**, Customer needs to click the button to select the desired Gift
- If **No**, the **add gift** button is not displayed in View Cart Page. Customers can only add gifts from the **product detail page**
- In case the gift is not displayed in the **Product Detail Page** nor in the **View Cart Page**, which means that the rule not being applied.
- **Show Gifts At Product Page**: select **Yes** so that the gift list shown on the Product Detail pages meets the condition of the rules
- **Show Gift List As Popup**:
  - Select **Yes** to have the gift list displayed on the Product Detail page as a popup
  - If you select **No**, the gift list is displayed as a block
  
#### 1.3 Button Design

![Imgur](https://i.imgur.com/zR1MXRo.png)

- **Button label**:
  - The button label will be displayed in Frontend with the **Add Manual** mode
  - The content needs to show Customer that the Product they are buying is given additional gifts
- **Button Color**: Set the background color of the button add gift
- **Text Color**: Set the font color of the text entered by the admin in the Button label field
### 2. Manage Rule

#### 2.1 Grid

![Imgur](https://i.imgur.com/iayppAU.png)

- All the created rules are shown on this grid
- From the grid, admin can capture the basic information of the rule such as ID, Name, Status, Apply For, State, Website, Customer Group, Priority and Action can be performed with the Rule.
- In the Actions tab, the admin can perform the following actions:
  - **Delete**: Admin needs to tick the Rule you want to delete, then select **Delete** in the Actions box (upper left of the Grid) to delete. A confirmation box will appear, click **OK** to continue
  - **Change Status**: Admin needs to tick the Rule you want to change the status, then select `Change Status > Active/ Inactive` in the Actions tab (upper left side of the Grid) to change. A confirmation box will appear, select **OK** to confirm the change
- In the **Action** column, amin click on **Edit to Rule** to edit the information
- In addition, the admin can Filter, Change Store View, Hide/Show the Columns, Export Grid or Edit inline

![Imgur](https://i.imgur.com/yjknWhY.png)

#### 2.2 Add New/ Edit Form

- There are two main types of rules: Rules that apply to **Whole Cart** and rules that apply **Per Item**. Both rules have the same form, except for the **Condition** tab. The rule that applies to the whole cart will use the condition of the cart, the rule applied to each item will use the condition of the product

##### 2.2.1 General tab

- **Name**: Enter the name of the rule. This name is only displayed in the backend to distinguish it from other rules
- **Status**: Select **Enable** to active the rule
- **Description**: Enter a simple description of the rule
- **Website**: Rule is applied only to the selected website
- **Customer Group**: Choose customer group to apply the rule
- **Active From**: Choose the date to start applying the rule
- **Active To**: Select the date to finish the rule
- **Priority**:
  - For fifferent rules applying to one product, the rule that has the highest priority is applied first
  - 0 is the highest priority


##### 2.2.2 Condition

- **Condition for Cart**

![Imgur](https://i.imgur.com/2yEoLve.png)

- **Condition for Item (Product)**

![Imgur](https://i.imgur.com/PQBpB6l.png)


- Here you select the conditions for the rule. Only apply rules for products that satisfy the selected condition
- You can add or remove conditions by clicking on the + or x sign
- You can change the true/ false of condition by clicking on the bold text

##### 2.2.3 Action

![Imgur](https://i.imgur.com/04muLKs.png)

- **Action**:
  - Type: Choose how to add a Gift to Cart:
    - **Automatic**: Gift is automatically added from Gift List in order from top to bottom
    - **Manually**: Customer can add the Free Gifts that they want. The Gift List will be displayed as a popup in the frontend
  - **Number of gifts allowed**: Limit the number of free gifts that a Customer receives when applying this rule
  - **Show notice for Gift**: Select **Yes** to notify customer when they add gift to the cart
  - **Notice**: The message notice that `Customer has successfully added free gift`
  - **Discard Subsequent Rules**:
    - Select **Yes** to limit the number of rules applied to the product.
    - Rules with lower priority than this rule or rules with Priority but created later will not be applied
    - **Discard Subsequent Rule**s are divided into 2 cases applicable to **Cart** or **Item**
- *For example*: There are 6 rules in which: rule 4 has a priority of 10; rule 1.5 is 1; rule 2 is 10; rule 3 is 15; rule 6 is 10. If you choose stop at 4 then:
  - Rule 1.5 with a higher priority should be applied
  - Rule 3 is not applied because the priority is lower
  - Rule 2 is applied because of the same priority but created earlier
  - 6 is not applied because it has the same priority but creates it later
- Gift List:
  - Contains basic information of Gift including: Product ID, Name, SKU, Qty, Original Price, Discount Type, Gift Price, Free shipping and - Action
  - Admin click **Add** to add Free Gift or click **Delete** to delete Free Gift
  - There are 3 types of Discount that admin can choose for Free Gift:
    - **Free**: Gift is completely free
    - **Percent**: Gift is sold at X % of the original price (0 <= X <= 100)
    - **Fixed**: Gift sold for $ X (0 <= X <= Original Price)
- For each Discount type, admin can set the amount of Discount Amount they want
- For each Free Gift, the Admin can allow the Free Ship or not

*Popup to add gifts to the gift list*

![Imgur](https://i.imgur.com/le0CmXJ.png)


### 3. Frontend

#### 3.1 View Cart Page

![Imgur](https://i.imgur.com/MViQy3X.png)

#### 3.2 Product Detail Page

***Popup***

![Imgur](https://i.imgur.com/zpY5cAf.png)

***Block****

![Imgur](https://i.imgur.com/oNHSZpe.png)

#### 3.3 Gift Layout

***Gift List = List***

![Imgur](https://i.imgur.com/U9JwEpb.png)

***Gift List = Grid***

![Imgur](https://i.imgur.com/O5lOCku.gifv)

***Gift List = Slider***

![Imgur](https://i.imgur.com/WsbNfCU.gifv)
