# Omeka-S-theme-IIP
 Omeka-S theme built for the International Institute for Peace, Rutgers University

Created by Anneliese Dehner http://anneliesedehner.com/, 2017

Compatible with Omeka-S v1.1 and Omeka-S 2.x (latest tested, 2.1.2)  
https://github.com/omeka/omeka-s

![Screenshot of theme in production](docs/screenshot1.png?raw=true "Screenshot of theme")

# Theme requirements
 *Reference module (daniel-km)*  
 https://github.com/Daniel-KM/Omeka-S-module-Reference
 
 *Generic module (daniel-km)* (required by Reference)   
 https://github.com/Daniel-KM/Omeka-S-module-Generic
 
# Theme features
 *List view*  
 Standard listing

![Screenshot of list view in Item Browse](docs/screenshot3.png?raw=true "Screenshot of list view")
 
 *Grid view*  
 "Stacked" image-based grid (Pinterest-style)

![Screenshot of grid view in Item Browse](docs/screenshot4.png?raw=true "Screenshot of grid view")
 
 *"Quick search" sidebar*  
 Utilizes Reference module. Does not provide multi-click faceted searching, just one-click searches.

![Screenshot of term lists in Item Browse](docs/screenshot5.png?raw=true "Screenshot of term lists")
 
# Theme settings
![Screenshot of theme settings in admin area](docs/screenshot8.png?raw=true "Screenshot of theme settings")

 *Top Navigation Depth*  
 Maximum number of levels to show in the site's top navigation bar. Set to 0 to show all levels.

 *Logo*  
 Can attach a media asset (JPG, PNG, etc.)

 *Footer Content*  
 HTML content to appear in the footer

![Screenshot of theme settings in admin panel](docs/screenshot2.png?raw=true "Screenshot of theme settings")

# Customization

 To customize the theme to your project, you will want to modify the following portions of the theme:
 
 *Banner graphic*   
 
 The banner file is coded into the theme directly at **files/asset/6394f1d86f058a725b421882d1c69a8cf986fbb2.png**
![Screenshot of theme banner](docs/screenshot7.png?raw=true "Screenshot of theme banner")

 You will find the site banner coded in **/view/layout/layout.phtml** in the tag **`<a id="institution-logo">`**
 
 The banner can vary in width from a small square, to a rectangle, to extending across the entire screen.
 
 *Logo image*   
 
 The logo file is not set by default, and can be uploaded/attached via *Sites > Theme > Edit theme settings*. The logo appears in the top right corner, to the right of the banner (outlined in blue in the example screenshot below). An appropriate size/ratio would be around 250px by 75px.

![Screenshot of theme header with logo outlined in blue](docs/screenshot6.png?raw=true "Screenshot of theme header with logo")

 *Sidebar*
 
 The sidebar is coded into the theme directly at **view/common/refine-list.phtml**. 
 