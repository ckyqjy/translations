## SSL vs TLS: SSL와 TLS의 차이점을 파헤쳐 보자
#
> SSL과 TLS 프로토콜이 어떻게 다른지 알고 있는가? 당신이 얼마나 알고 있는지 알아보자...

거북과 남생이. 알약과 정제(錠劑). 묘지와 묘소. SSL와 TLS.
이 단어들의 공통점은 무엇일까? 조금 생각 해 보자.

만약 당신이 이 단어 쌍들이 같은 것을 의미 한다고 생각했다면, 당신은 틀렸다!
이 단어 쌍들은 사실 동의어가 아니다 - 엄연히 차이점들이 있다, 그리고 우리 대부분은 그것을 알아차리지 못할 수 있다.
이 단어 쌍들의 차이점에 대해 알아보지 않는 대신, 우리는 SSL과 TLS의 차이점에 대해 탐구할 것이다.

## SSL vs TLS: 이 프로토콜들의 주요 차이점들
사람들이 SSL/TLS 인증서에 관해 이야기 할때, 주로 웹사이트가 공개키 암호화 방식을 이용하는 HTTPS로 동작 할 수 있게 해 주는 X.509 디지털 파일에 대해 이야기한다.
그래서, SSL과 TLS는 같은 것일까? 완전히는 아니다. 하지만 이것들이 다르다면, 왜 두 용어는 상호 호환이 되는 것일까?
답은 두 부분으로 볼 수 있다.

1. 첫째로 두 용어 모두 HTTPS를 통한 웹 서버와 클라이언트(브라우저)간의 암호화된 통신을 구축하는 보안 프로토콜이기 때문이고
2. 둘째로 사람들은 변화가 느리고, IT 분야에서는 알아야 할 용어들이 많기 때문이다. 사람들은 SSL이라는 단어에 친숙하기 때문에 TLS를 SSL이라고 계속 부르는게 더 쉽기 때문이다.

하지만 TLS와 SSL이 다른 이유는 TLS는 SSL 프로토콜의 계승자(successor)이기 때문이다.
이것은 무슨 말일까? SSL과 TLS를 비교할 때, SSL과 TLS 프로토콜은 기능, 메세지의 인증, 알람 메세지, 레코드 프로토콜, 그리고 암호화 강도 등이 다르다.
특히 "SSL/TLS 핸드쉐이크" 라고 알려진 프로세스에서도 차이점이 있다.
이 프로세스는 클라이언트와 서버간에 통신 할 때에 실행된다.

## SSL vs TLS: SSL과 TLS는 어떻게 연결을 수립할까
SSL과 TLS가 각각 어떻게 연결을 수립하는지에 대한 차이점에 주목하는 것이 중요하다.
예를 들어, SSL 핸드쉐이크는 포트를 통해 연결을 하고, TLS는 반대로, 프로토콜을 통해 연결을 가능하게 한다.
이러한 핸드쉐이크는 암호화 스위트라고 불리는 특정 메소드/알고리즘을 기반으로 실행된다. 
SSL과 TLS간에 많은 차이점들이 있을지라도, SSL과 TLS간의 기초적인 차이점은 이러한 연결 보안에 중요한 역활을 하는 암호화 스위트에 기초 하고 있다.

암호화 스위트는 키 교환 알고리즘, 인증 알고리즘, 벌크 암호화 알고리즘, 그리고 메세지 인증 코드(MAC) 알고리즘을 포함한다. 모든 SSL/TLS 버전은 각각 지원되는 암호화 스위트 세트를 가지고 있고, 새로운 버전에 따라 더 안전한 암호화 스위트를 지원해서 보안성과 연결 성능을 향상시킨다.

## 결론: SSL과 TLS는 관련이 있지만 같지는 않다
이 글에서 SSL과 TLS에 대해 알아보았듯이, TLS는 조금 더 안전한 SSL이다. 이 둘은 기본적으로 웹사이트를 HTTPS로 지원하는 같은 기능을 하지만, 그 방식에 차이가 있다.
만약 TLS가 개발 되지 않았다면, 우리는 "SSL vs TLS" 대신 "SSL 5.0 vs SSL 4.0" 같은 것을 말하고 있었을지도 모른다.

---

via: https://sectigostore.com/blog/ssl-vs-tls-decoding-the-difference-between-ssl-and-tls/

작가：[Jay Thakkar](https://sectigostore.com/blog)
역자：[ckyqjy](https://github.com/ckyqjy)