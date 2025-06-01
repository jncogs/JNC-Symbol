# JNC-Symbol

Plug-in Object

## Icon

![Tool Icon](icons/JNC%20Symbol@2x.png)

## Version

1.0.0 - 5/31/2025

This plug-in is written in Vectorscript (Pascal) and can be used in any version of [Vectorworks](https://www.vectorworks.net) 2019 or newer.

## Description

The plug-in object uses a given Symbol's geometry but allows users to override visual Attribute settings, auto-rotate text linked to Record Formats, link text to Symbols embedded inside other Symbols, toggle 2D or 3D geometry on and off, and scale on the X, Y, and Z axis separately.

## Instructions

Instructions go here

## Object Info Palette Parameters

Parameter explanation

## Example Screenshots as necessary

Examples

## Supplemental Commands

Supplemental commands

## Tips and Tricks

Any tips and tricks

## Installation Instructions

There are two methods of installation, direct download of the plug-in or through the **JNC Tools Free Manager** plug-in.

### Direct Download:

1. Download [source plug-in file](JNC-Symbol.vso)
2. Place downloaded file inside the **Vectorworks User Folder** within the **Plug-ins** directory
3. Restart Vectorworks

### JNC Tools Free Manager

1. Run the [**JNC Tools Free Manager**](https://jncogs.github.io/JNC-Tools-Manager-Free/) menu command
2. Select the **JNC-Symbol** tool
3. Press the **Install / Update** button
4. Press **Close** to close the dialog box
5. Restart Vectorworks

## Adding the Plug-in to your Workspace

1. Open the **Workspace Editor** by going to **Tools - Workspaces - Edit Current Workspace**
2. Select the **Tools** tab
3. In the box on the left, find and expand the **JNC** category
4. In the box on the right, find a suitable tool set to place the tool in, such as **Basic** or **Dims / Notes**
5. Click and drag the **JNC-Symbol** tool from the box on the left to the desired tool set in the box on the right
6. Click **OK** to close the editor

## Localization Instructions

The plug-in can be localized to your native language without having access to the source code.  This can be achieved by following the instructions below:

1. Open the **Plug-in Manager** by going to **Tools - Plug-ins - Plug-in Manager**
2. Select the **Third-party Plug-ins** tab
3. Select the **JNC-Symbol** tool
4. Click the **Customize** button
5. Select the **Strings** tab
6. Double-click a category, such as **Dialog Strings**
7. Select a string to edit and press the **Edit** button
8. Write a new string and press the **OK** button until you are back to the **Plug-in Manager**

The categories for this plug-in are as follows:

- **3000** - *Dialog Strings*: These strings are used to populate strings inside the **Set Override Classes** dialog box and can all freely be changed.
- **4000** - *Dialog Help Strings*: These strings are used in the Help Box at the bottom of the **Set Override Classes** dialog box and can all freely be changed.
- **5000** - *Misc Strings*: These strings serve multiple purposes in the code.  Only **5000** can be changed.
    - **5000**: Name for when no Symbol is selected. This is *"None"* by default.

## Release Notes

| Date | Version | Note |
| :---: | :---: | :--- |
| 05/31/2025 | 1.0.0 | Initial release |
| 05/31/2025 | 1.0.1 | Fixed bugs with 3D text |

## Known Bugs

No Known Bugs

## Feature Requests

No current Feature Requests


## License

Copyright (c) Jesse Cogswell (JNC Tools)

Permission is hereby granted, free of charge, to any person or organization
obtaining a copy of this software (the "User") and associated documentation files (the "Software"),
to use, reproduce, distribute, execute, and transmit the Software.

The User is not permitted to modify or attempt to reverse engineer the source code.  The User may
localize the Software using approved methods from within the Vectorworks software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT
SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE SOFTWARE BE LIABLE
FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.