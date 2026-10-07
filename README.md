# Lifecare Health System

**Mayank Singh Sadudia | MCA healthcare management project**

My existing Flask and SQLite academic prototype for patient and doctor registration, administrator approvals, appointment requests and profile management. The repository was prepared from my original local project archive.

## Implemented features

- Patient and doctor registration forms.
- Patient, doctor and administrator login interfaces.
- Administrator lists and approval of registration requests.
- Patient appointment requests and doctor approval or rejection.
- Doctor appointment lists and patient/doctor profile updates.
- SQLite tables for accounts, requests and appointments.

This project demonstrates **web application development and database workflows**. It is presented separately from sentiment analysis and business reporting; it is not a clinical prediction model.

## Run the local academic demo

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```

Set `LIFECARE_ADMIN_USERNAME` and `LIFECARE_ADMIN_PASSWORD` in your terminal to values you choose for this local demo, then run:

```powershell
python app.py
```

Open `http://127.0.0.1:5000`. A fresh local database is created in `database/`; the original database is excluded. Register fictional patients and doctors, sign in as the demo administrator, and approve their requests.

## Prototype limitations

The original application uses plaintext account passwords, request-based identifiers and incomplete authorization checks. It needs password hashing, authenticated sessions, route authorization and query hardening before any real deployment. Use fictional records only. No compliance, medical suitability or production security is claimed.

## Publication preparation

The original app and templates were retained. The existing patient database, IDE settings and report containing personal identifiers were excluded. The built-in administrator password was replaced with local environment configuration, and the entry point binds to localhost with debug disabled.

[Portfolio](https://mayanksinghsadudia.github.io/mayank-portfolio/) | [GitHub](https://github.com/Mayanksinghsadudia)
