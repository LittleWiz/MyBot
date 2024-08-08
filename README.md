This project uses Poetry for package management

* Poetry [https://python-poetry.org/docs/#installation]

Follow along below steps:

* Go to proejct path in anaconda prompt

* To check the python version
```bash
python --version
```

* Create new environment
```bash
conda create --name 3.11 python=3.11.7
```

* Check whether enviorment is created or not
```bash
conda info --envs
```

* Activate the environment
```bash
conda activate 3.11
```

* Install poetry package
```bash
pip install poetry
```

* Install dependencies using Poetry
```bash
poetry install
```

* Activate the virtual environment
```bash
poetry shell
```

* To check the environment
```bash
poetry env info
```

* To add new dependency
```bash
poetry add <package-name>
```

* To update dependencies
```bash
poetry update
```

