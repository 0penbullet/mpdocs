# Instagram Feed

## Overview

Instagram is becoming popular when people desire more and more to share, comment and post their images every day. Now you definitely can utilize this on Magento 2 for your eCommerce website with the support of [Mageplaza Instagram Feed module]().

The Instagram Feed supports displaying your Instagram photos on the homepage, product page or on any CMS page within your sites. You can also configure the number of images per row and the maximum number of images displayed. Images can be sorted and arranged according to the most recent, most liked, most comments and randomly. We support 3 image resolutions available: thumbnails, low resolution and standard resolution. You can also display like or comment button on photos or show popup when clicking on images.


## Download & Install

- [Mageplaza Instagram Feed]()
- [How to Install](https://www.mageplaza.com/install-magento-2-extension/)


## How to Use 

### 1. Single Row

![Imgur](https://i.imgur.com/UxbV1j1.png)


### 2. Multiple Rows

![Imgur](https://i.imgur.com/jOVztok.png)


### 3. Optimized images

![Imgur](https://i.imgur.com/LxPEF9f.png)

### 4. Show Likes/Comments


![Imgur](https://i.imgur.com/ZYSYcwr.png)

### 5. Show Popup when licking to the images

![Imgur](https://i.imgur.com/7UB5bj5.png)


## How to configure
 
From the **Admin Panel**, go to `Store > Settings > Configuration > MAGEPLAZA EXTENSIONS > Instagram Feed`

![Imgur](https://i.imgur.com/gtkq63P.png)


### 1. Configuration 


#### 1.1. General 


![Imgur](https://i.imgur.com/I9ZA7aE.png)

- **Enable**: Select `Yes` to enable the module
- **Client ID**: Insert the App ID
- **Client Secret**: Insert the App Secret
- You can see the instruction for creating Instagram API [here](https://docs.mageplaza.com/social-login-m2/how-to-configure-instagram-api.html)

#### 1.2. Display

![Imgur](https://i.imgur.com/ZB67Y2X.png)


- **Total number of photos**
  - Select the number of images to be shown on your site
  - The maximum image number is 20
  
- **Sort by**

![Imgur](https://i.imgur.com/yzqN72i.png)

- **Sort by = Most recent**: Show the most recent products
- **Sort by = Most liked**: Show the most liked products
- **Sort by = Most commented**: Show the most commented products
- **Sort by = Random**: Show random products

`Note`: The images will always be selected as most recent products before examining this Short-by configuration setting. 

- **Layout**

![Imgur](https://i.imgur.com/cxTACKL.png)


  - *Layout = Single Row*: Display images on a row
  - *Layout = Multiple Rows*: Display images on multiple rows
    - **Number of row**
      - Select the image number shown on a row
      - The default number is 2 
  - *Layout = Optimized image*: Display the optimized product images

- **Image resolutions**

![Imgur](https://i.imgur.com/1bmDFp6.png)

  - *Image resolutions = Standard*: Display images with standard resolution
  - *Image resolutions = Low*: Display images with low resolution
  - *Image resolutions = Thumbnail*: Display images with thumbnail
- **Show number of Likes/ Comments**: Select `Yes` to allow displaying like and comment numbers on products
- **Show pop-up**: Select `Yes` to allow displaying popup as clicking to images

### 2. Widget

#### 2.1 Add Widget

- Step 1: Select the Type
- Step 2: Complete the Storefront Properties section
- Step 3: Configure Widget Options to display Instagram images

##### Step 1: Select the Type

On the **Panel Admin**, go to `Content > Elements > Widgets`

- In the upper-right corner of **Widgets** workplace, click on **Add Widget** button.
- In the **Settings** section:
  - Choose **Widget type** in the Type box.
  - Choose the current theme you are applying in the **Design Theme**.
  - Click **Continue** button.

![Imgur](https://i.imgur.com/AB4TAd8.png)

##### Step 2: Complete the Storefront Properties section

- In the Storefront Properties section,
  - Enter **Widget Title** for the internal reference.
  - Assign the block to all store views in the **Assign to Store View** field or to any store view you want to apply the block.
  - Set the **Sort Order** if many blocks are placed at the same container. The block is at the top if the inserted value is zero.

![Imgur](https://i.imgur.com/xWcKx1u.png)


- In the **Layout Updates** section, click on **Layout Update** to set the layout.
  - In the **Display on** field, choose the **category**, **product**, or **page** in which the block can be shown 
  - If you want to display the block on specific page, you can choose the **Page** and the **Container** is the position the block will appear on that page.

![Imgur](https://i.imgur.com/O0nXEzZ.png)


##### Step 3: Configure Widget Options to display Instagram images

- **Title**: Insert the title for Instagram images displayed on Frontend
- **Description**: Insert the description for Instagram images displayed on Frontend
- **Design** 

![Imgur](https://i.imgur.com/kl2zUZt.png)

- **Design = Use Config**: Display the product images by using the Instagram images configuration
- **Design = Custom**: Admin can custom the displaying of Instagram images on frontend
- **Total number of photos**
  - Select the image number displayed on frontend
  - The maximum number is 20
- **Sort by**

![Imgur](https://i.imgur.com/J6tZ66f.png)

- **Sort by = Most recent**: Show the most recent products
- **Sort by = Most liked**: Show the most liked products
- **Sort by = Most commented**: Show the most commented products
- **Sort by = Random**: Show random products

`Note`: The images will always be selected as most recent products before examining this Short-by configuration setting. 

- **Layout**

![Imgur](https://i.imgur.com/cxTACKL.png)


  - *Layout = Single Row*: Display images on a row
  - *Layout = Multiple Rows*: Display images on multiple rows
    - **Number of row**
      - Select the image number shown on a row
      - The default number is 2 
  - *Layout = Optimized image*: Display the optimized product images

- **Image resolutions**

![Imgur](https://i.imgur.com/1bmDFp6.png)

  - *Image resolutions = Standard*: Display images with standard resolution
  - *Image resolutions = Low*: Display images with low resolution
  - *Image resolutions = Thumbnail*: Display images with thumbnail
- **Show number of Likes/ Comments**: Select `Yes` to allow displaying like and comment numbers on products
- **Show pop-up**: Select `Yes` to allow displaying popup as clicking to images

