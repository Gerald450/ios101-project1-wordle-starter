# Project 1 - Wordle

Submitted by: Gerald Shimo

Wordle is an iOS app that recreates the classic word puzzle game where players try to guess a hidden five-letter word within six attempts. The app features a custom on-screen keyboard, interactive letter input, and real-time feedback based on the accuracy of each guess. Each game randomly selects a new goal word, ensuring a fresh challenge every time you play.  

Time spent: 5 hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App displays a keyboard on the screen
- [x] When tapping on the keyboard, a letter is shown or deleted (letter selected)
- [x] User can play a basic version of Wordle, with different goal words each time

The following **optional** features are implemented:

- [x] Improved and customized the user interface by adding a launch screen and app icon
- [x] Ran the app on a physical iOS device rather than only in the simulator

The following **additional** features are implemented:

- [ ] Added animations when entering letters for a more engaging experience
- [ ] Customized cell coloring to match the official Wordle styling
- [ ] Implemented delete functionality with smooth UI updates

## Video Walkthrough

Here is a video walkthrough of the app:

<div>
    <a href="https://www.loom.com/share/7a4df2a805cb4a869563fd8412b0a2aa">
      <p>Videos | Library | Loom - 23 September 2025 - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/7a4df2a805cb4a869563fd8412b0a2aa">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/7a4df2a805cb4a869563fd8412b0a2aa-b6a0a1a46d53d0b5-full-play.gif">
    </a>
</div>

## Notes

During development, some challenges I encountered included:
- Setting up provisioning profiles and resolving Xcode signing errors when running the app on a physical device.  
- Correctly animating the letter cells when typing on the keyboard.  
- Ensuring that the board updated dynamically as letters were deleted or entered.  
- Getting comfortable with `UICollectionView` and custom cell configuration in UIKit.  

Despite these challenges, I was able to get the core gameplay running smoothly and enjoyed learning about iOS app development fundamentals.  

## License

    Copyright 2025 Gerald Shimo

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
