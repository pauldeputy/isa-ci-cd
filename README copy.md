# DOR8-test

## Local Run

```sh
sudo apt install python3-pip python3-venv -y
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

# Run tests
pytest -v

# Run app
uvicorn app.main:app

```