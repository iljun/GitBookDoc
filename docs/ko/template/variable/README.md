# 변수
***

GitBook은 다른 템플릿처럼 변수를 사용할 수 있습니다.


변수는 book.json에 정의되어습니다.

###### 사용법 
{% raw %}
    {{ variable }}
{% endraw %}

js처럼 배열 형태로도 가능합니다.
```book.foo.bar```로도 사용 가능하며
```book["bar"]```로도 변수 사용이 가능합니다.


***
    변수에서는 GitBook의 파일 경로나 마지막 수정시간 등 인스턴스 정보를 얻는 것이 가능
    file.path --> 파일의 상대 경로
    file.mtime --> 파일의 마지막 수정 시간
***

```file.path``` {{ file.path }}

```file.mtime``` {{ file.mtime }}

### 변수는 상위 book.json의 변수만을 참조합니다.