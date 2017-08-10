
If you are owning an online store and building up a physical shop as well, are you ready to bring both to be more intimate with your targeted consumers? `Magento 2 Store Locator`_ extension will help you shorten the distance wherever you are located. By this way, you can put  store icons each of which represents exactly the store address on Google Map. Installing Store Locator module on your Magento 2 store, your customer can find out the nearest place from their current positions when they visit your online store. This is the greatest and shortest way for online clients to seek and pick up expected products. 

In this helpful Mageplaza documentation, you will achieve the user guide of **How to use** and **How to config** on the frontend and backend of Store Locator Magento 2 module. 


I. How to use
--------------

After completing the installation of Store Locator module, **How to use** will give you good experience as a real customer. The following list is everything that you can do with the module at your website.

1. Search by impressive ways
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Store Locator allows the user to find all brick-and-mortar shops around the exact radius from their places. Thus, you also know the customers not only search by area but also search by radius for the fastest finding.

1.1. Search by radius
`````````````````````````

"Search by radius" is a smart slider and you feel free to move the distance as need.

.. image:: https://cdn.mageplaza.com/media/general/MEZQDNk.gif

If not dragging and dropping, you can insert a number into the box put next to the slider. 

1.2. Search by area
`````````````````````

"Search by area" allows the seeker to enter an address in the search box to load the nearest store. However, there is no need to type manually, the finder tool already applies `Google Address Suggestion`_ via embedded Google Map API and allows auto-complete the address instead. 

.. image:: https://cdn.mageplaza.com/media/general/jEZWgqR.gif

2. Store Information 
^^^^^^^^^^^^^^^^^^^^^^^^^

Basing on the given information, the best stores will instantly appear together with many attached info including Store Name, Address(Country, City, State/Province), Zip/Postal Code, Website, Email, and even Working Hour. All of them are both useful for the customer's visit. In addition, as a store admin, you can also upload some of the store images to preview the store. 

.. image:: https://cdn.mageplaza.com/media/general/1LSuBwX.png 

3. Google Map Functionality
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

3.1. Google Map Appearance
``````````````````````````````

Embedding Google Map API means enabling the map on the store locator interface. At that time, each store that is found by the customer will display on Google Map with store icon. When clicking on the icon, the store information also appears as admin's settings.

.. image:: https://cdn.mageplaza.com/media/general/v9dkSUp.png

3.2. Get Direction
`````````````````````

For more convenience, the customers will be clearly guided by Google Map Direction. There are two methods they can get the street direction:

**Direction on Map**

.. image:: https://cdn.mageplaza.com/media/general/QIf3O7a.png

**360-degree street view**

.. image:: https://cdn.mageplaza.com/media/general/wi0IhJH.png

II. How to configure
--------------------

Login to Magento 2 backend, you will have full of admin controls here.

1. Basic Configuration
^^^^^^^^^^^^^^^^^^^^^^^^^^^

On the left panel, `Store Locator > Settings`, General Settings is divided into four sections: General, Map Settings, Language options, and Hour of Operation.

.. image:: https://cdn.mageplaza.com/media/general/wYl1HIB.png

1.1. General
````````````````

**General** settings permit to enable the store locator module by choosing "Yes" in `Enable` field. Beside, you can set the specific name and URL of module in breadcrumb like *Homepage > Store Locator* 

.. image:: https://cdn.mageplaza.com/media/general/t1CWGvC.png 

1.2. Map Settings
````````````````````````

This setting is the workplace you can connect your store locator module with Google Map, an advanced solution for the fast location.

Under **Map Settings** section, you need to do the following:

* Take Google Map API key when clicking on `here` text link, and fill it into `Google Map API Key` field.
* Enabling `Location Autocomplete` means the module will automatically complete the location address in the search box.
* Set `Full map start` to "Yes" to auto display the map on the store finder.
* Allow showing the clear direction from the search place to your store by choosing "Yes" in the `Direction` field.
* Accept `Max Distance` when you search stores around a radius chosen before.
* Set the `Default Address` in the search address box.
* Set the `Default Distance` when searching by radius. If not change, the system will find your stores around the default radius.
* Possibly auto-detect customer's position via `AutoGeocode`
* Enter the number of stores displaying in store list in the `Stores Limit` field.
* Select `Distance Unit`: Mile or Kilometer (Km)

.. image:: https://cdn.mageplaza.com/media/general/9mQtRtB.png

1.3. Language options
`````````````````````````

Regarding your store language, Store Locator makes you free to convert into the native language. You can modify all words and phrases for the most effective customer awareness:

* Address Error Alert
* Autogeocode Error Alert
* Distance Error Alert
* Distance Unit Language: Mile, Miles, Kilometer, and Kilometers
* No results title
* No results description

.. image:: https://cdn.mageplaza.com/media/general/NslySAu.png

1.4. Hour of Operation
`````````````````````````

You will set `Time to closing` as a notification the store will out of work. As the taken photo, the status is auto changed into "Closing soon" if the current time is less than the store's closing time by 30 minutes. 

.. image:: https://cdn.mageplaza.com/media/general/GPtIJHJ.png 

2. Create Store Location
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Make step as the path: `Store Locator > Location`, on the **Location** page, do as following:

* On the right corner, tap **Add new location** button.
* Under **Location Information**, there are 4 sub-tabs of the new location information on the left panel: Location, Tags, Holidays, and Meta Data.

2.1. Entere Location Information
```````````````````````````````````

.. image:: https://cdn.mageplaza.com/media/general/JN8c6zH.gif

* Firstly, you will config the general information of the new store location

  * Enter `Name` for the location.
  * If need, you can write some descriptions in the text area in order to attract more customers to your stores.
  * Update `Location Image` as a store avatar by choosing a file image from your computer.
  * Generate the specific URL in the `URL Key` field that direct to that store. If missing it, the random URL will be used.
  * Assign the new store to `Store View`.
  * Select `Marker` (store type) and `Hours of Operation` (store's working time).

* Next, complete **Contact** of the new store including:

  * Contact Person
  * Phone #1
  * Phone #2
  * Phone #3
  * Fax
  * Email
  * Website

  All of them are visible when customers search your store by Magento 2 Store Locator.

* The final thing is **Address Information**. In this section, Mageplaza also supports Google Address Suggestion to fulfill all related fields which are:

  * City
  * Zip/Post Code
  * Country
  * Latitude
  * Longitude

  The locating on map is ready here.

.. image:: https://cdn.mageplaza.com/media/general/HBDlgS8.gif 

* Remember to say "Yes" for `Enable` to show the store location in the store list.

2.2. Assign to Tags
````````````````````````

On the left panel, open `Tags` tab, enable to tick many tags from the existing list.

.. image:: https://cdn.mageplaza.com/media/general/0sGfYtL.png 

2.3. Select Holidays Time
`````````````````````````````

Similar to Tags, you can select the holiday time as well.

.. image:: https://cdn.mageplaza.com/media/general/gdYiL5f.png

2.4. Fill out Meta Data
`````````````````````````

Meta Data is very useful for SEO. Raise your SEO rank via:

* Meta Title
* Meta Keywords
* Meta Description

.. image:: https://cdn.mageplaza.com/media/general/7zSKMuz.png

3. Create Store Marker
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Go to `Store Locator > Marker`.

.. image:: https://cdn.mageplaza.com/media/general/2ijMzpg.gif

Creating new store marker means to set a new style of the store (restaurant, bookstore, cafe, etc), then it might be assigned to the specific store.

* Click on **Add New Marker** button
* Enter `Marker Name`
* Apply separate icon for each marker by uploading the personal image.
* `Save Marker` to complete.

4. Create Store Tag
^^^^^^^^^^^^^^^^^^^^^^

Still, in the configuration, go to `Store Locator > Tags`

.. image:: https://cdn.mageplaza.com/media/general/y7S9xMA.gif

* Hover over the right corner of **Tag** page, click on **Add new Tag** button

* Under **Tab Information** section, you need to:
  * Set `Name` for the tag
  * Leave `Short Description` if need
  * To show this tag, choose "Yes" in `Enable` field

* In the **Location**, you are allowed to attach it to multiple available store location.

.. image:: https://cdn.mageplaza.com/media/general/3YUUWSf.png

* `Save Tag` to complete.

5. Set Working Hours
^^^^^^^^^^^^^^^^^^^^^

Provide visitors the working time of your stores in detail (from Monday to Sunday).

Follow the guide: `Store Locator > Hours of Operation`.

.. image:: https://cdn.mageplaza.com/media/general/djc3PSv.gif

* Click on **Add New Hours of Operation**
* `Name` for the new one
* Set opening and closing time of each day

6. Set Holiday Time
^^^^^^^^^^^^^^^^^^^^^^

Notify the visitors which holiday you will not be available.

Go to `Store Locator > Holidays`

.. image:: https://cdn.mageplaza.com/media/general/oGpFXAP.gif

* Start with **Holiday Information**
  * Set new name for that holiday.

   .. note:: Store holiday's name cannot duplicate 

  * Insert start and end time of the holiday through Calendar icon
  * You can describe this holiday in the `Short Description` text area
  * `Enable` is "Yes" to show it
* Choose more than one location to show that holiday

.. image:: https://cdn.mageplaza.com/media/general/VV17bEk.png

* `Save Holiday` to complete.


.. _Magento 2 Store Locator: https://www.mageplaza.com/magento-2-store-locator-extension/

.. _Google Address Suggestion: https://www.mageplaza.com/magento-2-one-step-checkout-extension/google-address-suggestion.html