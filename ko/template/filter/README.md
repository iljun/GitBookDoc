# Filter

변수값을 출력할때 다양하게 filter할수 있는 기능이 있습니다.

```
{{ foo | title }}
{{ foo | join(",") }}
{{ foo | replace("foo","bar") | capitalize }}
```

위와 같이 변수에 필터를 적용해서 사용할 수있습니다.

## 세번째인 경우 foo를 bar로 바꾸고 uppercase를 하는 filter입니다. 