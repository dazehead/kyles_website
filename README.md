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

## Local Run

```bash
python -m venv venv
source venv\Scripts\activate
pip install -r app/requirements.txt
python app/app.py
```

Open `http://localhost:5000`.

## Docker Run

```bash
docker build -t texas-gourmet-chef .
docker run -p 8080:8080 texas-gourmet-chef
```

Open `http://localhost:8080`.

## Notes

- `.env.example` lives in `app/` for future configuration. Keep real `.env` values out of source control.
- The booking form is currently presentational and ready to connect to email, a CRM, or a database.
- Images are downloaded into `app/static/images` for container-friendly deployment.
