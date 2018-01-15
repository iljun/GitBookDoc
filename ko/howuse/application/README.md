# application 내부에 GitBook을 포함하는 방식

Application 내부에 GitBook을 포함시켜 내부에서 구동시키는 방법

* 장점
    * 다른 플랫폼을 사용할 필요가 없다.
    * application 내부에 위치시키고 구동시키기 때문에 다른 도메인을 사용할 필요 없습니다.
    
* 이슈
    * GitBook에 push 했을 때 Application 내부에 GitBook을 udpate해야 됩니다.
        * webHook 방식을 이용해 수동으로 update 하는 방식
            * request를 받았을 때 git pull -> gitbook build -> gitbook serve
            * git pull이나 gitbook build에서 오류가나는 에러 처리가 필요합니다.
        * ci를 이용해 자동으로 배포하는 방식
            * [travis ci](https://travis-ci.org/)
            * 기술적으로 도입이 가능하지 테스트 및 라이센스 문제 검토