# scriptable-WordPress
iOS Scriptable Widget for WordPress Sites

This script should work for most WordPress sites with a standard REST API.

# Changelog

v1.0 - Initial Upload
v1.1 - fixed local date and time display, should now display properly according to your region
v1.2 - widget is now more customizable via parameters, even with custom background images! (see code comments for explanation)
v1.3 - fixed errors regarding urls with special characters

## Prerequisites:

Scriptable for iOS: [Link](https://apps.apple.com/de/app/scriptable/id1405459188)

## Config:

1. add the script to Scriptable
2. change SITE_URL and SITE_NAME to your preferred WordPress site
3. create a new widget on your Homescreen and assign the WordPress script
4. there are multiple parameters at the top of the script that you can change (background colors, gradients, font colors) 

You can change the size layout of the widget. Just long press on the widget and choose "edit widget".

![](https://github.com/Saudumm/scriptable-WordPress/blob/main/widget-config.PNG)

set on of the following parameters:
- **small** (standard) for small or medium widgets
  - this layout shows the latest post with a background image
- **medium** for medium widgets
  - this layout shows the two latest posts
- **large** for large widgets
  - this layout shows the five latest posts

## Examples:
![](https://github.com/Saudumm/scriptable-WordPress/blob/main/widget-examples.PNG)

top left: medium widget with standard parameter "small"

bottom left: smal widget with standard parameter "small"

top right: medium widget with parameter "medium"

bottom right: large widget with parameter "large"
