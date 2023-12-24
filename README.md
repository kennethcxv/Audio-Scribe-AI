# Pluto Hacks 2023 Hackathon Project

Welcome to our project for Pluto Hacks 2023! This repository contains all the necessary information and resources for our innovative hackathon project.

## Requirements 
- Python 3.x
- pip
- virtualenv (recommended for a contained environment)

## Setup
Follow these steps to get your development environment set up:
- Clone the repository:
 ```git clone https://github.com/kennethcxv/Audio-Scribe-AI.git```
 ```cd Audio-Scribe-AI```
- Set up a virtual environment (optional but recommended):
 ```python -m venv myenv```
- Activate the virtual environment:
On macOS and Linux:
 ```source myenv/bin/activate```
On Windows:
 ```myenv\Scripts\activate```
- Install the required packages

## Environment Variables:
- Set up the .env file in the root directory with your variables. Example:
 ```API_KEY=YOUR_OPENAI_API_KEY```
Replace YOUR_OPENAI_API_KEY with your actual API key.

## Running the Project

To run the project, activate the virtual environment and execute:
 ```python YOUR_MAIN_SCRIPT_NAME.py```
This will start the Flask server, making the API accessible at ```http://localhost:5000```

## Endpoints
Key API endpoints include:
- **Start Recording:** ```POST /start_recording```
- **Stop Recording:** ```POST /stop_recording```
- **Play Audio:** ```GET /play_audio```
- **Display Transcript:** ```GET /display_transcript```
- **Display Summary:** ```GET /display_summary```
- **Display Reminders:** ```GET /display_reminders```
- **Translate:** ```GET /translate/<target_language>```
- **Load Latest Recording:** ```GET /load_latest_recording```
- For detailed specifications, refer to the source code or the API documentation.

## Contributing

Contributions to this project are welcome!

## License

This project is licensed under the **MIT License**.

Note: Replace placeholders like YOUR_USERNAME, YOUR_REPO_NAME, YOUR_MAIN_SCRIPT_NAME, and YOUR_OPENAI_API_KEY with your specific details.
