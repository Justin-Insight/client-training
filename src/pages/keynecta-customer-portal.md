---
title: "Keynecta Customer Portal Website Training"
description: "Website Training for Keynecta"
---

![Keynecta Website Screenshot](/images/keynecta-dashboard-screenshot.jpg)

<h2>Table of Contents</h2>

- [Logging In](#logging-in)
- [Adding a New Customer Portal](#adding-a-new-customer-portal)
- [Editing Customer Portal Content](#editing-customer-portal-content)
- [Adding a Password](#adding-a-password)
- [Adding a Custom Domain](#adding-a-custom-domain)
- [Removing a Custom Domain](#removing-a-custom-domain)

## Logging In

Your customer portal content is managed with the content management system <a href="https://cloudcannon.com/" target="_blank" rel="noreferrer" class="external">CloudCannon</a>. To log in to your admin dashboard, navigate to

<a href="https://app.cloudcannon.com" target="_blank" rel="noopener noreferrer" class="external">https://app.cloudcannon.com</a>

Enter your username and password and click "Sign In".

## Adding a New Customer Portal

1. Click "Add new Site"
2. Select "Build with your own files"
3. Site name: Enter your customer name as the name of your new site
4. File source: Navigate to the "File source" dropdown menu and select GitHub repository.
5. Repository: From the Repository dropdown select "Keynecta/client-portal.keynecta.com"
6. Branch setup: Choose "Create a new branch"
7. Source branch: From the "Source branch" dropdown, select "main". This allows you to create a copy of the base template for your new customer portal.
8. New branch name: use your customer name as your branch name. You will probably never need this again, but this will help organize the source code within the repository.
9. Click "Sync Files"
10. Build options: you don't need to worry about anything here, just click "Build site" to complete

## Editing Customer Portal Content

1. From the main dashboard, click "Update home". Alternatively, click "Pages", then click "Home"
2. By default, the customer portal starter template will contain two content blocks, a hero section and content cards. Click on either to open the details of that block.
3. Each field will be slightly different depending on the content type. Heading fields are a simple text input, body fields use a full WYSIWYG editor with more advanced controls and the ability to use bold, italics, lists and more. 
4. When satisfied with your changes, click "Save" in the top right corner

## Adding a Password

1. Navigate to Site Settings > Authentication
2. Authenticaion: From the dropdown switch from the default of "None" to "Password"
3. Click "Switch to Password Authentication"
4. Site Password: Enter in your password of choice
5. Click "Update Site Password"

## Adding a Custom Domain

1. Navigate to Site Settings > Custom Domain
2. Choose your hosting option: Leave at the defaul of "Add new custom domain"
3. Domain Name: Enter in your custom domain in the format of customer-name.keynecta.com
4. Click "Add Domain"
5. You will be prompted with a "Confirm Billing Change", select "Accept Billing Increase"
6. That's it! Things like the SSL certificate will automatically install. It will take a few minutes to get set up.

## Removing a Custom Domain

1. Navigate to Site Settings > Custom Domain
2. Click "Remove"
3. Remove "Remove Custom Domain"
4. Click "Click to confirm"