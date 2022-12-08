
## Prerequisites



## Contributing

### Environment Setup

Clone the project to your work space:

```bash
git clone git@github.com:taskrabbit/feature_store.git
```

In this project, we use [Poetry](https://python-poetry.org/docs/) for depedency management. For MacOS users, you can install `poetry` using the following command:

```bash
$curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

At the root of the project, install the package dependencies (including `dev` dependencies):

```bash
poetry install
```

Then install the pre-commit hooks for this project:

```bash
poetry run pre-commit install
```



### Commit Messages

For this project, we use the following format: `type: message`.

* for example: `feat: added a feature view for the Iris dataset.`

You can refer to this [cheatsheet](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716) on writing semantic commit messages.

### Changelog

Please follow the patterns outlined in [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) when making changes to `CHANGELOG.md`.
* Put yourself in the user's shoes and think about what they would want to see in the log.

### Versioning

Follow the semantic versioning standards which are outlined in this [guide](https://semver.org/).
* **Do not** include `v` or `V` in the release version (e.g. `v1.0.0`).