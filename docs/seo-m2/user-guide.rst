===========
User Guide
===========

Introduction
--------------

`SEO extension for Magento 2`_ was developed by Mageplaza is the best marketing tool in order to help you automatically optimize and  greatly improve the performance of your Magento-based store in Search Engines. With a list of outstanding and effective tools, our Better SEO extension will bring to your store a great chance to own an amazing speed as well as gain the higher and higher rank in the popular and famous search engines such as Google, Bing, or Yahoo.

In order to install SEO extension on your store, you can learn and do it by yourself via `Installation Guide`_ or use `Installation Service Package`_ to request the specialist helps from Mageplaza Team.

 .. _Installation Guide: http://docs.mageplaza.com/kb/installation.html
 .. _Installation Service Package: https://www.mageplaza.com/magento-2-installation-services/

In User Guide Document, Mageplaza divides into three main parts: Basic Settings, DashBoard, and Rules.

1. Magento 2 SEO Basic Settings
--------------------------------------

Firstly, we will familar with the module via the list of the configuration. Login as Admin account, go to the path `Mageplaza > SEO > Settings`.

.. image:: https://i.imgur.com/bAveprS.gif

1.1. General Configuration
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Open **General Configuration** section, you can see:

* To allow improve the connect between component URLs in a paginated series as well as move to another page easily, you can use Next/Prev tag if choosing "Yes" in the `Enable Next/Prev tag` field

* `Add Nofollow meta in Search Result` if you select "Yes" option
* `Add Nofollow meta in Product Gallery` if you select "Yes" option
* Setting `Enable Sitelink Search Box` to "Yes" means showing another search box that shows the more detailed search results on the destination site.  

.. image:: https://i.imgur.com/eoLJmIc.png

1.2. Duplicate Content
^^^^^^^^^^^^^^^^^^^^^^^^

Continue with the next session - **Duplicate Content**, there are some configurations related to the duplicate content:

* To manage your content better and restrict the duplication, please set "Yes" for `Add Canonical URL Meta`
* In the `Canonical points to https` field, you can choose "Yes" or "No" option depending on whether you would prefer the https version of a page or not
* Also avoid the duplicate content, you can disable URL parameter as *?price=30-220&brand=abc* in canonical URL, that means "No" option must be active.

.. image:: https://i.imgur.com/7n3CHt6.png

1.3. Social Shares
^^^^^^^^^^^^^^^^^^^^^

**Social Shares** provides the working fields that support for the better SEO on the social channels. Now expand that section and do the following:

* It is possible to show **Open Graph** that is a short description of your website whenever visitors publish on the social medias like Facebook, Google+, Pinterest and other social networks. 

  If disable the open graph on the social network, please choose "No" to turn it off in `Add Open Graph meta tags` field

* You can also `add Twitter Card Meta tags` when the visitors share your website on Twitter

* Enter `Pinterest Confirmation Code` to verify your website. Follow the instruction here_
 .. _here: https://help.pinterest.com/en/articles/confirm-your-website#meta_tag

* Enter `Google+ Publisher Page` if you need

.. image:: https://i.imgur.com/PbdWf1p.png

1.4. Rich Snippets | Structured Data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Scroll down and expand the **Rich Snippet | Structured Data** section, you will:

* Include Rich Snippet in the search results right after enabling the rich snippet in the configuration
  
  Rich Snippet may be review stars, an aggregate rating value, and vote count, etc. You can learn it more at here_ 
 .. _here: https://mageplaza.freshdesk.com/support/solutions/articles/6000122361--rich-snippets/

* Disable `Product Structured Data` by selecting "No" if your theme or module implements it's own product snippets.

* Allow applying `Organization Information` that describes the results in detailed. Furthermore, you can custom that data via this guide_

 .. _guide: https://mageplaza.freshdesk.com/support/solutions/articles/6000122360

.. image:: https://i.imgur.com/xXWhUdv.png

1.5. Social Profiles
^^^^^^^^^^^^^^^^^^^^^^^

Mageplaza SEO extension permits to show **Social Profiles** when your website is searched on Google.

.. image:: https://i.imgur.com/blvjYv7.jpg

1.6. Business information
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can enable **Business Information** if choosing "Yes". Just enter the information into the corresponding fields, then all of them will be show on the search result.

.. image:: https://i.imgur.com/bsekXgl.png

1.7. Breadcrumbs
^^^^^^^^^^^^^^^^^^^

Enabling Breadcrumbs is the way to show the exact position in the site hierarchy, for example: `www.mageplaza.com > Magento 2 Extensions > Better SEO`. If you really want to apply for your product page, under **Breadcrumbs** section, please select "Yes" in the `Enable Breadcrumbs Rich Snippet` field.

.. image:: https://i.imgur.com/zixmHos.png

1.8. HTML Sitemap
^^^^^^^^^^^^^^^^^^^^^

This html sitemap configuration contains Categories Sitemap, Pages Sitemap, and Products Sitemap while all of them can be displayed in the footer of your page. You can see the settings in the following screenshots:

.. image:: https://i.imgur.com/NAiSlln.png

1.9. XML Sitemap
^^^^^^^^^^^^^^^^^^^^^^

XML Sitemap is a `.xml` map of your website and the map will show a list of the page that the visitors can access.

Under the **XML Sitemap** section, you can:

* Create `Homepage Optimization` when choosing "Yes"
* In case you need additional links, it is required to set `Enable Additional Links` to "Yes"

.. image:: https://i.imgur.com/0EgBnJT.png

1.10. Hreflang Tag
^^^^^^^^^^^^^^^^^^^^^^

The Hreflang tag is the necessary tag if your website must approach multi-countries. The hreflang attribute tells Google which language you are using on a specific page, so the search engine can serve that result to users searching in that language.

In order to use the hreflang tag, you need to do:

* Enable the hreflang URL when selecting "Yes"
* Allow you to apply the hreflang for the product, category, and pages if you need.
* Assign **X-default** to the specific store view that means if the visitors come from another country with the language you don't support, the assigned store view to X-default will be displayed in this situation.

.. image:: https://i.imgur.com/V5xhGtR.png

2. SEO Checklist
--------------------

SEO Checklist includes a list of the notifications: Success, Error, and Warning. Basing on this status of the notification, you will know whether your store is optimized and ready for SEO or not.

.. image:: https://i.imgur.com/NQt363V.gif

3. SEO Rules
------------------

Mageplaza SEO allows the store owner to create the specific rule information. To add new SEO rule, please follow the path `Mageplaza > SEO Rules > Rules`, click on **Add New Rule** button.

.. image:: https://i.imgur.com/nKdREcL.gif

* Enter `Rule Name`
* The rule can be applied to Product, Category, Pages, Post. You can choose one of them in the `Entity Type` field
* Set `Apply Template` to "Skip if ready defined" and "Force Update"
  * "Skip if ready defined" means if admin manually adds meta tag: title, description, so it will not apply this template.
  * "Force Update" means auto-applying the template for all meta tags
* Apply SEO Rule for "All" or "Product Attribute Set" or "Specific Product" as you need
* Enter `Meta Tile Template`, `Meta Description Template`, and `Meta Keywords Template` 
  * The Meta Title Template should be 55-60 characters. Use following syntax to add dynamic meta title: {{name}}, {{price}}, {{special_price}}.
  * The Meta Description Template should be between 150 and 160 characters. Use following syntax to add dynamic meta title: {{name}}, {{price}}, {{special_price}}.
  * The Meta Keywords Template should be between 3-5 keywords. Use following syntax to add dynamic meta title: {{name}}, {{price}}, {{special_price}}.
* Select `Robots Template` from one of the options:
  * Index, Follow
  * NoIndex, Follow
  * Index, NoFollow
  * NoIndex, NoFollow
* Set `Status` to "Enable" for the active rule
* Choose `Store View` where the rule is applied
* Set `Priority` if need while 0 is the highest level. 

.. image:: https://i.imgur.com/hiorYpE.png