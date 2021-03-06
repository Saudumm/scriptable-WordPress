# THIS SCRIPT WON'T BE SUPPORTED ANY LONGER
# PLEASE CHECK OUT THE NEW SCRIPT:
# https://github.com/Saudumm/scriptable-News-Widget

# Old text:
## scriptable-WordPress
iOS Scriptable Widget for WordPress Sites

This script should work for most WordPress sites with a standard REST API.

## Requirements:

Scriptable for iOS: [Link](https://apps.apple.com/de/app/scriptable/id1405459188)

## Changelog

- v1.0 - Initial Upload
- v1.1 - fixed local date and time display, should now display properly according to your region
- v1.2 - widget is now more customizable via parameters, even with custom background images! (see code comments for explanation)
- v1.3 - fixed errors regarding urls with special characters
- v1.4 - custom widget backgrounds on every widget size and config
- v1.5 - massive code cleanup, new descriptions for widget customization
- v1.5.1 - fix numeric display of date and time
- v1.5.2 - added twitter handle
- v1.6.0 - added blur effect option for background images (and post images in small widgets)
- v1.6.1 - fixed post date/time display

---

_If someone would like to buy me a coffee 😊: https://ko-fi.com/saudumm_

---

## Config:

1. add the script to Scriptable
2. change SITE_URL and SITE_NAME to your preferred WordPress site
3. create a new widget on your Homescreen and assign the WordPress script
4. there are multiple parameters at the top of the script that you can change (background colors, gradients, font colors) 

You can change the layout and look of the widget. Just long press on the widget and choose "edit widget".

![widget-config](https://user-images.githubusercontent.com/810494/97677556-b9390000-1a92-11eb-8a7e-0ece134e8f59.PNG)

### Widget parameters
 - example: small|https://www.stadt-bremerhaven.de|Caschys Blog|background.jpg
 - parameter order has to be: widget size, site url, site name, background image
 - parameters have to be separated by |
 - You can omit parameters, for example background image: small|https://www.stadt-bremerhaven.de|Caschys Blog
 - you can just set "small", "medium" or "large" as a parameter
 - parameters that are not set will be set by the standard widget config


## Examples:

![widget-examples](https://user-images.githubusercontent.com/810494/97783785-3ac78580-1b9a-11eb-93f2-265264eb11f8.jpg)

- top left: small widget with standard parameters
- top middle:  small widget with standard parameters and a custom background image
- top right: medium widget with parameter "medium"
- middle left: medium widget with standard parameter "small"
- bottom left: medium widget with parameter "medium" and a custom background image
- bottom right: large widget with parameter "large" and a custom background image

## WordPress Websites:

Here are a few suggestions:

### Gaming:
- PlayStation Blog: http://blog.playstation.com
- PlayStation Blog Germany: http://blog.de.playstation.com
- Xbox Wire US: https://news.xbox.com/en-us
- Xbox Wire Germany: https://news.xbox.com/de-de
- Dualshockers: https://www.dualshockers.com

### Tech: 
- 9to5Mac: https://9to5mac.com
- 9to5Google: https://9to5google.com
- TechCrunch: https://techcrunch.com
- VentureBeat: https://venturebeat.com
- Wired: https://wired.com
