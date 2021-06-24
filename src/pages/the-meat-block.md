---
title: "The Meat Block Website How-to"
description: "Website Training for The Meat Block"
---

![The Meat Block Website Screenshot](/images/The-Meat-Block-Screenshot.jpg)

# Table of Contents

- [Documents and Resources](#documents-and-resources)
- [Logging in](#logging-in)
- [Admin Dashboard](#admin-dashboard)
- [Product Attributes](#product-attributes)
- [Product Filters](#product-filters)
- [Add Product Filters to Shop Sidebar](#add-product-filter-to-shop-sidebar)
- [Add Products](#adding-products)
- [Simple Products](#simple-product)
- [Group Products](#group-product)
- [Variable Products](#variable-products)
- [Adding and Managing Specials](#adding-and-managing-specials)
- [Editing Basic Store Information](#editing-basic-store-information)
- [Create Coupons](#create-coupons)
- [Adding New Users](#adding-new-users)

## Documents and Resources

<a href="https://docs.woocommerce.com/document/managing-products/" target="_blank" rel="noopener noreferrer" class="external">Adding and Managing Products</a>

<a href="https://docs.woocommerce.com/document/related-products-up-sells-and-cross-sells/" target="_blank" rel="noopener noreferrer" class="external">Set up Related Products, Up-Sells and Cross-Sells</a>

<a href="https://docs.woocommerce.com/document/managing-orders/" target="_blank" rel="noopener noreferrer" class="external">Managing Orders</a>

<a href="https://woocommerce.com/posts/coupons-with-woocommerce/" target="_blank" rel="noopener noreferrer" class="external">Creating Coupons</a>

<a href="https://docs.woocommerce.com/document/roles-capabilities/" target="_blank" rel="noopener noreferrer" class="external">WooCommerce Roles</a>

<a href="https://wordpress.org/support/article/roles-and-capabilities/" target="_blank" rel="noopener noreferrer" class="external">WordPress Roles</a>

## Logging In

To log in to the admin dashboard, navigate to <a href="https://themeatblock.com/wp-admin" target="_blank" rel="noopener noreferrer" class="external">themeatblock.com/wp-admin</a>. Enter your username and password and click Log In.

## Admin Dashboard

### Posts

Posts are all your sites blog posts

### Media

Media is where you upload all assets such as images and PDFs

### Forms

Forms is where you will find your sites contact forms and can edit forms settings and view/resend form submissions

### Pages

This is where you will find all of your site's primary pages

### Specials

This is where you will post and manage specials

### Appearance

This is where you will make some changes to some of your stores basic settings. Navigate to Appearance > Customize

### Users

Users allows you to add new users if you need to give access to additional employees who are going to add tours, edit job posts, or additional blog authors

## Product Attributes

### Adding an Attribute Group

1. <a href="https://themeatblock.com/wp-admin/edit.php?post_type=product&page=product_attributes" target="_blank" rel="noopener noreferrer" class="external">Click here</a> to open up the product attributes.
2. Type in the name you want for your new attribute group
3. Slug will be auto-generated, you don’t need to do anything here
4. Choose the sort order you want
5. Click “add attribute” when done
6. When your attribute appears in the list on the right, click on the attribute title or “configure terms” to edit that attribute group.

### Adding Attributes to a Group

1. Once you are in the attribute group you want to edit, type in the new attribute name that you want to add in the name field.
2. Slug will be auto-generated
3. Description is only needed for internal purposes if you want to add a description. This may come in handy to help keep data clear and easy to understand
4. Click “Add New” to finalize

## Product Filters

The <a href="https://themeatblock.com/wp-admin/edit.php?post_type=br_product_filter" target="_blank" rel="noopener noreferrer" class="external">product filters</a> use product attribute groups to group similar products by specific features. This is to allow the ability to sort through various product attributes on the shop pages.

To set up a new product filter hover or click on the tab BeRocket then choose product filters > filters. Here you will see all the active filters. Simply select one to edit if needed. To create a new filter:

1. Click “Add Filter”
2. Enter the title for the new filter, this is exactly as it will display to a user on the shop pages
3. In the product filter settings, click the “Attribute” select box and select the attribute that you want to filter
4. Move down to the advanced settings, check “enable collapse option”, then check “collapse this widget on load”
5. Click “save” on upper right

## Add Product Filter to Shop Sidebar

1. Navigate to Appearance > Widgets
2. Click and drag a “AAPF Filter Single” widget over to your sidebar area on the right.
3. Click the new filter to open the filter options
4. Select the filter you want to apply
5. Click “save”

## Adding Products

### Simple Product

1. Type in your product name
2. Add in your product description in the WYSIWYG editor. This can be as detailed as you like. Text can be styled using the text editor options
3. Set your products featured image, click “set product image”
4. Choose the image from your image library or upload a new image
5. Image size should be about 700px x 700px.
6. A really nice free photo editor if you don’t have tools like Photoshop is <a href="https://pixlr.com/" target="_blank" rel="noopener noreferrer" class="external">https://pixlr.com/</a>
7. Save images as the lowest possible file size you can. Use a tool like <a href="https://tinypng.com/" target="_blank" rel="noopener noreferrer" class="external">https://tinypng.com/</a> to compress images and strip them of unnecessary data so they don’t slow down your website. Images should be no more than 100KB in size
8. To add a gallery of images, click “Add product gallery images”, select as many images as you want from the media library or upload new images as needed. Remember to keep image file size in mind at all times.
9. Product Brands. This is an optional field built with brand recognition in mind. Use this to show users what division of The Meat Block each product represents. To set a brand image for a specific product, click on “Product Brands”. Click “Add Image”, select the brand logo you wish to display with the specific product.
10. Product Categories. Select the categories you wish to group this product. All the categories that were included in the sitemap should be added into the category list. If you don’t see the category you’re looking for, click “Add new category”, type in the category name you need, select a parent category if it applies, then click “Add new category” button to finalize your change
11. Select the product type you are creating from the Product Data Dropdown box. You can either choose simple, grouped, or variable product
12. In the “General” tab, enter your product price. And select tax status.
13. Enter a sales price, if you choose. You can even go in and schedule sales prices to start and end on certain days
14. In the “Inventory” tab add a SKU or stock keeping unit. This isn’t absolutely needed but will help with search results in search engines, and also when users are searching for products onsite.
15. Click “manage stock” to select stock options if you want to limit a product to a set number of items. Choose whether or not you want to allow backorders. Select a “Low stock threshold” if you want to get email notifications from your store letting you know when a product is low.
16. In the “Shipping” tab, enter in your products shipping weight and dimensions.
17. “Linked Products” are Up-Sells, Cross-Sells and Related Products. Learn more about these types of sells <a href="https://inchoo.net/magento/related-products-up-sells-cross-sells-in-magento/" target="_blank" rel="noopener noreferrer" class="external">here</a>
18. “Attributes” are how your products will be filtered on the shop pages. Attributes are ways to group products by their specific features. To add attributes you first need to make sure you have <a href="https://themeatblock.com/wp-admin/edit.php?post_type=product&page=product_attributes" target="_blank" rel="noopener noreferrer" class="external">added your product attributes</a> to your store. Some have already been set up for you. Back in your new product, click on the select box of attributes, find the attribute that you want and click “add”. Next click on the “Values” field, this will open up a list of all the attribute options within that attribute group. Select the attribute that you want to apply. You can add as many attributes as you choose.

_Tip: A quick way to see all your attributes in an attribute group is to click the “Select All” button under the values field. Now you can see all attributes and remove the ones you don’t need._

To add additional attribute groups, simply start the process over by selecting an attribute from the select box, and click “add”. Then choose your attribute options.

19. Enter a product short description to give a product a one or two-sentence description that will show up “above the fold” next to the product image. This gives you a chance to draw the viewer in with a little detail before they get down to the full product description.
20. When you are ready to publish your new product to your site, scroll back to the top of the page, and click “Publish” in the top right corner.
21. For more information on adding products see the <a href="https://docs.woocommerce.com/document/managing-products/" target="_blank" rel="noopener noreferrer" class="external">woocommerce documentation</a> for adding products.

## Group Product

1. Follow all the steps as you would for adding a simple product
2. In the “product data” section. Select the product type you want from the select field. Choose “Grouped Product”.
3. Click on “Linked Products” to see the new “Grouped Products” field. Here you can now add all the products that you want to add to this group.
4. Group products have to be products that are already published that you want to combine into one bundle
5. Fill out all product data fields again as you would a simple product
6. Click “Publish“ when done

## Variable Products

1. Variable products are going to be the most complex products to set up.
2. To set up a variable product. Select “Variable Product”
3. Set up all your product settings just as you would for a simple product.
4. The major difference with variable products is that you will need to set attributes in order for these to work. To set your attributes click on the “Attributes” tab and set your attributes as you did for simple products.
5. Make sure to check the checkbox “used for variations”
6. Next go to the “Variations” tab. Here you can choose “Add variation” or “create variations from all attributes”. To add a new variation select “Add variation” and click “go”.
7. Select the attribute that you want to add as a variation. Now you can click on the new variation and open up all the associated fields with that variation. You can set a product image, price, stock options, weight and dimensions or shipping class, and your description. Make sure to do this for all variations of the product.
8. When done click “publish”
9. Learn more about <a href="https://docs.woocommerce.com/document/variable-product/" target="_blank" rel="noopener noreferrer" class="external">variable products</a>

## Adding and Managing Specials

1. Click on Specials in the admin menu or hover over and select Add New Special
2. Type in your specials title
3. In the post toolbar on the right hand side, click open the Permalink tab to edit your posts URL.
4. Next open the Categories tab. Select the type of special that you are creating. Specials are categorizes as either Regular Specials or Seafood Specials
5. Next open the Featured image tab. Here you will add the image for your special.

<div class="warning">
<div class="warning__svg-wrapper">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><title>ionicons-v5-r</title><path d="M85.57,446.25H426.43a32,32,0,0,0,28.17-47.17L284.18,82.58c-12.09-22.44-44.27-22.44-56.36,0L57.4,399.08A32,32,0,0,0,85.57,446.25Z" style="fill:none;stroke-linecap:round;stroke-linejoin:round;stroke-width:32px"/><path d="M250.26,195.39l5.74,122,5.73-121.95a5.74,5.74,0,0,0-5.79-6h0A5.74,5.74,0,0,0,250.26,195.39Z" style="fill:none;stroke-linecap:round;stroke-linejoin:round;stroke-width:32px"/><path d="M256,397.25a20,20,0,1,1,20-20A20,20,0,0,1,256,397.25Z"/></svg>
</div>
<h4>Important!</h4>

There will rarely be a time when you want to upload a full resolution image to your website. Images are the most resource-intensive form of media that your site will load. Loading full-size images will drastically affect the performance of your website.

To optimize an image. Make sure to only use .jpg image files. .png files save a lot more image data and can easily make an identical image four times the file size of a jpg. If you are using an image editor like photoshop you will have image options when you save. Save as the lowest quality you can before your image starts to look bad. When done right, it’s rare that the loss of image quality will be noticeable to an untrained eye.

After you save your image drop it into an image optimizer such as <a href="https://tinypng.com/" target="_blank" rel="noopener noreferrer" class="external">https://tinypng.com/</a>
This will optimize the image one step further for the web, typically cutting down the file size in half. You should shoot for under 100kb file size for all images you load to the site.

</div>

## Editing Basic Store Information

### Managing Store Info

1. Navigate to Appearance > Customize > Site Identity
2. Here you can edit your logo, site name, business address, phone, email, and business hours.
3. While in the customizer, you will see your website dynamically update with your changes. When ready to publish to the front-end of your website click Publish in the top left corner.

### Managing Social Media

1. Navigate to Appearance > Customize > Social Media
2. Here you can enter or edit your social media channels

## Create Coupons

WooCommerce has a built in way to provide coupons with flexible configurations. To learn more about coupons and what you can all do first <a href="https://woocommerce.com/posts/coupons-with-woocommerce/" target="_blank" rel="noopener noreferrer" class="external">read more about coupons</a>. To create a coupon:

1. Navigate to Marketing < Coupons
2. Give your coupon a title for the promotion. Optionally, add a description.
3. Select the type of coupone that you want to configure. WooCommerce has three coupon types so it's important to learn each type and what they can all do.
4. Fill in all your coupon data as needed, and click Publish when done.
5. Share your new coupon code on your social media pages, email campaigns or however else you intend to share it!

## Adding New Users

1. Type in the Username for your new account
2. Enter in the Email address of the new user
3. Enter in a First and Last name to make it clear who you are creating the account for
4. Select the type of role that you want to give the new user. You will likely want to choose Store Manager or Author depending on what they are going to be doing on the website. Read more about <a href="https://docs.woocommerce.com/document/roles-capabilities/" target="_blank" rel="noopener noreferrer" class="external">WooCommerce Roles</a> and <a href="https://wordpress.org/support/article/roles-and-capabilities/" target="_blank" rel="noopener noreferrer" class="external">WordPress Roles</a>.
