# Mock Interview Application

This application helps you conduct mock interviews by generating tailored interview questions based on a job description, capturing your spoken responses, and providing feedback and ratings.

## Prerequisites

1. [Anaconda](https://www.anaconda.com/products/distribution) - A Python distribution with package management and environment management.
2. [FFmpeg](https://ffmpeg.org/download.html) - A multimedia framework needed for audio processing.

## Installation

### Step 1: Install Anaconda

1. Download and install Anaconda from the [official website](https://www.anaconda.com/products/distribution).
2. Follow the installation instructions on the website.

### Step 2: Install FFmpeg

1. Download the FFmpeg executable for Windows from [this link](https://ffmpeg.org/download.html).
2. Extract the contents of the zip file to a folder on your computer (e.g., `C:\ffmpeg`).
3. Add FFmpeg to your system PATH:
    - Open the Start Menu, search for "Environment Variables," and select "Edit the system environment variables."
    - Click on "Environment Variables."
    - Under "System variables," find the `Path` variable, select it, and click "Edit."
    - Click "New" and add the path to the `bin` folder inside your FFmpeg directory (e.g., `C:\ffmpeg\bin`).
    - Click "OK" to close all dialog boxes.

### Step 3: Set Up the Conda Environment

1. Open Anaconda Prompt (you can find it in the Start Menu).
2. Create a new environment with Python 3.10:
    ```sh
    conda create -n interview_env python=3.10
    ```
3. Activate the environment:
    ```sh
    conda activate interview_env
    ```
4. Install the necessary packages:
    ```sh
    conda install -c conda-forge openai pyaudio tk
    pip install openai-whisper
    ```

### Step 4: Download and Run the Application

1. Download the application script (e.g., `main.py`) and place it in a folder (e.g., `C:\Python\interview_help`).
2. Open Anaconda Prompt and navigate to the folder where the script is located:
    ```sh
    cd C:\Python\interview_help
    ```
3. Run the script:
    ```sh
    python main.py
    ```

### Step 5: Compile the Script to an Executable (Optional)

If you want to create an executable file for easier distribution, you can use `PyInstaller`.

1. Install `PyInstaller`:
    ```sh
    pip install pyinstaller
    ```
2. Compile the script:
    ```sh
    pyinstaller --onefile --windowed main.py
    ```
3. The executable will be located in the `dist` folder inside your script's directory.

## Usage

1. Open the application (either by running the script or the compiled executable).
2. Enter the job description in the "Job Description" box.
3. Press the "Start" button to get a tailored interview question.
4. Answer the question verbally. Press the "Submit" button to stop recording.
5. The application will transcribe your response, provide feedback, and rate your answer.

## Troubleshooting

If you encounter any issues, ensure that all dependencies are correctly installed and that your system PATH includes the path to the FFmpeg `bin` folder.

For further assistance, feel free to reach out!
