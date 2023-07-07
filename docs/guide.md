# Guide

## Build System

There are several build system options available to development of Python
packages. SciCookie support the following:

- [**Poetry**](https://python-poetry.org/) (default): It's a Python package
  manager that streamlines dependency management and package distribution. It
  provides a simple and intuitive syntax for defining project dependencies and
  allows you to easily create and manage virtual environments for your projects.
  With Poetry, you can easily install, update, and remove dependencies, and it
  automatically handles conflicts and resolution between packages. Additionally,
  Poetry provides a comprehensive toolset for packaging and publishing your
  projects to PyPI, including support for building source distributions and
  wheel packages, as well as generating and uploading documentation. Overall,
  Poetry simplifies the development and distribution of Python projects, making
  it a popular tool for many Python developers.

- [**Flit**](https://flit.pypa.io): It's a Python package and a lightweight tool
  for creating and distributing Python packages. It automates the processes
  involved in packaging and submitting a project to PyPI, and provides a
  straightforward interface for managing a project's dependencies. With just a
  few  commands, you can use Flit to quickly create source distributions and
  wheel packages and submit them to PyPI.

- [**Hatchling**](https://hatch.pypa.io): 
  It's a is a PEP 517/PEP 660 compatible build backend used by Hatch, a modern, extensible Python project manager. It provides a standardized build system with reproducible builds by default, robust environment management with support for custom scripts, easy publishing to PyPI or other indexes, version management, and configurable project generation with sane defaults.
  Hatchling ensures that your builds are reproducible, so you can be confident that they will always produce the same results. It also helps you manage your Python environments, so you can be sure that your projects have the correct dependencies. Additionally, Hatchling makes it easy to publish your Python projects to PyPI or other indexes. It also helps you manage the versions of your Python projects, so you can be sure that you are always using the latest stable versions. Finally, Hatchling allows you to configure the project generation process, so you can create projects that meet your specific needs.

The idea behind the options in SciCookie is that you can choose from some of the
most popular system compilers to suit your needs and preferences for developing
Python packages. If you think we should add more options, you can submit your
suggestion as a issue at
https://github.com/osl-incubator/scicookie/issues/new/choose.
 
## Test Library

There are several test library options available to development of Python packages. SciCookie support the following:

-  [**Pytest**](https://docs.pytest.org/en/): is a popular testing framework for Python. It simplifies the process of writing and running tests by providing a concise syntax and powerful features. With Pytest, you can automatically discover and collect test cases, use fixtures for test setup and resource management, and write test functions with assert statements to check expected outcomes. It offers various options for test execution, including running specific tests, parallel execution, and generating test reports. Pytest also has a thriving ecosystem of plugins that extend its capabilities, such as code coverage analysis and test parameterization. Overall, Pytest is widely adopted for its simplicity, flexibility, and community support, making it an effective tool for ensuring the quality and reliability of Python code. You can check documentation [here](https://docs.pytest.org/en/)

- [**Hypothesis**](https://hypothesis.readthedocs.io/): is a property-based testing library for Python. It focuses on generating diverse input data and exploring different scenarios to thoroughly test code. Instead of relying on specific examples, Hypothesis allows you to define general properties that your code should satisfy. It automatically generates random inputs, including edge cases, to uncover potential bugs and unexpected behaviors. Hypothesis integrates well with popular testing frameworks like Pytest and promotes comprehensive testing to improve code reliability. You can check documentation [here](https://hypothesis.readthedocs.io/)
