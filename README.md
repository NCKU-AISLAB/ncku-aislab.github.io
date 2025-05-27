# AISLab Website

This is the official website of AISLab, built using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) and automatically deployed via GitHub Pages at: [https://ncku-aislab.github.io](https://ncku-aislab.github.io)

## Prerequisites

- Python 3.7+
- PIP (or other Python package manager)
- Git

All required packages will be installed via `requirements.txt`. It is recommended to use a virtual environment.


## Editing

Clone the repository.

```shell
git clone git@github.com:NCKU-AISLAB/ncku-aislab.github.io.git
cd ncku-aislab.github.io
```

Install the required packages. It is recommended to use a virtual environment.

```shell
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Run the MkDocs server to preview the site.

```shell
mkdocs serve
```

Then, open your browser to [`http://127.0.0.1:8000`](http://127.0.0.1:8000).
You can edit the files in the `docs` directory to update the content of the site. The changes will be reflected in real-time in your browser.

## Deployment

We have set up GitHub Actions to automatically deploy the site when changes are pushed to the `main` branch. After editing the webpage, you can trigger a deployment by running:

```shell
git add .
git commit -m "docs: update webpage" # or any other commit message
git push
```

Please refer to the commit history for the commit message format.

```shell
git log --oneline
```
