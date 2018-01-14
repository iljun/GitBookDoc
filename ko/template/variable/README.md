# 변수
***

GitBook은 다른 템플릿 처럼 변수를 사용할수 있습니다.


변수는 book.json에 정의되어있고
사용법은 중괄호로 사용할수 있습니다.
js처럼 배열형태로도 가능하다.
```book.foo.bar```로도 사용가능하며
```book["bar"]```로도 변수사용이 가능하다.


***
    변수에서는 GitBook의 파일경로나 마지막 수정시간등 인스턴스 정보를 얻는것이 가능하다.
    file.path --> 파일의 상대경로
    file.mtime --> 파일의 마지막 수정 시간
***

```file.path``` {{ file.path }}
```file.mtime``` {{ file.mtime }}

### 변수는 상위 book.json의 변수만을 참조한다.