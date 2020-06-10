== exec

Execute a command in a container.

.Example: Execute the `ls` command in the `python` container from Pod `python-1-mz2rf`
----
$ oc exec python-1-mz2rf -c python ls
----