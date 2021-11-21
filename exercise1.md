The most popular Python linters are probably Pylint and Flake8. For testing,
there is the unittest framework which is part of the Python standard library.
Another popular choice is pytest. Building can be done with the help of a
standard library package called setuptools.

Some alternatives to Jenkins and GitHub Actions are TeamCity by JetBrains,
Bamboo by Atlassian, GitLab Continuous Integration and Travis CI.

For an application that is developed by only 6 people, a cloud-based CI system
would probably be the best choice, unless there are some unusual requirements.
The reason is that setting up a cloud-based CI system is easier than a
self-hosted one so if you don't need the flexibility offered by a self-hosted
system, it's usually best to use a cloud-based one.
