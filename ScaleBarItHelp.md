# ScaleBarIT guide

Welcome to the ScaleBarIT guide. ScaleBarIt provides a user interface (UI) built in MATLAB by Dan Scotson to enable users to add scale bars to images quickly and efficiently.

Dan has built this capability during his PhD in a Materials Science field and hopes the distribution of this app will provide a tailored and simple solution to adding scale bars to images.

## Getting started:
Download the app from the repo.

## Instructions on use:

There are four major steps that can be performed in ScaleBarIt.
1. Select Image
2. Select Pixel Size
3. Region of Interest Method
4. Add Scale Bar

Guiding you through these steps is a colour coding system - red = not possible yet, blue = possible and green = complete.

### 1. Select Image
Select an image file of your choice and visualise this in the app.

### 2. Select Pixel Size
Selecting the pixel size of your image is really important.

Selecting the pixel size can be performed by two methdods.
1. Known (i.e. you know what the pixel size is).
2. From Image (i.e. there's an existing scale bar in the uploaded image that can be used).

### 3. Region of Interest Method
You don't want all your image being displayed?

You have two options here:
1. Point (i.e Centre the new image around a point in the existing image)
2. Crop (i.e. UI to select a region of interest)

### 4. Add Scale Bar

Options are available for adding scale bars that are at least half of your image after the pixel size has been determined.

## Saving an image:
You have two options to save the image.
1. Press the Save Image button once it is blue or green.
   
   The image will be saved in the original location with _proc_SB added to the filename.

3. Press the Save Button that appears in the top right toolbar of the image.

## Key bits:
+ Any crop commands require the dragging of the interactive box, then right click and select 'Crop image' to confirm.
+ Grayed out labels are not enabled and need another step
+ Feedback to user gives tips as to what is next/what has happened.
+ Hover over buttons or functionality to get further help in the user interface.

## Menu settings:
1. Reset
  - Made an error or want to reload another image/start again.
2. Font
  - Change the font name, size and font weight (e.g. 'normal' and 'bold')
  - Change the font colour
3. Appearance
   - Change the style of the scale bar - solid rectangle or H shape. The thickness of the H tails can also be set here.
    - Height of the footer (i.e. chosen as a % of the entire image').
   - Change the colour of the scale bar (font colour can be updated in the font menu).
- Select position of the scale bar (e.g. bottom left or bottom right).


### Further info
Add an issue to alert Dan to a problem with the UI.
Alternatively, get in touch with Dan Scotson via email - daniel.scotson@manchester.ac.uk.
