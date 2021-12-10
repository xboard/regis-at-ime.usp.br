# regis-at-ime.usp.br
Mkdocs-material files to generate my academic webpage at https://www.ime.usp.br/~regis/

## Installing mkdocs-material

```bash
pip install -U mkdocs-material
```

## Building webpages
```bash
mkdocs build
```

## Serving locally

```bash
mkdocs serve
```
Open [http://localhost:8000](http://localhost:8000).

### Deploying
```bash
scp -r -p site/. regis@ime.usp.br:~/www/
```
