# PIP Chill 개선 버전
 > 테스트 및 작업 중인 패키지입니다..


`pip chill`에서 `--required-pkgs` 옵션을 하나 추가했습니다. 이 옵션으로 넘긴 패키지명은 `requirements.txt`에서 남아있게 되는 옵션입니다.



pip chill에 대한 링크
* Github : https://github.com/rbanffy/pip-chill
* Documentation: https://pip-chill.readthedocs.io.


# 설명
예시

`pip chill`을 할 때에 `django, django-environ` 두 개가 있다면 `django-environ`만 나오게 된다.




# 셋팅
```shell
pip install git+https://github.com/exizt/pip-chill-forked.git
```


# 사용법
예시
```shell
$ pip-chill

django-debug-toolbar==4.2.0
django-environ==0.11.2
pip-chill==1.0.2


$ pip-chill --required-pkgs django
django==4.2.7
django-debug-toolbar==4.2.0
django-environ==0.11.2
pip-chill==1.0.2
...




