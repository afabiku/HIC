Simple portfolio Flask app

Run locally:

1. Create a virtualenv and install requirements:

   python -m venv .venv
   .\.venv\Scripts\Activate.ps1; pip install -r requirements.txt

2. Run the app:

   python index.py

Open http://127.0.0.1:5000 in your browser.

The CV is available at /static/files/Abimbola_Fabiku_CV.txt
Setup and run (PowerShell on Windows):

1. Create a virtual environment and activate it:
   python -m venv venv; .\venv\Scripts\Activate.ps1

2. Install dependencies:
   pip install -r requirements.txt

3. Run the app:
   python index.py

4. Open http://127.0.0.1:5000 in your browser.

Notes:
- The app serves templates from `templates/` and static files from `static/`.
- If you previously had a `template/` folder, this project prefers `templates/` when present.
