# ir-tsukuba.github.io

## How to make changes online
- Add or edit files
- The change will be automatically applied to the website

## How to make changes locally
- Clone the repo
- Create a virtual environment
    ```
    python -m venv venv
    source venv/bin/activate    # Linux/Mac
    .\venv\Scripts\activate     # Windows
    ```
- Install libraries and start the server
    ```
    (venv) python -m pip install -U pip
    (venv) python -m pip install -r requirements.txt
    (venv) mkdocs serve
- Visit localhost:8000