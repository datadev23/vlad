# Vlad to project rsync script

## Description

Use this script (````vlad-rsync.sh````) to copy Vlad's files from this directory to a new or existing project directory.
Unnecessary files will not be copied (.git and so on). See the exclude & include lists beside this script for further details.

### BEWARE!
Any old Vlad files found at the destination path that are no longer required will be deleted.

## Usage

Ensure this script is executable and then run it passing the destination path as an argument.

For example:

```
$ path/to/this/script path/to/your/project
```