# Marketing Resources 
This file contains explanation for the app's marketing resources used on the App Store.
The resources are split in four different folders.

## Folders 

### AppIcon.appiconset
This folder contains the app's icon in different scales.

### Pngs
This folder contains the app's screenshots used on the App Store.

### Psds
This folder contains the _.psd_ files used to create the files contained in the _Pngs_ folder.

### Screenshots
This folder contains the actual in-app screenshots taken on an iOS device or simulator.

## Screenshot scenarios
Following scenarios are represented in the screenshots. 
### Take notes
A simple notebook page with some notes.
### Add text and image
A notebook page with an added image and a text view that is currently being edited.
### Dark Mode
Shows the app's dark mode support.
### Export
Shows the exporting capabilities of the app.
### Search
Shows an active notebook search.
### Folders
Shows notebooks organized in a folder.
### Share
Shows the support for iCloud synching on iPhone and iPad.
### Page types
Shows the different page types that can be added.

## File Names
File names contain only lowercase letters and numbers, words are separated by underscores.
File names are constructed as follows:
<_screenshot scenario_>\_<_device type_>\_<_screen size in inches_>.<_file extension_> \
e.g. _search_iphone_6.5.png_.

## Contributions 
When contributing keep in mind that the folders ar interdependent as follows: 
**_screenshots_ -> _psds_ -> _pngs_** \
This means that a change in the _screenshots_ directory **must** be reflected by a change in the _psds_ and _pngs_ directory because the screenshot was used in the _.psd_ file which was used to create the final _.png_ file. \
When contributing for a new app icon keep in mind all required sizes needed for app store publishing and provide a _.json_ file to map the files to the correct size.




