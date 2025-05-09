# ScaleBarIT Guide


**Welcome to the ScaleBarIT guide**. ScaleBarIT enable users to **add scale bars to images** quickly and efficiently. **The basic steps involve choosing your image, specifying its pixel size, then choosing a region of interest and finally adding your scale bar of choice**.

Dan has built this capability during his PhD in a Materials Science field and hopes the distribution of this app will provide a tailored and simple solution to adding scale bars to images.

Written by Dan Scotson, 09/05/2025 for ScaleBarIT's version 1.5. If you have any **further questions**, please get in touch with Dan at **daniel.scotson@manchester.ac.uk**.

## Getting started:
Install with the ScaleBarIT_installer.exe from the repository.

## Instructions on use:

There are **five major steps** that can be performed in ScaleBarIT. Guiding you through these steps in the app is a **colour coding system - red = not possible yet, blue = possible and green = complete**.

1. Select Image
2. Select Pixel Size
3. Region of Interest Method
4. Add Scale Bar
5. Save Image

## Major steps in ScaleBarIT:

The following steps should be followed to add scale bars to your images.

### 1. Select Image
Select an image file of your choice and visualise this in the app.

### 2. Select Pixel Size

Selecting the pixel size of your image is really important.

First, the app will try to automatically extract the pixel size from the metadata of the image. If this is not possible, selecting the pixel size can be performed by two methods.

#### A. Known (i.e. you know what the pixel size is).
- Enter the known pixel size in the pop up menu.
#### B. From Image (i.e. there's an existing scale bar in the uploaded image that can be used).
- Choose a region of interest containing a scale bar. This involves cropping the image. First drag the interactive box into the desired position, then right click and select 'Crop image' to confirm.
- Then a new image will appear, click at each end of the horizontal extent of the existing scale bar. Press enter to confirm.
- Then confirm the size of the scale bar and the units in the pop up menu.

  
### 3. Region of Interest Method
You don't want all your image being displayed?

You have two options here:
#### A. Point (i.e Centre the new image around a point in the existing image)
   - Click on the Point button then proceed to select a single point on the image. Then press Confirm!
#### B. Crop (i.e. Select a region of interest)
- Click on Crop button and then proceeed to draw a rectangle on the image. Then press Confirm!


### 4. Add Scale Bar

Two options are available for adding scale bars:
#### A. Suggested Scale Bar
Automatic suggestions of scale bars that are half of your image size after the pixel size has been determined.
#### B. Custom Scale Bar
Set a custom scale bar (choose your value in the edit field) with the unit of choice. 

### 5. Save image:
You have two options to save the image.
#### 1. Press the Save Image button once it is blue or green.
   
   The image will be saved in a location of your choice with _proc_SB added to the filename.

#### 2. Press the Save Button that appears in the top right toolbar of the image.

## Key bits:
+ Grayed out labels are not enabled and need another step before becoming available.
+ Feedback to user gives tips as to what is next/what has happened.
+ Hover over buttons or functionality to get further help in the user interface.
+ The crop command for selection of the pixel size requires the dragging of the interactive box, then right click and select 'Crop image' to confirm.

## Menu settings:
### 1. Reset

  - Made an error or want to reload another image/start again.

### 2. Scale Bar Appearance
- Customise the colour of the scale bar and font.
- Customise the font name, font size and font weight (e.g. bold or normal).
- Choose whether a pad bar is added to the image. This increases the size of the image to ensure the scale bar isn't overlaid onto your image. The pad bar's height can also be customised.
- Select position of the scale bar (e.g. bottom left or bottom right).
- Change the style of the scale bar - solid rectangle or H shape. The thickness of the H can also be set here.

 ###  3. Edit Image
 
  - Rotate the image clockwise or anticlockwise by 90°.

  ### 4. Save settings
  
  - Change the resolution of the saved image.

### 5. Measure

- Measure between two points on your image once the pixel size is set. Select menu, click on point to point distance and you can create a line. The distance of the line will automatically update in the feedback to user button and also if you hover over the line.

 ### 6. Info
 
 - Copyright notice details will display within the user interface of the app.

   
 ## Default settings:
 - New for v1.5 is the capability to customise the default parameters for the app. These included the style and placement of the scale bar, scale bar font and also the scale bar colour.


## Further info
- Add an **issue** to alert Dan to a problem with the UI.
- Alternatively, get in touch with **Dan Scotson via email - daniel.scotson@manchester.ac.uk**.
