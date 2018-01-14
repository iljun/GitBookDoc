# WebHook 기능

gitbook.com에서 WebHook기능을 설정할수 있습니다.

아래와 같은 화면에서

![capture](../../img/capture.png)

특정한 이벤트때 webHook을 받을 url을 설정 가능합니다.

특정한 이벤트란 4가지가 존재합니다.

| 이벤트   | 설명    |
|----------|---------|
| All   |   이벤트 발생시 언제나 reqeust전송   |
| Publish   |   특정한 branch에서 puslbish됐을때 reqeust전송  |
| thread     |  Discussion이 열리거나 닫혔을때 또는 다시 열렸을때 reqeuest전송 |
| thread_comment     |  Discussion이나 pullRequest에 comment가 달렸을때 request전송   |

WebHook의 request

|   RequestHeader   |   설명  |
|----------|---------|
| X-GitBook-Event	Name     |   이벤트명   |
| X-GitBook-Signature   |   secret키를 설정한 경우 HMAC방식으로 인코딩되어 전송됩니다. |
| X-GitBook-Delivery  |  Request의 고유한 ID가 전송됩니다. |

webHook은 post의 형태로 전달받습니다.
