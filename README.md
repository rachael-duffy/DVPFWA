# Damn Vulnerable Python Flask Web Application

Make [Flask Tutorial Project](https://github.com/pallets/flask/blob/main/examples/tutorial) to be security vulnerable

## Installation

Run bellow command:
```bash
python3 -m venv damn-vulnerable-python-flask-web-application
cd damn-vulnerable-python-flask-web-application
source bin/active
pip3 install -r requirements.txt
```

## Run application

If it's your first time or you want to clear the database, run:
```bash
python3 main.py --init
```

If you want to keep the old database, run:
```bash
python3 main.py
```