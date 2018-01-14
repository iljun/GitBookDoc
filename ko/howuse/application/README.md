# application 내부에 GitBook을 포함하는 방식

Application내부에 GitBook을 포함시켜 source코드를 외부로 유출시키지 않는 방법

* 장점
    * source코드가 외부로 유출되지 않는다.
    * application내부에 위치시키고 구동시키기 때문에 다른 도메인을 사용할 필요없습니다.
    
    
* 이슈
    * GitBook에 push했을때 application내부에 gitBook을 udpate해야된다.
        * webHook방식을 이용해 수동으로 update하는 방식
            * webHook을 받았을때 git pull -> gitbook build -> gitbook serve
            * git pull이나 gitbook build에서 오류가나는 에러처리가 필요합니다.
        * ci를 이용해 자동으로 배포하는 방식
            * [travis ci](https://travis-ci.org/)
            * 기술적으로 도입이 가능하지 테스트 및 라이센스 문제 검토