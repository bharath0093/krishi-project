# Farm Equipment Management System

A Streamlit application for farm equipment booking and billing. The repository contains the app, database, service, notification, and security modules.

## Run locally

1. Install Python 3.10 or later.
2. Clone the repository and enter the project folder:

   ```bash
   git clone https://github.com/YogeshdiplomaCS/krishi-equipment-management-system---hackathon_winned-project.git
   cd krishi-equipment-management-system---hackathon_winned-project
   ```

3. Create and activate a virtual environment, then install dependencies:

   ```bash
   python -m venv .venv
   # Linux/macOS: source .venv/bin/activate
   # Windows PowerShell: .venv\Scripts\Activate.ps1
   python -m pip install -r requirements.txt
   ```

4. Configure database and service settings locally, following the names expected by the app. Never commit real passwords, tokens, or API keys. Use a disposable test database while developing.
5. Launch the app:

   ```bash
   streamlit run app.py
   ```

## Before production use

Verify authentication and booking-conflict behavior, configure backups and database access controls, and add tests and deployment instructions. Treat the current repository as a project in development until those checks are documented.
