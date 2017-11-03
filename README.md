# [JENKINS-46054](https://issues.jenkins-ci.org/browse/JENKINS-46054) -repo URL with '.url' won't update submodule

The regular expression which matched the output of the `git config`
command was too aggressive.

This file is from the JENKINS-46054.url repository.

See the [regression test job](https://github.com/MarkEWaite/jenkins-bugs/blob/JENKINS-46054/Jenkinsfile) that uses this repository.
