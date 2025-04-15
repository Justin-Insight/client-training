---
title: "GreenWin Website Training"
description: "Website Training for GreenWin"
---

![GreenWin Website Screenshot](/images/greenwin-screenshot.jpg)

<h2>Table of Contents</h2>

- [Logging In](#logging-in)
- [Admin Dashboard Overview](#admin-dashboard-overview)
  - [Home](#home)
  - [Inboxes](#inboxes)
  - [Pages](#pages)
  - [Data](#data)
- [Editing Basic Website Information](#editing-basic-website-information)
  - [Managing Business Info](#managing-business-info)
  - [Managing Social Media](#managing-social-media)
- [Managing Pages](#managing-pages)
- [Editing Basic SEO Information](#editing-basic-seo-information)
- [Dynamic Blocks](#dynamic-blocks)
- [Adding New Team Member](#adding-new-team-member)
- [Adding New Projects](#adding-new-projects)
- [Special Considerations](#special-considerations)
  - [Image Handling](#image-handling)
  - [Uploading Images](#uploading-images)
  - [Bulk Saving of Edits](#bulk-saving-of-edits)

## Logging In

Your website content is managed with the content management system <a href="https://cloudcannon.com/" target="_blank" rel="noreferrer" class="external">CloudCannon</a>. To log in to your admin dashboard, navigate to

<a href="https://greenwindg.com/ic-sec=greenwin-admin" target="_blank" rel="noopener noreferrer" class="external">https://greenwindg.com/ic-sec=greenwin-admin</a>

Enter your password and click "Sign In".

## Admin Dashboard Overview

### Home

Home is where you can find your Live URL, a preview of your website, documentation, and a list of recent activity.

### Inboxes

See your form notifications, check spam, resend notification emails and export contacts to a spreadsheet.

### Pages

Here you will find a list of all your website pages. Pages are broken out by their section rather than being one large group.

### Data

Data acts as a database of global information used throughout your website. Data is split between Global Partials, Locations and Site Settings. Global Partials are common blocks used throughout the website such as global Call to Action blocks. Site Settings are general settings like your business name, address, phone number and so on.

## Editing Basic Website Information

### Managing Business Info

1. Navigate to Data > Site Settings.
2. Here you can edit your business name, address, phone, fax, email and social media links.
3. As soon as you make a change, you will see the save button in the top right corner activate. Click "Save" to publish your changes to the website, or continue to other pages that you need to edit. Alternatively, your changes will be bulk saved and you can publish all changes together.

### Managing Social Media

1. Navigate to Data > Site Settings.
2. Your website is preconfigured with options for Facebook, Instagram, X, LinkedIn, TikTok and YouTube.
3. Click on the social media platform you want to add a link to and simply paste your page's URL in the link field.
4. Click "Save", to publish your change. Alternatively, your changes will be bulk saved and you can publish all changes together. As soon as you add a link to any of these, the appropriate icon will be displayed in the footer of your website. 

## Managing Pages

1. Navigate to Pages. Here you will see a list of all your website's pages. Select the page you are looking for by clicking on the preview image of the page. You can also open the editor by clicking the three vertical dots in the top right corner and then selecting your options.
2. Once the editor is open you will see a similar content structure for all pages. All primary pages will contain a Title, SEO metadata, followed by all content blocks the page uses. 
3. To edit a content block, click on the content block field, this will open all the fields contained within the block. 
4. Once you are done making your changes, click "Save" in the top right corner, or continue to other pages that you need to edit. Your changes will be bulk saved and you can publish all changes together.

## Editing Basic SEO Information

If you ever feel the need to edit SEO metadata for your website, SEO settings can be found on each individual page. Navigate to the page you want to edit and click open the "SEO" content block. Here you will find Page Title, Meta Description, and Featured Image for your page.

## Dynamic Blocks

The employee spotlight, featured projects, blog feed, careers feed and services slider are populated with dynamic content and therefor cannot be previewed in the editor live preview. Placeholder data will be shown in the editor instead. 

## Adding New Team Member

1. To add a new team page, select the + Add button at the top right corner of the screen. Then click, + Add New Team Member. Optionally, you can also clone and existing post to use as a starting point.
2. Once the editor is open you will see a similar content structure as all your pages. The post editor will be split between two main sections, the <a href="https://cloudcannon.com/documentation/articles/introducing-the-data-editor/?ssg=Hugo#data-editing-with-the-sidebar" target="_blank" rel="noopener noreferrer nofollower">data editor</a> and the <a href="https://cloudcannon.com/documentation/articles/introducing-the-content-editor/?ssg=Hugo" target="_blank" rel="noopener noreferrer nofollower">content editor</a>.
3. Within the data editor, enter your post title, SEO data like page title, meta description and featured image, weight, job title and more.
4. **Note:** Your SEO featured image, is used two ways for team pages. The featured image is used in metadata for social media and search engines, but also as the featured image of the page itself. This get's displayed at the top of every page.
5. Add post content within the content editor and use the formatting options of the WYSIWYG editor to style your post as you need.
6. When ready to publish, ensure that your post is not in draft state and click Save.

## Adding New Projects

1. To add a new project, select the + Add button at the top right corner of the screen. Then click, + Add New Project. Optionally, you can also clone and existing post to use as a starting point.
2. Once the editor is open you will see a simpler content structure than the rest of your pages. The post editor will contain the <a href="https://cloudcannon.com/documentation/articles/introducing-the-data-editor/?ssg=Hugo#data-editing-with-the-sidebar" target="_blank" rel="noopener noreferrer nofollower">data editor</a>.
3. Within the data editor, enter your post title, edit SEO data like page title, meta description and featured image and more.
4. Optionally add a YouTube video ID if you have a YouTube video to display. 
5. Add additional project data like location and project complete date.
6. When ready to publish, ensure that your post is not in draft state and click Save.

## Special Considerations

### Image Handling

All images throughout the website are configured and served through an image transformation service called [Cloudinary](https://cloudinary.com/). Cloudinary automatically handles all images that are uploaded to the website, resizes them and transforms them into modern image formats like AVIF and WEBP.

### Uploading Images

<div class="warning">
<div class="warning__svg-wrapper">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><title>ionicons-v5-r</title><path d="M85.57,446.25H426.43a32,32,0,0,0,28.17-47.17L284.18,82.58c-12.09-22.44-44.27-22.44-56.36,0L57.4,399.08A32,32,0,0,0,85.57,446.25Z" style="fill:none;stroke-linecap:round;stroke-linejoin:round;stroke-width:32px"/><path d="M250.26,195.39l5.74,122,5.73-121.95a5.74,5.74,0,0,0-5.79-6h0A5.74,5.74,0,0,0,250.26,195.39Z" style="fill:none;stroke-linecap:round;stroke-linejoin:round;stroke-width:32px"/><path d="M256,397.25a20,20,0,1,1,20-20A20,20,0,0,1,256,397.25Z"/></svg>
</div>
<h4>Important!</h4>

You will never need to upload a full-resolution image to your website. Images are the most resource-intensive form of media that your website will load. Loading full-size images will negatively affect the performance of your website and will hurt your search rankings. If you're unsure how to handle images for the web, please reach out to <a href="https://insightcreative.com/contact/" target="_blank" rel="noopener noreferrer" class="external">Insight Creative, Inc.</a> for assistance.

To optimize an image: Use a tool like <a href="https://squoosh.app/" target="_blank">Squoosh</a> or another photo editing tool. Make sure to primarily use .jpg image files. .png files save a lot more image data and can easily make an identical image four times the file size of a .jpg. If you are using an image editor like Photoshop, you will have image options when you save. Save as the lowest quality you can before your image starts to look bad (usually 80% quality). You should almost always shoot for under 300kb file size for all images you load to the website. When done right, it’s rare that the loss of image quality will be noticeable.

After you save your image, the front end of the website will automatically optimize and transform your image into a more modern and performant image. This ensures your images are loading as fast as possible.

</div>

### Bulk Saving of Edits

You can now take advantage of CloudCannon's <a href="https://cloudcannon.com/blog/saving-time-our-new-editor-improvements/" target="_blank" rel="noopener noreferrer nofollower">bulk saving of edits</a>. Make multiple edits across pages, files, and collections and save them all simultaneously in a single batch. CloudCannon records your edits as you go, allowing you to save them all in one click. This means you only need to wait for your site to build once.
