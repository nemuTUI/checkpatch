# Checkpatch for nEMU

This repository contains the [checkpatch.pl](checkpatch.pl) script, which is
used for checking patches submitted for the nEMU project.

The checkpatch.pl script was forked from the `checkpatch.pl`
script used for checking patches submitted for the Linux kernel.

## Quick start

To check git commit or file on the current branch, run the following command in
your local nEMU Git directory:

```sh
$ git clone git@github.com:nemuTUI/checkpatch.git
$ checkpatch/checkpatch.pl --color=always --show-types --git commit_hash
$ checkpatch/checkpatch.pl --color=always --show-types -f path_to_file
```
