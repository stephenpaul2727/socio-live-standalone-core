# SocioLive Core Standalone
A standalone version of SocioLive that is completely offline and runs on a simple index.html file. 


### Socio Labs Summer 2017 Take Home Assignment

### Overview
- Assignment is to implement upload CSV functionality to support new users who want to test their luck using Attendee Drawing Functionality.
- Implemented using Plain JavaScript as react carries a lot of dependencies in the project which includes good amount of refactoring.
- Used External Library PapaParse(Vendor) for parsing CSV Files. 

### Functionality Added

##### Added UI Buttons
- Added Spin Button which slides from left instead of big bottom button to increase canvas area.
- Added some font awesome icons. 

##### Added JS
- Added upload files using file reader of javascript.
- Uploaded files are parsed by PapaParse.
- Added validation code to check duplications.
- Added validation code to verify fields
- Added Hot Reloading of the attendee drawing on uploading files.

##### Added Example CSV
- By Default, given example simple-example-1 is example of an acceptable format file.(alerts)
- Added DuplicateData.csv, which is an example of csv file having duplications. (alerts)
- Added Non Matching Fields.csv, which represents csv file not having required fields. (alerts)

### Tools and Technologies
> JavaScript  
> JQuery( PapaParse )  
> CSS  
> Brackets  
