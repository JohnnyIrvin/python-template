# Project Name

This template is for creating a new project. Please replace this section with your project's introduction.

# Tasks

- [ ] Create a new project from this template.
- [ ] Replace the project name in the README.md file.
- [ ] Rename project_name/ to your project_name in snake_case.
- [ ] Update usage notes to reflect the new project name.
- [ ] Update the license to reflect the new project contributors.
- [ ] Update each file's license header to reflect the new project contributors.

# Usage

Inside of a python environment, you can import the requirements and run the following commands to start the project.

```bash
pip install -r requirements.txt
python -m project_name
```

If you prefer to use docker, you can use the docker image.
```bash
docker build -t project_name --target RUN .
docker run project_name
```

# Testing
To test the library, you can use the `run_tests.py` script. It is highly recommended to use the docker image to keep your system isolated from integration tests.

Using docker, you can run the following commands to run the tests.
```bash
docker build -t tests --target TEST .
docker run tests
```

You may still run the tests on your system, but it is recommended to use the docker image.
```bash
pip install pytest
python -m pytest
```

# License

This project is licensed under the MIT license.

# Contribution

This project is open source. Feel free to contribute to the project by making a pull request, creating an issue ticket, or sending an email to [Johnny Irvin](mailto:irvinjohnathan@gmail.com).
