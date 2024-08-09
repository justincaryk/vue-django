

### Requirements

- [Install python](https://www.python.org/downloads/)
- [TODO: add db](https://docs.djangoproject.com/en/5.1/topics/install/#get-your-database-running)


### Setup

1. initialize .venv

```bash
python -m venv .venv
```
2. activate the virtual environment

```bash
source .venv/bin/activate
```

To kill the virtual environment, run:

```bash
deactivate
```

3. install packages into venv:

```bash
pip3 install -r requirements.txt
```

### Adding new packages

```bash
python3 -m pip install [package_name]
```

after adding any new package, run this command to ensure the package is tracked in github

```bash
pip freeze > requirements.txt
```

*avoid manually modifying `requirements.txt`*
