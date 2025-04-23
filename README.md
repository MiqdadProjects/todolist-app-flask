# 📝 Flask To-Do App

A simple, elegant to-do list web application built with [Flask](https://flask.palletsprojects.com/).  
Easily manage your daily tasks with a minimal and intuitive web interface.

---

## 🚀 Getting Started

Choose your platform and follow the step-by-step instructions:

---

## 🐧 Linux/macOS Setup

1. **Install Python & pip (if not already installed):**
    ```
    sudo apt-get update
    sudo apt-get install python3 python3-pip
    ```

2. **Create and activate a virtual environment:**
    ```
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install dependencies:**
    ```
    pip install -r requirements.txt
    # If requirements.txt is missing or incomplete, run:
    pip install Flask python-dotenv
    ```

4. **(Optional) Add a `.flaskenv` file for development:**
    ```
    echo -e "FLASK_APP=app\nFLASK_ENV=development" > .flaskenv
    ```

5. **Run the application:**
    ```
    flask run
    ```
    Or, if you prefer:
    ```
    python3 app.py
    ```

6. **Open your browser and visit:**  
   [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🪟 Windows Setup

1. **Install Python 3**  
   Download and install from [python.org](https://www.python.org/downloads/). Make sure to check "Add Python to PATH" during installation.

2. **Create a virtual environment:**
    ```
    python -m venv venv
    ```

3. **Activate the virtual environment:**
    - **PowerShell:**
      ```
      .\venv\Scripts\Activate.ps1
      ```
    - **Command Prompt:**
      ```
      venv\Scripts\activate.bat
      ```

4. **Install dependencies:**
    ```
    pip install -r requirements.txt
    ```
    If you get errors, also run:
    ```
    pip install Flask python-dotenv
    ```

5. **(Optional) Add a `.flaskenv` file for development:**  
   Create a file named `.flaskenv` in your project directory and add:
    ```
    FLASK_APP=app
    FLASK_ENV=development
    ```

6. **Run the application:**
    ```
    flask run
    ```
    Or, if you prefer:
    ```
    python app.py
    ```

7. **Open your browser and visit:**  
   [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 💡 Tips

- For environment variables, you can use a `.env` or `.flaskenv` file for convenience.
- Use `deactivate` to exit the virtual environment.
- This app is for development purposes. For production, use a WSGI server like Gunicorn or uWSGI.

---

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---


