# RAW

GitBook의 template Tag를 무시하고 있는 그대로의 텍스트를 출력하고 싶을 때는

```
    {% raw %}
        this will {{ not be processed }}
    {% endraw %}
```

이러한 형식으로 출력이 가능합니다.