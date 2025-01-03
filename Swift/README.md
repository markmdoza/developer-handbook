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

# Methods For Controlling Video Playback

- AVPlayer(url: URL(fileURLWithPath: path))

  - This specifies the path of the video to be played. This can be a remote video URL or a local video on the device.

- play()

  - Allows for the video to be played.

- currentTime()

  - Gets the current time of playback.

- pause()

  - Pauses video playback.

- isMuted()

  - Returns a boolean value that indicates if the video is muted.

- AVPlayerViewController
- The AVPlayerViewController is the UI to control the video. Specifically, it is a view that contains media controls such as "Play/Pause", "Rewind", "Fast Forward" and a progress slider. It synchronizes the controls with the state of the MediaPlayer. By default, the AVPlayerViewController comes with a default set of controls. If you want to make changes to it, you must implement the AVPlayerViewController programmatically within your Swift code.

# Swift Arrays

```
var a:Int = 5

var b:[Int] = [5, 10, 15, 20, 25]

print(b[0])

This will print out 5. Very similar to JS.

```

# Updating an Array

```
b[0] = 100

print(b[0])
```
