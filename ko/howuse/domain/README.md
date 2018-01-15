# Domain 활용법

Editor사용자들을 위한 Guide를 작성하고

GitBook에 배포된 URL을 iframe에 삽입하는 방식입니다.

* 이슈
    * GitBook플랫폼의 도메인을 기업에서 사용하므로 라이센스부분에 문제가 있을수 있습니다.
    * CORS를 위한 별도의 설정이 필요할수 있습니다.
    
* 장점
    * 가장 간편하고 ci등 다른 도구가 필요하지 않습니다.

* 단점
    * 성능에 문제가 생길수 있습니다.(iframe)
    * GitBook 플랫폼의 속도가 매우 느리다.
    
domain forwarding을 이용해 GitBook domain에 등록해 이용하는방법