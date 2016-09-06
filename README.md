# FontIcons
Use windows fonts Segoe MDL2 Assets and Segoe UI Symbol to display font icons

## Description
While developing an app for the Band, I realized, there was no way to retrieve icons from the default band tiles, therefore I decided to go the old way of using icons. Now, since it is a Universal Platform Application, the app was expected to work across many different windows 10 platforms and screen sizes. One solution is to use an image file as an icon, which is pretty common, however, the image gets pixelated when the screen size increases and the image size is increased as well. Another solution is to use different icon files for different screen sizes, however, it is too much of hassle.  
An easier solution I found was using the font icons, already predefined in the fonts Segoe MDL2 Assets and Segoe UI Symbol, the best part is you can bind the font size to a particular value, depending upon the screen size and everything else is taken care. Another benefit of using font icons is that, in case you change the theme from light to dark, the icons are updated as well, depending on the theme.  

This UWP solution offers 3 unique ways to use font icons:  
- Using TextBlock
- Using FontIcon
- Using SymbolIcon

## Screenshots
![Alt text](/FontIcons.jpg?raw=true Windows 10 UWP Font Icons Segoe MDL2 Segoe UI")
