# Screen Recorder Web Application

This is a simple **Screen Recorder** built using **HTML**, **CSS**, and **JavaScript** that allows users to record their screen and download the video as an MP4 file. The web app uses the **MediaRecorder API** to capture the screen and provides an intuitive user interface to start and stop the recording.

## Features

- **Screen Recording**: Allows users to record their screen with just one click.
- **Download Video**: Once the recording stops, the video is saved as an MP4 file, ready to be downloaded.
- **Responsive Design**: The app is designed to work on both desktop and mobile devices, with a responsive layout.
- **User-Friendly Interface**: Clean and simple UI with start/stop recording buttons.

## How It Works

The web application leverages the **MediaDevices API** to capture the user's screen, specifically using the `getDisplayMedia` function to capture the screen. The **MediaRecorder API** is then used to record the screen stream, and upon stopping the recording, the recorded video is packaged into a downloadable MP4 file.

## Screenshots

![Screenshot](screenshot.png)

## Technologies Used

- **HTML**: For structuring the layout of the screen recorder.
- **CSS**: For styling the application and making it responsive.
- **JavaScript**: For the screen capture and recording functionality.
- **MediaRecorder API**: For recording the screen and saving the file.

## Getting Started

To use the Screen Recorder locally, follow these steps:

### Prerequisites

You need a browser that supports **MediaRecorder API** (most modern browsers like Chrome, Firefox, and Edge support this).

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/screen-recorder.git
