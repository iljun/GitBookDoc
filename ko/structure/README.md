# GitBook의 구조
***

***
     - book.json
     - LANGS.md
     - README.md
     - SUMMARY.md
     - GLOSSARY.md
     - chatper/
            - README.md
            - SUMMARY.md
    
|   파일명 |   설명  |
|----------|---------|
|   book.json   |   설정 파일, 상위 폴더에 book.json이 존재할 시 상위 폴더의 설정을 물려받습니다.  |
|   README.md   |   파일의 본문 내용   |
|   SUMMARY.md  |   목차  |
|   LANGS.md    |   다국어를 지원하기 위해 언어마다 디렉토리를 설정해줍니다.   |
|   GLOSSARY.md  |   본문의 내용에서 설명이 필요한 부분의 설명을 적어놓는 파일(사전의 역할) 언어별로 나눈 디렉토리의 최상단에서 적용하는 방법이 가장 좋은 방법이라고 생각합니다.    |


##### 다국어 버전

***
    - README.md
    - LANGS.md
    - ko /
        README.md
        SUMMARY.md
        GLOSSARY.md
            -chapter1 /
                README.md
                SUMMARY.md
                
    - en /
        README.md
        SUMMARY.md
        GLOSSARY.md
            -charpter1 /
                README.md
                SUMMARY.md
***