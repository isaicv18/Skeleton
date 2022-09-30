#### Create a virtual environment
pyenv install 3.10.2(Solo se hace una vez)
pyenv global 3.10.2
pyenv virtualenv my-project
pyenv activate my-project
pyenv local my-project

#### 2) Create a folder structure
repo_name
  -project_name
    -apps
    -models
    -etl
  -notebooks
  -private_notebooks
  -data

#### Copy the following files
pre-commit-config.yaml
pyproject.toml
readme.md

#### Install Packages with poetry
poetry add name_package
