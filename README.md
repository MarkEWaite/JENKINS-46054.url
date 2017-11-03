# [JENKINS-46054](https://issues.jenkins-ci.org/browse/JENKINS-46054) - submodule with '.url' in repo URL won't clone or update

The regular expression which matched the output of the `git config` command was too aggressive.
