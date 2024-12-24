- Assistant panel loads the code window beside the storyboard page.
- Main.storyboard is also known as an interface builder.
- ctrl + click and hold an image and drag it to code creates an interface builder outlet.
- You cannot change the output name of the interface outlet you make. It will throw an error when you run the app. Instead, ctrl click on the variable you want to rename - refactor and rename.

# Dot Notation

- Who.What = Value
  (Who needs to be changed and what what variable needs to be changed and what is the new value)

# AppDelegate

- The AppDelegate is effectively the foundation of an application and manages some interactions with the system.

# SceneDelegate

- This is responsible for displaying the screen UI and data.

# ViewControllers

- The only component users can interact with. Most applications will provide more than one ViewController.

# UIViews

- These dsiplay images, texts and more.

# Storyboard

- This serves as a blueprint for the interface that an application presents to the user.

# Project files

- Within Xcode, files belong into three main categories. Configuration, code and resource. Config defines the project structure, code for the logic and resource for everything else.

# Mobile CPU Architecture

- There are 3 main CPU architectures used in most smartphones. ARM, ARM64, and ARMx86
- ARM (Advanced RISC Machines) are the most used because it is optimized for battery use. Some examples of ARM include ARMv7 and Armeabi.
- ARM64 is a 64-bit extension of the original ARM. Some examples include AArch64. They are more powerful in the form of 64-bit processing and it is gradually becoming the standard in newer devices.
- x86 is not as battery-friendly due to being a bit more sophisticated than ARM. An example of x86 is x86abi.
