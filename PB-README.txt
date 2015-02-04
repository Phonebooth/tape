This project was forked as to not rely on the 1.2.4-SNAPSHOT version but still
get access to API added in master since 1.2.3.

build deplloy to local file system with something similar to the following:
$ mvn clean deploy -DaltDeploymentRepository=repo::default::file:/tmp/repo
