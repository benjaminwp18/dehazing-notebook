# Dehazing notebook

## Dependencies
 - [Install Quarto](https://quarto.org/docs/get-started/)
 - [Install Quarto VSCode Extension](https://marketplace.visualstudio.com/items?itemName=quarto.quarto)
 - Pip packages:
```bash
python -m venv venv
. venv/bin/activate
pip install -r requirements.txt
```

## Deploy

```bash
cd notebook
quarto install tinytex
quarto publish gh-pages
```

## Preview

Whole site:
```bash
quarto preview notebook
```

Or `ctrl` + `k` for a single file in VSCode.
