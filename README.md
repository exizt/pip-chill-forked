# PIP Chill 개선 버전

pip chill에서 옵션을 하나 추가했습니다.


pip chill에 대한 링크

* Documentation: https://pip-chill.readthedocs.io.
* github : https://github.com/rbanffy/pip-chill



# 추가한 옵션
`--required-pkgs`


예시
```shell
$ pip-chill --no-chill --required-pkgs django -v > requirements.test.txt
...
