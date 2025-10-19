# ScaleBarIT

**Welcome to ScaleBarIT created by Dan Scotson**.

![Screenshot of ScaleBarIT v1.8](ScaleBarIT_Screenshot_v1_8.png "ScaleBarIT v1.8 screenshot")

## Why use ScaleBarIT?
ScaleBarIT enables users to **add scale bars to images quickly and efficiently**. The basic steps involve choosing your image, specifying its pixel size, then choosing a region of interest and finally adding your scale bar of choice.

Dan has built this capability during his PhD in a Materials Science field and hopes the distribution of this app will provide a tailored and simple solution to adding scale bars to images.

## How can I get started?
- **Download the installer from the repository**. While the code has been written in MATLAB, the app is a standalone installation which does not require MATLAB software to use.
- Download the Matlab 2025b Runtime installer from here: **https://uk.mathworks.com/products/compiler/matlab-runtime.html** to ensure the app works (this should be included during installation but please download separately if not!).

## App Customisation
- **The default_settings.txt is a text file to customise the app default settings**. For example, prefer Arial font over Calibri, size 20 over 16 or like your scale bars with a particular colour - all of this can be customised in this file.

- **Ensure the default_settings.txt file remains in the same folder as the ScaleBarIT app**. If this is not found, upon opening app, the app will state that master default settings have been applied (text box to bottom left populated). If default_settings.txt is successfully found then the text box will read that custom default settings have been applied.

## Publishing and acknowledgement
If you publish any of the images created using **ScaleBarIT**, please honour the licensing and cite this repository. You can get an APA or LaTeX formatted bibliographical reference using the 'Cite this repository' feature on the right-hand information menu.

## How can I help?
- Please feel free to **add issues where necessary** or contact **Dan directly via email at daniel.scotson@manchester.ac.uk**.

- Suggestions of improvements and additional features are extremely welcome. 

- If you have a .tif image where the pixel size is not automatically detected, please raise this issue and Dan can look into adding this functionality.

- If you benefit from this app, please cite its use - it's great to see where this app is being used.

- Consider supporting Dan at [Buy Me A Coffee](https://buymeacoffee.com/danscotson).

## Project maintenance
Dan Scotson is the sole maintainer of this project.

## Collaboration opportunities
If you're interested in developing this app further, please get in touch with Dan to discuss sharing of the codebase, collaboration and licensing options.

## Acknowledgements

### Third-party libraries

This software reuses and modifies code from:

1) https://github.com/wlepage/parseTescanmetadata (parseTescanmetadata) to parse TESCAN Mira 3 Header files to extract metadata. parseTescanmetadata is licensed under an Apache 2.0 License.
