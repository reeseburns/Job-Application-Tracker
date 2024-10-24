# Job Tracking Web Application

Our vision is to create a simple and easy to use job application tracker, that aims to help job seekers stay organized and prepared during their application process.

## Instructions

### Step 1: Download Files
1. Zip File
    * Download all files from this repository
2. Python
    * Download and install python and pip

### Step 2: Setting up the Virtual Environment:
1.  Create a new virtual environment
    ```
    python -m venv venv
    ```
2. Activate the Environment
    * On Mac OS
        ```
        source venv/bin/activate
        ```
    * On Windows
        ```
        venv\Scripts\activate
        ```

### Step 3. Install Package Requirements
1. In the activated virtual environment run
    ```
    pip install -r requirements.txt
    ```

### Step 4. Set Up The Environment File
* The environment file contains sensitive information that is needed to run the web app.
This is information like the server name, server identifier, the secret key, and other environment variables. For this project, the environemnt file was sent to the graders and admins.

1. Download the environment file
2. Move the .env file to the main directory of the web app

### Step 5. Run The Web App
1. Make sure you are in the directory of the web app, and the virtual environment is activated 
2. Export the flask app
    * For Mac OS
        ```
        export FLASK_APP=app.py
        ```
    * For Windows
        ```
        set FLASK_APP=app.py
        ```
3. Start Flask
    * Run 
        ```
        flask run
        ```
4. Open the web app
    * Your terminal will output a link, open the link in your web browser to run the app
