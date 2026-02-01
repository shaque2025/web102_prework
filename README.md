# WEB102 Prework - *Name of App Here*

Submitted by: **Syeda Haque**

**Sea Monster** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **3** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [x] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='walkthrough.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with LICEcap. 
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

1) State Management: Clearing the DOM using deleteChildElements before reapplying filters to prevent duplicate game cards from stacking.

2) Data Aggregation: Using the .reduce() method to accurately sum total backers and pledged amounts across the entire JSON dataset.

3) Dynamic UI Pluralization: Implementing ternary operators to ensure the summary text is grammatically correct (e.g., "1 game" vs. "7 games").

4) Data Readability: Utilizing toLocaleString() to format large integers into human-readable currency and backer counts with proper punctuation.

5) Array Manipulation: Sorting objects by numerical values and using destructuring with the spread operator to isolate the top-performing games.

6) Template Literals: Nesting complex logic and variables within backticks to create clean, dynamic HTML strings without messy concatenation.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
