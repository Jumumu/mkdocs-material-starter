# MkDocs Material Starter

A starter project for using MkDocs with the Material theme.

## Getting Started

1. Optionally, create a Python virtual environment:
    ```
    python3 -m venv .venv
    ```
    ```
    source .venv/bin/activate
    ```
1. Install MkDocs and MkDocs material:
    ```
    pip3 install -r requirements.txt
    ```
1. Copy your Markdown files to the `docs` folder. The `index.md` file will be
   used as the home page.
1. Run the builtin development server:
    ```
    mkdocs serve
    ```
1. Open http://localhost:8000/ in a browser to view the documentation
1. Build HTML documentation as desired. The HTML will be output to the `site`
   folder.
    ```
    mkdocs build
    ```

## Publishing to GitHub Pages

See the documentation
[here](https://squidfunk.github.io/mkdocs-material/publishing-your-site/#github-pages)
for instructions.
