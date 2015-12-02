# version-inc-pre-commit

## Example
```
$ cd versionnumbers/

/c/util/web/versionnumbers (master)
$ ls
foo/  version.info

/c/util/web/versionnumbers (master)
$ cat version.info
version = 1.0.1

/c/util/web/versionnumbers (master)
$ touch abc.txt

/c/util/web/versionnumbers (master)
$ git add :/
warning: LF will be replaced by CRLF in foo/version.info.
The file will have its original line endings in your working directory.

/c/util/web/versionnumbers (master)
$ git commit -m "abc"
PHP SCRIPT IN PRE-COMMIT
array(3) {
  [0]=>
  string(1) "1"
  [1]=>
  string(1) "0"
  [2]=>
  string(1) "1"
}
int(2)
array(3) {
  [0]=>
  string(1) "1"
  [1]=>
  string(1) "0"
  [2]=>
  string(1) "2"
}
version.info: Version 1.0.1, Next Version: 1.0.2
warning: LF will be replaced by CRLF in version.info.
The file will have its original line endings in your working directory.
[master warning: LF will be replaced by CRLF in version.info.
The file will have its original line endings in your working directory.
4edd11d] abc
warning: LF will be replaced by CRLF in version.info.
The file will have its original line endings in your working directory.
 2 files changed, 1 insertion(+), 1 deletion(-)
 create mode 100644 abc.txt

/c/util/web/versionnumbers (master)
$ cat version.info
version = 1.0.2
```
