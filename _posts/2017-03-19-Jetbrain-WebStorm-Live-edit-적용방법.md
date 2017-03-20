---
layout: post
title: "Jetbrain WebStorm Live edit 적용방법"
description: "실시간으로 변경사항을 확인할 수 있는 Front-End 개발자의 무기"
tags: [webstorm, liveedit, jetbrain]
---

학교 이메일로 웹 스톰을 쓰고 있다. Live Edit 이라는 기능이 정말 마음에 드는데, 처음 할 때 친절히 설명된 곳을 찾기 어려웠다. 간단히 설명해보자면 HTML 페이지의 변경사항을 바로 브라우저에 띄워주는 기능이다. 하나 변경하고 새로고침 하는게 꽤 번거로운일이라 Live Edit 기능을 이용하면 정말 쉽게 변경사항을 확인할 수 있다.

## 준비물

- WebStorm
- Jetbrain 크롬 익스텐션 설치 ( [https://goo.gl/u9t3SH](https://goo.gl/u9t3SH) )
- Live Edit 할 Html 페이지

## 설정

아래와 같은 순서로 진행한다.

![](https://s3-us-west-2.amazonaws.com/notion-static/80dd132b78ec4c29b37a075f0721f01c/Untitled)
![](https://s3-us-west-2.amazonaws.com/notion-static/6d8e403de2ca4d73a7dbc2f3af37f227/Untitled)

1. 우측 상단의 `Edit Configurations.. ` 를 선택한다. (Fig. 1)
2. 2번째 이미지와 같은 설정창이 표시된다. + 버튼으로 Javascript Debug 를 새로 추가한다. (Fig. 2)
3. 원하는 프로젝트를 열고, Live Edit 하려는 파일을 선택한다.
4. 브라우저를 크롬으로 설정한다. (Default : Chrome)

## 실행

간단히 상단에 표시되는 벌레(Debug) 버튼을 누르면 아래 Debug Console 이 활성화 되고 크롬 브라우저에 Live Edit 이 되는 창이 띄워진다.

![](https://s3-us-west-2.amazonaws.com/notion-static/a439034a2d8c452a84a4e3d37bbb5f74/Untitled)

혹시나 크롬 익스텐션을 설치하지 않았다면 [JetBrain IDE Support Extension](https://goo.gl/u9t3SH) 을 설치하자.

( 안해봤지만 PHP storm 등도 마찬가지로 세팅 할 수 있을 듯 하다. )

## 결론

이렇게 하면 편하다!
