
# Pre-work - *Tippy*

**Tippy** is a tip calculator application for iOS.

Submitted by: **Arun Mannuru**

Time spent: **4** hours spent in total

## User Stories

The following **required** functionality is complete:

* [ .] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [. ] Settings page to change the default tip percentage.
* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ .] Using locale-specific currency and currency thousands separators.
* [ .] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [ .] The app logo is displayed on the splash screen whenever the app is started
- [ .] An option for users to round the tip amount to the nearest dollar (ceil function)
- [ .] 10% tip option
- [ .] Users could select the number of people (up to a maximum of 5) to split the bill with
## Video Walkthrough

Here's a walkthrough of implemented user stories:

<blockquote class="imgur-embed-pub" lang="en" data-id="a/c7cX1"><a href="//imgur.com/c7cX1">TippyCalculator</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Migrated everything to Swift 3.0. Started off with an older version of xCode, but after updating it, there were a lot of compilation errors.

Splash Screen: Tried to implement a custom splash screen with animation, but that didn't work. As a result, I resorted to using an image on LaunchScreen.storyboard.

## License

Copyright [2018] [Arun Mannuru]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
