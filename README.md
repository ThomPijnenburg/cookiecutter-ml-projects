# cookiecutter-ml-projects

Cookiecutter for Machine Learning projects

## Features

Project structure populated with:

* [Poetry](https://python-poetry.org) for python dependency management
* Makefile with all repetitive tasks automated
* Dockerfile for portability and reproducibility

## Requirements

* cookiecutter
* Python >="3.6"

## Usage

If you do not have cookiecutter installed you could do so with `pip`
```bash
$ pip install --user cookiecutter
```

Start generating the project with

```bash
# Create project from the cookiecutter-ml-projects repo template
# You'll be prompted to enter values.
# Then it'll create your Python package in the current working directory,
# based on those values.
$ cookiecutter https://github.com/ThomPijnenburg/cookiecutter-ml-projects
# For the sake of brevity, repos on GitHub can just use the 'gh' prefix
$ cookiecutter gh:/ThomPijnenburg/cookiecutter-ml-projects
```

It will ask you for the following:

```json
{
    "author_name": "author_name",
    "email": "example@test.com",
    "repo_name": "example-project",
    "package_name": "example_package",
    "project_short_description": "This is a project.",
    "version": "0.0.0"
}
```

Happy hacking!
