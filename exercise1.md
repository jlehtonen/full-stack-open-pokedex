The most popular Python linters are probably Pylint and Flake8. For testing,
there is the unittest framework which is part of the Python standard library.
Another popular choice is pytest. Building can be done with the help of a
standard library package called setuptools and a file called setup.py which is
similar to package.json in the JavaScript world. In setup.py you use the
functions provided by setuptools to add metadata associated with the package
you are building. The actual build step consists of running the setup.py file
with the Python interpreter.

Some alternatives to Jenkins and GitHub Actions are TeamCity by JetBrains,
Bamboo by Atlassian, GitLab Continuous Integration and Travis CI.

For an application that is developed by only 6 people, a cloud-based CI system
would probably be the best choice, unless there are some unusual requirements.
The reason is that setting up a cloud-based CI system is easier than a
self-hosted one so if you don't need the flexibility offered by a self-hosted
system, it's usually best to use a cloud-based one. For a small to medium sized
project a cloud based CI system is probably also cheaper than setting up a
self-hosted system. However, if you need to, for example, have some tests run
on a graphics card or if your project has some other "unusual" requirements, a
self-hosted system could be a better option.
