# Python Alarm Clock

A simple and functional alarm clock application built with Python's Tkinter GUI library. Set your alarm time using dropdown menus and get notified with a sound alert.

## Features

- ⏰ Set custom alarm time (hours, minutes, seconds)
- 🔊 Audio alert when alarm triggers
- 🎯 Real-time comparison with current system time
- 🛑 Stop alarm functionality
- 🧵 Multi-threaded operation (alarm runs in background)
- 🎨 Clean and intuitive GUI interface
- 🕐 24-hour time format support

## Screenshots

![Alarm Clock Screenshot](screenshot.png)
*Add a screenshot of your alarm clock here*

## Prerequisites

Before running this application, ensure you have:

- Python 3.6 or higher installed
- Required Python packages (see Installation section)

## Installation

### 1. Clone the Repository



### 2. Install Required Dependencies


**Note**: Tkinter usually comes pre-installed with Python. If not, install it:


### 3. Add Sound File

Place a sound file named `sound.wav` in the same directory as the script. You can:
- Use your own `.wav` file
- Download a free alarm sound from [freesound.org](https://freesound.org)
- Rename your sound file to `sound.wav`

## Usage

### Running the Application


### How to Use

1. **Launch the application** - A window will appear with time selectors
2. **Set your alarm time**:
   - Select **Hour** (00-24) from the first dropdown
   - Select **Minute** (00-60) from the second dropdown
   - Select **Second** (00-60) from the third dropdown
3. **Activate the alarm** - Click the "Set Alarm" button
4. **Stop the alarm** - When the alarm rings, click the "Stop Alarm" button

### Example

To set an alarm for 2:30 PM:
- Hour: 14
- Minute: 30
- Second: 00
- Click "Set Alarm"

## Project Structure


## Technical Details

### Technologies Used

- **Tkinter** - GUI framework for creating the interface
- **Pygame** - Audio playback library for alarm sound
- **Threading** - For running alarm in background without freezing UI
- **Datetime** - For time comparison and formatting

### Key Components

| Component | Purpose |
|-----------|---------|
| `Threading()` | Creates a new thread for alarm monitoring |
| `alarm()` | Main alarm loop that checks time continuously |
| `stop_alarm()` | Stops the alarm sound playback |
| `OptionMenu` | Dropdown menus for time selection |

### Dependencies

