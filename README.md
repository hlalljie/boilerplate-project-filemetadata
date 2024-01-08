# File Metadata Microservice

This backend appplication allow users to upload files to your website through a form while also giving the user back info on the file.

See a live version of this app here: https://qv9fc7-3000.csb.app/

## Usage

User can upload files by chosing a file from their computer and clicking the upload button. The users are then given back file information (filename, filetype, and size).

The files are then stored in the uploads folder of your project directory.

## Installation and Setup

1. Clone this repo to a development environment
2. Open the terminal in the project directory and run `npm install`. You will need to run this command as an admin, so use `sudo` before the command on Mac and Linux, or run the Powershell as an administrator on Windows.
3. After the moduls have finished installing from the previous command, run the project by entering `npm start` in the terminal. You live webpage can now be found at <yoururl or localhost>:3000
4. If changes are made you will need to save, stop running the program, run the `npm start` command again.
5. If you would like to use another port you can create a .env file containing `PORT=<port to run on>`