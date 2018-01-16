# customStyle

GitBook에서는 default theme나 theme plugin을 확장 시킬수 있는 방법이 있습니다.

```
    * css 파일을 적용해 사용하는 방법
        * book.json과 같은 위치에 styles/website.css를 생성
        * book.json에 styles 설정을 적용합니다.
        * .md 파일이 변환된 html 태그에 css를 적용합니다.
            * 우선순위는 직접 작성한 css 파일이 우선순위가 높습니다.
            
    * theme에 존재하는 block을 재정의 하는 방법
        * theme는 block 단위로 구성되어있습니다. 이 block을 재정의해 custom하는 방법이 있습니다.
            * 이 부분은 조금더 상세하게 code를 첨부하도록 하겠습니다.
```