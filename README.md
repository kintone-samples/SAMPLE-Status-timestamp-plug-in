# [Sample plug-in: Status Timestamp Plug-in]
## Purpose of the Sample Plug-in
This sample plug-in is available for educational purposes.  
Use this plug-in to understand how Kintone plug-ins work, and how they are structured.

## What the plug-in does
This plug-in inserts the date (and time) that a record reached a specified Status into a Date or Datetime field.

## Plug-in directory structure
This sample plug-in is created with the following directory structure.

src/  
└── html/  
│        └──── config.html  
└── css/  
│        └──── 51-modern-default.css  
│        └──── config.css  
└── js/  
│        └──── config.js  
│        └──── desktop.js  
└── image/  
│        └──── clock.png  
└── manifest.json  

## How to use
To simply test out the plug-in on your Kintone domain, follow these steps:

1. Download the plug-in zip file  
Reference: https://github.com/kintone/SAMPLE-Status-timestamp-plug-in/releases
2. Install the plug-in into your domain  
Reference: https://get.kintone.help/hc/en-us/articles/115001519707-Installing-Viewing-Plug-ins
3. Add the plug-in to a specific Kintone App  
Reference: https://get.kintone.help/hc/en-us/articles/115001511188-Adding-Plug-ins-to-an-App
4. Make sure that a Date or Datetime field is placed in the form of your Kintone App, and that Process Management is enabled. Access the plug-in settings, and set up the neccessary settings. Save the settings, and update the App.
5. Click the + button on the Record List page to start adding a new record. Proceed the process management status until the status that was specified in the settings. When the process management reaches the specified settings, the date (and time) will be entered in the Date or Datetime field.

## How to modify
1. Fork to your repo
2. Make changes to files under /src
3. Repackage the plug-in by:  
 i. Zipping the manifest.json file, css directory, html directory, image directory and js directory into one zip file.  
 ii. Drag and dropping the file into the [kintone plug-in packer](https://kintone.github.io/plugin-packer/).

## Pull Request Policy
As this repo exists for educational purposes, we will most likely turn down pull requests that contain updates with new features.  
Please feel free to host plug-ins with new features on your own repository.  
Bug fixes are happily accepted.
