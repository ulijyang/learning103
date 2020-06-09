== cp

Copy files and directories to and from containers.

.Example: Copy a file from the `python-1-mz2rf` Pod to the local file system
----
$ oc cp default/python-1-mz2rf:/opt/app-root/src/README.md ~/mydirectory/.
----