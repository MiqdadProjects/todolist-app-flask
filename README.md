# Flask To-Do App

A simple to-do list web application built using Flask.

## Setup

1. Create a virtual environment:
    ```bash
    python -m venv venv
    ```

2. Activate the virtual environment:

   - **Windows (PowerShell):**
     ```powershell
     .\venv\Scripts\Activate.ps1
     ```
   - **Windows (Command Prompt):**
     ```cmd
     venv\Scripts\activate.bat
     ```
   - **macOS/Linux:**
     ```bash
     source venv/bin/activate
     ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. (Optional) Add a `.flaskenv` file for easier development:

    Create a file named `.flaskenv` and add:
    ```env
    FLASK_APP=app
    FLASK_ENV=development
    ```

    Now you can run the app with:
    ```bash
    flask run
    ```

5. Or, run directly with Python:
    ```bash
    python app.py
    ```

Visit `http://127.0.0.1:5000` in your browser.
