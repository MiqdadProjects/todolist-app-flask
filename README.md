📝 Flask To-Do App
A simple, elegant to-do list web application built with Flask.
Easily manage your daily tasks with a minimal and intuitive web interface.

🚀 Getting Started
Choose your platform and follow the step-by-step instructions below.

🐧 Linux/macOS Setup
1. Install Python & pip
bash
Copy
Edit
sudo apt-get update
sudo apt-get install python3 python3-pip
2. Create and activate a virtual environment
bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate
3. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
💡 If requirements.txt is missing or incomplete:

bash
Copy
Edit
pip install Flask python-dotenv
4. (Optional) Add a .flaskenv file for development
bash
Copy
Edit
echo -e "FLASK_APP=app\nFLASK_ENV=development" > .flaskenv
5. Run the application
bash
Copy
Edit
flask run
# OR
python3 app.py
Visit: http://127.0.0.1:5000

🪟 Windows Setup
1. Install Python 3
Download and install Python from python.org
✅ Be sure to check "Add Python to PATH" during installation.

2. Create a virtual environment
bash
Copy
Edit
python -m venv venv
3. Activate the virtual environment
PowerShell:

powershell
Copy
Edit
.\venv\Scripts\Activate.ps1
Command Prompt:

cmd
Copy
Edit
venv\Scripts\activate.bat
4. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
💡 If requirements.txt is missing or incomplete:

bash
Copy
Edit
pip install Flask python-dotenv
5. (Optional) Add a .flaskenv file
Create a file named .flaskenv and add:

ini
Copy
Edit
FLASK_APP=app
FLASK_ENV=development
6. Run the application
bash
Copy
Edit
flask run
# OR
python app.py
Visit: http://127.0.0.1:5000

💡 Tips
Use a .env or .flaskenv file to manage environment variables.

Use deactivate to exit the virtual environment.

This app is for development purposes. For production, use a WSGI server like Gunicorn or uWSGI.

🙌 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss what you'd like to change.