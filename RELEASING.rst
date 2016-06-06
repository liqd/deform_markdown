.. highlight:: shell

=========
Releasing
=========

Initial setup
-------------

We use https://github.com/peritus/bumpversion to ease version bumping
and travis to automically deploy new tags to pypi.
Read: https://cookiecutter-pypackage.readthedocs.io/en/latest/travis_pypi_setup.html

Release
-------

1. Update HISTORY.txt (If not done yet)

2. Bump version number (major|minor|patch)

   `bumpversion minor`

3. Push commit and tag

   `git push --tags`

4. Check:

   * all test pass on travis
   * new release is deployed to pypi
   * pypi page displays properly
