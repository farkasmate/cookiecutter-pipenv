# {{ cookiecutter.name }}

## Add to project (Pipenv)

    [packages]
    {{ cookiecutter.name }} = { git = '{{ cookiecutter.homepage }}' }

## Usage

    import {{ cookiecutter.name }}

## Run linter

    pipenv install --dev
    pipenv run pylint {{ cookiecutter.name }}

## Package

    pipenv run python setup.py sdist bdist_wheel
