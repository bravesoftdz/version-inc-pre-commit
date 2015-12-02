# version-inc-pre-commit

## Example
```
$ ls
foo/  version.info

/c/util/web/versionnumbers (master)
$ touch abc.txt

/c/util/web/versionnumbers (master)
$ git add :/

/c/util/web/versionnumbers (master)
$ git commit -m "abc"
Attempting to Increment Version Number...
version.info: Version 1.0.6, Next Version: 1.0.7
[master d17a6b0] abc
 2 files changed, 1 insertion(+), 1 deletion(-)
 create mode 100644 abc.txt
 
/c/util/web/versionnumbers (master)
$ cat version.info
version = 1.0.7
date = 12/2/2015
```
