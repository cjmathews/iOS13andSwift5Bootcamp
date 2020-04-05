### Setting up a new project                    
Create new Xcode project > start with single view app, can be changed/added later                    
Change user interface to Storyboard                    
Bundle identifier - used to identify the app on the App                     
### Xcode working environment                     
Starting point - General tab                    
Target iOS level - minimum supported level                    
Device orientation - how can it be viewed                    
In files view on LHS - Swift icon - Swift files, yellow icon = design files                    
#### Top of screen                    
- Status Bar                    
#### LHS Navigator pane                    
- Eg flies view within the app                    
#### RHS Inspector pane                    
Eg Attibute inspector - allows you to design the various elements in your programme                    
Size inspector - size and placing of an item on screen                     
#### LHS Inner panel - Document Outline                    
Where layers exist                    
Lists all components in the design eg buttons, labels etc                    
#### Bottom of screen - Debug pane                    
Cmd/Shift/Y                    
### View controller.swift                    
Where most of your code exists                     
                    
## 19 Designing the user interface                    
Launchscreen.storyboard - splash screen                    
Main.storyboard - main app view                    
Can use trackpad to move the view around, zoom etc                    
Object library: + Button top right Status Bar; add different elements to your design                    
Within View Controller Scene, View is the background of your app, can be altered in Atribute inspector just like any other design element                    
* **Tip** - Use a site like colorhunt.co to access colour palettes with associated hex codes etc                    
To add a picture - Use Image View from object library                    
Co-ordinates: Top left = 0, 0 - always measured in terms of points                     
eg iPhone 6 - 375 x 667 full screen                    
[iPhone screen sizes](https://Paintcodeapp.com/news/ulitmate-guide-to-iPhone-resolutions) - measured in points - as screen resolution has improved, the number of pixels per point has increased                     
When assigning co-ordinates to an object on the screen, you define where the top left corner is placed                    
                    
## 20 Adding images                     
Attribute inspector > Image                    
Add image assets to Assets.xcassets - can drag and drop into the folder - will first drop into 1x version                    
1x - 1 pixel to 1 point                    
2x - 4 pixels to 1 point                    
3x - 9 pixels to 1 point                    
Use software - or site such as [App Icon Generator](https://appicon.co) to produce scaled versions of required images                    
    
## Design and Create an App Icon    
Providing versions in all various available sizes and scales helps the app run more quickly as it isn't having to scale the icon on the fly in different scenarios    
Once design is complete and you run your icon through  appicon.co, you will have a downloaded folder (AppIcon.appiconset) which can be dragged directly into Xcode project and which will populate your icon into all the correct positions     
    
## Running the app     
Either through Simulator    
Or direct on a device:     
- Xcode and iOS versions must be aligned (inc no after decimal in version number eg 11.1/13.1    
- Requires free Apple developer account added in Xcode     
- App must be signed - Signing and Capabilities tab in Xcode on your app    
- Once device is trusted, it becomes available in the list of available devices, also requires developer account to be trusted on the device     
- Can also be run wirelessly - Select Connect via network in Window > Devices and Simulators. Must be on same network    
