# Project 1 - *Tip Calc*

**Tip Calc** is a tip calculator application for iOS.

Submitted by: **Matthew Ponce de Leon**

Time spent: **6** hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:

* [ ] Settings page to change the default tip percentage.
* [x] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [x] Making sure the keyboard is always visible *(not implemented as a design choice)* and **the bill amount is always the first responder**. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] App icon

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![GIF demo of Tip Calc's features](https://i.imgur.com/EdlwZIk.gif)

GIF created with [EZGIF.COM](https://ezgif.com/video-to-gif).

## Notes

Describe any challenges encountered while building the app.

I tried to prefix the UITextField with a dollar sign while editing the bill amount, but I could not devise a solution in reasonable time without introducing some bugs. 
Moreover, implementing the app icon took some time due to having to add a background to the transparent PNG icon I found and using a third-party tool to 
generate icons to import into Xcode. I also consulted Stack Overflow for designating the bill UITextField as the first responder and determining the syntax for 
string manipulation in Objective-C.

## Credits

List an 3rd party libraries, icons, graphics, or other assets you used in your app.

- Icons made by [Freepik](https://www.freepik.com) from [Flaticon](https://www.flaticon.com)

## License

    Copyright 2021 Matthew Ponce de Leon

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
