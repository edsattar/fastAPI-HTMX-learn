## Setting up

### create a python virtual environment
```sh
mkdir .venv
pipenv shell
```

### git
```sh
ni README.md
ni .gitignore
@"
.venv\
__pycache__\*
"@ >> .gitignore
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/edsattar/fastAPI-HTMX-learn.git
git push -u origin main
```
