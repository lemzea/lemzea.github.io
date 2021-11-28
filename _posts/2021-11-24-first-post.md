# MarkDown 문법 정리
Github로 블로그를 이용하기 위해서는 MarkDown문법을 통해 Posting 해야했다.

익숙치 않은 MarkDown으로 작성하는 MarkDown 문법 정리 해보려고한다.
## MarkDown 개요
![MarkDown](https://heropy.blog/css/images/vendor_icons/markdown.png)
MarkDown은 일반 텍스트 기반의 경량 마크업 언어이며, 읽기 쉽고 쓰기 쉬운 것이 특징이다.

## MarkDown의 장점
* 편리하다.
* 관리가 쉽다.
* 지원 가능한 플랫폼과 프로그램이 많다.

```
어쨋든 해보니 편리하고 쉽긴 하다.
다른건 아직 잘 모르겠다.
```
## MarkDown의 단점
* 표준이 없다.
* 모든 HTML 마크업을 대신하진 못한다.

## MarkDown 연습
### 목록
```
1. 하나
1. 둘
1. 셋

순서없는 목록은 space 두번만큼 들여쓴다.
+ 순서없는 목록 하나
  - 순서없는 목록 둘
    * 순서없는 목록 셋
      + 순서없는 목록 넷
```
1. 하나
1. 둘
1. 셋

+ 순서없는 목록 하나
  - 순서없는 목록 둘
    * 순서없는 목록 셋
      + 순서없는 목록 넷

### 강조
```
__볼드__
_이태릭_
~~취소~~
<u>밑줄</u>
__볼드와 *이태릭*의 혼합 사용과 <u>밑줄까지</u> 하고나서 ~~이건 취소~~__
```
__볼드__<br>
_이태릭_<br>
~~취소~~<br>
<u>밑줄</u><br>
__볼드와 *이태릭*의 혼합 사용과 <u>밑줄까지</u> 하고나서 ~~이건 취소~~__

### 인용구
```
> 1단계 인용
>> 2단계 인용
>>> 3단계 인용
```
> 1단계 인용
>> 2단계 인용
>>> 3단계 인용

### 링크
```
URL 직접 링크 : <https://lemzea.github.io>
URL 간접 링크(설명 클릭) : [내 블로그](https://lemzea.github.io/)
동일 파일 내 문단 이동 : [문단 이동] (## MarkDown 연습)
```
URL 직접 링크 : <https://lemzea.github.io><br>
URL 간접 링크(설명 클릭) : [내 블로그](https://lemzea.github.io "이동 하기")<br>
동일 파일 내 문단 이동 : [문단 이동](#MarkDown-연습)

### 이미지
원본으로 이미지 삽입 : <br>![이미지](https://heropy.blog/css/images/vendor_icons/markdown.png)<br>

사이즈 조절해서 이미지 삽입 : <br><img src="https://heropy.blog/css/images/vendor_icons/markdown.png" width="300" height="200">

이미지에 링크 담기 : <br>[![이미지](https://heropy.blog/css/images/vendor_icons/markdown.png)](https://lemzea.github.io)