# docker-python-qa
Repository for Docker image with all those little tools that keep you Python code clean

**Available tags**
```
valian/python-qa  # python 3
valian/python-qa:2  # python 2
```

# Usage

```bash
docker run --rm -v $PWD:/srv valian/python-qa pip-compile
docker run --rm -v $PWD:/srv valian/python-qa flake8
# etc
```

# Installed packages

**Python 3 image**

```
pip-tools 
flake8 
flake8-import-order 
flake8-docstrings 
flake8-bugbear 
flake8-commas 
flake8-quotes 
flake8-comprehensions 
mccabe 
mypy
isort
pre-commit
```

**Python 2 image**


```
pip-tools
flake8
flake8-import-order
flake8-docstrings
flake8-commas
flake8-quotes
flake8-comprehensions
mccabe
isort
pre-commit
```

# License

MIT
