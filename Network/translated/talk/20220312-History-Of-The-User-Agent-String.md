## 브라우저 user-agent string 의 역사


처음에는 일리노이 대학교 어배너-섐페인 부설 연구소, 미국 국립 수퍼컴퓨팅 응용 연구소인 NCSA(National Center for Supercomputing Applications)의 대학생이었던 던 마크 앤드리슨(Marc Andreessen)과 에릭 비나(Eric Bina)가 공동 개발한 웹 브라우저인 `모자이크`가 있었다. 모자이크는 NCSA_Mosaic/2.0 (Windows 3.1) 라고 불렸다. 팀 버너스리가 만든 기존의 WorldWideWeb 브라우저가 텍스트 위주였던 것과 달리, 모자이크는 이미지를 표시할 수 있는 최초의 그래픽 웹 브라우저였다.


그리고 `모자이크 킬러`, 줄여서 `모질라`라고 알려진 새로운 웹 브라우저가 탄생했다. 모자이크는 그에 대해 불쾌해 했고, 곧 공식 명칭을 `넷스케이프`로 변경했다. 그리고 넷스케이프는 Mozilla/1.0 (Win3.1) 라고 불렸고, 그에 대해 만족해 했다.
넷스케이프는 `프레임`을 지원했고 프레임은 사람들 사이에서 유명해졌다. 하지만 모자이크는 프레임을 지원하지 않았고, 그래서 `user agent sniffing`이라는 것이 사용되었다. 웹마스터들은 모질라에게는 프레임을 보내고, 다른 웹브라우저들에게는 프레임을 보내지 않았다.


넷스케이프는 마이크로소프트를 조롱하고 윈도우즈를 폄하했다. 그래서 마이크로소프트는 화가 났고 넷스케이프를 사장시키기 위해 웹 브라우저를 직접 개발해서 인터넷 익스플로러라고 명명했다. 웹마스터들이 인터넷 익스플로러에 익숙해지기도 전에 마이크로소프트는 너무 급속도로 성장했다. 그래서 인터넷 익스플로러는 `모질라 호환` 이라고 선언하고 자신을 Mozilla/1.22 (compatible; MSIE 2.0; Windows 95) 라고 명명하며 넷스케이프를 흉내내기 시작했다. 인터넷 익스플로러는 프레임을 받았고, 마이크로소프트는 행복해 했다. 하지만 웹마스터들은 헷갈려 했다.


마이크로소프트는 윈도우즈에 인터넷 익스플로러를 끼워 팔았고, (실적이) 넷스케이프보다 더 좋아졌다. 그리고 첫 번째 브라우저 전쟁이 발발했다. 그 결과 넷스케이프는 사장되었고 마이크로소프트는 기뻐했다. 하지만 넷스케이프는 모질라로서 부활했고, 모질라는 직접 개발한 게코 프레임워크를 탑재하고 Mozilla/5.0 (Windows; U; Windows NT 5.0; en-US; rv:1.1) Gecko/20020826 라고 명명했다. 게코는 좋은 렌더링 엔진이었다. 그리고 모질라는 `파이어폭스`가 되었고, Mozilla/5.0 (Windows; U; Windows NT 5.1; sv-SE; rv:1.7.5) Gecko/20041108 Firefox/1.0 라고 명명하였다. 파이어폭스는 성능이 좋았고, 다른 브라우저들이 게코 코드 기반으로 개발되면서 게코는 번성하기 시작했다. 그러한 게코 엔진 기반 브라우저들은 각각 Mozilla/5.0 (Macintosh; U; PPC Mac OS X Mach-O; en-US; rv:1.7.2) Gecko/20040825 Camino/0.8.1, Mozilla/5.0 (Windows; U; Windows NT 5.1; de; rv:1.8.1.8) Gecko/20071008 SeaMonkey/1.0 등으로 명명하며 모질라를 흉내내었다. 


당시 게코가 좋고, 인터넷 익스플로러가 좋지 않았기 때문에 `agent user sniffing`이 다시 생겨났다. 게코는 다른 브라우저들에게는 없는 좋은 웹 코드가 제동되었다. 그리고 리눅스 추종자들은 슬퍼했다. 왜냐하면 리눅스에는 KHTML 엔진을 탑재한 캉커러를 탑재했는데, 리눅스 추종자들은 KHTML 엔진이 게코만큼 좋다고 생각했지만 그것이 게코는 아니었기 때문에, 좋은 페이지들을 서비스 할 수 없었고, 캉커러는 좋은 페이지들을 얻기 위해서 스스로 Mozilla/5.0 (compatible; Konqueror/3.2; FreeBSD) (KHTML, like Gecko) 라고 명명하며 `like Gecko`처럼 흉내 내기 시작했고, 그것은 더 많은 혼란을 불러 일으켰다.


그리고 "어떤 브라우저가 표준이 되어야 하는지 유저가 결정해야 한다"며 오페라가 등장했다. 오페라는 메뉴 아이템을 생성하고 유저의 옵션 선택에 따라서 Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.1; en) Opera 9.51, Mozilla/5.0 (Windows NT 6.0; U; en; rv:1.8.1) Gecko/20061208 Firefox/2.0.0 Opera 9.51, Opera/9.51 (Windows NT 5.1; U; en) 중에 하나로 명명했다.


애플은 사파리를 탑재했는데, KHTML 기반에 많은 기능들을 추가했고, 그것을 웹킷이라고 불렀지만 페이지가 KHTML로 쓰여지기를 원했기 때문에 사파리는 Mozilla/5.0 (Macintosh; U; PPC Mac OS X; de-de) AppleWebKit/85.7 (KHTML, like Gecko) Safari/85.5 라고 명명했지만 나쁜 선택이었다.


마이크로소프트는 파이어폭스를 몹시 두려워했고, 인터넷 익스플로러는 Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.0) 로 칭하며 새롭게 돌아왔고, 웹마스터들이 잘 설정한다면 좋은 코드를 렌더링 할 수 있었다.


구글은 크롬을 만들었는데, 사파리와 비슷하고 사파리를 위한 페이지를 원했다. 그래서 그래서 크롬은 웹킷을 사용하였고, 사파리와 비슷하게 되었다. KHTML은 게코를 흉내내었고, 결국 모든 브라우저들이 모질라를 따라하게 된 셈이다. 그래서 크롬은 Mozilla/5.0 (Windows; U; Windows NT 5.1; en-US) AppleWebKit/525.13 (KHTML, like Gecko) Chrome/0.2.149.27 Safari/525.13 이라고 했고, user agent string은 서로가 서로를 따라하며 은 완전히 엉망진창이 되었다.  


---

via: https://webaim.org/blog/user-agent-string-history/


작가：[Aaron Andersen](https://webaim.org/blog/user-agent-string-history/)

역자：[ckyqjy](https://github.com/ckyqjy)

참조 : 
https://ko.wikipedia.org/wiki/NCSA
https://ko.wikipedia.org/wiki/%EB%AA%A8%EC%9E%90%EC%9D%B4%ED%81%AC_(%EC%9B%B9_%EB%B8%8C%EB%9D%BC%EC%9A%B0%EC%A0%80)
https://ko.wikipedia.org/wiki/%ED%94%84%EB%A0%88%EC%9E%84_(%EC%9B%94%EB%93%9C_%EC%99%80%EC%9D%B4%EB%93%9C_%EC%9B%B9)
https://ko.wikipedia.org/wiki/%EA%B2%8C%EC%BD%94_(%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4)
https://ko.wikipedia.org/wiki/%EC%BA%89%EC%BB%A4%EB%9F%AC
https://ko.wikipedia.org/wiki/KHTML
