# Release Audit

Small Python program for displaying support-ticket information.

## Requirements

- Python 3.12 or newer
- Git 
- All project dependancies found in "Requirements.txt"

## Setup

1. Create a clone of the repository by typing "git clone https://github.com/LukeStreeter835/CPS310-ICA08-DevOps.git" into your IDE terminal 
2. Create a virtual envioroment (.venv) by typing "python -m venv .venv" into your IDE terminal
3. Activate the .venv by typing ".venv\Scripts\Activate.ps1" into your IDE Terminal
4. Download the dependancies by typing "python -m pip install -r requirements.txt" in terminal

# Configuration

This program uses the "config.json" file to store all special configuration settings.
- "data_file" : holds the name of the text file that holds all the important data for the program itself
- "report_title" : holds the name of the report title
- "high_priority_threshold" : holds the number which decides how important the ticket is compared to other tickets

## Running the program

```text
python release_audit.py
```

## Running the unit test

```text
python -m pytest -v
```

## Running the verification test

```text
.\verify.ps1
```

## Ready Realese 

```text
Original version had a solid foundation with a runnable program that worked. But it lacked a lot of important features making it hard to run in different enviroments. This new version has added features to make it alot easier to do just that. Instead of not knowing what dependancies and what versions are needed, you can now access and download all of them with the "requirements.txt" file. Important configurations are now in a seperate file from actual program file, making them easire to access. And now "verify.ps1" now lets you check dependancies, configuration, and unit tests at the same time for convience. 
```