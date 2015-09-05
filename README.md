# Profile Inspector
Give it a Gentoo profile, and this utility will parse it and all its parents. It will print out the accumulated results, to show how the profile will act when selected.

It also complains if the PMS is violated by unexpected input or circular dependencies.

# Building
ant

For binary distribution:
ant dist

# Usage
bin/profileinspector -p <path to profile>
