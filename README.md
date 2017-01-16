# Ahab: self-modifying Docker files
```sh
$ ahab new mysql
created ~/bin/mysql
run "mysql --ahab-dockerfile" to edit the dockerfile
run "mysql --ahab-run" to edit the runtime script
run "mysql --ahab-build" to build the untagged docker image
run "mysql <anything else>" to launch the application in a transient container
```

That about sums it up. The scripts are self-contained, self-modifying things
that turn custom-image Dockerized setups into single files.
