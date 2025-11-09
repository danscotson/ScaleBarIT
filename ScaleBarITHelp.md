# ScaleBarIT Guide



**Welcome to the ScaleBarIT guide**.



Updated by Dan Scotson, 09/11/2025 for ScaleBarIT's version 2.0.



ScaleBarIT enable users to **add scale bars to images** quickly and efficiently. **The basic steps involve choosing your image, specifying its pixel size (if not done automatically), then choosing a region of interest and finally adding your scale bar of choice**.



Dan has built this capability during his PhD in a Materials Science field and hopes the distribution of this app will provide a tailored and simple solution to adding scale bars to images.



The current version of ScaleBarIT can be found at GitHub or Zenodo.

* **GitHub:** [https://github.com/danscotson/ScaleBarIT/](https://github.com/danscotson/ScaleBarIT/)
* **Zenodo:** [https://doi.org/10.5281/zenodo.13998539](https://doi.org/10.5281/zenodo.13998539)



If you have any **further questions**, please get in touch with Dan at **daniel.scotson@manchester.ac.uk**.



## Getting started:

Install with the ScaleBarIT\_installer.exe from the repository.

## Instructions on use:

There are **five major steps** that can be performed in ScaleBarIT. Guiding you through these steps in the app is a **colour coding system - red = not possible yet, blue = possible and green = complete**.

1. Select Image
2. Select Pixel Size
3. Region of Interest Method
4. Add Scale Bar
5. Save Image

## Major steps in ScaleBarIT:

The following steps should be followed to add scale bars to your images.

### 1\. Select Image

Select an image file of your choice and visualise this in the app. Once, you've added an image, the current folder is saved so that if you want to add another scale bar to a different image you will return to this folder.

### 2\. Select Pixel Size

Selecting the pixel size of your image is really important.

Firstly, the app will try to automatically extract the pixel size from the metadata of the image. If this is not possible, selecting the pixel size can be performed by two methods. The interface used to do this is new for v2.0.

#### Option 1. Known (i.e. you know what the pixel size is).

* Enter the known pixel size and the units. These units will be used as the default display for the resulting scale bar. This can be changed in the 'units' menu.

#### Option 2. From Image (i.e. there's an existing scale bar or known distance in the uploaded image that can be used).

* Select two points to define the horizontal distance (note - even if there is vertical differences between the points, only the horizontal distance between the two points will be used). These can be dragged and adjusted as needed.
* Then enter the known horizontal distance with the correct units. These units will be used as the default display for the resulting scale bar. This can be changed in the 'units' menu.



### 3\. Region of Interest Method

You don't want all your image being displayed?

You have two options here:

#### A. Point (i.e. Centre the new image around a point in the existing image)

* Click on the Point button then proceed to select a single point on the image. Then press Confirm!

#### B. Crop (i.e. Select a region of interest)

* Click on Crop button and then proceed to draw a rectangle on the image. This can be adjusted and rescaled. When happy, just press Confirm!



### 4\. Add Scale Bar

Two options are available for adding scale bars:

#### A. Suggested Scale Bar

Automatic suggestions of scale bars that are half of your image size after the pixel size has been determined.

#### B. Custom Scale Bar

Set a custom scale bar (choose your value in the edit field) with the unit of choice.

### 5\. Exporting image:



* #### Copy
* Press the copy button to add the current display into the clipboard. Once, performed the text in the feedback box will be updated to 'copied'.
* Paste the image with the scale bar in your chosen application - for example, add the image to a powerpoint slide. This will copy as a vector graphic, so the scale bar will remain sharp upon rescaling.
* #### Save

You have two options to save the image.

##### 1\. Press the Save Image button once it is blue or green.

The image will be saved in a location of your choice with \_proc\_SB added to the filename.

##### 2\. Press the Save Button that appears in the top right toolbar of the image.

## Key bits:

* Grayed out labels are not enabled and need another step before becoming available.
* Feedback to user gives tips as to what is next/what has happened.
* Hover over buttons or functionality to get further help in the user interface.

## Menus:

### 1\. Reset

* Made an error or want to reload another image/start again. This is equivalent to closing the app and reopening the app.

### 2\. Scale Bar Appearance

* #### Text:

Change the colour, fontname, fontweight, fontstyle and size of the font.

* Colour: User interface for changing the text colour.
* Fontname and Size: User interface for changing the font, the fontweight font style,  and also its size for the scalebar text.
* #### Background:

Change the colour and transparency of the background to the scalebar.

* #### Padbar:

Change the style of the scalebar used.

1. External - Scalebar appears outside of the original image with a selected background colour and transparency.
2. Internal - Scalebar appears inside the original image with a selected background colour and transparency.
3. No Bar - Only the scalebar appears within the original image without a background.
4. Height - Change the height of the external and internal bar. This might be needed to account for a bigger font size.

* #### Scale Bar Style:
* H - In the style of an elongated H with end bars where the maximum horizontal distance of the scale bar is the distance. The thickness of these end bars can also be set here.
* Solid - A solid, rectangle shaped scale bar.
* Customise the font name, font size and font weight (e.g. bold or normal).
* #### Scale Bar Style:

Select position of the scale bar (e.g. bottom left or bottom right).

### 3\. Edit Image

* #### Rotate

Rotate the image clockwise or anticlockwise by 90°.

* #### Autocrop

If the image is recognised from its metadata, this will remove the existing scale bar area from the image preventing the user needing to crop this region.

### 4\. Save settings

* Change the resolution of the saved image.

### 5\. Measure

* Measure between two points on your image once the pixel size is set. Select menu, click on point to point distance and you can create a line. The distance of the line will automatically update in the feedback to user button and also if you hover over the line. The points can be dragged and dropped to measure different distances and features within the image.

### 6\. Info

* Copyright notice details will display within the user interface of the app.
* Visit the Zenodo page directly from the app.
* Visit Buymeacoffee to support Dan's development of the ScaleBarIT app.



## Default settings:

* New for v2.0 is the capability to customise the default settings interactively within the app and then save these. A default settings file is found if upon opening the app - the app reports 'Custom default settings applied'.
* **Save Current Settings:** The current settings will be saved in a filename of your choice.
* **Load Settings:** Apply settings from a .txt file. This option might be needed if the default settings file is not in the same folder as the executable ScaleBarIT.exe.
* **Overwrite Default Settings:** The most aggressive setting to permanently change the settings file.



## Further info

* Add an **issue** via GitHub to alert Dan to a problem with the user interface. App users are vital to identifying bugs and improving the app.
* Alternatively, get in touch with **Dan Scotson via email - daniel.scotson@manchester.ac.uk**.
