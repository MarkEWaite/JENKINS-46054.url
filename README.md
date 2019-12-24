# [JENKINS-46054](https://issues.jenkins-ci.org/browse/JENKINS-46054) -repo URL with '.url' won't update submodule

The regular expression which matched the output of the `git config`
command was too aggressive. It captured too much.

This file is from the JENKINS-46054.url repository.
