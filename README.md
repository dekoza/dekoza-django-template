# dekoza-django-template


Bleeding edge `django3.2` template focused on code quality and security. Based on [wemake-django-template](https://github.com/wemake-services/wemake-django-template) but with **current** LTS Django.

---

## Purpose

This project is used to scaffold a `django` project structure.
Just like `django-admin.py startproject` but better.


## Features

- Always [`up-to-date`](https://github.com/dekoza/dekoza-django-template/pulls?utf8=%E2%9C%93&q=is%3Apr%20author%3Aapp%2Fdependabot) with the help of [`@dependabot`](https://dependabot.com/)
- Supports latest `python3.8+`
- [`poetry`](https://github.com/python-poetry/poetry) for managing dependencies
- [`mypy`](https://mypy.readthedocs.io) and [`django-stubs`](https://github.com/typeddjango/django-stubs) for static typing
- [`pytest`](https://pytest.org/) and [`hypothesis`](https://github.com/HypothesisWorks/hypothesis) for unit tests
- [`pre-commit`](https://pre-commit.com/), [`isort`](https://pycqa.github.io/isort/) and [`black`](https://black.readthedocs.io/) for automated linting
- [`docker`](https://www.docker.com/) for development, testing, and production
- [`sphinx`](http://www.sphinx-doc.org/en/master/) for documentation
- [`Gitlab CI`](https://about.gitlab.com/gitlab-ci/) with full `build`, `test`, and `deploy` [pipeline configured by default](https://gitlab.com/sobolevn/wemake-django-template/-/pipelines)
- [`Caddy`](https://caddyserver.com/) with [`https`](https://caddyserver.com/docs/automatic-https) and `http/2` turned on by default


## Installation

Firstly, you will need to install [dependencies](https://cookiecutter.readthedocs.io/en/latest/):

```bash
pip install cookiecutter jinja2-git
```

Then, create a project itself:

```bash
cookiecutter gh:dekoza/dekoza-django-template
```



## License

MIT. See [LICENSE](https://github.com/dekoza/dekoza-django-template/blob/master/LICENSE) for more details.
