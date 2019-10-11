# Better Layout Hints
Magento 2 module to show better layout hints.

## Why?
The default layout hints in Magento 2 lack much of the needed information.
 
Because knowledge is key and information is primordial.

The goal is to provide all the additional information about the layout of the current page. 

This module provides information about each Container, Block and uiElement on the page. It does this in a
non-intrusive manner.

## Features

 - [x] Admin panel control 
 - [x] Console command line control
 - [x] Front-end hide/show function with `Shift + Ctrl + H`
 - [x] Non-intrusive display 
 - [x] Additional layout information at the bottom of the page. 

## How to use it?

### Frontend

You can use the `Shift + Ctrl + H` key combination on the frontend to toggle the display of the layout hints.

### Enable/Disable
You can enable the hints from the console or the admin panel.

**Console:**
```
justinkase:hints:on
justinkase:hints:off
```
*Note: Clear caches after!* `magento cache:flush` 

**Admin panel:**

`Stores > Configuration > JustinKase > Layout Hints` 

![](https://i.imgur.com/j4vgKKk.png)

## Screens
Bottom additional information
![](https://i.imgur.com/NhJhmco.png)

Non-intrusive display
![](https://i.imgur.com/BxpJZ1C.png)

## Author
[Alex Ghiban](mailto:drew7721@gmail.com)

