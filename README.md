# 플라스크 공부

## 회사에서 사용하는 python 프로젝트 알기위해 공부하기

1. 실행하기

flask run 명령어를 사용하여 실행할 수 있다.  
단, Flask가 설치되어 있어야한다.

```commandline
flask run    
```

2. 트러블 슈팅

예전에는 ``db.create_all()`` 사용을 할 수 있었지만, 현재는 flask 컨텍스트가 실행후 사용하도록 with을 사용하여 실행해야한다.
