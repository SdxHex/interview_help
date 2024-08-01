# Mock Interview Application
## Created by Michael Bailey
This application helps you conduct mock interviews by generating tailored interview questions based on a job description, capturing your spoken responses, and providing feedback and ratings.

## Prerequisites

1. [FFmpeg](https://ffmpeg.org/download.html) - A multimedia framework needed for audio processing.
2. [Interview_Helper] From email message - Main Program

## Installation

### Step 1: Install FFmpeg

1. Download the FFmpeg executable for Windows from [this link](https://ffmpeg.org/download.html).
2. Extract the contents of the zip file to a folder on your computer (e.g., `C:\ffmpeg`).
3. Add FFmpeg to your system PATH:
    - Open the Start Menu, search for "Environment Variables," and select "Edit the system environment variables."
    - Click on "Environment Variables."
    - Under "System variables," find the `Path` variable, select it, and click "Edit."
    - Click "New" and add the path to the `bin` folder inside your FFmpeg directory (e.g., `C:\ffmpeg\bin`).
    - Click "OK" to close all dialog boxes.

### Step 2: Download and Run the Application

1. Download the `main.exe` file and place it in a folder (e.g., `C:\Python\interview_help`).
2. Double-click `main.exe` to run the application.

## Usage

1. Open the application by double-clicking the `main.exe` file.
2. Enter the job description in the "Job Description" box.
3. Press the "Start" button to get a tailored interview question.
4. Answer the question verbally. Press the "Submit" button to stop recording.
5. The application will transcribe your response, provide feedback, and rate your answer (1-5).

## Troubleshooting

If you encounter any issues, ensure that FFmpeg is correctly installed and that your system PATH includes the path to the FFmpeg `bin` folder.

For further assistance, feel free to reach out!

