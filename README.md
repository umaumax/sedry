# sedry

sed dry-run command

## how to use
``` bash
sedry 's/#/@/g' /etc/hosts /etc/passwd
cat /etc/hosts /etc/passwd | sedry 's/#/@/g'
```
### env
``` bash
SEDRY_SED=gsed
SEDRY_WHOLE_FILE=1
```


## ISSUE
* 引数のファイルパスの確認方法をそのファイルが存在するかどうかで判定している
