# Texas Gourmet Chef Mockup

Flask homepage mockup for a Texas-rooted private chef, events, and consulting brand.

## Structure

```text
.
|-- Dockerfile
|-- README.md
`-- app/
    |-- app.py
    |-- requirements.txt
    |-- templates/
    |   `-- index.html
    `-- static/
        |-- css/
        |   `-- styles.css
        `-- images/
            |-- chef-hands.jpg
            |-- chef-plating.jpg
            |-- kitchen-service.jpg
            |-- prep-board.jpg
            |-- salmon-table.jpg
            `-- texas-table.jpg
```

## Install Dependencies

```bash
python -m venv venv
source venv\Scripts\activate
pip install -r app/requirements.txt
```
## Local Run
```bash
python app/app.py
```

Open `http://localhost:5000`.
