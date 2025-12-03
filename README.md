# Git repo (https://github.com/JRiyaz/ai-ml)

# Git command
Use `git init --separate-git-dir <folder>` to create a git repository in different path.
```shell
git init --separate-git-dir C:\\Users\\Riyaz\\aiml-git
```

# uv commands
Use `uv venv <folder>` to create a virtual environment in different path.
```shell
uv venv C:\\Users\\Riyaz\\aiml-venv
```
    (or)
```shell
export UV_PROJECT_ENVIRONMENT=C:\\Users\\Riyaz\\aiml-venv
```
add above line in .env file and run following commands
```shell
source .env

uv venv

uv init

uv sync
```

