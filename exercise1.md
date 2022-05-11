
We will assume that the application is coded with Python.

Apaprently Python applications can be linted with Pylint, Flake8, mypy or Pyright to name a few. There seems to be some differences on the supported Python versions withint the tools. All of the mentioned tools are free to use. 

Testing, in turn, can be dealt with PyUnit, Python Roobt Framework, PyTest or Python Gauge. Selecting the testing tool should be based on what kind of test are going to be written. For example, unit tests and integration tests may benefit from different libraries.

According to the course material, there is no need for build step with Python. However, for example a Python-Build library still exists. 

There seems to be plenty of tools to set up the CI besides Jenkins and GitHub Actions. Buddy, TeamCity, GoCD, Bamboo and Codeship could for example be utilized for this matter.

To decide if the CI setup should be local or cloud-based introduces many questions. Cloud-based solutions seem to be easier to get started with. However, there may be more limited set of confugrations and hardware resources with cloud-based CI tools. Also, security questions may raise concern.

Locally hosted CI systems usually provide larger set of options for the user. Extraordinary hardware resources may also be utilized. This, however, causes the need for monitoring and maintainig these systems.

