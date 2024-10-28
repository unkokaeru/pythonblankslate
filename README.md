# pythonblankslate

[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/unkokaeru/pythonblankslate?label=version)](https://github.com/unkokaeru/pythonblankslate)
[![Lines Of Code](https://tokei.rs/b1/github/unkokaeru/pythonblankslate?category=code)](https://github.com/unkokaeru/pythonblankslate)
[![Continuous Integration (CI) Tests](https://img.shields.io/github/actions/workflow/status/unkokaeru/pythonblankslate/continuous_integration.yml?label=tests)](https://github.com/unkokaeru/pythonblankslate)
[![GitHub last commit](https://img.shields.io/github/last-commit/unkokaeru/pythonblankslate)](https://github.com/unkokaeru/pythonblankslate)

Start your Python project from a Blankslate!

- [pythonblankslate](#pythonblankslate)
    - [Features](#features)
    - [Installation and Usage](#installation-and-usage)
    - [Usage](#usage)
    - [Documentation](#documentation)
    - [Contributing](#contributing)
    - [License](#license)

## Features

- [x] Installable via Cookiecutter
- [ ] Installable via Poetry package
- [x] Command-line interface
- [x] Interactive documentation
- [ ] Project validation and auto-upgrading
- [ ] Automatic test generation
- [ ] GUI generation

## Installation and Usage

Before starting, you'll need a GitHub account and Poetry account. For Poetry, you should go to your account settings and click on "Add API token" within the "API tokens" section where you can then name and add a token. Once created, copy the token and add it Poetry's config with this command:

```bash
poetry config pypi-token.pypi your-api-token
```

To create a project with untitledpython project, simply run:

```bash
pip install cookiecutter
```

and then

```bash
cookiecutter gh:unkokaeru/pythonblankslate
```

In order for GitHub Pages `docs` deployment and the TODO action to work, then you'll need to configure your new repository on GitHub a bit first. In your repository settings, go to...
- Code and automation -> Actions -> General -> Workflow permissions, then enable "Read and write permissions".
- Code and automation -> Pages -> Build and Development -> Branch, then select the `docs` branch and save.

## Documentation
For more information, you can find the documentation within the [docs](./docs/index.html) directory or on the project's [GitHub Pages](https://unkokaeru.github.io/pythonblankslate/).

## Contributing

Contributions are welcome! Please refer to our [CONTRIBUTING.md](./CONTRIBUTING.md) for more information.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
