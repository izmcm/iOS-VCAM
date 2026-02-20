# iPhone-VCAM

Virtual Camera based on *Cydia Substrate*

## Purpose

Replace the iOS system camera feed

## Supported Apps

- Supports most apps

## Supported iOS Versions

- Developed and tested on iOS 13.3; other versions not tested due to device limitations
- Theoretically supports iOS 11.0 and above
- iOS 15 may have issues, and currently there is no jailbreak solution for iOS 15

## Getting Started

### Installation

### Usage

- The **-** symbol means **Volume Down**, **+** means **Volume Up**. Press both within one second to trigger actions.

#### Full Mode

More popups, some apps may pause after a popup

- Shortcut: + -
- See button descriptions for features
- Download video
  - *After each download, a system mute notification will pop up*
    1. Video file
        1. Online video URL, make sure the link points to an accessible video
        2. If the file is corrupted, unplayable, or unsupported, nothing will happen
    2. Streaming media (not supported yet)

#### Convenient Mode

Minimizes popups to avoid interrupting app operation  

- Shortcut: - + triggers **Select Video**
- If **Download Video** is set, this shortcut triggers **Download Video** instead
- If the **Download Video** link is empty, it continues to trigger **Select Video**
  - After download, a mute notification will pop up
  - If the remote file is unavailable, replacement is disabled

## FAQ

- The **-** symbol means **Volume Down**, **+** means **Volume Up**. Press both within one second to trigger actions.

### Q: How to select video resolution?

A: After using the camera, press + -, and detailed info will appear. If width is greater than height, the video is rotated. Usually, the rear camera needs a 90° counterclockwise rotation, the front camera needs a 90° clockwise rotation, sometimes rotation and horizontal flip are needed. The exact orientation depends on the app and may require observation. **Replacement preview always keeps the correct orientation**. *If the video width/height does not match the prompt, there may be offset, stretched preview, or even crashes.*

- In short, the replacement video’s width and height must match the W, H shown by the + - shortcut. Adjust the video angle according to the preview.

### Q: Why is the photo rotated after taking a picture?

A: The preview always keeps the correct orientation. Some apps process landscape images directly but rotate the preview for the user.

- In short, rotate the replacement video in the opposite direction of the rotation seen.

## TODO

- Audio support
- Fix issues with some apps where video replacement fails after looping
