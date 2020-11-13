---
layout: post
permalink: /seosecond/
title: '검색엔진에게 인사하기 : title, meta 태그의 활용'
date: 2020-11-11 23:02:00 +09:00
feature: '/img/posts/002/blog_thumbnail.jpg'
background: '/img/posts/002/seosecond_main.jpg'
categories:
  - SEO
tags:
  - 검색엔진최적화
  - 구글
  - 디지털마케팅
  - 검색광고
description: 'html의 title과 meta 태그를 활용하는 것은, 검색엔진최적화의 첫걸음과도 같습니다.'
---
## 지난 글 핵심 요약
 * SEO란 Search Engine Optimization의 약자로, ‘검색 엔진 최적화’를 의미
 * 웹의 뼈대가 되는 정보들은 html 이라는 마크업 언어로 쓰임
 * 검색엔진은 웹을 html을 통해 정보의 관점으로 해석하기에, seo를 위해서는 html에 대한 이해가 필요함

> 지난 글 [바로가기](https://earth971.github.io/seofirst/){: target="_blank"}

## 1. html을 편집하기 위한 에디터 추천 (feat. 아톰)

Html 을 직접 작성하기 위해서는 html 편집기가 필요합니다. 우리가 글을 쓰는데 노트와 연필이 필요하듯이, html 언어를 작성하기 위해서도 편집기가 필요한 것처럼요! 필자가 추천하는 편집기는 atom 에디터 입니다. 아톰 에디터는 깃허브에서 개발한 소스코드 편집기로, html 외에도 다양한 언어들을 지원하고 있습니다.

 >아톰 다운로드 홈페이지 [바로가기](https://atom.io/){: target="_blank"}

![아톰 홈페이지](/img/posts/002/atom.jpeg)
해당 페이지로 접속하고, Download를 눌러 다운로드를 진행해주시면 됩니다.

## 2. 아톰을 활용한 html 시작하기 - 패키지 설치 및 첫 실행
다운로드를 모두 마치고, atom을 실행하셨나요? 실행하셨다면, 본격적으로 html을 시작하기에 앞서 기본적인 패키지 설치를 해주셔야 합니다.

<b>다운로드가 필요한 패키지</b>
 * emmet
 * Language-asp
 * atom-html-preview
 * atom-beautify

<b>패키지 다운로드 방법</b>
 1. File -> Setting -> +install 을 클릭하시고, 위에 쓰여진 패키지들을 모두 다운로드 해주세요!
 2. 위의 화면이 뜨지 않는다면,  atom -> Preferences -> Settings -> +install 을 통해서도 가능합니다.

다운로드가 완료 되었다면, file -> add project file 을 눌러주시고,
![폴더추가](/img/posts/002/htmlfirst.jpeg)
추가된 폴더를 마우스 우클릭하여 New File을 생성해주세요. 제목을 작성할 때, index.html 과 같이 html 이라는 확장자명을 꼭 포함해주셔야 합니다! 이제 생성된 파일에 html 이라는 글자를 입력하시면, atom 편집기에서 자동으로 기본 구조를 입력해줄 것 입니다 :)


```
<html lang="ko" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>    
  </body>
</html>
```

위의 코드 속 head 라는 글자가 보이시나요? html은 크게 머리와 몸으로 이루어져 있는데, 그중에서도 머리 부분은 정보가 담겨있습니다. 마치 우리가 사람과 만날 때 얼굴을 통해 인상을 파악하는 것처럼, 검색엔진도 head에 담겨진 정보를 통해 많은 것을 읽어냅니다. 다음으로는, SEO를 위한 타이틀 태그와 메타 태그 활용법에 대해 안내하겠습니다.

## 3. SEO, 검색엔진최적화를 위한 title 태그와 meta description 태그 설정하기

- 본 내용은 생활코딩 검색엔진최적화 강의에서 정리된 title과 meta 태그의 seo 활용법을 포함하고 있습니다.

### (1) 명확하고 독창적인 html 타이틀의 사용
Title 태그는 사용자와 검색엔진에게 해당 페이지의 주제를 알려주고, 이는 검색 결과에 반영됩니다.
따라서,
 * 페이지의 콘텐츠를 정확하게 설명하는 제목
 * 페이지마다 고유한 title 태그 작성 (홈페이지 내 다른 페이지와 겹치지 않아야함)
 * 간결하면서 내용을 포함하는 제목 작성
 * 60글자 이내가 권고됨

### (2) 메타 태그의 “description” 활용하기
![메타 디스크립션 설명](/img/posts/002/metadescription.jpeg)
<p>메타 태그는 위의 사진의 빨간 박스와 같이, 구글 검색 시에 홈페이지 내용 미리보기로 활용되기에 매우 중요합니다.</p>
 * 100글자 이내
 * 페이지 고유의 메타 디스크립션 활용하기
 * 구글 웹마스터 도구를 통해 메타 태그 분석이 가능함
 * 1-2 문장 정도 이내에서 간결하고 명확하게 브랜드가 제공하는 가치를 기술할 것

## 4. Semantic HTML
html은 semantic tag와 non-semantic 태그로 이루어져 있습니다. 여기에서 Semantic tag 란, 의미론적 태그를 의미합니다. 이는 태그 자체가 정보로서 어떠한 의미를 제공한다는 뜻입니다. 검색엔진최적화를 위해서는 html의 의미론적 태그들을 적절하게 활용할 필요가 있습니다.

다음은 html의 semantic 태그 목록입니다. (출처 :[생활코딩](https://opentutorials.org/course/2039/10954){: target="_blank"})
![시멘틱태그](/img/posts/002/semantictag.jpeg)

## 5. 시맨틱 태그를 활용한 예제 영상
{% include youtube.html id="l3HowwEmqYA" %}
위의 영상을 보며 똑같이 따라해보세요! html 감을 익히기 위해서는 일단 따라해보는 것이 가장 좋습니다.

## 6. 다음 편, 검색엔진최적화를 위한 URL 구조 개선하기
오늘은 크게 title 태그와 meta 태그, 시멘틱 태그들에 대해 알아봤습니다. 다음 게시물에서는 seo를 위해 URL 구조를 어떻게 개선할 수 있을지와 몇가지 주의사항, 참고하면 좋은 영상들을 가져오도록 하겠습니다 :)
