# ecosystem

Submit a description of your app, integration, project, or ideas here. 

To add your project to the site, push a markdown file that uses the following structure to the content folder in this repository.

```
---
title: "REQUIRED The display title of your project"
icon: "REQUIRED A path to your project's icon. Note that your tile's highlight color will be based on this image."
description: "OPTIONAL A short description of your app. <64 characters"
category: "OPTIONAL a comma separated list of categories. See categories.json for a list of valid entries"
appStore: "OPTIONAL a download link for the Apple app store"
playStore: "OPTIONAL a download link for the Google play store"
signalBot: "OPTIONAL a download link for a Signal bot"
developer: "OPTIONAL your name or the name of your organization as you want it to appear on screen"
developerSite: "OPTIONAL a link to your website"
---
A long description of your proejct goes here. Any GFM syntax or HTML is allowed, and it will render in a blog-like fashion at https://developers.mobilecoin.com/ecosystem/\[title\], where the \[title\] slug is a sanitized version of the title provided in the head above.
```
