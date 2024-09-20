# Multi-Runner Timer

## Overview

The **Multi-Runner Timer** is a simple web application designed to time the runs of multiple individuals simultaneously. Each runner has an individual stop button, allowing you to capture and save their run times as they cross the finish line. This tool is perfect for timing events such as the 1-mile run for PE students or other group activities requiring precise time tracking for multiple participants.

## Features

- **Start Timer for All Runners**: Start a global timer for the race with a single click.
- **Individual Stop Buttons**: Stop the timer for each runner individually as they finish the race.
- **Real-Time Display**: Track and display each runner's time in real-time.
- **Reset Functionality**: Easily reset the timers to start a new race.
- **Time Format**: Times are displayed in hours, minutes, and seconds (`hh:mm:ss`).

## Usage

### Getting Started

1. Download or clone the repository to your local machine.
2. Open the `index.html` file in a modern web browser.

### How to Use

1. **Start the Race**: Click the "Start Race" button to begin the global timer for all runners.
2. **Stop a Runner’s Time**: As each runner finishes, click their corresponding "Stop" button to record and display their final time.
3. **Reset the Race**: Once all runners have finished, click the "Reset" button to clear the timers and prepare for the next race.

### Example Walkthrough

1. You have 3 runners:
   - Click "Start Race" to begin the race for all.
   - As Runner 1 finishes, click "Stop" next to their name to capture their final time.
   - Repeat for Runner 2 and Runner 3.
2. Once all runners are finished, click "Reset" to prepare for the next race.

## Customization

If you need to add more runners, edit the `runners` array in the `index.html` file:

```javascript
let runners = [
    { name: 'Runner 1', time: null, isRunning: true },
    { name: 'Runner 2', time: null, isRunning: true },
    { name: 'Runner 3', time: null, isRunning: true },
    // Add more runners as needed
];
```

Each runner is an object with:
- `name`: The runner’s display name.
- `time`: The recorded time once the "Stop" button is pressed (initially `null`).
- `isRunning`: A boolean flag to indicate whether the runner's timer is active.

## Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari) is recommended to run this app.
- No additional software or frameworks are required.

## License

This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).

---
