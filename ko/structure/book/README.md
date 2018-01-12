# book.json

~~~
{
  "title" : "",//현재 문서의 제목
  "authors" : "", 
  "isbn" : "" , 
  "language" : "ko",//해당 문서의 언어
  "description" : "",//GitBook의 설명
  "structure" :{//파일들의 구조 정의 비워놨을시 default값
    "readme" : "README.md",
    "summary" : "SUMMARY.md",
    "glossary" : "GLOSSARY.md",
    "languages" : "LANGS.md"
  },
  "language" : "ko",
  "plugins" : [],// 플러그인 목록 플러그인들의 설정이나 선언은 최상위 book.json에서만 가능 따로해도 설정이 적용되지 않는다.
  "pluginsConfig" : {
  },//플러그인의 설정
  // 현재 문서에 추가할 링크
  	"links": {
  		// 링크를 추가할 위치. 왼쪽 상단에 나온다.
  		"sidebar": {
  			// 보여줄 링크 이름: 링크
  		}
  	},
  	// css 적용 가능하다.
    "styles": {
        "website": "styles/website.css",
    	"ebook": "styles/ebook.css",
    	"pdf": "styles/pdf.css",
    	"mobi": "styles/mobi.css",
    	"epub": "styles/epub.css"
    },
    "pdf" : {
    
    }//pdf옵션 설정
}
~~~