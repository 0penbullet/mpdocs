# Magento 2 Call for Price

## Overview

## How to configure

From the Admin Panel, go to ``Store > Settings > Configuration > Mageplaza Extensions > Call for Price > Configuration``

### Configuration
From the Admin Panel, go to ``Store > Settings > Configuration > Mageplaza Extensions > Call for Price  > Configuration``, choose ``General`` sections

#### General

- **Enable**: Choose `Yes` to use the functions of this module
- **Status**:
  - Select the default display label whenever a request from the customers arrive
  - Allow adding/deleting custom admin labels so that admins easily manage requests
  
#### Terms and Conditions

- **Check by default**: Choose `Yes` to auto-tick on the checkbox (always agree with the terms and conditions of the store)
- **Title**:
  - Enter the title for the **Terms and Conditions**
  - If this field is filled with the **%anchor** variable, the title will be paired with the content in the `Anchor` field
  
- **Anchor**: Enter the content displaying for this field
- **URL**:
  - Enter the URL that store owners want to redirect the customers when clicking in the content filled in the `Anchor` field
  - For instance: In the `Title` field, you fill is that *I agree with the %anchor*, in the `Anchor` field, you fill is that *Terms and Conditions* and the `URL` field is that *[https://domain.com/tos.html](https://www.domain.com/tos?)*, then the result displaying on the frontend is that *I agree with the <a href="https://domain.com/tos.html">Terms and Conditions</a>*

#### Disable Default Functions

- **Disable Add to compare, Wishlist**: Choose `Yes` to hide the `Add to compare` and `Add to Wishlist` buttons on the product on the frontend
- **Disable Register Customer Account**: Choose `Yes` to hide the `Create an Account` button after customers checkout by their guest account
- **Disable Shopping cart by Customer groups**:
  - 
