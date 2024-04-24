
 ## Update: Font Family - 
 ### Overview:
 As per our new brand guidelines, the font family of headings and body text has been updated to "Reckless" and "Accord" respectively. This update will be applied to all landing pages created using the latest template. There is no need to add a font-family externally as it will be fetched automatically. 

 ### Changes Made
 * Font family of headings updated to **"Reckless"**.
 * Font family of body text updated to **"Accord"**.

 <br>
 
 ## New Feature: Conditional Section BG classes.
 ### Overview:
 To ensure consistency with our brand guidelines, we have introduced automatic font color setting for sections in our landing pages. When specific background color classes are applied to a section, the font color will be automatically set to comply with our brand guidelines. Additionally, if a developer attempts to change the font color using inline styling, the script will check if the color is valid for the background and reset it if necessary.

### How It Works
* When a CSS class associated with one of the specified background colors is applied to a section, the font color will be automatically set to comply with our brand guidelines.

* If a developer tries to change the font color using inline styling, the script will check if the color is valid for the background and reset it if necessary.

### Available Section Classes and Colors:
* **.section_white**: Background color White, font color Onyx or Midnight Blue.
* **.section_darkblue**: Background color Midnight Blue, font color White, Horizon Blue, or Ice Blue.
* **.section_snowblue**: Background color Snow Blue, font color Onyx or Midnight Blue.
* **.section_iceblue**: Background color Ice Blue, font color Onyx or Midnight Blue.
* **.section_cyan**: Background color Horizon Blue, font color Onyx or Midnight Blue.
* **.section_green**: Background color Fresh Green, font color Onyx or Midnight Blue.
* **.section_gold**: Background color Honey Gold, font color Onyx or Midnight Blue.
* **.section_purple**: Background color Orchid Purple, font color White.

### Brand Guideline Colors
* **Horizon Blue**: #00B7F1
* **White**: #FFFFFF
* **Midnight Blue**: #000E4E
* **Fresh Green**: #81BB41
* **Ice Blue**: #BFEDFC
* **Orchid Purple**: #993399
* **Honey Gold**: #F4BE03
* **Onyx**: #020C33
* **Snow Blue**: #DFF6FE

### Benefits
* **Consistency**: Ensures that font colors in sections adhere to our brand guidelines, maintaining consistency across all landing pages.
* **Brand Compliance**: Helps us follow our brand guidelines strictly and maintain a consistent brand identity.

<br>


 ## New Feature: Automatic Button Styling for ``<a>`` Tags
 ### Overview
The ``<a>`` tags used to create buttons inside the sections will be automatically styled to a button that is valid to use with the specific background color class. This feature eliminates the need for developers to manually add class names or inline styles to the ``<a>`` tags for styling.

### How It Works
* ``<a>`` tags used to create buttons inside the sections will be automatically styled to match the background color class of the section.
* Certain class names like "video-popup" and "zenith-guarded" serve specific purposes and are acceptable.
* Additional classes and styles will be ignored by the script to maintain consistency.
* If you are linking an image, you should add the "thumbnail" class to the ``<a>`` tag, as shown in the example below.  

```html
<a href="#" class="thumbnail">
    <img src="#" alt="#">
</a>
```
 

### Accepted Classes for ``<a>`` Tags
* **thumbnail**
* **video-popup**
* **video-play-button**
* **zenith-guarded**
* **zenith-tracked**
* **video-play-button-darkBlue**
* **video-play-button-cyan**
* **video-play-button-center**
* **v-icon-radius**
* **no-shadow**

```html 
<a href="#" class="thumbnail video-popup zenith-guarded">Learn more</a>
```

### Benefits

* **Effortless Styling**: ``<a>`` tags are automatically styled to match the background color class of the section.
* **Simplified Development**: Developers do not need to manually add class names or inline styles for button styling.
* **Consistent Design**: Ensures consistency and adherence to design guidelines across all buttons.  
 
 <br>

 ## New Feature: Video Thumbnails with Customizable Play Icons
 ### Overview
 With our new feature, you can easily customize video thumbnails with different play icons by simply adding a class name to the anchor tag. This eliminates the need for the creative team to manually add play icons to thumbnails, saving time and effort.

 ### How It Works
* Simply add a specific class name to the anchor tag to choose from different play icon styles and positions.
* This feature gives developers the flexibility to choose the most suitable play icon for each thumbnail.

### Available Video Icon Classes
* **.video-play-button**: Play icon at the bottom left in white color with shadow.
* **.video-play-button-darkBlue**: Play icon at the bottom left in Midnight blue color with shadow.
* **.video-play-button-cyan**: Play icon at the bottom left in Horizon blue color with shadow.
* **.video-play-button-center**: Play icon at the center in Horizon blue color with no shadow.
* **.noShadow**: Removes shadow behind the icon.
* **.v-icon-radius**: Adds round edges to the thumbnail.

### Input:
```html
<a href="#" class="thumbnail video-play-button-cyan v-icon-radius">
    <img src="https://now.blueyonder.com/thumbnail.jpg" alt="video_thumbnail">
</a>
```
### output:
 
<img src="doc_images/ss.png" alt="drawing" width="400"/>
  
### Benefits
* **Effortless Customization**: Easily customize video thumbnails with different play icons.
* **Reduced Efforts**: Eliminate the need for the creative team to manually add play icons to thumbnails.
* **Enhanced Flexibility**: Developers can choose the most suitable play icon for each thumbnail.

<br>

 ## New Feature: Mobile Responsive Backgrounds
 ### Overview
 To enhance the legibility of content on mobile devices, we have introduced a new feature that provides fallback background colors for sections. These fallback background colors are based on the section BG class assigned during page development.

 ### Why We Implemented This Feature
 * **Improved Legibility**: On mobile devices, section background images may not always be fully visible, affecting the legibility of content.
* **Enhanced User Experience**: To ensure a consistent and legible viewing experience across all devices, we have introduced this feature.

### How It Works
* When viewing a page on a mobile device, if the section background image is not completely visible, the fallback background color, based on the section BG class, will be displayed.
* This ensures that content remains easily readable, even if the background image is not fully displayed.

### Benefits
* **Improved Readability**: Ensures that content remains easily readable on mobile devices, even if the section background image is not fully visible.
* **Consistent User Experience**: Provides a consistent viewing experience across all devices, enhancing user satisfaction.

<br>

 ## Update: Code Improvement, Bug Fixes, and Mobile Responsiveness
 ### Overview
 In addition to the new features, we have updated the code to fix several bugs and improve mobile responsiveness. These changes ensure that our landing pages display correctly and maintain a consistent user experience across all devices.

### Changes Made
* Fixed several bugs in the code.
* Improved mobile responsiveness to fix issues on various devices.
* Landing pages now display correctly and maintain a consistent user experience.

### Benefits
* **Enhanced User Experience**: Landing pages now display correctly on all devices, ensuring a consistent user experience.
* **Bug Fixes**: Several bugs in the code have been fixed, improving the overall performance and stability of our landing pages.


 
