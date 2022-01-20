---
title: "A to Z Machine Website Training and Documentation"
description: "Website Training for A to Z Machine"
---

![A to Z Machine Website Screenshot](/images/a-to-z-machine-website-screenshot.jpg)

# Table of Contents

- [Table of Contents](#table-of-contents)
  - [Logging in](#logging-in)
    - [Trouble Logging in?](#trouble-logging-in)
  - [Admin Dashboard Overview](#admin-dashboard-overview)
    - [Collections](#collections)
  - [Managing Content](#managing-content)
    - [Editing Basic Business Information](#editing-basic-business-information)
    - [Editing Pages](#editing-pages)
    - [Adding New Hero Images](#adding-new-hero-images)
    - [Adding New Blog Posts](#adding-new-blog-posts)
    - [Adding New Equipment](#adding-new-equipment)
    - [Adding Gallery Images](#adding-gallery-images)
  - [Shortcodes](#shortcodes)
    - [Figure](#figure-example)
    - [Image Grid](#image-grid-example)
    - [Image Thumbnail](#image-thumbnail-example)
    - [Image Medium](#image-medium-example)
    - [YouTube Embed](#youtube-embed-example)
    - [Vimeo Embed](#vimeo-embed-example)
    - [Instagram Embed](#instagram-embed-example)
    - [Tweet Embed](#tweet-embed-example)
  - [Special Considerations](#special-considerations)

## What is Jamstack?

Welcome to your new Jamstack website! Jamstack is an simpler architecture designed to make the web faster, more secure, and easier to scale. The core principles of pre-rendering and decoupling enable sites and applications to be delivered with greater confidence and resilience than ever before.

Here are the main benefits provided by the Jamstack.

#### Faster performance

Serve pre-built markup and assets over a Content Delivery Network.

#### More secure

No need to worry about server or database vulnerabilities.

#### Scalability

If your website suddenly goes viral and has many active users, the CDN seamlessly compensates.

## Logging in

1. Navigate to <a href="https://www.atozmachine.com/admin/#/" target="_blank" rel="noopener noreferrer" class="external">https://www.atozmachine.com/admin/#/</a>
2. Click **_Login with Netlify Identity_**
3. Enter your email and password and click **_Log in_**

### Trouble Logging in?

1. Click **_Login with Netlify Identity_**
2. Click **_Forgot password?_** at the bottom of the Log in form
3. Enter the email address your account was set up with and click **_Send recovery email_**
4. Check your email and follow the steps to update your password

## Admin Dashboard Overview

Your website uses Netlify CMS for a back-end Content Management System. Unlike older CMS' Netlify CMS focuses on only the items you need and cuts out everything unnecessary. Your content is stored and can be found in Collections.

### Collections

Collections are the groupings of editable content for your website. This website consists of Data, Posts, Equipment and Pages.

## Managing Content

### Editing Basic Business Information

To edit content such as business name, phone number and hours:

1. Navigate to Data > Business Info.
2. Here you'll find options to edit business name, phone number, email address, address and hours. Make your desired change as needed and click **_Publish_** in the top left corner when you're ready to save and publish your change.

### Editing Pages

1. Click on **_Pages_** in the Collections menu. Here you'll see a list of all your website's pages.
2. Click on the page that you need to edit. Pages are broken out into three core sections, Page Title, SEO and Page Content.
   1. Page Title. This is your page's primary title.
   2. SEO. SEO contains your SEO Title, Description and Featured Image. The SEO Title is the page title that gets used by search engines, not a front-facing page title. Description is the meta description that gets used by search engines. Featured Image is an image that you can select that will be used as a featured image for social sharing. Note: this image doesn't actually get used on your website, only as a preview image when the website gets shared on social media.
   3. Page Content. While this isn't necessarily labeled as such, the remaining fields are all your actual page content. Content is structured in the same order it is displayed on your page.
3. When ready to publish, simply click the **_Publish_** button in the top right corner.

### Adding New Hero Images

The hero images for all pages need to be sized at 2500x1000. These images are then automatically scaled, resized for smaller devices, and transformed to serve modern image formats. Always upload images as .jpg images. Using .png images will break resizing and transformation functions.

### Adding Gallery Images

The product galleries can be found on both the CNC Machining and Fabrication pages. Navigate down to the Parts Gallery section, here you will find a list of all your gallery images. Click open the accordion-style box to open the image options. Here you will find, an Image Small, Image Alt Text, and Image Large. Image Small is the preview or thumbnail image. Image alt text is alternative text or a description of your image that will be used by screen readers. Image Large is your full-size image that gets opened in the lightbox if an image is clicked.

Gallery images need to be cropped to a square size to fit their given space, other image sizes will be stretched to fit the space. The Image Small version uses a 600 x 600 image, and the Image Large uses a 1600 x 1600 version of the image.

<div class="warning">
<div class="warning__svg-wrapper">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><title>ionicons-v5-r</title><path d="M85.57,446.25H426.43a32,32,0,0,0,28.17-47.17L284.18,82.58c-12.09-22.44-44.27-22.44-56.36,0L57.4,399.08A32,32,0,0,0,85.57,446.25Z" style="fill:none;stroke-linecap:round;stroke-linejoin:round;stroke-width:32px"/><path d="M250.26,195.39l5.74,122,5.73-121.95a5.74,5.74,0,0,0-5.79-6h0A5.74,5.74,0,0,0,250.26,195.39Z" style="fill:none;stroke-linecap:round;stroke-linejoin:round;stroke-width:32px"/><path d="M256,397.25a20,20,0,1,1,20-20A20,20,0,0,1,256,397.25Z"/></svg>
</div>
<h4>Important!</h4>

You will never need to upload a full resolution image to your website. Images are the most resource-intensive form of media that your website will load. Loading full-size images will negatively affect the performance of your website and will hurt your search rankings. If you're unsure how to handle images for the web, please reach out to <a href="https://insightcreative.com/contact/" target="_blank" rel="noopener noreferrer" class="external">Insight Creative, Inc.</a> for assistance.

To optimize an image: make sure to only use .jpg image files. .png files save a lot more image data and can easily make an identical image four times the file size of a .jpg. If you are using an image editor like Photoshop, you will have image options when you save. Save as the lowest quality you can before your image starts to look bad (usually 80% quality). When done right, it’s rare that the loss of image quality will be noticeable to an untrained eye.

After you save your image, the front end of the website will automatically optimize and transform your image into a more modern and performant image. This ensures your images are loading as fast as possible. You should always shoot for under 200kb file size for all images you load to the website.

</div>

### Adding New Blog Posts

1. Click on **_Post_** in the Collections menu and then click **_New Post_**. You can also click **_Quick add_**, in the primary navigation menu, and then click **_Post_** from the dropdown.
2. Posts are broken out into three core sections, Post Title, SEO and Body Content. Enter in your title, SEO title, date, draft state, description, image and body.
3. Post Title. This is your post's primary title.
4. SEO. SEO contains your SEO Title, Description and Featured Image. The SEO Title is the page title that gets used by search engines, not a front-facing page title. Description is the meta description that gets used by search engines. Featured Image is an image that you can select that will be used as a featured image for social sharing. Note: this image doesn't actually get used on your website, only as a preview image when the website gets shared on social media.
5. Body Content. This will be the main body that holds all the content of your new post.
6. Select your post's Publish Date. Typically it's best practice to set your date to the current date and time of writing. If scheduling posts is a feature requirement for content management, additional functionality will need to be built into the CMS to allow this.
7. Select the category you want your post to be grouped within. Currently the category options are "Articles" and "News".
8. Write out the main body of your post as needed using the rich text editor. In addition to the rich text editor, shortcodes allow injection of templated code blocks to add a little more power and flexibility to your posts. [See the Shortcodes section](#shortcodes) for more detailed information on how to use these.
9. When ready to publish, simply click the **_Publish_** button in the top right corner.

### Adding New Equipment

1. Click on **_Equipment_** in the Collections menu and then click **_New Equipment_**. You can also click **_Quick add_**, in the primary navigation menu, and then click **_Equipment_** from the dropdown.
2. Equipment pages are broken out into three core sections, Page Title, SEO and Body Content. Enter in your title, SEO title, date, draft state, description, image and body.
3. Page Title. This is your page's primary title.
4. SEO. SEO contains your SEO Title, Description and Featured Image. The SEO Title is the page title that gets used by search engines, not a front-facing page title. Description is the meta description that gets used by search engines. Featured Image is an image that you can select that will be used as a featured image for social sharing. Note: this image doesn't actually get used on your website, only as a preview image when the website gets shared on social media.
5. Body Content. This will be the main body that holds all your pages content.
6. Write out the main body of your page as needed using the rich text editor.
7. When ready to publish, simply click the **_Publish_** button in the top right corner.

## Shortcodes

Shortcodes are a convenient way to inject templated code blocks into your content without needing to actually write any HTML code. Your website comes configured with a number of pre-built shortcodes that are ready to use. New shortcodes can also be built to accomodate future additions.

Some of the available shortcodes are:

- [Figure](#figure-example)
- [Image Grid](#image-grid-example)
- [Image Thumbnail](#image-thumbnail-example)
- [Image Medium](#image-medium-example)
- [YouTube Embed](#youtube-embed-example)
- [Vimeo Embed](#vimeo-embed-example)
- [Instagram Embed](#instagram-embed-example)
- [Tweet Embed](#tweet-embed-example)

To use shortcodes you will need to use a much simpler syntax by using

\{\{\< shortcode-name-here >\}\}

### Figure Example

Use a figure shortcode to mark up a photo in a document, and a title element to define a caption for the photo

\{\{\< figure src="image-url.jpg" title="image caption here" \>\}\}

### Image Grid Example

Display a grid of up to four images

\{\{\< image-grid image1="image1-url.jpg" image2="image2-url.jpg" image3="image3-url.jpg" image4="image4-url.jpg" \>\}\}

### Image Thumbnail Example

Display a thumbnail sized version of an image

\{\{\< image-thumbnail image="image-url.jpg" image_alt="image alternative text here" \>\}\}

### Image Medium Example

Display a medium sized version of an image

\{\{\< image-medium image="image-url.jpg" image_alt="image alternative text here" \>\}\}

### YouTube Embed Example

The YouTube shortcode embeds a responsive video player for YouTube videos. Only the ID of the video is required. Copy the YouTube video ID that follows v= in the video’s URL and pass it to the YouTube shortcode.

\{\{\< youtube BHACKCNDMW8 \>\}\}

For accessibility reasons, it’s best to provide a title for your YouTube video. You can do this using the shortcode by providing a title parameter. If no title is provided, a default of “YouTube Video” will be used.

\{\{\< youtube id="BHACKCNDMW8" title="3 Hours of Amazing Nature Scenery" \>\}\}

### Vimeo Embed Example

Adding a video from Vimeo is equivalent to the YouTube shortcode, simply extract the Vimeo video ID and pass it to the shortcode

\{\{\< vimeo 146022717 \>\}\}

For accessibility reasons, it’s best to provide a title for your Vimeo video. You can do this using the shortcode by providing a title parameter. If no title is provided, a default of “Vimeo Video” will be used.

\{\{\< vimeo id="146022717" title="The Clock of the Long Now" \>\}\}

### Instagram Embed Example

If you’d like to embed a photo from Instagram, you only need the photo’s ID. You can find an Instagram photo ID in the URL

example URL https://www.instagram.com/p/BWNjjyYFxVx/

\{\{\< instagram BWNjjyYFxVx \>\}\}

### Tweet Embed Example

You want to include a single tweet into your blog post? Everything you need is the URL of the tweet

example URL https://twitter.com/SanDiegoZoo/status/1453110110599868418

\{\{\< tweet user="SanDiegoZoo" id="1453110110599868418" \>\}\}

## Special Considerations

Your new Jamstack website does all the work up front to prepare files for your website visitors so pages can be delivered much faster. After editing a page's content, sit back, and enjoy some coffee. Give it a minute to rebuild your website, and then go view your newly published change on the front end of your website.

**_Pro Tip:_** If planning to make multiple changes to your content at the same time, make your easy changes first (an edit to an existing page). While your website rebuilds, you can then tackle your larger change (writing a new blog post). This leads to an editing process that still feels productive and reduces waiting times.
