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
 2 files changed, 1 insertion(+), 1 deletion(-)
 create mode 100644 abc.txt

/c/util/web/versionnumbers (master)
$ cat version.info
version = 1.0.2
```
