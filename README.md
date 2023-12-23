# Multi-Timer App

## Overview
The Multi-Timer App is a web application that allows users to set multiple timers. The design of the application matches the UI provided in the Figma file.

!Reference Image

## Features
The application is divided into three main components:

1. **Timer Input Section**: This section allows the user to input the desired time in hours, minutes, and seconds. Upon setting the time and clicking the 'Start New Timer' button, a new timer is started and added to the Active Timers Display Section.

2. **Active Timers Display Section**: This section dynamically displays all active timers. Each timer shows the time remaining and has a 'Stop Timer' button to cancel the timer. Each timer shows the countdown from whatever time was set to 0, updating every second.

3. **Timer End Display Design**: Upon reaching zero, the display for that timer changes to match the design provided in the Figma file. Additionally, an audio alert of the user's choice is played to notify the user that the timer has ended.

## Best Practices
While building this web application, the following best practices were followed:

- Semantic HTML: Correct element tags were used for better SEO and accessibility.
- CSS Flexbox/Grid: Flexbox and CSS Grid were used to manage the layouts.
- Vanilla JavaScript: No libraries or frameworks were used for this project.
- Code cleanliness: Clean and commented code was maintained to enhance readability.

## How to Use
To use the Multi-Timer App, simply input the desired time in hours, minutes, and seconds in the Timer Input Section and click the 'Start New Timer' button. The timer will then appear in the Active Timers Display Section, where it will count down to zero. If you wish to cancel the timer, click the 'Stop Timer' button.
