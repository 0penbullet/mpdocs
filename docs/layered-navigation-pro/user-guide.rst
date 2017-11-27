`Mageplaza Layered Navigation`_ is a smart map for your Magento 2 store. It's the shortest way for the shoppers to find what they want, especially when you have a bunch of items with various prices, attributes or brands.

 .. _Mageplaza Layered Navigation: https://www.mageplaza.com/magento-2-layered-navigation-extension/) 

Overview 
----------------

After enabling the module, the Layered Navigation will be displayed on the left sidebar on Categories pages.

.. image:: https://i.imgur.com/A0Cq43m.jpg

Layered Navigation Configuration
--------------------------------

The Configuration is available under `Admin Panel > Mageplaza > Layered Navigation > Configuration`.

.. image:: https://i.imgur.com/28dBmmi.gif

* General configuration
* Filter configuration
* Design configuration
* All Products page

Here are the details for the settings of each tab.

1. General Configuration tab
--------------------------------

.. image:: https://cdn.mageplaza.com/media/general/UIIFzKu.png

* In **Module Enable** field: You can choose to use the Module `Layered Navigation` or not. Leave as **Yes** to enable and **No** to disable.
* In **Multi-Filters** field:

  * By enabling this feature, the shoppers are allowed to choose more than 1 filter to find the desired items. You can also filter by multi-choose from multiple categories at the same time. For example: The shopper can choose to filter by **Color** with *Black*, *White* and **Size** with *Small*, *Large* at the same time. This can be also applied with multiple categories. 
  * To config this feature, go to `Enable Multi-filter` field, set **Yes/ No** to **Enable/ Disable** 
  
.. image:: https://i.imgur.com/jSaFtmp.gif  

* In **Scroll to Top** field:

  * This feature allows the shoppers, after filtering, can automatically back to the top of the products list and start to find the desired items. 
  * On the `Scroll to Top after Filtering` field, you will have 2 options:
  
    * **YES** : After choosing a filter or click on the `Apply Filter` button, the site will automatically scroll up to the top-page.
    *  **NO** : After choosing a filter or click on the `Apply Filter` button, the site still stay at the current position.

* In **Quick Lookup Options** field: 

  * By enabling this feature, in each of the attribute group, there is a search box. The shoppers only need to insert the letters and the filter whose name contains this letter will be displayed. 
  * Go to `Enable Filter options` field to **Enable/ Disable** this feature by setting **Yes/ No**.

.. image:: https://i.imgur.com/5GUCriq.gif

* In **Display Out-of-stock option** field: There are 2 options to choose: 

  * **Yes**: Show all the attributes and options even the product is currently out of stock. 
  * **No**: Hide all the attributes and options of the product which is currently out of stock.

* In **Product Count** With this feature, there will have a number which is displayed next to the filter. This number allows the shoppers to know how many items which is matched the filter. For example: If the filter is displayed: **Cotton(2)**, that means there are 2 items which are matched the filter *Cotton*.

.. image:: https://i.imgur.com/ZfTnGp2.jpg

* In **Display Product Count** field:

  * Set **Yes** to display the number to the left of the filter name.
  * Set **No** to hide this number.

* In **Expand by default** field: 

  * **Yes** : The attribute group will already be expanded when the shoppers go to the Categories page.
  * **No** : The shoppers need to click on the attribute group name to expand the filters.

* In **Apply Filter button** field:

  * The `Apply Filter` button allows the shoppers to choose when to apply the chosen filters. With this button, the shoppers don't need to wait for the page to reload again and again each time they choose a filter.
  * In ``Add Apply Filter button`` field, set **Yes** to show the button and leave **No** to disable. 
  * Here is how the ``Apply Filter`` button works, you can choose lots of attribute before applying it.  Also, SEO friendly URL is compatible with ``Apply Filter``'s search result. As you can the this example chose *Insulated* and *Cold*, and name of those attributes appears on the URL as well.

.. image:: https://imgur.com/Ve8nGAA.gif

* In **Infinite Scroll** field

  * Continue with the next session. **Infinite Scroll**, or also called the **Lazy-scrolling** on a website, this feature will help to automatically load the new products in the list when the shoppers scroll to the bottom, without clicking or reloading. 
  * In the field **Infinite scroll**, set "Yes" to enable the feature and "No" to disable. 

* In **Show Navigation** field

  * By default, the `Vertical & Horizontal Navigation` feature has 3 display styles so `Mageplaza Layered Navigation`_() can match to any store design with different purposes.
  * In the **Show Navigation** field, choose 1 of 3 options below :

    * Vertical
    * Horizontal
    * Both

2. Additional Filter 
------------------------------

2.1. Product State Filter
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The `Product State Filter`feature allows the shoppers to filter the items by the **New**, **Sale**, and **Stock** status. Here is how the `Product State Filter` configuration will be displayed: 

.. image:: https://i.imgur.com/qFiyMCO.jpg

* **Group label** : The name of the group attribute 
* **Expand by default**: Choose **Yes** to automatically expand the group attribute `Rating` when shoppers go to the collection page.
* **Enable New Filter**, **Enable On Sales filter**, **Enable Stock filter**: Choose **Yes** to enable the filter and leave **No** to disable.
* **New label**, **On Sales label**, **Stock label**: Add the name for each label filter.

2.2. Rating Filter
^^^^^^^^^^^^^^^^^^^^^^^

This feature allows the shoppers can filter the items by the rating follows 5 levels from 1 star to 5 stars. For example: when you choose the option **4 stars and up**, the received result will display the items which have the 4-star and 5-star rating.

The Rating Filter configuration is available under the `Filter Configuration` tab.

.. image:: https://imgur.com/n1patLV.jpg

* In **Enable Rating Filter** field: Choose "Yes" to enable and display the group attribute **Rating** on the Layered Navigation and leave "No" to disable this feature. When you choose "Yes", there are 2 more options for the modification:
  
  * In **Group Label** : Adding the text as the group attribute's name.
  * In **Expand by default** : Choose "Yes" to automatically expand the group attribute **Rating** when shoppers go to the collection page.

3. Attribute Configuration 
-------------------------------

Go to ``Admin Panel > Stores > Attributes: Product``, then choose an attribute and go to **Layered Navigation Properties** tab.

3.1 Attribute Properties
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Example of a specific attribution and its configuration in detail

.. image:: https://i.imgur.com/kJYk1Oh.jpg

* In **Use in ProductsPage Navigation** field: choose the possibility of being displayed on Layered Navigation or not
* In **Use in Search Results ProductsPage Navigation**: choose the possibility of being filtered by Layered Navigation or not.
* In **Position** field:
* **Allow Multiple Filter** : By choose **Yes**, the shoppers are able to filter by multi-option in this group attribute. For example: You can allow the shoppers to choose more than 1 filter in `Color` group attribute but only can choose 1 filter in `Style` group attribute.   
* **Display Style** : Choose the display style of the group attribute. The specific design for each style is mentioned in the *next section*.    
* **Enable search option** : Choose to enable/ disable the **Quick Lookup Option** in this attribute group.
* **Expand by default** : Choose to automatically expand this attribute group or not when the shoppers go to the collection page.

3.2 Filter by decimal attributes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Layered Navigation also allows store owner can set up and visitor can filter decimal attributes.

* In the ``Attribute Information > Properties > Advanced Attribute Properties > Input Validation for Store Owner``, choose **Decimal Number** or **Intergal Number** to set your optional attribute.

.. image:: https://imgur.com/Z4txesm.jpg

* Follow ``Attribute Information > ProductsPage Navigation Properties``

  * In **Use in ProductsPage Navigation** field choose *Filterable (with results)*
  * In **Use in Search Results ProductsPage Navigation** choose *Yes* 
  * In **Display Style** choose your preferred style as *Slider*, *Range* or *Slider and Range*

.. image:: https://imgur.com/XmNmCJR.jpg

For example with **Weight** option for which product has weight as 15 lb. In the frontend the search result can be filtered like: 

.. image:: https://imgur.com/mHR1l4E.jpg
