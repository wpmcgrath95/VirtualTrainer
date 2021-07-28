# Virtual Trainer Project

# Setup for developement:

- Setup a python 3.x venv (usually in `.venv`)
  - You can run `./scripts/create-venv.sh` to generate one
  - virtual environment called *env*
- `python -m pip install --upgrade pip-tools`
- `pip3 install --upgrade pip` if need be 
- Install dev requirements `pip3 install -r requirements.dev.txt`
- Install requirements `pip3 install -r requirements.txt`
- `pre-commit install`

## Update versions

`pip-compile --output-file=requirements.dev.txt requirements.dev.in --upgrade`

# Run `pre-commit` locally.

`pre-commit run --all-files`