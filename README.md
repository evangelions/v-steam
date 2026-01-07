
# Steam URL Checker

This is a cmd tool written in Go that allows you to check for thousands of available Steam IDs.
With This tool you can check all usernames from the `targets.txt` file.. If a username is available, it will be saved in the `output.txt` file under the sessions folder. This tool will also track progress, so you can stop and resume your session at any time.

## Features

- **Check Steam ID availability**: Check if a Steam ID is available.
- **Session management**: Create a new session or resume an existing one.
- **Progress tracking**: Pick up where you left off in case of interruptions.
- **Target generator**: Generates thousands of 3c/3l/4c/4l usernames in `targets.txt`.
  
## Download 
Download the win64 folder from the [release](https://github.com/evangelions/Vsteam/releases/tag/v1.4) page.

## Usage

When you run this tool, you'll see a menu to choose one of these actions:

1. **Start a New Session**: Create a new session to begin checking usernames from your `targets.txt` file.
2. **Resume an Existing Session**: Choose any existing session to continue checking.
3. **Generate Random IDs**: Generates a list of random 3c/3l/4c/4l in the `targets.txt` file.
4. **Exit**: Close the program.

## Issues
- Checker will currently give false positives for shadowbanned accounts (working on fix)
