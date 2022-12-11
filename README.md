

## Installing and Managing Packages in Contained Environment

Make sure you have pip

```{wsl}
python -m pip --version
```

download or upgrade as necessary

```{wsl}
python -m pip install -–upgrade pip
```

```{wsl}
# Allow Python Script to Run
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
python -m venv venv
venv\Scripts\activate
```

```{wsl}
deactivate
```

## Handy Snippets

```{wsl}
python --version
# Or
python -V
```

## GIT Stuff
