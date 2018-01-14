# include
 
다른 문서의 내용을 재사용가능 하게 하는 문법입니다.
다른 파일의 내용을 include태그를 이용해 사용 가능합니다.

```
    {% include ".test.md" %}
```

또한 git태그를 이용해 컨텐츠를 include할수 있습니다.

```
    {% include "gitURL" %}
   git URL의 형태는 git+https://user@hostname/project/blah.git/file#commit-ish.git
   gitURL의 형태는 반드시 .git으로 끝내야합니다.
   commit-ish는 어떠한 태그, 커밋, 브랜치를 지정할수 있습니다. default는 master입니다.
   
```

delveopmentEnviroment를 include한 결과물

{% include "../../developmentEnviroment/README.md" %}
