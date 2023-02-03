---
title: "Whistler's Run & Rescue Website Training Manual"
description: "Website Training for Whistler's Run & Rescue"
---

![Whistler's Run & Rescue Website Screenshot](/images/whistlers-run-homepage-screenshot.jpg)

# Table of Contents

- [Table of Contents](#table-of-contents)
  - [What is Jamstack?](#what-is-jamstack)
    - [Faster performance](#faster-performance)
    - [More secure](#more-secure)
    - [Scalability](#scalability)
  - [Logging In](#logging-in)
  - [Admin Dashboard Overview](#admin-dashboard-overview)
    - [Home](#home)
    - [Inbox](#inbox)
    - [Pages](#pages)
    - [Data](#data)
  - [Editing Basic Website Information](#editing-basic-website-information)
    - [Managing Business Info](#managing-business-info)
    - [Managing Social Media](#managing-social-media)
  - [Managing Pages](#managing-pages)
  - [Adding Events](#adding-events)
  - [Editing Basic SEO Information](#editing-basic-seo-information)
  - [Inbox](#inbox-1)
  - [Special Considerations](#special-considerations)
    - [Image Handling](#image-handling)
    - [Uploading Images](#uploading-images)
    - [Bulk Saving of Edits](#bulk-saving-of-edits)
    - [Build Times](#build-times)

## What is Jamstack?

Welcome to your new Jamstack website! Jamstack creates a simple website architecture that makes your website faster, more secure and scalable. Jamstack’s core principles of pre-rendering and decoupling enable your website to be delivered with greater confidence and resilience than ever before.

Here are the main benefits of Jamstack:

### Faster performance

Serve pre-built markup and assets over a Content Delivery Network.

### More secure

No need to worry about server or database vulnerabilities.

### Scalability

If your website suddenly goes viral and has many active users, the CDN seamlessly compensates.

## Logging In

Your website content is managed with the content management system <a href="https://cloudcannon.com/" target="_blank" rel="noreferrer" class="external">CloudCannon</a>. To log in to your admin dashboard, navigate to

<a href="https://www.whistlersrun.com/ic-sec=whistlers-admin" target="_blank" rel="noopener noreferrer" class="external">https://www.whistlersrun.com/ic-sec=whistlers-admin</a>

Enter your password and click "Sign In".

## Admin Dashboard Overview

### Home

Home is where you can find your Live URL, a preview of your website and a list of recent activity.

### Inbox

Inbox is where you can view and manage the email notifications from your contact forms.

### Pages

Here you will find a list of all your website pages.

### Data

Data acts as a database of global information used throughout your website. Data is split between Global Partials and Site Settings. Global Partials are common blocks used throughout the website such as global Call to Action blocks. Site Settings are general settings like your business name, address, phone number and so on.

## Editing Basic Website Information

### Managing Business Info

1. Navigate to Data > Site Settings.
2. Here you can edit your business name, address, phone, fax, email and social media links.
3. As soon as you make a change, you will see the save button in the top right corner activate. Click "Save" to publish your changes to the website. Or continue to other pages that you need to edit. Your changes will be bulk saved and you can publish all changes together.

### Managing Social Media

1. Navigate to Data > Site Settings.
2. Your website is preconfigured with options for Facebook, Instagram, Twitter, LinkedIn, and YouTube.
3. Click on the social media platform you want to add a link to and simply paste your page's URL in the link field.
4. Click "Save", to publish your change. As soon as you add a link to any of these, the appropriate icon will be displayed in the "Connect With Us" section in the footer of your website.

## Managing Pages

![Whistler's Run Editor Preview Screenshot](/images/whistlers-run-cloudcannon-editor-preview.jpg)

1. Navigate to Pages. Here you will see a list of all your website's pages. Select the page you are looking for by clicking on the preview image of the page. You can also open the editor by clicking the three vertical dots in the top right corner and then selecting your options.
2. **Note:** To open the visual editor, if not already open by default, click the three vertical dots and choose, "Open With >" and then select "Visual Editor.” If already in the editor, open the dropdown menu in the top left corner and select visual editor.
3. Once the editor is open you will see a similar content structure for all pages. All primary pages will contain a Title, SEO, Menu, Hero, and Intro, followed by all content blocks the page uses. Each content block gives a brief overview of what is contained within it.
4. To edit a content block, click on the content block field, this will open all the fields contained within the block. Once you are done making your changes, click "Save" in the top right corner of the editor.

## Adding Events

Event management is done through the events management software Loxi.
1. Log into <a href="https://loxi.io/login/" target="_blank" rel="noopener noreferrer nofollower">Loxi</a>.
2. Click the plus icon in the left hand sidebar area called "Create an Event".
3. Enter in your event title and event date at a mimimum in order to get started. Optionally, add in your event image and description.
4. After your initial event details are started, you will be taken to the full events settings page. Go through all of these options to find all the options available for your event.
5. Click the "Publish" button at the bottom right of the page to publish your new event.

## Editing Basic SEO Information

![Whistler's Run SEO Preview Screenshot](/images/whistlers-run-cloudcannon-seo-preview.jpg)

If you ever feel the need to edit SEO metadata for your website, SEO settings can be found on each individual page. Navigate to the page you want to edit and click open the "SEO" content block. Here you will find Page Title, Meta Description, and Featured Image for your page.

## Inbox

Inbox is where you can view and manage the email notifications from your contact forms. When you enter your inbox, you will see a list of all mail notifications that you have received. Click on any notification to view the full email details. You can also click the three vertical dots in the right corner to find options to resend the message, mark as spam, or delete the message.

## Special Considerations

### Image Handling

All images throughout the website are configured and served through an image transformation service called [Imagekit.io](https://imagekit.io/). Imagekit automatically handles all images that are uploaded to the website, resizes them and transforms them into modern image formats like AVIF and WEBP.

### Uploading Images

<div class="warning">
<div class="warning__svg-wrapper">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><title>ionicons-v5-r</title><path d="M85.57,446.25H426.43a32,32,0,0,0,28.17-47.17L284.18,82.58c-12.09-22.44-44.27-22.44-56.36,0L57.4,399.08A32,32,0,0,0,85.57,446.25Z" style="fill:none;stroke-linecap:round;stroke-linejoin:round;stroke-width:32px"/><path d="M250.26,195.39l5.74,122,5.73-121.95a5.74,5.74,0,0,0-5.79-6h0A5.74,5.74,0,0,0,250.26,195.39Z" style="fill:none;stroke-linecap:round;stroke-linejoin:round;stroke-width:32px"/><path d="M256,397.25a20,20,0,1,1,20-20A20,20,0,0,1,256,397.25Z"/></svg>
</div>
<h4>Important!</h4>

You will never need to upload a full-resolution image to your website. Images are the most resource-intensive form of media that your website will load. Loading full-size images will negatively affect the performance of your website and will hurt your search rankings. If you're unsure how to handle images for the web, please reach out to <a href="https://insightcreative.com/contact/" target="_blank" rel="noopener noreferrer" class="external">Insight Creative, Inc.</a> for assistance.

To optimize an image: make sure to only use .jpg image files. .png files save a lot more image data and can easily make an identical image four times the file size of a .jpg. If you are using an image editor like Photoshop, you will have image options when you save. Save as the lowest quality you can before your image starts to look bad (usually 80% quality). You should almost always shoot for under 300kb file size for all images you load to the website. When done right, it’s rare that the loss of image quality will be noticeable to an untrained eye.

After you save your image, the front end of the website will automatically optimize and transform your image into a more modern and performant image. This ensures your images are loading as fast as possible.

</div>

### Bulk Saving of Edits

You can now make multiple edits across pages, files, and collections and save them all simultaneously in a single batch. CloudCannon records your edits as you go, allowing you to save them all in one click. This means you only need to wait for your site to build once.

### Build Times

Your new Jamstack website does all the work upfront to prepare files for your website visitors so pages can be delivered much faster. At the time of the website launch, your site is loading at around 600ms\*.

After editing a page's content, sit back, and enjoy some coffee. Give it a minute to rebuild your website and then go view your newly published change on the front end of your website. Builds typically take about 14 seconds, on average.
