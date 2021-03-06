여기서는 툴체인(Toolchain)의 의미가 무엇인지를 정리합니다. 

툴체인이라는 용어는 주로 임베디드 시스템에서 사용하는 용어인 것 같습니다.

툴체인이란 타겟 시스템에서 동작하는 프로그램 개발에 필요한 호스트 시스템의 소프트웨어들 또는 개발 환경을 통칭합니다. [^leeyongjeon-toolchain] 조금 더 자세하게 설명하면 소스 코드를 컴파일하고 빌드하여 바이너리 실행 파일을 생성하는데 필요한 각종 유틸리티 및 라이브러리의 모음이라고 할 수 있습니다. 

툴체인의 기본적인 구성 요소는 다음과 같습니다.  [^devmonster-65]

* Assembler
* Linker
* C Compiler
* C Library

등이 있습니다

위의 설명을 보면 툴체인이라는 용어는 크로스 컴파일을 염두해 둔 것임을 알 수 있습니다.  [^linuxism-96] 이 부분은 조금 더 이해하고 정리합니다.

> 그런 의미에서 리눅스에 Swift 를 설치할 때도 툴체인이라는 용어를 사용하는 것 같습니다. 해당 리눅스를 호스트로 해서 다른 시스템에 배포 가능한 실행 파일을 만들어 낼 수 있기 때문인 것 같습니다. 

### 고찰하기

나중에 툴체인, 라이브러리, 프레임웍 등의 용어를 비교 정리할 필요가 있을 것 같습니다. 

### 참고 자료

[^leeyongjeon-toolchain]: [툴체인(Toolchain)이란?](http://leeyongjeon.tistory.com/entry/툴체인Toolchain이란) : 설명에 그림이 곁들어 있어서 좋은 것 같습니다.  

[^linuxism-96]: [toolchain 이란](http://linuxism.tistory.com/96) : 툴체인이란 용어에 대한 풀이가 조금 나옵니다. 역시 좋은 글 같습니다. 

[^devmonster-65]: [용어정리: 툴체인(Tool chain)이란?](http://devmonster.tistory.com/65) : 툴체인에 대해서 간결하게 설명하고 있습니다. 