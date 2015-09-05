# Profile Inspector
Give it a Gentoo profile, and this utility will parse it and all its parents. It will print out the accumulated results, to show how the profile will act when selected.

It also complains if the PMS is violated by unexpected input or circular dependencies.

# Building
To build, run:
````bash
ant
````

For binary distribution:
````bash
ant dist
````

# Usage
Simply run:
````bash
bin/profileinspector -p <path to profile>
````
