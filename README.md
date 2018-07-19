# Custom Project Templates

Custom Project templates for Static and Dynamic Libraries in Xcode. 

### What are Xcode Templates?

These are file or project type templates such a Cocoa Touch Class, Storyboard, Core Data, Dynamic or Static Libraries. These are default templates which are bundled up with Xcode and for most of our use cases these should be sufficient, however if you are having to duplicate a certain functionality many times then things can get repetitive and inefficient. Lets say you have a policy of running a certain build script (SwiftLint for example) for all your project frameworks, you then have to introduce that script every time you introduce a new framework to your project.

### What are Custom Xcode Templates?

These are file or project type templates but with customised setup such as pre-baked linting or build configurations. 

### Where to store your Custom Templates?

Custom templates are stored under a folder called `File Templates` and `Project Templates` under the following path `~/Library/Developer/Xcode/Templates`. 

When you first navigate to this path you may find it empty, this is expected as you may not have any custom templates.

The `File Templates` folder holds file templates and `Project Templates` holds project templates. 

### Custom Templates

The Custom Templates in this repo support swift lint build script and custom build configurations.

You can find the tutorial on how to set up your own custom template for static lib [here](https://medium.com/@09mejohn/custom-xcode-template-for-static-library-in-ios-820e8e90ca93). 

### Setup

Copy the Project Templates folder to path `~/Library/Developer/Xcode/Templates`

### How to use it?

Navigate to `File -> New -> Project` from Xcode and scroll to the bottom of the templates list to see the custom templates.
 