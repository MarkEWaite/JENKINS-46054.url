# [JENKINS-46054](https://issues.jenkins-ci.org/browse/JENKINS-46054) -repo URL with '.url' won't update submodule

The regular expression which matched the output of the `git config`
command was too aggressive. It captured too much.  Also needs a specific
text string in the most recent commit message.

This file is from the JENKINS-46054.url repository.
