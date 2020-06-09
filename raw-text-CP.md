== cp

Copy files and directories to and from containers using the following example.

.Example: Copy a file from the `python-1-mz2rf` Pod to the local file system
----
$ oc cp default/python-1-mz2rf:/opt/app-root/src/README.md ~/mydirectory/.
----
