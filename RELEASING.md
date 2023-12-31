# Making a Release of pytest-mpl

To make a new release of pytest-mpl follow the following steps:

* Ensure the sdist and wheel GitHub Actions jobs succeeded on main after the last merge.
* Also ensure that the tarball built has an autogenerated version number from setuptools_scm.
* Write the release notes in the GitHub releases UI, use the autogenerated
  notes and tidy up a little.
* Publish the new release, using the format `vX.Y.X`.
* Watch as GitHub actions builds the sdist and universal wheel and pushes them to PyPI for you, and updates CHANGES.md on the main branch.
* Enjoy the beverage of your choosing 🍻.
