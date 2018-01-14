# build된 html만 사용하는 방법

GitBook이 build될때 생성된 html파일만을 가져와 사용하는 방법입니다.
Front html에서 build된 html을 include하는 방식

* 이슈
    * Front단에서 보통 html을 inlcude가능한지 여부
    * build된 html만 사용할때 GitBook을 사용해야하는가???
        * markDown을 html로 변환하는 가벼운 lib만 사용하면 더욱 빠르고 간결하지 않을까?
    
* 장점
    * 내부에서 존재하는 html을 가져오는 방식이기 때문에 HTTP통신을 거칠 필요가 없습니다.
    
* 단점
    * build된 html만 사용하는경우 markDown을 html로 변환하는 다른 라이브러리가 더욱 가벼울것같다.
 