### Homebrew에 새로운 저장소 등록하기 

`brew` 명령은 homebrew의 저장소에서 패키지를 다운받는 명령입니다. 하지만 어떤 경우에는 해당 저장소가 아닌 다른 저장소에 원하는 파일들이 있을 수 있습니다. 이 경우 homebrew는 새로운 저장소를 등록해서 다운받을 수있도록 하고 있습니다.

이것은 `brew tap` 명령을 통해 수행합니다. [^brew-tap]  [^brew-tap-1]

```
$ brew tap new_repository
$ brew install something
```

즉 위와 같이 하면 `new_repository`를 등록하고 `something` 패키지를 다운 받을 수 있습니다. 

### 이슈

참고 자료를 봅니다. [^brew-issues]

찬찬히 봐야할 자료입니다. [^kevinelliott]

### 참고 자료

[MacPorts](https://www.macports.org)

[Homebrew](http://brew.sh)

[HOMEBREW 로 OS X 패키지 관리하기](https://rkjun.wordpress.com/2013/07/14/os-x-missing-package-manager-home-brew/) : Homebrew의 사용법에 대해서 아주 설명을 잘 해놓은 글입니다.

[^brew-tap]: [brew tap](https://github.com/Homebrew/brew/blob/master/docs/brew-tap.md) : brew tap 명령에 대해서 잘 설명한 글입니다. 

[^brew-tap-1]: [brew-tap(1) -- Multi-Repository Support for Homebrew](https://raw.githubusercontent.com/Sharpie/homebrew/brew-tap/Library/Contributions/manpages/brew-tap.1.md) : brew tap 명령에 대한 다른 글입니다. 원본을 찾지 못해서 마크다운 원본 문서 링크를 걸어둡니다.

[^brew-issues]: [In macOS 10.12 Sierra, /usr/local is readonly.](https://github.com/Homebrew/brew/issues/385)

[^kevinelliott]: [macOS 10.12 Sierra Setup](https://gist.github.com/kevinelliott/7a152c556a83b322e0a8cd2df128235c) : macOS 1012 Sierra 에서 여러가지 도구들을 셋업하는 방법을 소개한 글 같습니다. 

[Homebrew 설치하기](https://veryfaraway.github.io/digging/homebrew.html) : `brew pin` 명령에 대한 설명이 있습니다.