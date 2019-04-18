# 코딩 인터뷰 대학(Coding Interview University)

> 나는 원래 이것을 소프트웨어 엔지니어가 되기 위한 짧은 연구 목록으로 만들었다.
> 그러나 지금 당신이 볼수 있듯이 이 목록은 매우 커졌다. 이 목록을 숙지 한 후, 
> [나는 아마존에 소프트웨어 엔지니어로 채용됐다](https://startupnextdoor.com/ive-been-acquired-by-amazon/?src=ciu)!
> 당신은 아마 내가 한 것처럼 많이 공부할 필요는 없을 것이다. 어쨌든 당신이 필요로 하는 모든 것은 여기에 있다.
>
> 여기에 나열된 목록들은 아마존, 페이스북, 구글, 마이크로소프트 같은 거대 기업을 포함한 거의 모든 소프트웨어 회사의 인터뷰를 준비하는데에 도움이 될것이다.
> 
>
> *행운을 빈다!*

번역:
- [중국어](translations/README-cn.md)
- 진행 중인 번역:
    - [스페인어](https://github.com/jwasham/coding-interview-university/issues/80)
    - [힌디어](https://github.com/jwasham/coding-interview-university/issues/81)
	- [히브리어](https://github.com/jwasham/coding-interview-university/issues/82)
    - [바하사 인도네시아어](https://github.com/jwasham/coding-interview-university/issues/101)
    - [아랍어](https://github.com/jwasham/coding-interview-university/issues/98)
    - [베트남어](https://github.com/jwasham/coding-interview-university/issues/92)
    - [터키어](https://github.com/jwasham/coding-interview-university/issues/90)
    - [프랑스어](https://github.com/jwasham/coding-interview-university/issues/89)
    - [러시아어](https://github.com/jwasham/coding-interview-university/issues/87)
    - [우크라이나어](https://github.com/jwasham/coding-interview-university/issues/106)
    - [브라질 포르투갈어](https://github.com/jwasham/coding-interview-university/issues/113)
	- [한국어](https://github.com/jwasham/coding-interview-university/issues/118)

## 코딩 인터뷰 대학이란?

코딩 인터뷰 대학은 웹 개발자(컴퓨터공학 학위 없이 독학)에서 구글의 소프트웨어 엔지니어가 되기 위한 나의 몇 달 간의 공부 계획이다.

![Coding at the whiteboard - from HBO's Silicon Valley](https://dng5l3qzreal6.cloudfront.net/2016/Aug/coding_board_small-1470866369118.jpg)

이 기나긴 리스트는 **구글 코칭 노트**에서 선별되고 확장된 것으로 여러분이 알아야 할 내용이다. 맨 아래에는 인터뷰에 등장하거나 문제를 푸는 데에 도움이 될 만한 추가적인 내용이 있다. 많은 내용이 Steve Yegge의  "[Get that job at Google](http://steve-yegge.blogspot.com/2008/03/get-that-job-at-google.html)"이라는 책에서 나왔으며, 때때로 구글 코칭 노트의 내용을 그대로 담고있기도 하다.

나는 Yegge의 추천으로부터 여러분이 알아야만 할 내용들을 추려내었다. 구글과의 연락으로 얻은 정보를 바탕으로 그의 추천내용을 수정하였다. 이 리스트는 신입 소프트웨어 엔지니어, 혹은 소프트웨어/웹 개발에서 소프트웨어 엔지니어링(컴퓨터과학 지식이 필요한)으로 전환하는 사람들을 위한 것이다

만약 당신이 여러 해의 소프트웨어 엔지니어링 경력이 있다면, 더 어려운 인터뷰가 예상된다. [더 보기](https://googleyasheck.com/what-you-need-to-know-for-your-google-interview-and-what-you-dont/).

만약 당신이 여러 해의 소프트웨어/웹 개발 경험을 가지고 있다면, 구글은 소프트웨어 엔지니어링을 소프트웨어/웹 개발과 다르게 바라보고 있으며 컴퓨터과학 지식을 요구한다는 사실에 주목하도록 하자.

신뢰할만한 엔지니어, 혹은 시스템 엔지니어가 되고 싶다면 선택적 주제 목록(네트워크, 보안 등)을 더 공부하도록 하자.

---

## Table of Contents

- [코딩 인터뷰 대학이란?](#코딩-인터뷰-대학이란)
- [Why use it?](#why-use-it)
- [How to use it?](#how-to-use-it)
- [구글 분위기 내기](#구글-분위기-내기)
- [Did I Get the Job](#did-i-get-the-job)
- [팔로우 하려면](#팔로우-하려면)
- [당신은 충분히 똑똑합니다](#당신은-충분히-똑똑합니다)
- [구글에 대해](#구글에-대해)
- [영상 자료에 관하여](#영상-자료에-관하여)
- [인터뷰 과정 & 전반적인 인터뷰 준비 과정](#인터뷰-과정--전반적인-인터뷰-준비-과정)
- [인터뷰를 위한 언어 고르기](#인터뷰를-위한-언어-고르기)
- [도서 목록](#도서-목록)
- [시작하기 전에](#시작하기-전에)
- [다루지 않을 것](#다루지-않을-것)
- [선수 과목](#선수-과목)
- [하루 하루의 계획](#하루-하루의-계획)
- [알고리즘 복잡도 / Big-O / 점근적 분석](#알고리즘-복잡도--big-o--점근적-분석)
- [자료구조](#자료구조)
    - [배열](#배열)
    - [링크드 리스트](#링크드-리스트)
    - [스택](#스택)
    - [큐](#큐)
    - [해쉬 테이블](#해쉬-테이블)
- [추가 지식](#more-knowledge)
    - [이진 검색](#binary-search)
    - [비트 연산](#bitwise-operations)
- [트리](#trees)
    - [트리 - 배경지식](#trees---notes--background)
    - [이진 탐색 트리: BSTs](#binary-search-trees-bsts)
    - [힙 / 우선순위 큐 / 이진 힙](#heap--priority-queue--binary-heap)
    - 균형 탐색 트리 (간단한 개념)
    - 트리운행: 전위운행, 중위운행, 후위운행, 너비우선탐색(BFS), 깊이우선탐색(DFS)
- [정렬](#sorting)
    - 선택정렬
    - 삽입정렬
    - 힙정렬
    - 퀵정렬
    - 병합정렬
- [그래프](#graphs)
    - 방향 그래프
    - 무방향 그래프
    - 인접행렬
    - 인접리스트
    - 운행: 너비우선탐색(BFS), 깊이우선탐색(DFS)
- [더 많은 지식](#even-more-knowledge)
    - [재귀](#recursion)
    - [동적 프로그래밍](#dynamic-programming)
    - [객체 지향 프로그래밍](#object-oriented-programming)
    - [디자인 패턴](#design-patterns)
    - [조합 & 확률](#combinatorics-n-choose-k--probability)
    - [NP, NP-완전 and 근사 알고리즘](#np-np-complete-and-approximation-algorithms)
    - [캐쉬](#caches)
    - [프로세스와 쓰레드](#processes-and-threads)
    - [논문](#papers)
    - [테스팅](#testing)
    - [스케쥴링](#scheduling)
    - [시스템 루틴의 구현](#implement-system-routines)
    - [문자열 검색 & 조작](#string-searching--manipulations)
- [시스템 디자인, 확장성, 데이터 핸들링](#system-design-scalability-data-handling) (4년 이상 경력자를 위한 주제)
- [최종 리뷰](#final-review)
- [코딩 문제 연습](#coding-question-practice)
- [코딩 연습 / 도전](#coding-exerciseschallenges)
- [인터뷰가 얼마 남지 않았을 때](#once-youre-closer-to-the-interview)
- [이력서](#your-resume)
- [Be thinking of for when the interview comes](#be-thinking-of-for-when-the-interview-comes)
- [Have questions for the interviewer](#have-questions-for-the-interviewer)
- [직업을 갖게 되었을 때](#once-youve-got-the-job)

---------------- Everything below this point is optional ----------------

- [추가 도서](#additional-books)
- [추가 주제](#additional-learning)
    - [컴파일러](#compilers)
    - [부동 소수점 수](#floating-point-numbers)
    - [유니코드](#unicode)
    - [엔디언](#endianness)
    - [Emacs 와 vi(m)](#emacs-and-vim)
    - [유닉스 명령어 도구](#unix-command-line-tools)
    - [정보 이론](#information-theory)
    - [패리티 & 해밍코드](#parity--hamming-code)
    - [엔트로피](#entropy)
    - [암호기법](#cryptography)
    - [압축](#compression)
    - [네트워크](#networking) (if you have networking experience or want to be a systems engineer, expect questions)
    - [컴퓨터 보안](#computer-security)
    - [가비지 콜렉션](#garbage-collection)
    - [병렬 프로그래밍](#parallel-programming)
    - [메세징, 직렬화, 그리고 큐잉 시스템](#messaging-serialization-and-queueing-systems)
    - [고속 푸리에 변환(FFT)](#fast-fourier-transform)
    - [블룸 필터](#bloom-filter)
    - [HyperLogLog](#hyperloglog)
    - [Locality-Sensitive Hashing](#locality-sensitive-hashing)
    - [van Emde Boas 트리](#van-emde-boas-trees)
    - [Augmented Data Structures](#augmented-data-structures)
    - [트라이(Tries)](#tries)
    - [N-ary (K-ary, M-ary) trees](#n-ary-k-ary-m-ary-trees)
    - [균형 탐색 트리](#balanced-search-trees)
        - AVL 트리
        - Splay 트리
        - 레드블랙 트리(RBT)
        - 2-3 탐색 트리
        - 2-3-4 트리(aka 2-4 트리)
        - N-ary (K-ary, M-ary) 트리
        - B-트리
    - [k-D 트리](#k-d-trees)
    - [스킵 리스트](#skip-lists)
    - [네트워크 플로우(유량)](#network-flows)
    - [분리집합 & 유니온 파인드(Disjoint Sets & Union Find)](#disjoint-sets--union-find)
    - [빠른 프로세싱을 위한 수학](#math-for-fast-processing)
    - [트립](#treap)
    - [선형 계획법](#linear-programming)
    - [기하학, 볼록 껍질](#geometry-convex-hull)
    - [이산수학](#discrete-math)
    - [기계학습](#machine-learning)
    - [Go](#go)
- [몇몇 주제에 대한 세부사항](#additional-detail-on-some-subjects)
- [영상 자료](#video-series)
- [컴퓨터 과학 강좌](#computer-science-courses)

---

## Why use it?

나는 구글 인터뷰를 준비하기 위해 이 계획을 따랐다. 1997년 부터 나는 웹과 서비스를 개발하고 스타트업을 세웠다. 나는 컴퓨터과학이 아닌 경제학 학위를 가지고 있다.
나의 커리어는 굉장히 성공적이어왔지만, 나는 구글에서 일하고 싶었다. 나는 더 큰 시스템을 다루고 컴퓨터 시스템, 알고리즘 효율, 자료구조 퍼포먼스, 저급 언어 등과 그 것들이 어떻게 작동하는지에 대하여
이해하고 싶었다. 그리고 당신이 그런 것들을 모른다면 구글은 당신을 채용하지 않을 것이다.

내가 이 프로젝트를 시작했을 때, 나는 힙스택, Big-O, 트리, 그래프 운행 등에 대하여 전혀 아는 바가 없었다.
만약 내가 정렬 알고리즘을 코딩해야했다면, 나는 그리 잘 하지 못했을 것이다.
모든 사용했던 모든 자료 구조는 언어 안에서 구현 되어 있던 것들이고, 나는 그 것들이 보이는 것 아래서 어떻게 작동하고 있는지 알지 못했다.
나는 진행 중인 프로세스가 메모리 부족 에러를 메세지를 보내지 않는 한 메모리를 관리할 필요가 없었고, 나는 회피방법을 찾아야만 했다.
나는 몇몇 다차원 배열이나 연관 배열을 사용해왔지만, 자료구조를 처음부터 구현해본 적은 없었다.

하지만 이 공부 계획을 진행하면서 나는 내가 고용될 것이라는 자신감을 갖게 되었다. 이 것은 내게 여러 달이 필요한 긴 계획이다.
만약 당신이 이 중 많은 내용에 익숙하다면 시간은 훨씬 덜 들 것이다.

## How to use it

아래의 모든 것은 대략적인 개요이며 당신은 위에서 아래 순서대로 진행해야 한다.

진행상황을 확인하기 위한 목록를 포함하여, 나는 Github'special markdown flavor를 사용하고 있다.

**새 브랜치를 만들어서 중괄호에 x표를 넣는 식으로 항목을 체크하라: [x]**

	브랜치를 포크하고 아래의 명령을 따라라

`git checkout -b progress`

`git remote add jwasham https://github.com/jwasham/coding-interview-university`

`git fetch --all`

    끝났으면 박스에 x로 체크하라

`git add . `

`git commit -m "Marked x" `

`git rebase jwasham/master `

`git push --force `

[Github-flavored markdown에 대하여](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

## 구글 분위기 내기

"[미래의 구글러](https://github.com/jwasham/coding-interview-university/blob/master/extras/future-googler.pdf)"를 인쇄하고
자주 바라보자.

[![future Googler sign](https://dng5l3qzreal6.cloudfront.net/2016/Oct/Screen_Shot_2016_10_04_at_10_13_24_AM-1475601104364.png)](https://github.com/jwasham/coding-interview-university/blob/master/extras/future-googler.pdf)

## Did I Get the Job?

I'm in the queue right now. Hope to interview soon.

    Thanks for the referral, JP.

## 팔로우 하려면

나의 이야기: [내가 구글 인터뷰를 풀 타임으로 8 개월 동안 공부한 이유](https://www.vobour.com/book/view/fiRGQMcmRkaw7pgpL) (원문 : [Why I Studied Full-Time for 8 Months for a Google Interview](https://medium.com/@googleyasheck/why-i-studied-full-time-for-8-months-for-a-google-interview-cc662ce9bb13))


저의 구글로 향하는 여행 함께 해주세요!
- **블로그**: [GoogleyAsHeck.com](https://googleyasheck.com/)
- Twitter: [@googleyasheck](https://twitter.com/googleyasheck)
- Twitter: [@StartupNextDoor](https://twitter.com/StartupNextDoor)
- Google+: [+Googleyasheck](https://plus.google.com/+Googleyasheck)
- LinkedIn: [johnawasham](https://www.linkedin.com/in/johnawasham)

![John Washam - Coding Interview University](https://dng5l3qzreal6.cloudfront.net/2016/Aug/book_stack_photo_resized_18_1469302751157-1472661280368.png)


## 당신은 충분히 똑똑합니다
- 구글 엔지니어들은 똑똑합니다. 하지만 그들 조차도 자신들의 지적 능력면에 대해서 불안감을 갖기 일쑤입니다.
- [천재 프로그래머에 대한 미신(迷信)](https://www.youtube.com/watch?v=0SARbwvhupQ)
- [위험한 홀로서기: 테크 산업의 보이지 않는 괴물들의 전쟁](https://www.youtube.com/watch?v=1i8ylq4j_EY)

## 구글에 대해

- [ ] 학생들을 위한 자료 - [구글 채용 정보: 기술 개발 가이드](https://www.google.com/about/careers/students/guide-to-technical-development.html)
- [ ] 검색 동작 원리:
    - [ ] [검색의 진화 - 동영상](https://www.youtube.com/watch?v=mTBShTwCnD4)
    - [ ] [검색 동작 원리 - 스토리](https://www.google.com/insidesearch/howsearchworks/thestory/)
    - [ ] [검색 동작 원리](https://www.google.com/insidesearch/howsearchworks/)
    - [ ] [검색 동작 원리 - 맷 커츠(Matt Cutts) - 동영상](https://www.youtube.com/watch?v=BNHR6IQJGZs)
    - [ ] [구글의 검색 알고리즘 개선 방법 - 동영상](https://www.youtube.com/watch?v=J5RZOU6vK4Q)
- [ ] 시리즈:
    - [ ] [구글 검색이 모바일을 처리하는 방법](https://backchannel.com/how-google-search-dealt-with-mobile-33bc09852dc9)
    - [ ] [우리의 니즈를 발견하기 위한 구글의 비밀 연구](https://backchannel.com/googles-secret-study-to-find-out-our-needs-eba8700263bf)
    - [ ] [구글 검색은 당신의 두뇌가 된다](https://backchannel.com/google-search-will-be-your-next-brain-5207c26e4523)
    - [ ] [데미스 허사비스(Demis Hassabis)의 딥마인드](https://backchannel.com/the-deep-mind-of-demis-hassabis-156112890d8a)
- [ ] [책: 구글은 어떻게 일하는가](https://www.amazon.com/How-Google-Works-Eric-Schmidt/dp/1455582344)
- [ ] [구글 발표자료 - 2016.10 - 동영상](https://www.youtube.com/watch?v=q4y0KOeXViI)

## 비디오 자료


## 영상 자료에 관하여

몇몇 영상들은 Cousera, Edx, Lynda.com 클래스에 등록하여야만 시청이 가능합니다. 이것들은 MOOCs라고 불리는데요.
강의가 없는 경우에는 몇 달 동안 기다려야 할 수도 있습니다. Lynda.com 강좌들은 무료가 아닙니다.

    여러분이 YouTube 온라인 강의 동영상과 같이 무료이고 항상 접근 가능한 동영상 소스들을 추가해주면 정말 감사하겠습니다.
    저는 대학 강의 듣는 것을 좋아합니다.

## 인터뷰 과정 & 전반적인 인터뷰 준비 과정

- [ ] 비디오:

    - [ ] [구글에서 일하게 되는법: 기술 인터뷰 준비하기 (video)](https://www.youtube.com/watch?v=ko-KkSmp-Lk)
    - [ ] [구글에서 일하게 되는법: 코딩/기술 인터뷰 예시 (video)](https://www.youtube.com/watch?v=XKu_SEDAykw)
    - [ ] [구글에서 일하게 되는법 - 지원자 코칭 시간 (video)](https://www.youtube.com/watch?v=oWbUtlUhwa8&feature=youtu.be)
    - [ ] [구글 리크루터들이 공유한 기술 인터뷰 팁들 (video)](https://www.youtube.com/watch?v=qc1owf2-220&feature=youtu.be)
    - [ ] [구글에서 일하게 되는법: 기술 레쥬메 준비 (video)](https://www.youtube.com/watch?v=8npJLXkcmu8)

- [ ] 읽을 거리들:

    - [ ] [구글러 되기 3단계](http://www.google.com/about/careers/lifeatgoogle/hiringprocess/)
    - [ ] [구글에서 그 직업 갖기](http://steve-yegge.blogspot.com/2008/03/get-that-job-at-google.html)
      - 이 글에서 저자가 언급한 당신이 알아야 할 모든 것들은 이 리스트 아래에 소개되어 있습니다.
    - [ ] _(아주 오래됨)_ [구글에 취업하는 방법, 인터뷰 질문들, 채용 절차](http://dondodge.typepad.com/the_next_big_thing/2010/09/how-to-get-a-job-at-google-interview-questions-hiring-process.html)
    - [ ] [화상통화 인터뷰 질문들](http://sites.google.com/site/steveyegge2/five-essential-phone-screen-questions)


- [ ] 준비 코스:
    - [ ] [소프트웨어 엔지니어 인터뷰 대공개 (유료 강좌)](https://www.udemy.com/software-engineer-interview-unleashed):
        - 전직 구글 엔지니어로부터 당신이 어떻게 소프트웨어 엔지니어 인터뷰를 준비해야 하는지 배우게 됩니다.

- [ ] 부가물 (구글이 추천하지않은 내가 더한 것들):
    - [ ] [ABC: 항상 코딩 하라](https://medium.com/always-be-coding/abc-always-be-coding-d5f8051afce2#.4heg8zvm4)
    - [ ] [학위 없이 구글에 들어가기 4단계](https://medium.com/always-be-coding/four-steps-to-google-without-a-degree-8f381aa6bd5e#.asalo1vfx)
    - [ ] [화이트 보드 쓰기](https://medium.com/@dpup/whiteboarding-4df873dbba2e#.hf6jn45g1)
    - [ ] [채용, 관리, 문화에 대한 구글의 생각](http://www.kpcb.com/blog/lessons-learned-how-google-thinks-about-hiring-management-and-culture)
    - [ ] [코딩 인터뷰에서 화이트 보드 효율적으로 쓰기](http://www.coderust.com/blog/2014/04/10/effective-whiteboarding-during-programming-interviews/)
    - [ ] 코딩 인터뷰 정복 Set 1:
      - [ ] [Gayle L McDowell - 코딩 인터뷰 정복 (영상)](https://www.youtube.com/watch?v=rEJzOhC5ZtQ)
      - [ ] [저자와 함께하는 코딩 인터뷰 정복 (영상)](https://www.youtube.com/watch?v=aClxtDcdpsQ)
    - [ ] Big 4에 취업하는 방법:
      - [ ] ['Big 4에 취업하는 방법 - Amazon, Facebook, Google & Microsoft' (영상)](https://www.youtube.com/watch?v=YJZCUhxNCv8)
    - [ ] [구글 인터뷰 실패기](http://alexbowe.com/failing-at-google-interviews/)


## 인터뷰를 위한 언어 고르기

인터뷰때 사용할 언어 고르는 법에 대해 짧은 글을 하나 썼습니다: [구글 인터뷰를 위한 언어 고르기](https://googleyasheck.com/important-pick-one-language-for-the-google-interview/)

인터뷰때에 당신이 쓰기에 편한 언어를 선택해도 되지만, 구글 인터뷰에 선호되는 언어들은 다음과 같습니다.


- C++
- Java
- Python


아래 언어들을 사용할 수 있지만 주의하여야 합니다.


- JavaScript
- Ruby


당신은 당신의 언어에 익숙하고 그 언어에 대해 잘 알아야 합니다.

언어 선택을 도와줄 만한 읽을 거리들

- http://www.byte-by-byte.com/choose-the-right-language-for-your-coding-interview/
- http://blog.codingforinterviews.com/best-programming-language-jobs/
- https://www.quora.com/What-is-the-best-language-to-program-in-for-an-in-person-Google-interview


[프로그래밍 언어 참고목록](programming-language-resources.md)

제가 공부하고 있는 C, C++, Python 강의를 아래서 볼 수 있습니다. 아래를 보시면 관련된 책들이 몇 개 있습니다.


## 도서 목록

아래의 목록은 내가 공부했던 책들보다는 적다. 당신의 시간을 절약하기 위해 몇몇 책들은 생략하였다.


### 인터뷰 준비를 위해서

- [ ] [Programming Interviews Exposed: Secrets to Landing Your Next Job, 2nd Edition](http://www.wiley.com/WileyCDA/WileyTitle/productCd-047012167X.html)
    - C++ 과 JAVA 문제의 답변을 위해서
    - 구글 지원자를 위해 추천되었기 때문에
    - Cracking the Coding Interview 책을 위한 좋은 사전학습용 책이기 때문에
    - 어렵지 않고, 당신이 인터뷰에서 마주할 대부분의 문제들 보다 쉽기 때문에
- [ ] [Cracking the Coding Interview, 6th Edition](http://www.amazon.com/Cracking-Coding-Interview-6th-Programming/dp/0984782850/)
    - JAVA 문제의 답변을 위해서
    - Google Careers site에서 추천되었기 때문에 [Google Careers site](https://www.google.com/about/careers/how-we-hire/interview/)
    - 만일 당신이 다른 사람들의 "The Google Resume"를 참고자료로 봤다면, "Cracking the Coding Interview"는 그것을 대신할 수 있는 책이다.


만일 당신이 많은 여유 시간이 있다면:

- [ ] [Elements of Programming Interviews](https://www.amazon.com/Elements-Programming-Interviews-Insiders-Guide/dp/1479274836)
    - 모든 코드가 C++로 되어있다, 만일 당신의 인터뷰에서 C++를 사용하길 고려한다면 정말 좋은 책이다.
    - 일반적인 문제들을 해결하기 위해 좋은 책이다.


### 컴퓨터 구조

준비기간이 짧을 때,

- [ ] [Write Great Code: Volume 1: Understanding the Machine](https://www.amazon.com/Write-Great-Code-Understanding-Machine/dp/1593270038)
    - 이 책은 2004년에 출판된 다소 구식의 책이지만, 간략히 컴퓨터를 이해하는 데에 훌륭한 자료입니다.
    - 이 책의 저자는 HLA를 발명했습니다. 그래서 회의적인 시선으로 HLA에 대해 언급하고 예로 듭니다. 널리 읽히지는 않지만, 어셈블리가 어떻게 생겼는 지를 보여주는 좋은 예입니다.
    - 이 장들은 당신에게 탄탄한 기초를 세워줄 것입니다:
        - Chapter 2 - Numeric Representation
        - Chapter 3 - Binary Arithmetic and Bit Operations
        - Chapter 4 - Floating-Point Representation
        - Chapter 5 - Character Representation
        - Chapter 6 - Memory Organization and Access
        - Chapter 7 - Composite Data Types and Memory Objects
        - Chapter 9 - CPU Architecture
        - Chapter 10 - Instruction Set Architecture
        - Chapter 11 - Memory Architecture and Organization

만약에 시간적 여유가 좀 더 있다면 아래 서적을 읽어보는 것을 권유합니다.
- [ ] [Computer Architecture, Fifth Edition: A Quantitative Approach](https://www.amazon.com/dp/012383872X/)
    - For a richer, more up-to-date (2011), but longer treatment

### 언어 구체적

**인터뷰를 위해 당신의 언어를 선택하여야 합니다 (윗글 참조)** 아래는 제가 추천하는 언어들입니다. 이 언어들중에 부연설명이나 부가 자료들이 있다면 나눠 주세요.

이 중 하나를 읽으려면 코딩 문제 푸는 데 필요한 데이터 구조 및 알고리즘 지식이 있어야합니다.

**You can skip all the video lectures in this project**, unless you'd like a review.

[Additional language-specific resources here.](programming-language-resources.md)

### C++

나는 아래의 두 책들을 읽지 않았습니다. 하지만 Sedgewick이 높게 평가한 책들입니다. 그는 정말 대단한 사람입니다.


- [ ] [Algorithms in C++, Parts 1-4: Fundamentals, Data Structure, Sorting, Searching](https://www.amazon.com/Algorithms-Parts-1-4-Fundamentals-Structure/dp/0201350882/)
- [ ] [Algorithms in C++ Part 5: Graph Algorithms](https://www.amazon.com/Algorithms-Part-Graph-3rd-Pt-5/dp/0201361183/)

C++에 대한 더 나은 추천 책이 있다면 알려주십시오. 포괄적인 자료를 찾고 있습니다.

### Java

- [ ] [Algorithms (Sedgewick and Wayne)](https://www.amazon.com/Algorithms-4th-Robert-Sedgewick/dp/032157351X/)
    - videos with book content (and Sedgewick!):
        - [Algorithms I](https://www.youtube.com/user/algorithmscourses/playlists?view=50&sort=dd&shelf_id=2)
        - [Algorithms II](https://www.youtube.com/user/algorithmscourses/playlists?shelf_id=3&view=50&sort=dd)

OR:

- [ ] [Data Structures and Algorithms in Java](https://www.amazon.com/Data-Structures-Algorithms-Michael-Goodrich/dp/1118771338/)
    - by Goodrich, Tamassia, Goldwasser
    - UC버클리 대학의  CS입문 과정의 선택 텍스트로 사용됨
    - 아래에서 Python 버전에 대한 나의 책 보고서를 참조하십시오. 이 책은 동일한 주제를 다루고 있습니다.

### Python

- [ ] [Data Structures and Algorithms in Python](https://www.amazon.com/Structures-Algorithms-Python-Michael-Goodrich/dp/1118290275/)
    - by Goodrich, Tamassia, Goldwasser
    - 나는 이 책을 사랑한다. 이 책은 모든 것을 다룬다.
    - Pythonic code
    - 나의 열렬한 서적 보고서: https://googleyasheck.com/book-report-data-structures-and-algorithms-in-python/


### 선택 도서

**어떤 사람들은 이 책들을 추천한다. 하지만 만약 당신이 소프트웨어 엔지니어링 분야에 오랜 경험이 있고, 그로 인해 훨씬 더 어려운 인터뷰를 볼 것이라 생각하지 않는다면, 나는 이 책들을 공부하는 것이 너무 과하다고 생각한다:**

- [ ] [Algorithm Design Manual](http://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1849967202) (Skiena)
    - 복습과 문제인식 용
    - 알고리즘 카탈로그 부분은 당신이 면접에서 마주하게 될 난이도 이상을 다룬다.
    - 이 책은 2 파트로 구성되어 있다.:
        - 자료구조 및 알고리즘에 대한 강의 교재
            - 장점:
                - 어떠한 알고리즘 교과서라도 복습하는 데에는 도움이 된다.
                - 산업과 학술 분야에서 저자가 문제를 했던 경험들은 좋은 이야깃거리이다.
                - C 언어로 된 코드 예제들.
            - 단점:
                - CLRS 만큼이나 dens 하거나 impentrable 할 수 있으며, 몇 몇 주제에 대해서는 CLRS가 더 나은 대안이 될지도 모른다.
                - 몇 가지 항목들은 잘 설명돼있지 않거나 내 수준보다 높은 수준을 요구하기 때문에, 챕터 7, 8, 9는 따라 하기 힘들 수 있다.
                - (오해 없길 바란다) 나는 Skiena의 교육 방식, 방법론 들을 좋아하지만, Stony Brook의 것들은 회의적이다.
        - 알고리즘 카탈로그:
            - 이 부분이 당신이 이 책을 사야하는 진짜 이유이다.
            - 이 부분을 거의 다 읽었다. 이 부분은 책을 다 읽어본 후에 업데이트 할 것이다.
    - Yegge를 인용하자면, "그래프 문제가 얼마나 astonishingly 일반 상식인지 이해하는 데 어떤 책 보다도 도움이 되었다(그래프 문제는 모든 현업 프로그래머의 툴킷에 들어가야 한다.) 또한 이 책은 기초적인 자료 구조와 정렬 알고리즘들을 다룬다. 하지만 진짜 꿀은 zillions 유용한 문제에 대한 일종의 1-pagers의 백과사전같은(지나치게 자세하지도 않다) 책의 뒤쪽 절반이다. 거의 대부분의 1-pager는 기억하기 쉽게 해주는 간단한 사진이 있다. 이것은 수 백가지 문제들의 유형을 어떻게 식별할 수 있는지 배우기 위한 좋은 방법이다."
    - 킨들에서 읽을 수 있다.
    - Half.com 은 괜찮은 가격에 교과서를 마련할 수 있는 좋은 사이트이다.
    - 해설지:
        - [Solutions](http://www.algorithm.cs.sunysb.edu/algowiki/index.php/The_Algorithms_Design_Manual_(Second_Edition))
        - [Solutions](http://blog.panictank.net/category/algorithmndesignmanualsolutions/page/2/)
    - [Errata](http://www3.cs.stonybrook.edu/~skiena/algorist/book/errata)

- [ ] [Introduction to Algorithms](https://www.amazon.com/Introduction-Algorithms-3rd-MIT-Press/dp/0262033844)
    - **중요:** 이 책을 읽는 것은 썩 효율적이지 않다. 이 책은 알고리즘과 자료구조를 복습하는 데에는 좋지만, 좋은 코드를 작성하는 것에 대해서는 가르쳐주지 않는다. 당신은 decent 솔루션의 코드를 효율적으로 작성할 수 있어야 한다.
    - Yegge를 인용하자면, "하지만 당신의 면접이 *prepped*하길 원한다면, 이 책을 다 읽기 전 까지는 당신의 어플리케이션을 deffering 하는 것을 고려하라."
    - Half.com 은 괜찮은 가격에 교과서를 마련할 수 있는 좋은 사이트이다.
    - CLR로도, CLRS로도 알려져 있다. (Stein이 너무 늙었기 때문에.)

- [ ] [Programming Pearls](http://www.amazon.com/Programming-Pearls-2nd-Jon-Bentley/dp/0201657880)
    - 처음 몇 챕터는 프로그래밍 문제(어떤 문제는 매우 오래됐다)에 대한 영리한 해결책을 제시하지만 도입부일 뿐이다. 이 책은 Code Complte와 같은 프로그램 디자인과 구조에 대한 가이드북이지만 훨씬 짧다.

- ~~"Algorithms and Programming: Problems and Solutions" by Shen~~

    - 괜찮은 책이지만, 몇 가지 문제를 풀어보고 난 뒤 Pascal의 do while 루프들, 1-indexed 배열, 명확하지 않은 post-condition satisfaction 결과에 완전히 좌절했다.

    - 차라리 다른 책이나 온라인 코딩 문제에 시간을 쏟는 편이 나을 수도 있다.


## 시작하기 전에

이 문서는 몇 달간 계속 업데이트 되고 있으며, 그런 이유로, 내가 감당할 수 없어지기 시작한 듯하다.

내가 저지른 몇 가지 실수들을 소개한다. 이를 통해 당신은 이 과정을 좀 더 효과적으로 진행할 수 있기를 바란다.

### 1. 당신은 이것을 다 기억하지 못할 것이다.

나는 수 시간의 비디오를 보고 방대한 양의 노트를 작성했지만, 몇 달 뒤에는 대부분의 내용을 기억하지 못했다. 나는 3일 동안 내가 작성한 노트를 보고 flashcard를 만들면서 내용들을 다시 검토해야 했다.

꼭 읽고 내가 한 실수들을 반복하지 않길 바란다.

[Retaining Computer Science Knowledge](https://googleyasheck.com/retaining-computer-science-knowledge/)

### 2. Flashcard를 사용하자.

이 문제를 해결하기 위해 나는 2가지 종류(일반적인 내용, 코드)의 flashcard를 보관하고 추가할 수 있는 작은 사이트를 만들었다. 각 카드는 다른 서식을 가지고 있다.

이 사이트는 모바일에 최적화 되어있기 때문에 내 전화기나 태블릿 어디에서든 이를 확인할 수 있다.

당신만의 카드를 만들어보자(무료로):

- [Flashcard 사이트 repo](https://github.com/jwasham/computer-science-flash-cards)
- [내 flashcard 데이터베이스 (old - 1200 cards)](https://github.com/jwasham/computer-science-flash-cards/blob/master/cards-jwasham.db):
- [내 flashcard 데이터베이스 (new - 1800 cards)](https://github.com/jwasham/computer-science-flash-cards/blob/master/cards-jwasham-extreme.db):

앞에서도 언급했듯이 나는 불필요하게 많은 것을 공부하려고 했고, 내 카드의 내용들은 어셈블리 언어와 Python의 자잘한 지식들부터 기계 학습과 통계학까지 넘나들게 되었다. 결국 구글이 요구하는 것보다 훨씬 멀리 가버리고 말았다.

**flashcard에 대한 참고사항:** 답을 할 수 있더라도 처음부터 안다고 표시하지 말자. 정확히 알기 전까지는 같은 카드를 보고 여러 번 답변할 수 있어야한다.
반복 학습을 통해 해당 지식은 당신의 뇌에 깊이 각인될 것이다.



나의 flashcard site를 사용하는 대신 [Anki](http://ankisrs.net/)를 사용해도 된다. 나는 이 것을 여러 번 추천받았다. 이것은 당신이 기억하는 것을 돕기 위해 반복적인 시스템을 사용한다.

이것은 사용자 친화적이며, 모든 플랫폼에서 사용가능하다. 또한 클라우드 동기화 시스템을 제공한다. 이것은 iOS에서는 $25이지만 다른 플랫폼에서는 무료로 사용 가능하다.

Anki format의 내 flashcard 데이터베이스: https://ankiweb.net/shared/info/25173560 (thanks [@xiewenya](https://github.com/xiewenya))

### 3. 검토, 검토, 검토

나는 ASCII, OSI 구조, Big-O 표기법 등에 관한 일련의 치트시트를 만들어 놓고, 여유 시간이 날 때마다  공부한다.

30분 동안 프로그래밍 문제를 해결하고, flashcard를 살펴보자.

### 4. 집중

주의를 산만하게 만드는 많은 것이 있으며, 이것들은 우리의 귀중한 시간을 뺏어간다. 주의를 집중하는 것은 힘든 일이다.

## 다루지 않을 것

이 큰 주제들은 모두 Google 인터뷰 코칭 노트에서 개인적인 to-do list로 시작되었다.
이 기술들은 널리 퍼져 있는 기술이지만, Google 인터뷰 코칭 노트에서 언급 되지 않았다:

- SQL
- Javascript
- HTML, CSS, 그리고 다른 프론트엔드 기술들


## 하루 하루의 계획

어떤 주제들은 하루가 걸리고, 어떤 것들은 며칠이 걸릴 것이다.
또 어떤것은 구현할 것들이 없이 그냥 배우는 것들이다.

아래 리스트에 있는 것에서 매일 하나의 주제를 택했고, 그 주제에 대한 강의를 보고, 구현을 했다:
- C - 인자를 가지는 구조체와 함수 사용
- C++ - 빌트인 타입 사용하지 않음
- C++ - 링크리스트를 위한 STL's std::list 같은 빌트인 타입 사용
- Python - 빌트인 타입 사용 (파이선 연습을 계속 하려고)
- 제대로 하고 있는지 테스트를 했고 가끔은 간단한 assert() 사용
- 당신은 아마 자바나 그 어떤 언어를 이용하겠지만 이것은 그냥 내 것들이다.

당신은 이것을 다 할 필요는 없다. 단지 [인터뷰를 위한 하나의 언어를 할 것.](#인터뷰를 위한 언어를 하나 골라 두어라).

왜 이 모든것을 코딩해야 하는가?
- 나는 이것에 미칠때까지 연습하고 또 연습했고, 아무런 문제 없이 할 수 있게 되었다 (어떤 것들은 다양한 케이스가 있고 이것을 기억하기 위해 기록을 보관했다.)
- 있는 그대로의 제한 속에서 연습 (garbage collection의 도움없이 메모리 할당과 해지 (파이선 빼고))
- 빌트인 타입을 사용하여 나는 빌트인 도구에 대한 경험이 있게 되었다. (내 프로젝트의 링크 리스트 구현은 쓰지 않을 예정)

모든 주제에 대한 모든 것을 할 수 없지만 나는 노력했다.

나의 코드를 여기서 확인하세요:

 - [C] (https://github.com/jwasham/practice-c)
 - [C++] (https://github.com/jwasham/practice-cpp)
 - [Python] (https://github.com/jwasham/practice-python)


당신은 모든 알고리즘에 대해서 기억할 필요는 없다.

컴퓨터에 코딩하지 말고 와이트보드나 종이에 적어보아라. 인풋 값으로 샘플 테스트를 해 보아라. 그리고 컴퓨터로 테스트해 보아라.

## 선수 과목

- [ ] **Learn C**
    - C 는 어디에나 있다. 당신은 책이나 강의, 비디오 등 공부하는 동안 모든 곳에서 예제를 볼 것이다.
    - [ ] [C Programming Language, Vol 2](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628)
        - 이 책은 분량이 적은 책이지만 C 를 잘 다룰 수 있게 해 줄 것이다. 또한 조금만 연습하더라도 연습량에 비해 빠르게 배울 수 있을 것이다. C 를 이해하는 것은 프로그램과 메모리가 어떻게 돌아가는지 이해하는 것을 도와준다.
        - [answers to questions](https://github.com/lekkas/c-algorithms)


- [ ] **How computers process a program:**
    - [ ] [How does CPU execute program (video)](https://www.youtube.com/watch?v=42KTvGYQYnA)
    - [ ] [Machine Code Instructions (video)](https://www.youtube.com/watch?v=Mv2XQgpbTNE)

## 알고리즘 복잡도 / Big-O / 점근적 분석
- nothing to implement
- [ ] [Harvard CS50 - Asymptotic Notation (video)](https://www.youtube.com/watch?v=iOq5kSKqeR4)
- [ ] [Big O Notations (general quick tutorial) (video)](https://www.youtube.com/watch?v=V6mKVRU1evU)
- [ ] [Big O Notation (and Omega and Theta) - best mathematical explanation (video)](https://www.youtube.com/watch?v=ei-A_wy5Yxw&index=2&list=PL1BaGV1cIH4UhkL8a9bJGG356covJ76qN)
- [ ] Skiena:
    - [video](https://www.youtube.com/watch?v=gSyDMtdPNpU&index=2&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
    - [slides](http://www3.cs.stonybrook.edu/~algorith/video-lectures/2007/lecture2.pdf)
- [ ] [A Gentle Introduction to Algorithm Complexity Analysis](http://discrete.gr/complexity/)
- [ ] [Orders of Growth (video)](https://class.coursera.org/algorithmicthink1-004/lecture/59)
- [ ] [Asymptotics (video)](https://class.coursera.org/algorithmicthink1-004/lecture/61)
- [ ] [UC Berkeley Big O (video)](https://youtu.be/VIS4YDpuP98)
- [ ] [UC Berkeley Big Omega (video)](https://youtu.be/ca3e7UVmeUc)
- [ ] [Amortized Analysis (video)](https://www.youtube.com/watch?v=B3SpQZaAZP4&index=10&list=PL1BaGV1cIH4UhkL8a9bJGG356covJ76qN)
- [ ] [Illustrating "Big O" (video)](https://class.coursera.org/algorithmicthink1-004/lecture/63)
- [ ] TopCoder (includes recurrence relations and master theorem):
    - [Computational Complexity: Section 1](https://www.topcoder.com/community/data-science/data-science-tutorials/computational-complexity-section-1/)
    - [Computational Complexity: Section 2](https://www.topcoder.com/community/data-science/data-science-tutorials/computational-complexity-section-2/)
- [ ] [Cheat sheet](http://bigocheatsheet.com/)


    만약 일부 강의가 깊은 수학적 지식을 요구한다면, 배경지식을 얻기 위해 아래에 있는 개별적인 수학에 대한 비디오를 먼저 보라.
## 자료구조

- ### 배열
    - 자동 리사이징 벡터 구현하기
    - [ ] 설명:
        - [배열 (영상)](https://www.coursera.org/learn/data-structures/lecture/OsBSF/arrays)
        - [UCBerkley CS61B - 선형과 다차원 배열 (영상)](https://youtu.be/Wp8oiO_CZZE?t=15m32s)
        - [배열 기본 (영상)](https://archive.org/details/0102WhatYouShouldKnow/02_04-basicArrays.mp4)
        - [다차원 배열 (영상)](https://archive.org/details/0102WhatYouShouldKnow/02_05-multidimensionalArrays.mp4)
        - [동적 배열 (영상)](https://www.coursera.org/learn/data-structures/lecture/EwbnV/dynamic-arrays)
        - [가변 배열 (영상)](https://www.youtube.com/watch?v=1jtrQqYpt7g)
        - [가변 배열 (영상)](https://archive.org/details/0102WhatYouShouldKnow/02_06-jaggedArrays.mp4)
        - [배열 리사이징 (영상)](https://archive.org/details/0102WhatYouShouldKnow/03_01-resizableArrays.mp4)
    - [ ] 벡터 구현하기 (자동 리사이징을 포함한 동적 배열):
        - [ ] 배열, 포인터 및 인덱싱 대신하여 특정 인덱스에 접근하는 포인터 연산을 통한 코딩 연습
        - [ ] 메모리 할당을 포함한 새 배열
            - 배열 메소드 등의 기능을 활용하지 않으면서 정수 배열에 메모리를 할당할 수 있어야 함
            - 16으로 시작하거나 시작하는 숫자가 크다면 2의 제곱수(16, 32, 64, 128)로 시작
        - [ ] size() - 항목의 개수
        - [ ] capacity() - 들어갈 수 있는 항목의 최대 개수
        - [ ] is_empty()
        - [ ] at(index) - 인덱스에 있는 항목을 돌려주고, 인덱스가 범위 밖이면 에러를 냄
        - [ ] push(item)
        - [ ] insert(index, item) - index에 item을 삽입하고 기존 인덱스의 값부터 쭉 오른쪽으로 쉬프트
        - [ ] prepend(item) - 맨 앞에 원소를 삽입
        - [ ] pop() - 마지막 원소를 삭제하고 값을 돌려준다
        - [ ] delete(index) - 인덱스에 있는 항목을 삭제하고, 이어지는 모든 요소를 왼쪽으로 한 칸씩 당긴다.
        - [ ] remove(item) - 값을 찾아서 해당 값에 할당된 인덱스를 제거한다. (같은 값이 여러 곳에 있어도 모두 제거한다.)
        - [ ] find(item) - 값을 찾아서 해당 값에 할당된 인덱스 중 첫 번째 것을 반환하며, 찾지 못할 경우 -1을 반환한다.
        - [ ] resize(new_capacity) // private 함수
            - 배열이 다 찼을 경우, 크기를 두 배로 늘린다.
            - 항목이 삭제될 때, 남은 크기가 전체 크기의 1/4일 경우 전체 크기를 절반으로 줄인다.
    - [ ] Time
        - 맨 뒤에 추가/제거 하거나, 값에 접근하거나, 수정하는 것 모두 O(1) 의 시간이 걸린다. (추가 공간을 할당하는 작업은 여러 번에 걸쳐 수행된다.)
        - 다른 장소에 삽입/제거 하는 경우 O(n) 의 시간이 걸린다.
    - [ ] Space
        - 메모리 상에 연속적으로 저장돼있으며, 이러한 근접성이 성능을 향상시킨다.
        - space needed = (array capacity, which is >= n) * size of item, but even if 2n, still O(n)

- ### 링크드 리스트
    - [ ] 설명:
        - [ ] [Singly Linked Lists (video)](https://www.coursera.org/learn/data-structures/lecture/kHhgK/singly-linked-lists)
        - [ ] [CS 61B - Linked Lists (video)](https://www.youtube.com/watch?v=sJtJOtXCW_M&list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd&index=5)
    - [ ] [C Code (video)](https://www.youtube.com/watch?v=QN6FPiD0Gzo)
            - 노드 구조와 메모리 할당에 대한 부분만 유용하다.
    - [ ] 링크드 리스트 vs 배열:
        - [Core Linked Lists Vs Arrays (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/rjBs9/core-linked-lists-vs-arrays)
        - [In The Real World Linked Lists Vs Arrays (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/QUaUd/in-the-real-world-lists-vs-arrays)
    - [ ] [why you should avoid linked lists (video)](https://www.youtube.com/watch?v=YQs6IC-vgmo)
    - [ ] 잡았다! 당신은 이제 포인터의 포인터에 대한 지식이 필요하다.
        (포인터가 함수를 통과할 때 포인터가 가리키는 주소가 변할 수 있기 때문.)
        이 페이지는 포인터의 포인터 개념을 확실히 하기 위한 것이다. I don't recommend this list traversal style. Readability and maintainability suffer due to cleverness.
        - [Pointers to Pointers](https://www.eskimo.com/~scs/cclass/int/sx8.html)
    - [ ] 구현 (나는 tail 포인터가 있는 버전과 없는 버전 모두 구현했다.):
        - [ ] size() - 리스트 안의 데이터 개수를 반환한다.
        - [ ] empty() - 리스트가 비었을 때 참 값을 반환한다.
        - [ ] value_at(index) - n 번째 항목의 값을 반환한다. (0 번째 항목부터 시작)
        - [ ] push_front(value) - 리스트의 맨 앞에 항목을 추가한다.
        - [ ] pop_front() - 맨 앞의 항목을 제거하고 항목의 값을 반환한다.
        - [ ] push_back(value) - 리스트의 맨 뒤에 항목을 추가한다.
        - [ ] pop_back() - 맨 뒤의 항목을 제거하고 항목의 값을 반환한다.
        - [ ] front() - 맨 앞의 항목 값을 가져온다.
        - [ ] back() - 맨 뒤의 항목 값을 가져온다.
        - [ ] insert(index, value) - 인덱스가 가리키는 곳에 값을 삽입한다. 즉, 원래 있던 노드는 삽입된 노드가 가리키는 뒤로 이동한다.
        - [ ] erase(index) - 주어진 인덱스가 가리키는 노드를 제거한다.
        - [ ] value_n_from_end(n) - 리스트의 끝에서부터 n 번째 노드에 해당하는 값을 반환한다.
        - [ ] reverse() - 리스트의 순서를 뒤집는다.
        - [ ] remove_value(value) - 주어진 값에 해당하는 첫 번째 값을 제거한다.
    - [ ] 이중 링크드 리스트
        - [Description (video)](https://www.coursera.org/learn/data-structures/lecture/jpGKD/doubly-linked-lists)
        - 구현할 필요 없음.

- ### 스택
    - [ ] [Stacks (video)](https://www.coursera.org/learn/data-structures/lecture/UdKzQ/stacks)
    - [ ] [Using Stacks Last-In First-Out (video)](https://archive.org/details/0102WhatYouShouldKnow/05_01-usingStacksForLast-inFirst-out.mp4)
    - [ ] 구현하지 않을 것임. 배열로 구현하는 것은 너무 쉬움.

- ### 큐
    - [ ] [Using Queues First-In First-Out(video)](https://archive.org/details/0102WhatYouShouldKnow/05_03-usingQueuesForFirst-inFirst-out.mp4)
    - [ ] [Queue (video)](https://www.coursera.org/learn/data-structures/lecture/EShpq/queue)
    - [ ] [Circular buffer/FIFO](https://en.wikipedia.org/wiki/Circular_buffer)
    - [ ] [Priority Queues (video)](https://archive.org/details/0102WhatYouShouldKnow/05_04-priorityQueuesAndDeques.mp4)
    - [ ] tail 포인터를 이용한 링크드 리스트로 구현한 경우:
        - enqueue(value) - tail이 가리키는 위치에 값을 추가함.
        - dequeue() - 맨 처음 추가된 값을 반환하고 리스트에서 삭제함.
        - empty()
    - [ ] 고정크기 배열로 구현한 경우:
        - enqueue(value) - adds item at end of available storage
        - dequeue() - returns value and removes least recently added element
        - empty()
        - full()
    - [ ] Cost:
        - a bad implementation using linked list where you enqueue at head and dequeue at tail would be O(n)
            because you'd need the next to last element, causing a full traversal each dequeue
        - enqueue: O(1) (amortized, linked list and array [probing])
        - dequeue: O(1) (linked list and array)
        - empty: O(1) (linked list and array)

- ### 해쉬 테이블
    - [ ] Videos:
        - [ ] [Hashing with Chaining (video)](https://www.youtube.com/watch?v=0M_kIqhwbFo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=8)
        - [ ] [Table Doubling, Karp-Rabin (video)](https://www.youtube.com/watch?v=BRO7mVIFt08&index=9&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
        - [ ] [Open Addressing, Cryptographic Hashing (video)](https://www.youtube.com/watch?v=rvdJDijO2Ro&index=10&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
        - [ ] [PyCon 2010: The Mighty Dictionary (video)](https://www.youtube.com/watch?v=C4Kc8xzcA68)
        - [ ] [(Advanced) Randomization: Universal & Perfect Hashing (video)](https://www.youtube.com/watch?v=z0lJ2k0sl1g&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=11)
        - [ ] [(Advanced) Perfect hashing (video)](https://www.youtube.com/watch?v=N0COwN14gt0&list=PL2B4EEwhKD-NbwZ4ezj7gyc_3yNrojKM9&index=4)

    - [ ] Online Courses:
        - [ ] [Understanding Hash Functions (video)](https://archive.org/details/0102WhatYouShouldKnow/06_02-understandingHashFunctions.mp4)
        - [ ] [Using Hash Tables (video)](https://archive.org/details/0102WhatYouShouldKnow/06_03-usingHashTables.mp4)
        - [ ] [Supporting Hashing (video)](https://archive.org/details/0102WhatYouShouldKnow/06_04-supportingHashing.mp4)
        - [ ] [Language Support Hash Tables (video)](https://archive.org/details/0102WhatYouShouldKnow/06_05-languageSupportForHashTables.mp4)
        - [ ] [Core Hash Tables (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/m7UuP/core-hash-tables)
        - [ ] [Data Structures (video)](https://www.coursera.org/learn/data-structures/home/week/3)
        - [ ] [Phone Book Problem (video)](https://www.coursera.org/learn/data-structures/lecture/NYZZP/phone-book-problem)
        - [ ] distributed hash tables:
            - [Instant Uploads And Storage Optimization In Dropbox (video)](https://www.coursera.org/learn/data-structures/lecture/DvaIb/instant-uploads-and-storage-optimization-in-dropbox)
            - [Distributed Hash Tables (video)](https://www.coursera.org/learn/data-structures/lecture/tvH8H/distributed-hash-tables)

    - [ ] 선형 탐색 및 배열을 이용한 구현
        - hash(k, m) - m 은 해시 테이블의 크기이다.
        - add(key, value) - 키가 이미 존재한다면 값을 수정함.
        - exists(key)
        - get(key)
        - remove(key)

## 추가 지식

- ### 이진 탐색
    - [ ] [Binary Search (video)](https://www.youtube.com/watch?v=D5SrAga1pno)
    - [ ] [Binary Search (video)](https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/binary-search)
    - [ ] [detail](https://www.topcoder.com/community/data-science/data-science-tutorials/binary-search/)
    - [ ] 구현:
        - 정렬된 정수 배열을 이용한 이진 탐색
        - 재귀를 이용한 이진 탐색

- ### 비트 연산
    - [ ] [Bits cheat sheet](https://github.com/jwasham/coding-interview-university/blob/master/extras/cheat%20sheets/bits-cheat-cheet.pdf) - 2의 거듭제곱 형태를 띈 것들을 숙지해야 한다. (2^1 to 2^16 and 2^32)
    - [ ] 비트를 다루는 것을 꼼꼼히 이해하자: &, |, ^, ~, >>, <<
        - [ ] [words](https://en.wikipedia.org/wiki/Word_(computer_architecture))
        - [ ] Good intro:
            [Bit Manipulation (video)](https://www.youtube.com/watch?v=7jkIUgLC29I)
        - [ ] [C Programming Tutorial 2-10: Bitwise Operators (video)](https://www.youtube.com/watch?v=d0AwjSpNXR0)
        - [ ] [Bit Manipulation](https://en.wikipedia.org/wiki/Bit_manipulation)
        - [ ] [Bitwise Operation](https://en.wikipedia.org/wiki/Bitwise_operation)
        - [ ] [Bithacks](https://graphics.stanford.edu/~seander/bithacks.html)
        - [ ] [The Bit Twiddler](http://bits.stephan-brumme.com/)
        - [ ] [The Bit Twiddler Interactive](http://bits.stephan-brumme.com/interactive.html)
    - [ ] 2s and 1s complement
        - [Binary: Plusses & Minuses (Why We Use Two's Complement) (video)](https://www.youtube.com/watch?v=lKTsv6iVxV4)
        - [1s Complement](https://en.wikipedia.org/wiki/Ones%27_complement)
        - [2s Complement](https://en.wikipedia.org/wiki/Two%27s_complement)
    - [ ] count set bits
        - [4 ways to count bits in a byte (video)](https://youtu.be/Hzuzo9NJrlc)
        - [Count Bits](https://graphics.stanford.edu/~seander/bithacks.html#CountBitsSetKernighan)
        - [How To Count The Number Of Set Bits In a 32 Bit Integer](http://stackoverflow.com/questions/109023/how-to-count-the-number-of-set-bits-in-a-32-bit-integer)
    - [ ] round to next power of 2:
        - [Round Up To Next Power Of Two](http://bits.stephan-brumme.com/roundUpToNextPowerOfTwo.html)
    - [ ] swap values:
        - [Swap](http://bits.stephan-brumme.com/swap.html)
    - [ ] absolute value:
        - [Absolute Integer](http://bits.stephan-brumme.com/absInteger.html)

## 트리

- ### Trees - Notes & Background
    - [ ] [Series: Core Trees (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/ovovP/core-trees)
    - [ ] [Series: Trees (video)](https://www.coursera.org/learn/data-structures/lecture/95qda/trees)
    - 기본적인 트리 생성
    - 순회
    - 알고리즘 다루기
    - BFS (넓이 우선 탐색)
        - [MIT (video)](https://www.youtube.com/watch?v=s-CYnVz-uh4&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=13)
        - level order (BFS, using queue)
            시간 복잡도: O(n)
            공간 복잡도: 최선의 경우 O(1), 최악의 경우 O(n/2)=O(n)
    - DFS (깊이 우선 탐색)
        - [MIT (video)](https://www.youtube.com/watch?v=AfSk24UTFS8&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=14)
        - notes:
            시간 복잡도: O(n)
            공간 복잡도:
                최선의 경우 O(log n) - avg. height of tree
                최악의 경우 O(n)
        - 중위 순회 (DFS: left, self, right)
        - 후위 순회 (DFS: left, right, self)
        - 전위 순회 (DFS: self, left, right)

- ### 이진 탐색 트리: BSTs
    - [ ] [Binary Search Tree Review (video)](https://www.youtube.com/watch?v=x6At0nzX92o&index=1&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
    - [ ] [Series (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/p82sw/core-introduction-to-binary-search-trees)
        - symbol table 부터 시작해서 BTS 응용까지
    - [ ] [Introduction (video)](https://www.coursera.org/learn/data-structures/lecture/E7cXP/introduction)
    - [ ] [MIT (video)](https://www.youtube.com/watch?v=9Jry5-82I68)
    - C/C++:
        - [ ] [Binary search tree - Implementation in C/C++ (video)](https://www.youtube.com/watch?v=COZK7NATh4k&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=28)
        - [ ] [BST implementation - memory allocation in stack and heap (video)](https://www.youtube.com/watch?v=hWokyBoo0aI&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=29)
        - [ ] [Find min and max element in a binary search tree (video)](https://www.youtube.com/watch?v=Ut90klNN264&index=30&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Find height of a binary tree (video)](https://www.youtube.com/watch?v=_pnqMz5nrRs&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=31)
        - [ ] [Binary tree traversal - breadth-first and depth-first strategies (video)](https://www.youtube.com/watch?v=9RHO6jU--GU&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=32)
        - [ ] [Binary tree: Level Order Traversal (video)](https://www.youtube.com/watch?v=86g8jAQug04&index=33&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Binary tree traversal: Preorder, Inorder, Postorder (video)](https://www.youtube.com/watch?v=gm8DUJJhmY4&index=34&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Check if a binary tree is binary search tree or not (video)](https://www.youtube.com/watch?v=yEwSGhSsT0U&index=35&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
        - [ ] [Delete a node from Binary Search Tree (video)](https://www.youtube.com/watch?v=gcULXE7ViZw&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P&index=36)
        - [ ] [Inorder Successor in a binary search tree (video)](https://www.youtube.com/watch?v=5cPbNCrdotA&index=37&list=PL2_aWCzGMAwI3W_JlcBbtYTwiQSsOTa6P)
    - [ ] 구현:
        - [ ] insert    // 트리에 값 삽입
        - [ ] get_node_count // 저장된 값들의 개수
        - [ ] print_values // min 에서 max까지 트리의 모든 값 출력
        - [ ] delete_tree
        - [ ] is_in_tree // 트리 안에 값이 있으면 true 반환
        - [ ] get_height // 노드의 높이 반환 (단일 노드일 경우 1 반환)
        - [ ] get_min   // 트리에 저장된 최소값 반환
        - [ ] get_max   // 트리에 저장된 최대값 반환
        - [ ] is_binary_search_tree
        - [ ] delete_value
        - [ ] get_successor // 트리에서 주어진 값 다음으로 높은 값 반환. 없을 경우 -1 반환.

- ### 힙 / 우선순위 큐 / 이진 힙
    - 트리처럼 그려졌지만 보통 선형적으로 저장됨 (배열, 링크드 리스트)
    - [ ] [Heap](https://en.wikipedia.org/wiki/Heap_(data_structure))
    - [ ] [Introduction (video)](https://www.coursera.org/learn/data-structures/lecture/2OpTs/introduction)
    - [ ] [Naive Implementations (video)](https://www.coursera.org/learn/data-structures/lecture/z3l9N/naive-implementations)
    - [ ] [Binary Trees (video)](https://www.coursera.org/learn/data-structures/lecture/GRV2q/binary-trees)
    - [ ] [Tree Height Remark (video)](https://www.coursera.org/learn/data-structures/supplement/S5xxz/tree-height-remark)
    - [ ] [Basic Operations (video)](https://www.coursera.org/learn/data-structures/lecture/0g1dl/basic-operations)
    - [ ] [Complete Binary Trees (video)](https://www.coursera.org/learn/data-structures/lecture/gl5Ni/complete-binary-trees)
    - [ ] [Pseudocode (video)](https://www.coursera.org/learn/data-structures/lecture/HxQo9/pseudocode)
    - [ ] [Heap Sort - jumps to start (video)](https://youtu.be/odNJmw5TOEE?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3291)
    - [ ] [Heap Sort (video)](https://www.coursera.org/learn/data-structures/lecture/hSzMO/heap-sort)
    - [ ] [Building a heap (video)](https://www.coursera.org/learn/data-structures/lecture/dwrOS/building-a-heap)
    - [ ] [MIT: Heaps and Heap Sort (video)](https://www.youtube.com/watch?v=B7hVxCmfPtM&index=4&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [CS 61B Lecture 24: Priority Queues (video)](https://www.youtube.com/watch?v=yIUFT6AKBGE&index=24&list=PL4BBB74C7D2A1049C)
    - [ ] [Linear Time BuildHeap (max-heap)](https://www.youtube.com/watch?v=MiyLo8adrWw)
    - [ ] max-힙 구현:
        - [ ] insert
        - [ ] sift_up - 삽입을 위해 필요함.
        - [ ] get_max - 최대값을 제거하지 않고 반환함
        - [ ] get_size() - 저장된 항목들의 수를 반환함
        - [ ] is_empty() - 힙이 비어있을 경우 true를 반환함
        - [ ] extract_max - 최대값을 반환하면서 제거함.
        - [ ] sift_down - extract_max를 위해 필요함.
        - [ ] remove(i) - 지정된 인덱스에 있는 값을 제거함
        - [ ] heapify - 배열로부터 힙을 생성함, 이를 위해 heap_sort 필요함.
        - [ ] heap_sort() - take an unsorted array and turn it into a sorted array in-place using a max heap
            - note: using a min heap instead would save operations, but double the space needed (cannot do in-place).

## 정렬

- [ ] Notes:
    - 정렬 구현하기 & 최선/최악의 경우 숙지하기, 다음 각각의 평균 복잡도 알기:
        - 거품 정렬 금지! - 끔찍한 성능 - O(n^2), n <= 16 일 때 예외적으로 사용
    - [ ] stability in sorting algorithms ("Is Quicksort stable?")
        - [Sorting Algorithm Stability](https://en.wikipedia.org/wiki/Sorting_algorithm#Stability)
        - [Stability In Sorting Algorithms](http://stackoverflow.com/questions/1517793/stability-in-sorting-algorithms)
        - [Stability In Sorting Algorithms](http://www.geeksforgeeks.org/stability-in-sorting-algorithms/)
        - [Sorting Algorithms - Stability](http://homepages.math.uic.edu/~leon/cs-mcs401-s08/handouts/stability.pdf)
    - [ ] Which algorithms can be used on linked lists? Which on arrays? Which on both?
        - 나는 링크드 리스트를 정렬하는 것을 추천하지 않는다. 하지만 병합 정렬은 할 만 하다.
        - [Merge Sort For Linked List](http://www.geeksforgeeks.org/merge-sort-for-linked-list/)

- 힙 정렬을 위해서 우선 위에 설명한 힙의 데이터 구조를 먼저 보라. 힙 정렬은 훌륭하지만 안정적이지는 않다.

- [ ] [Sedgewick - Mergesort (5 videos)](https://www.youtube.com/watch?v=4nKwesx_c8E&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9)
    - [ ] [1. Mergesort](https://www.youtube.com/watch?v=4nKwesx_c8E&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9&index=1)
    - [ ] [2. Bottom up Mergesort](https://www.youtube.com/watch?v=HGOIGUYjeyk&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9&index=2)
    - [ ] [3. Sorting Complexity](https://www.youtube.com/watch?v=WvU_mIWo0Ac&index=3&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9)
    - [ ] [4. Comparators](https://www.youtube.com/watch?v=7MvC1kmBza0&index=4&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9)
    - [ ] [5. Stability](https://www.youtube.com/watch?v=XD_5iINB5GI&index=5&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9)

- [ ] [Sedgewick - Quicksort (4 videos)](https://www.youtube.com/playlist?list=PLe-ggMe31CTeE3x2-nF1-toca1QpuXwE1)
    - [ ] [1. Quicksort](https://www.youtube.com/watch?v=5M5A7qPWk84&index=1&list=PLe-ggMe31CTeE3x2-nF1-toca1QpuXwE1)
    - [ ] [2. Selection](https://www.youtube.com/watch?v=CgVYfSyct_M&index=2&list=PLe-ggMe31CTeE3x2-nF1-toca1QpuXwE1)
    - [ ] [3. Duplicate Keys](https://www.youtube.com/watch?v=WBFzOYJ5ybM&index=3&list=PLe-ggMe31CTeE3x2-nF1-toca1QpuXwE1)
    - [ ] [4. System Sorts](https://www.youtube.com/watch?v=rejpZ2htBjE&index=4&list=PLe-ggMe31CTeE3x2-nF1-toca1QpuXwE1)

- [ ] UC Berkeley:
    - [ ] [CS 61B Lecture 29: Sorting I (video)](https://www.youtube.com/watch?v=EiUvYS2DT6I&list=PL4BBB74C7D2A1049C&index=29)
    - [ ] [CS 61B Lecture 30: Sorting II (video)](https://www.youtube.com/watch?v=2hTY3t80Qsk&list=PL4BBB74C7D2A1049C&index=30)
    - [ ] [CS 61B Lecture 32: Sorting III (video)](https://www.youtube.com/watch?v=Y6LOLpxg6Dc&index=32&list=PL4BBB74C7D2A1049C)
    - [ ] [CS 61B Lecture 33: Sorting V (video)](https://www.youtube.com/watch?v=qNMQ4ly43p4&index=33&list=PL4BBB74C7D2A1049C)

- [ ] [Bubble Sort (video)](https://www.youtube.com/watch?v=P00xJgWzz2c&index=1&list=PL89B61F78B552C1AB)
- [ ] [Analyzing Bubble Sort (video)](https://www.youtube.com/watch?v=ni_zk257Nqo&index=7&list=PL89B61F78B552C1AB)
- [ ] [Insertion Sort, Merge Sort (video)](https://www.youtube.com/watch?v=Kg4bqzAqRBM&index=3&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
- [ ] [Insertion Sort (video)](https://www.youtube.com/watch?v=c4BRHC7kTaQ&index=2&list=PL89B61F78B552C1AB)
- [ ] [Merge Sort (video)](https://www.youtube.com/watch?v=GCae1WNvnZM&index=3&list=PL89B61F78B552C1AB)
- [ ] [Quicksort (video)](https://www.youtube.com/watch?v=y_G9BkAm6B8&index=4&list=PL89B61F78B552C1AB)
- [ ] [Selection Sort (video)](https://www.youtube.com/watch?v=6nDMgr0-Yyo&index=8&list=PL89B61F78B552C1AB)

- [ ] Merge sort code:
    - [ ] [Using output array (C)](http://www.cs.yale.edu/homes/aspnes/classes/223/examples/sorting/mergesort.c)
    - [ ] [Using output array (Python)](https://github.com/jwasham/practice-python/blob/master/merge_sort/merge_sort.py)
    - [ ] [In-place (C++)](https://github.com/jwasham/practice-cpp/blob/master/merge_sort/merge_sort.cc)
- [ ] Quick sort code:
    - [ ] [Implementation (C)](http://www.cs.yale.edu/homes/aspnes/classes/223/examples/randomization/quick.c)
    - [ ] [Implementation (C)](https://github.com/jwasham/practice-c/blob/master/quick_sort/quick_sort.c)
    - [ ] [Implementation (Python)](https://github.com/jwasham/practice-python/blob/master/quick_sort/quick_sort.py)

- [ ] 구현:
    - [ ] 병합 정렬: O(n log n) 평균과 최악의 경우
    - [ ] 퀵 정렬 O(n log n) 평균적인 경우
    - 선택 정렬과 삽입 정렬 모두 평균과 최악의 경우에서 O(n^2)임.
    - 힙정렬에 관해서는, 위의 힙 데이터 구조를 보라.

- [ ] 요구사항은 아니지만 개인적으로 추천하는 것들:
    - [ ] [Sedgewick - Radix Sorts (6 videos)](https://www.youtube.com/playlist?list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53)
        - [ ] [1. Strings in Java](https://www.youtube.com/watch?v=zRzU-FWsjNU&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53&index=6)
        - [ ] [2. Key Indexed Counting](https://www.youtube.com/watch?v=CtgKYmXs62w&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53&index=5)
        - [ ] [3. Least Significant Digit First String Radix Sort](https://www.youtube.com/watch?v=2pGVq_BwPKs&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53&index=4)
        - [ ] [4. Most Significant Digit First String Radix Sort](https://www.youtube.com/watch?v=M3cYNY90R6c&index=3&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53)
        - [ ] [5. 3 Way Radix Quicksort](https://www.youtube.com/watch?v=YVl58kfE6i8&index=2&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53)
        - [ ] [6. Suffix Arrays](https://www.youtube.com/watch?v=HKPrVm5FWvg&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53&index=1)
    - [ ] [Radix Sort](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#radixSort)
    - [ ] [Radix Sort (video)](https://www.youtube.com/watch?v=xhr26ia4k38)
    - [ ] [Radix Sort, Counting Sort (linear time given constraints) (video)](https://www.youtube.com/watch?v=Nz1KZXbghj8&index=7&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [Randomization: Matrix Multiply, Quicksort, Freivalds' algorithm (video)](https://www.youtube.com/watch?v=cNB2lADK3_s&index=8&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [ ] [Sorting in Linear Time (video)](https://www.youtube.com/watch?v=pOKy3RZbSws&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf&index=14)

만약 이 주제에 대해서 더 자세한 설명이 필요하다면, [Additional Detail on Some Subjects](#additional-detail-on-some-subjects) 에 있는 "정렬" 섹션을 보라.

## 그래프

그래프는 컴퓨터 과학의 여러 문제들을 표현하는 데 사용할 수 있다. 때문에 이 섹션은 트리나 정렬 섹션처럼 길다.

- Yegge의 노트:
    - 메모리에 그래프를 표시하는 세 가지 기본 방법이 있다:
        - 오브젝트와 포인터
        - 행렬
        - 인접 리스트
    - 각각의 표현과 장단점을 숙지하라.
    - 넓이우선탐색(BFS)와 깊이우선탐색(DFS) - 계산상의 복잡성, 장단점, 실제 코드로 구현하는 방법을 알아야 한다.
    - 질문을 받을 시 먼저 그래프 기반 솔루션을 찾고, 없을 경우에 다른 솔루션으로 넘어가라.

- [ ] Skiena의 강좌 - 훌륭한 인트로:
    - [ ] [CSE373 2012 - Lecture 11 - Graph Data Structures (video)](https://www.youtube.com/watch?v=OiXxhDrFruw&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=11)
    - [ ] [CSE373 2012 - Lecture 12 - Breadth-First Search (video)](https://www.youtube.com/watch?v=g5vF8jscteo&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=12)
    - [ ] [CSE373 2012 - Lecture 13 - Graph Algorithms (video)](https://www.youtube.com/watch?v=S23W6eTcqdY&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=13)
    - [ ] [CSE373 2012 - Lecture 14 - Graph Algorithms (con't) (video)](https://www.youtube.com/watch?v=WitPBKGV0HY&index=14&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
    - [ ] [CSE373 2012 - Lecture 15 - Graph Algorithms (con't 2) (video)](https://www.youtube.com/watch?v=ia1L30l7OIg&index=15&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
    - [ ] [CSE373 2012 - Lecture 16 - Graph Algorithms (con't 3) (video)](https://www.youtube.com/watch?v=jgDOQq6iWy8&index=16&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)

- [ ] 그래프 (검토, 그 외 여러가지):

    - [ ] [6.006 Single-Source Shortest Paths Problem (video)](https://www.youtube.com/watch?v=Aa2sqUhIn-E&index=15&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [6.006 Dijkstra (video)](https://www.youtube.com/watch?v=2E7MmKv0Y24&index=16&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [6.006 Bellman-Ford (video)](https://www.youtube.com/watch?v=ozsuci5pIso&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=17)
    - [ ] [6.006 Speeding Up Dijkstra (video)](https://www.youtube.com/watch?v=CHvQ3q_gJ7E&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=18)
    - [ ] [Aduni: Graph Algorithms I - Topological Sorting, Minimum Spanning Trees, Prim's Algorithm -  Lecture 6 (video)]( https://www.youtube.com/watch?v=i_AQT_XfvD8&index=6&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
    - [ ] [Aduni: Graph Algorithms II - DFS, BFS, Kruskal's Algorithm, Union Find Data Structure - Lecture 7 (video)]( https://www.youtube.com/watch?v=ufj5_bppBsA&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=7)
    - [ ] [Aduni: Graph Algorithms III: Shortest Path - Lecture 8 (video)](https://www.youtube.com/watch?v=DiedsPsMKXc&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=8)
    - [ ] [Aduni: Graph Alg. IV: Intro to geometric algorithms - Lecture 9 (video)](https://www.youtube.com/watch?v=XIAQRlNkJAw&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=9)
    - [ ] [CS 61B 2014 (starting at 58:09) (video)](https://youtu.be/dgjX4HdMI-Q?list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd&t=3489)
    - [ ] [CS 61B 2014: Weighted graphs (video)](https://www.youtube.com/watch?v=aJjlQCFwylA&list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd&index=19)
    - [ ] [Greedy Algorithms: Minimum Spanning Tree (video)](https://www.youtube.com/watch?v=tKwnms5iRBU&index=16&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [ ] [Strongly Connected Components Kosaraju's Algorithm Graph Algorithm (video)](https://www.youtube.com/watch?v=RpgcYiky7uw)

- Full Coursera Course:
    - [ ] [Algorithms on Graphs (video)](https://www.coursera.org/learn/algorithms-on-graphs/home/welcome)

- Yegge: 기회가 된다면, 더 멋진 알고리즘을 연구해 보라:
    - [ ] Dijkstra's algorithm - see above - 6.006
    - [ ] A*
        - [ ] [A Search Algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm)
        - [ ] [A* Pathfinding Tutorial (video)](https://www.youtube.com/watch?v=KNXfSOx4eEE)
        - [ ] [A* Pathfinding (E01: algorithm explanation) (video)](https://www.youtube.com/watch?v=-L-WgKMFuhE)

- 내가 구현할 것:
    - [ ] DFS with adjacency list (recursive)
    - [ ] DFS with adjacency list (iterative with stack)
    - [ ] DFS with adjacency matrix (recursive)
    - [ ] DFS with adjacency matrix (iterative with stack)
    - [ ] BFS with adjacency list
    - [ ] BFS with adjacency matrix
    - [ ] single-source shortest path (Dijkstra)
    - [ ] minimum spanning tree
    - DFS-based algorithms (see Aduni videos above):
        - [ ] check for cycle (needed for topological sort, since we'll check for cycle before starting)
        - [ ] topological sort
        - [ ] count connected components in a graph
        - [ ] list strongly connected components
        - [ ] check for bipartite graph

Skiena의 책(아래의 책 섹션 참조)과 인터뷰 책에서 더 많은 그래프 실습을 할 수 있다.

## Even More Knowledge

- ### Recursion
    - [ ] Stanford lectures on recursion & backtracking:
        - [ ] [Lecture 8 | Programming Abstractions (video)](https://www.youtube.com/watch?v=gl3emqCuueQ&list=PLFE6E58F856038C69&index=8)
        - [ ] [Lecture 9 | Programming Abstractions (video)](https://www.youtube.com/watch?v=uFJhEPrbycQ&list=PLFE6E58F856038C69&index=9)
        - [ ] [Lecture 10 | Programming Abstractions (video)](https://www.youtube.com/watch?v=NdF1QDTRkck&index=10&list=PLFE6E58F856038C69)
        - [ ] [Lecture 11 | Programming Abstractions (video)](https://www.youtube.com/watch?v=p-gpaIGRCQI&list=PLFE6E58F856038C69&index=11)
    - when it is appropriate to use it
    - how is tail recursion better than not?
        - [ ] [What Is Tail Recursion Why Is It So Bad?](https://www.quora.com/What-is-tail-recursion-Why-is-it-so-bad)
        - [ ] [Tail Recursion (video)](https://www.youtube.com/watch?v=L1jjXGfxozc)

- ### 동적 계획법
    - **NOTE:** 동적 계획법은 중요한 기술이지만, 구글에서 제공하는 어떠한 준비 사항에도 언급되지 않았다. 하지만 당신은 동적 계획법이 최적의 해답인 경우 문제를 겪을 수도 있다. 따라서 나는 이 부분을 포함했다.
    - 동적 계획법으로 풀 수 있는 문제는 반드시 재귀 형태로 정의되어야 하기 때문에, 이 주제는 꽤 어려울 수 있다.
    - 나는 당신이 수많은 동적 계획법 문제 예제들이 포함하는 패턴을 확실히 이해할 때 까지 그것들을 계속 찾아볼 것을 권한다.
    - [ ] 비디오:
        - Skiena의 비디오는 종종 알아보기 힘든 화이트보드를 사용하기 때문에 이해하기 어려울 수 있다.
        - [ ] [Skiena: CSE373 2012 - Lecture 19 - Introduction to Dynamic Programming (video)](https://youtu.be/Qc2ieXRgR0k?list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&t=1718)
        - [ ] [Skiena: CSE373 2012 - Lecture 20 - Edit Distance (video)](https://youtu.be/IsmMhMdyeGY?list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&t=2749)
        - [ ] [Skiena: CSE373 2012 - Lecture 21 - Dynamic Programming Examples (video)](https://youtu.be/o0V9eYF4UI8?list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&t=406)
        - [ ] [Skiena: CSE373 2012 - Lecture 22 - Applications of Dynamic Programming (video)](https://www.youtube.com/watch?v=dRbMC1Ltl3A&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=22)
        - [ ] [Simonson: Dynamic Programming 0 (starts at 59:18) (video)](https://youtu.be/J5aJEcOr6Eo?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3558)
        - [ ] [Simonson: Dynamic Programming I - Lecture 11 (video)](https://www.youtube.com/watch?v=0EzHjQ_SOeU&index=11&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
        - [ ] [Simonson: Dynamic programming II - Lecture 12 (video)](https://www.youtube.com/watch?v=v1qiRwuJU7g&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=12)
        - [ ] 동적 계획법 문제들 목록(짧은 것들로 구성됨):
            [Dynamic Programming (video)](https://www.youtube.com/playlist?list=PLrmLmBdmIlpsHaNTPP_jHHDx_os9ItYXr)
    - [ ] Yale Lecture notes:
        - [ ] [Dynamic Programming](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#dynamicProgramming)
    - [ ] Coursera:
        - [ ] [The RNA secondary structure problem (video)](https://www.coursera.org/learn/algorithmic-thinking-2/lecture/80RrW/the-rna-secondary-structure-problem)
        - [ ] [A dynamic programming algorithm (video)](https://www.coursera.org/learn/algorithmic-thinking-2/lecture/PSonq/a-dynamic-programming-algorithm)
        - [ ] [Illustrating the DP algorithm (video)](https://www.coursera.org/learn/algorithmic-thinking-2/lecture/oUEK2/illustrating-the-dp-algorithm)
        - [ ] [Running time of the DP algorithm (video)](https://www.coursera.org/learn/algorithmic-thinking-2/lecture/nfK2r/running-time-of-the-dp-algorithm)
        - [ ] [DP vs. recursive implementation (video)](https://www.coursera.org/learn/algorithmic-thinking-2/lecture/M999a/dp-vs-recursive-implementation)
        - [ ] [Global pairwise sequence alignment (video)](https://www.coursera.org/learn/algorithmic-thinking-2/lecture/UZ7o6/global-pairwise-sequence-alignment)
        - [ ] [Local pairwise sequence alignment (video)](https://www.coursera.org/learn/algorithmic-thinking-2/lecture/WnNau/local-pairwise-sequence-alignment)

- ### 객체 지향 프로그래밍
    - [ ] [Optional: UML 2.0 Series (video)](https://www.youtube.com/watch?v=OkC7HKtiZC0&list=PLGLfVvz_LVvQ5G-LdJ8RLqe-ndo7QITYc)
    - [ ] 객체 지향 소프트웨어 공학: UML과 Java를 이용한 소프트웨어 개발 (21 개 비디오):
        - 객체 지향과 실제 객체지향 디자인에 대해 잘 이해하고 있다면 넘어가도 된다.
        - [OOSE: Software Dev Using UML and Java](https://www.youtube.com/playlist?list=PLJ9pm_Rc9HesnkwKlal_buSIHA-jTZMpO)
    - [ ] 중요한 객체 지향 프로그래밍 원리들:
        - [ ] [Bob Martin SOLID Principles of Object Oriented and Agile Design (video)](https://www.youtube.com/watch?v=TMuno5RZNeE)
        - [ ] [SOLID Design Patterns in C# (video)](https://www.youtube.com/playlist?list=PL8m4NUhTQU48oiGCSgCP1FiJEcg_xJzyQ)
        - [ ] [SOLID Principles (video)](https://www.youtube.com/playlist?list=PL4CE9F710017EA77A)
        - [ ] S - [Single Responsibility Principle](http://www.oodesign.com/single-responsibility-principle.html) | [Single responsibility to each Object](http://www.javacodegeeks.com/2011/11/solid-single-responsibility-principle.html)
            - [more flavor](https://docs.google.com/open?id=0ByOwmqah_nuGNHEtcU5OekdDMkk)
        - [ ] O - [Open/Closed Principal](http://www.oodesign.com/open-close-principle.html)  | [On production level Objects are ready for extension for not for modification](https://en.wikipedia.org/wiki/Open/closed_principle)
            - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgN2M5MTkwM2EtNWFkZC00ZTI3LWFjZTUtNTFhZGZiYmUzODc1&hl=en)
        - [ ] L - [Liskov Substitution Principal](http://www.oodesign.com/liskov-s-substitution-principle.html) | [Base Class and Derived class follow ‘IS A’ principal](http://stackoverflow.com/questions/56860/what-is-the-liskov-substitution-principle)
            - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgNzAzZjA5ZmItNjU3NS00MzQ5LTkwYjMtMDJhNDU5ZTM0MTlh&hl=en)
        - [ ] I - [Interface segregation principle](http://www.oodesign.com/interface-segregation-principle.html) | clients should not be forced to implement interfaces they don't use
            - [Interface Segregation Principle in 5 minutes (video)](https://www.youtube.com/watch?v=3CtAfl7aXAQ)
            - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgOTViYjJhYzMtMzYxMC00MzFjLWJjMzYtOGJiMDc5N2JkYmJi&hl=en)
        - [ ] D -[Dependency Inversion principle](http://www.oodesign.com/dependency-inversion-principle.html) | Reduce the dependency In composition of objects.
            - [Why Is The Dependency Inversion Principle And Why Is It Important](http://stackoverflow.com/questions/62539/what-is-the-dependency-inversion-principle-and-why-is-it-important)
            - [more flavor](http://docs.google.com/a/cleancoder.com/viewer?a=v&pid=explorer&chrome=true&srcid=0BwhCYaYDn8EgMjdlMWIzNGUtZTQ0NC00ZjQ5LTkwYzQtZjRhMDRlNTQ3ZGMz&hl=en)

- ### 디자인 패턴
    - [ ] [Quick UML review (video)](https://www.youtube.com/watch?v=3cmzqZzwNDM&list=PLGLfVvz_LVvQ5G-LdJ8RLqe-ndo7QITYc&index=3)
    - [ ] 이 패턴들을 공부할 것:
        - [ ] strategy
        - [ ] singleton
        - [ ] adapter
        - [ ] prototype
        - [ ] decorator
        - [ ] visitor
        - [ ] factory, abstract factory
        - [ ] facade
        - [ ] observer
        - [ ] proxy
        - [ ] delegate
        - [ ] command
        - [ ] state
        - [ ] memento
        - [ ] iterator
        - [ ] composite
        - [ ] flyweight
    - [ ] [Chapter 6 (Part 1) - Patterns (video)](https://youtu.be/LAP2A80Ajrg?list=PLJ9pm_Rc9HesnkwKlal_buSIHA-jTZMpO&t=3344)
    - [ ] [Chapter 6 (Part 2) - Abstraction-Occurrence, General Hierarchy, Player-Role, Singleton, Observer, Delegation (video)](https://www.youtube.com/watch?v=U8-PGsjvZc4&index=12&list=PLJ9pm_Rc9HesnkwKlal_buSIHA-jTZMpO)
    - [ ] [Chapter 6 (Part 3) - Adapter, Facade, Immutable, Read-Only Interface, Proxy (video)](https://www.youtube.com/watch?v=7sduBHuex4c&index=13&list=PLJ9pm_Rc9HesnkwKlal_buSIHA-jTZMpO)
    - [ ] [Series of videos (27 videos)](https://www.youtube.com/playlist?list=PLF206E906175C7E07)
    - [ ] [Head First Design Patterns](https://www.amazon.com/Head-First-Design-Patterns-Freeman/dp/0596007124)
        - "Design Patterns: Elements of Reusable Object-Oriented Software" 이 바이블급 교과서 인 것은 알지만, Head First 역시 객체 지향 초보자들에게 좋다.
    - [ ] [Handy reference: 101 Design Patterns & Tips for Developers](https://sourcemaking.com/design-patterns-and-tips)

- ### 조합 (n 개 중에 k개 고르기) & 확률
    - [ ] [Math Skills: How to find Factorial, Permutation and Combination (Choose) (video)](https://www.youtube.com/watch?v=8RRo6Ti9d0U)
    - [ ] [Make School: Probability (video)](https://www.youtube.com/watch?v=sZkAAk9Wwa4)
    - [ ] [Make School: More Probability and Markov Chains (video)](https://www.youtube.com/watch?v=dNaJg-mLobQ)
    - [ ] Khan Academy:
        - Course layout:
            - [ ] [Basic Theoretical Probability](https://www.khanacademy.org/math/probability/probability-and-combinatorics-topic)
        - Just the videos - 41 (each are simple and each are short):
            - [ ] [Probability Explained (video)](https://www.youtube.com/watch?v=uzkc-qNVoOk&list=PLC58778F28211FA19)

- ### NP, NP-Complete 과 근사 알고리즘들
    - NP-complete 문제 중 가장 유명한 것 들을 알아둬라(예를 들어 외판원 문제, 배낭 문제 등). 그리고 면접관이 문제를 속여서 낼 때 알아차릴 수 있을 정도로 준비해둬라.
    - NP-complete 의 의미가 무엇인지 알아둘 것.
    - [ ] [Computational Complexity (video)](https://www.youtube.com/watch?v=moPtwq_cVH8&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=23)
    - [ ] Simonson:
        - [ ] [Greedy Algs. II & Intro to NP Completeness (video)](https://youtu.be/qcGnJ47Smlo?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=2939)
        - [ ] [NP Completeness II & Reductions (video)](https://www.youtube.com/watch?v=e0tGC6ZQdQE&index=16&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
        - [ ] [NP Completeness III (Video)](https://www.youtube.com/watch?v=fCX1BGT3wjE&index=17&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
        - [ ] [NP Completeness IV (video)](https://www.youtube.com/watch?v=NKLDp3Rch3M&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=18)
    - [ ] Skiena:
        - [ ] [CSE373 2012 - Lecture 23 - Introduction to NP-Completeness (video)](https://youtu.be/KiK5TVgXbFg?list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&t=1508)
        - [ ] [CSE373 2012 - Lecture 24 - NP-Completeness Proofs (video)](https://www.youtube.com/watch?v=27Al52X3hd4&index=24&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
        - [ ] [CSE373 2012 - Lecture 25 - NP-Completeness Challenge (video)](https://www.youtube.com/watch?v=xCPH4gwIIXM&index=25&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
    - [ ] [Complexity: P, NP, NP-completeness, Reductions (video)](https://www.youtube.com/watch?v=eHZifpgyH_4&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=22)
    - [ ] [Complexity: Approximation Algorithms (video)](https://www.youtube.com/watch?v=MEz1J9wY2iM&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=24)
    - [ ] [Complexity: Fixed-Parameter Algorithms (video)](https://www.youtube.com/watch?v=4q-jmGrmxKs&index=25&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - Peter Norvig 이 외판원 문제의 근접-최적해에 관해 논의한 것:
        - [Jupyter Notebook](http://nbviewer.jupyter.org/url/norvig.com/ipython/TSP.ipynb)
    - Pages 1048 - 1140 in CLRS if you have it.

- ### 캐시
    - [ ] LRU cache:
        - [ ] [The Magic of LRU Cache (100 Days of Google Dev) (video)](https://www.youtube.com/watch?v=R5ON3iwx78M)
        - [ ] [Implementing LRU (video)](https://www.youtube.com/watch?v=bq6N7Ym81iI)
        - [ ] [LeetCode - 146 LRU Cache (C++) (video)](https://www.youtube.com/watch?v=8-FZRAjR7qU)
    - [ ] CPU cache:
        - [ ] [MIT 6.004 L15: The Memory Hierarchy (video)](https://www.youtube.com/watch?v=vjYF_fAZI5E&list=PLrRW1w6CGAcXbMtDFj205vALOGmiRc82-&index=24)
        - [ ] [MIT 6.004 L16: Cache Issues (video)](https://www.youtube.com/watch?v=ajgC3-pyGlk&index=25&list=PLrRW1w6CGAcXbMtDFj205vALOGmiRc82-)

- ### 프로세스와 스레드
    - [ ] Computer Science 162 - Operating Systems (25 videos):
        - 프로세스와 스레드는 비디오 1-11 부분을 볼 것.
        - [Operating Systems and System Programming (video)](https://www.youtube.com/playlist?list=PL-XXv-cvA_iBDyz-ba4yDskqMDY6A1w_c)
    - [What Is The Difference Between A Process And A Thread?](https://www.quora.com/What-is-the-difference-between-a-process-and-a-thread)
    - 다루는 내용:
        - 프로세스, 스레드, 동시성 이슈
            - 프로세스와 스레드의 차이점
            - 프로세스
            - 스레드
            - 락(locks)
            - 뮤텍스
            - 세마포어
            - 모니터
            - 각각의 동작 원리
            - 데드락
            - 무한반복(livelock)
        - CPU 이용률, 인터럽트, 컨텍스트 스위칭
        - 멀티코어 프로세서의 현대적인 동시성 구조
        - 프로세서가 필요로 하는 자원들 (메모리: 코드, 정적 용량, 스택, 힙, 파일 디스크립터, I/O)
        - 스레드가 필요로 하는 자원들 (한 프로세스 내에서 위에 언급한 것들(스택 제외)을 다른 스레드와 공유함. 단, 각각은 자신의 pc, 스택 카운터, 레지스터, 스택을 가짐.)
        - Forking is really copy on write (read-only) until the new process writes to memory, then it does a full copy.
        - 컨텍스트 스위칭
            - 어떻게 운영체제와 하드웨어에 의해 컨텍스트 스위칭이 시작되는 지에 대하여
    - [ ] [threads in C++ (series - 10 videos)](https://www.youtube.com/playlist?list=PL5jc9xFGsL8E12so1wlMS0r0hTQoJL74M)
    - [ ] concurrency in Python (videos):
        - [ ] [Short series on threads](https://www.youtube.com/playlist?list=PL1H1sBF1VAKVMONJWJkmUh6_p8g4F2oy1)
        - [ ] [Python Threads](https://www.youtube.com/watch?v=Bs7vPNbB9JM)
        - [ ] [Understanding the Python GIL (2010)](https://www.youtube.com/watch?v=Obt-vMVdM8s)
            - [reference](http://www.dabeaz.com/GIL)
        - [ ] [David Beazley - Python Concurrency From the Ground Up: LIVE! - PyCon 2015](https://www.youtube.com/watch?v=MCs5OvhV9S4)
        - [ ] [Keynote David Beazley - Topics of Interest (Python Asyncio)](https://www.youtube.com/watch?v=ZzfHjytDceU)
        - [ ] [Mutex in Python](https://www.youtube.com/watch?v=0zaPs8OtyKY)

- ### 논문들
    - 구글의 논문들과 잘 알려진 논문들.
    - 모든 논문을 처음부터 끝까지 완전히 이해하며 읽는 것은 불가능할 것이다. 논문을 고르고 특정 부분을 이해하는 데에 선택과 집중할 것을 추천한다.
    - [ ] [1978: Communicating Sequential Processes](http://spinroot.com/courses/summer/Papers/hoare_1978.pdf)
        - [implemented in Go](https://godoc.org/github.com/thomas11/csp)
        - [Love classic papers?](https://www.cs.cmu.edu/~crary/819-f09/)
    - [ ] [2003: The Google File System](http://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)
        - replaced by Colossus in 2012
    - [ ] [2004: MapReduce: Simplified Data Processing on Large Clusters]( http://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf)
        - mostly replaced by Cloud Dataflow?
    - [ ] [2006: Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
        - [An Inside Look at Google BigQuery](https://cloud.google.com/files/BigQueryTechnicalWP.pdf)
    - [ ] [2006: The Chubby Lock Service for Loosely-Coupled Distributed Systems](https://research.google.com/archive/chubby-osdi06.pdf)
    - [ ] [2007: What Every Programmer Should Know About Memory (very long, and the author encourages skipping of some sections)](https://www.akkadia.org/drepper/cpumemory.pdf)
    - [ ] [2010: Dapper, a Large-Scale Distributed Systems Tracing Infrastructure](https://research.google.com/pubs/archive/36356.pdf)
    - [ ] [2010: Dremel: Interactive Analysis of Web-Scale Datasets](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36632.pdf)
    - [ ] [2012: Google's Colossus](https://www.wired.com/2012/07/google-colossus/)
        - paper not available
    - [ ] 2012: AddressSanitizer: A Fast Address Sanity Checker:
        - [paper](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/37752.pdf)
        - [video](https://www.usenix.org/conference/atc12/technical-sessions/presentation/serebryany)
    - [ ] 2013: Spanner: Google’s Globally-Distributed Database:
        - [paper](http://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf)
        - [video](https://www.usenix.org/node/170855)
    - [ ] [2014: Machine Learning: The High-Interest Credit Card of Technical Debt](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43146.pdf)
    - [ ] [2015: Continuous Pipelines at Google](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43790.pdf)
    - [ ] [2015: High-Availability at Massive Scale: Building Google’s Data Infrastructure for Ads](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44686.pdf)
    - [ ] [2015: TensorFlow: Large-Scale Machine Learning on Heterogeneous Distributed Systems](http://download.tensorflow.org/paper/whitepaper2015.pdf )
    - [ ] [2015: How Developers Search for Code: A Case Study](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43835.pdf)
    - [ ] [2016: Borg, Omega, and Kubernetes](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44843.pdf)

- ### 테스팅
    - 알아 두어야 할 것:
        - 유닛 테스트는 어떻게 작동하는지
        - mock object 는 무엇인지
        - 통합 테스트는 무엇인지
        - 의존성 주입은 무엇인지
    - [ ] [James Bach과 함께하는 애자일 소프트웨어 테스트 (비디오)](https://www.youtube.com/watch?v=SAhJf36_u5U)
    - [ ] [소프트웨어 테스트에 대한 James Bach의 무료 강의 (비디오)](https://www.youtube.com/watch?v=ILkT_HV9DVU)
    - [ ] [Steve Freeman - Test-Driven 개발 (이것은 우리가 의미하는 것은 아니다) (비디오)](https://vimeo.com/83960706)
        - [참고자료](http://gotocon.com/dl/goto-berlin-2013/slides/SteveFreeman_TestDrivenDevelopmentThatsNotWhatWeMeant.pdf)
    - [ ] [TDD는 끝났다. 오래 사는 테스팅.](http://david.heinemeierhansson.com/2014/tdd-is-dead-long-live-testing.html)
    - [ ] [TDD는 정말 끝났는가? (비디오)](https://www.youtube.com/watch?v=z9quxZsLcfo)
    - [ ] [비디오 시리즈 (152 개) - 다 볼 필요 없음 (비디오)](https://www.youtube.com/watch?v=nzJapzxH_rE&list=PLAwxTw4SYaPkWVHeC_8aSIbSxE_NXI76g)
    - [ ] [파이턴과 함께하는 Test-Driven 웹 개발](http://www.obeythetestinggoat.com/pages/book.html#toc)
    - [ ] 의존성 주입:
        - [ ] [비디오](https://www.youtube.com/watch?v=IKD2-MAkXyQ)
        - [ ] [Tao Of Testing](http://jasonpolites.github.io/tao-of-testing/ch3-1.1.html)
    - [ ] [테스트 어떻게 작성하는지](http://jasonpolites.github.io/tao-of-testing/ch4-1.1.html)

- ### 스케쥴링
    - 운영체제에서 스케쥴링이 어떻게 동작하는지
    - 여러 운영체제 비디오에서 배울 수 있음

- ### 시스템 루틴 구현
    - 당신이 보는 프로그래밍 API 밑은 어떻게 되어있는지 이해할 것
    - 직접 구현할 수 있는가?

- ### 문자열 검색 & 다루기
    - [ ] [Sedgewick - Suffix Arrays (video)](https://www.youtube.com/watch?v=HKPrVm5FWvg)
    - [ ] [Sedgewick - Substring Search (videos)](https://www.youtube.com/watch?v=2LvvVFCEIv8&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66&index=5)
        - [ ] [1. Introduction to Substring Search](https://www.youtube.com/watch?v=2LvvVFCEIv8&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66&index=5)
        - [ ] [2. Brute-Force Substring Search](https://www.youtube.com/watch?v=CcDXwIGEXYU&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66&index=4)
        - [ ] [3. Knuth-Morris Pratt](https://www.youtube.com/watch?v=n-7n-FDEWzc&index=3&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66)
        - [ ] [4. Boyer-Moore](https://www.youtube.com/watch?v=fI7Ch6pZXfM&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66&index=2)
        - [ ] [5. Rabin-Karp](https://www.youtube.com/watch?v=QzI0p6zDjK4&index=1&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66)
    - [ ] [Search pattern in text (video)](https://www.coursera.org/learn/data-structures/lecture/tAfHI/search-pattern-in-text)

    이 주제에 대한 더 자세한 정보가 필요하다면 [Additional Detail on Some Subjects](#additional-detail-on-some-subjects)에 있는 "문자열 매칭" 부분을 볼 것.

---

## 시스템 디자인, 확장성, 데이터 핸들링
- **만약 당신이 4년 이상의 경험이 있다면 시스템 디자인에 대한 질문을 받을 수도 있다.**
- 확장 가능한 소프트웨어/하드웨어를 설계하는 것은 많은 것을 고려해야 하기 때문에, 확장성과 시스템 디자인은 다른 많은 주제를 포함한 아주 큰 주제이다. 여기에 꽤 많은 시간을 소비하게 될 것으로 예상된다.
- Yegge가 언급한 것들:
    - 확장성
        - 큰 데이터 셋을 단일 값들로 압축
        - 어떤 데이터를 다른 곳으로 보내는 것
        - 말도안되게 큰 양의 데이터를 다루는 것
    - 시스템 디자인
        - 피처 셋
        - 인터페이스
        - 클래스 계층
        - 임의의 제약사항을 지키며 시스템 디자인하기
        - 단순성과 견고성
        - 트레이드오프
        - 퍼포먼스 분석과 최적화
- [ ] **시작점**: [System Design from HiredInTech](http://www.hiredintech.com/system-design/)
- [ ] [How Do I Prepare To Answer Design Questions In A Technical Inverview?](https://www.quora.com/How-do-I-prepare-to-answer-design-questions-in-a-technical-interview?redirected_qid=1500023)
- [ ] [8 Things You Need to Know Before a System Design Interview](http://blog.gainlo.co/index.php/2015/10/22/8-things-you-need-to-know-before-system-design-interviews/)
- [ ] [Algorithm design](http://www.hiredintech.com/algorithm-design/)
- [ ] [Database Normalization - 1NF, 2NF, 3NF and 4NF (video)](https://www.youtube.com/watch?v=UrYLYV7WSHM)
- [ ] [System Design Interview](https://github.com/checkcheckzz/system-design-interview) - 여기에는 많은 자료가 있다. 수록된 글과 예제를 훑어보라. 나도 몇 가지를 추가했다.
- [ ] [How to ace a systems design interview](http://www.palantir.com/2011/10/how-to-rock-a-systems-design-interview/)
- [ ] [Numbers Everyone Should Know](http://everythingisdata.wordpress.com/2009/10/17/numbers-everyone-should-know/)
- [ ] [How long does it take to make a context switch?](http://blog.tsunanet.net/2010/11/how-long-does-it-take-to-make-context.html)
- [ ] [Transactions Across Datacenters (video)](https://www.youtube.com/watch?v=srOgpXECblk)
- [ ] [A plain English introduction to CAP Theorem](http://ksat.me/a-plain-english-introduction-to-cap-theorem/)
- [ ] Paxos Consensus algorithm:
    - [short video](https://www.youtube.com/watch?v=s8JqcZtvnsM)
    - [extended video with use case and multi-paxos](https://www.youtube.com/watch?v=JEpsBg0AO6o)
    - [paper](http://research.microsoft.com/en-us/um/people/lamport/pubs/paxos-simple.pdf)
- [ ] [Consistent Hashing](http://www.tom-e-white.com/2007/11/consistent-hashing.html)
- [ ] [NoSQL Patterns](http://horicky.blogspot.com/2009/11/nosql-patterns.html)
- [ ] Scalability:
    - [ ] [Great overview (video)](https://www.youtube.com/watch?v=-W9F__D3oY4)
    - [ ] Short series:
        - [Clones](http://www.lecloud.net/post/7295452622/scalability-for-dummies-part-1-clones)
        - [Database](http://www.lecloud.net/post/7994751381/scalability-for-dummies-part-2-database)
        - [Cache](http://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache)
        - [Asynchronism](http://www.lecloud.net/post/9699762917/scalability-for-dummies-part-4-asynchronism)
    - [ ] [Scalable Web Architecture and Distributed Systems](http://www.aosabook.org/en/distsys.html)
    - [ ] [Fallacies of Distributed Computing Explained](https://pages.cs.wisc.edu/~zuyu/files/fallacies.pdf)
    - [ ] [Pragmatic Programming Techniques](http://horicky.blogspot.com/2010/10/scalable-system-design-patterns.html)
        - [extra: Google Pregel Graph Processing](http://horicky.blogspot.com/2010/07/google-pregel-graph-processing.html)
    - [ ] [Jeff Dean - Building Software Systems At Google and Lessons Learned (video)](https://www.youtube.com/watch?v=modXC5IWTJI)
    - [ ] [Introduction to Architecting Systems for Scale](http://lethain.com/introduction-to-architecting-systems-for-scale/)
    - [ ] [Scaling mobile games to a global audience using App Engine and Cloud Datastore (video)](https://www.youtube.com/watch?v=9nWyWwY2Onc)
    - [ ] [How Google Does Planet-Scale Engineering for Planet-Scale Infra (video)](https://www.youtube.com/watch?v=H4vMcD7zKM0)
    - [ ] [The Importance of Algorithms](https://www.topcoder.com/community/data-science/data-science-tutorials/the-importance-of-algorithms/)
    - [ ] [Sharding](http://highscalability.com/blog/2009/8/6/an-unorthodox-approach-to-database-design-the-coming-of-the.html)
    - [ ] [Scale at Facebook (2009)](https://www.infoq.com/presentations/Scale-at-Facebook)
    - [ ] [Scale at Facebook (2012), "Building for a Billion Users" (video)](https://www.youtube.com/watch?v=oodS71YtkGU)
    - [ ] [Engineering for the Long Game - Astrid Atkinson Keynote(video)](https://www.youtube.com/watch?v=p0jGmgIrf_M&list=PLRXxvay_m8gqVlExPC5DG3TGWJTaBgqSA&index=4)
    - [ ] [7 Years Of YouTube Scalability Lessons In 30 Minutes](http://highscalability.com/blog/2012/3/26/7-years-of-youtube-scalability-lessons-in-30-minutes.html)
        - [video](https://www.youtube.com/watch?v=G-lGCC4KKok)
    - [ ] [How PayPal Scaled To Billions Of Transactions Daily Using Just 8VMs](http://highscalability.com/blog/2016/8/15/how-paypal-scaled-to-billions-of-transactions-daily-using-ju.html)
    - [ ] [How to Remove Duplicates in Large Datasets](https://blog.clevertap.com/how-to-remove-duplicates-in-large-datasets/)
    - [ ] [A look inside Etsy's scale and engineering culture with Jon Cowie (video)](https://www.youtube.com/watch?v=3vV4YiqKm1o)
    - [ ] [What Led Amazon to its Own Microservices Architecture](http://thenewstack.io/led-amazon-microservices-architecture/)
    - [ ] [To Compress Or Not To Compress, That Was Uber's Question](https://eng.uber.com/trip-data-squeeze/)
    - [ ] [Asyncio Tarantool Queue, Get In The Queue](http://highscalability.com/blog/2016/3/3/asyncio-tarantool-queue-get-in-the-queue.html)
    - [ ] [When Should Approximate Query Processing Be Used?](http://highscalability.com/blog/2016/2/25/when-should-approximate-query-processing-be-used.html)
    - [ ] [Google's Transition From Single Datacenter, To Failover, To A Native Multihomed Architecture]( http://highscalability.com/blog/2016/2/23/googles-transition-from-single-datacenter-to-failover-to-a-n.html)
    - [ ] [Spanner](http://highscalability.com/blog/2012/9/24/google-spanners-most-surprising-revelation-nosql-is-out-and.html)
    - [ ] [Egnyte Architecture: Lessons Learned In Building And Scaling A Multi Petabyte Distributed System](http://highscalability.com/blog/2016/2/15/egnyte-architecture-lessons-learned-in-building-and-scaling.html)
    - [ ] [Machine Learning Driven Programming: A New Programming For A New World](http://highscalability.com/blog/2016/7/6/machine-learning-driven-programming-a-new-programming-for-a.html)
    - [ ] [The Image Optimization Technology That Serves Millions Of Requests Per Day](http://highscalability.com/blog/2016/6/15/the-image-optimization-technology-that-serves-millions-of-re.html)
    - [ ] [A Patreon Architecture Short](http://highscalability.com/blog/2016/2/1/a-patreon-architecture-short.html)
    - [ ] [Tinder: How Does One Of The Largest Recommendation Engines Decide Who You'll See Next?](http://highscalability.com/blog/2016/1/27/tinder-how-does-one-of-the-largest-recommendation-engines-de.html)
    - [ ] [Design Of A Modern Cache](http://highscalability.com/blog/2016/1/25/design-of-a-modern-cache.html)
    - [ ] [Live Video Streaming At Facebook Scale](http://highscalability.com/blog/2016/1/13/live-video-streaming-at-facebook-scale.html)
    - [ ] [A Beginner's Guide To Scaling To 11 Million+ Users On Amazon's AWS](http://highscalability.com/blog/2016/1/11/a-beginners-guide-to-scaling-to-11-million-users-on-amazons.html)
    - [ ] [How Does The Use Of Docker Effect Latency?](http://highscalability.com/blog/2015/12/16/how-does-the-use-of-docker-effect-latency.html)
    - [ ] [Does AMP Counter An Existential Threat To Google?](http://highscalability.com/blog/2015/12/14/does-amp-counter-an-existential-threat-to-google.html)
    - [ ] [A 360 Degree View Of The Entire Netflix Stack](http://highscalability.com/blog/2015/11/9/a-360-degree-view-of-the-entire-netflix-stack.html)
    - [ ] [Latency Is Everywhere And It Costs You Sales - How To Crush It](http://highscalability.com/latency-everywhere-and-it-costs-you-sales-how-crush-it)
    - [ ] [Serverless (very long, just need the gist)](http://martinfowler.com/articles/serverless.html)
    - [ ] [What Powers Instagram: Hundreds of Instances, Dozens of Technologies](http://instagram-engineering.tumblr.com/post/13649370142/what-powers-instagram-hundreds-of-instances)
    - [ ] [Cinchcast Architecture - Producing 1,500 Hours Of Audio Every Day](http://highscalability.com/blog/2012/7/16/cinchcast-architecture-producing-1500-hours-of-audio-every-d.html)
    - [ ] [Justin.Tv's Live Video Broadcasting Architecture](http://highscalability.com/blog/2010/3/16/justintvs-live-video-broadcasting-architecture.html)
    - [ ] [Playfish's Social Gaming Architecture - 50 Million Monthly Users And Growing](http://highscalability.com/blog/2010/9/21/playfishs-social-gaming-architecture-50-million-monthly-user.html)
    - [ ] [TripAdvisor Architecture - 40M Visitors, 200M Dynamic Page Views, 30TB Data](http://highscalability.com/blog/2011/6/27/tripadvisor-architecture-40m-visitors-200m-dynamic-page-view.html)
    - [ ] [PlentyOfFish Architecture](http://highscalability.com/plentyoffish-architecture)
    - [ ] [Salesforce Architecture - How They Handle 1.3 Billion Transactions A Day](http://highscalability.com/blog/2013/9/23/salesforce-architecture-how-they-handle-13-billion-transacti.html)
    - [ ] [ESPN's Architecture At Scale - Operating At 100,000 Duh Nuh Nuhs Per Second](http://highscalability.com/blog/2013/11/4/espns-architecture-at-scale-operating-at-100000-duh-nuh-nuhs.html)
    - [ ] 서비스를 묶어줄 수 있는 몇몇 기술을 위해서 "메시징, 직렬화, 큐잉 시스템"을 보라.
    - [ ] 트위터:
        - [O'Reilly MySQL CE 2011: Jeremy Cole, "Big and Small Data at @Twitter" (video)](https://www.youtube.com/watch?v=5cKTP36HVgI)
        - [Timelines at Scale](https://www.infoq.com/presentations/Twitter-Timeline-Scalability)
    - 나아가서 비디오 시리즈 섹션에 있는 "거대한 데이터셋 마이닝하기" 비디오를 보라.
- [ ] 시스템 디자인 절차 실습하기. 여기에 실제로는 어떻게 다루어졌는지를 설명하는 문서가 포함된 몇 가지 아이디어가 있다.
    - 복습: [System Design from HiredInTech](http://www.hiredintech.com/system-design/)
    - [cheat sheet](https://github.com/jwasham/coding-interview-university/blob/master/extras/cheat%20sheets/system-design.pdf)
    - 절차:
        1. 문제와 범위를 이해할 것:
            - 면접관이 유도하는대로 사용 예시를 정의할 것.
            - 추가적인 기능을 제시.
            - 면접관의 의도를 넘어가는 내용들은 제거할 것.
            - 고도의 유용성이 요구될 것으로 가정하고, 사용 예시로 추가하라.
        2. 제약 사항에 대해 생각할 것:
            - 월간 얼마나 많은 요청이 발생하는지 질문
            - 초당 얼마나 많은 요청이 발생하는지 질문 (알려줄 수도 있고 직접 계산하게 시킬 수도 있다.)
            - 읽기 vs 쓰기의 비율(%)을 추정할 것
            - 추정할 때는 80/20 규칙을 유념할 것
            - 초당 얼마 만큼의 데이터가 쓰이는지?
            - 5 년간 필요한 저장공간의 총량?
            - 초당 얼마 만큼으 데이터를 읽는지?
        3. 디자인을 추상화할 것:
            - 계층 (서비스, 데이터, 캐싱)
            - 기반 구조: 부하 분산, 메세징
            - 서비스를 운용하는 모든 주요 알고리즘에 대한 대략적인 개요.
            - 병목현상에 대한 고려와 해결책 결정
    - 실습:
        - [Design a CDN network: old article](http://repository.cmu.edu/cgi/viewcontent.cgi?article=2112&context=compsci)
        - [Design a random unique ID generation system](https://blog.twitter.com/2010/announcing-snowflake)
        - [Design an online multiplayer card game](http://www.indieflashblog.com/how-to-create-an-asynchronous-multiplayer-game.html)
        - [Design a key-value database](http://www.slideshare.net/dvirsky/introduction-to-redis)
        - [Design a picture sharing system](http://highscalability.com/blog/2011/12/6/instagram-architecture-14-million-users-terabytes-of-photos.html)
        - [Design a recommendation system](http://ijcai13.org/files/tutorial_slides/td3.pdf)
        - [Design a URL-shortener system: copied from above](http://www.hiredintech.com/system-design/the-system-design-process/)
        - [Design a cache system](https://www.adayinthelifeof.nl/2011/02/06/memcache-internals/)

---

## 최종 검토

    이 섹션에는 중요한 개념들을 빠르게 검토할 수 있는 짧은 영상들이 포함되어 있다.
    복습을 하고자 한다면, 이 영상들이 도움이 될 것이다.

- [ ] 2-3분 분량의 주제별 짧은 영상 시리즈 (23 videos)
    - [Videos](https://www.youtube.com/watch?v=r4r1DZcx1cM&list=PLmVb1OknmNJuC5POdcDv5oCS7_OUkDgpj&index=22)
- [ ] 2-5분 분량의 주제별 짧은 영상 시리즈 - Michael Sambol (18 videos):
    - [Videos](https://www.youtube.com/channel/UCzDJwLWoYCUQowF_nG3m5OQ)
- [ ] [Sedgewick Videos - Algorithms I](https://www.youtube.com/user/algorithmscourses/playlists?shelf_id=2&view=50&sort=dd)
    - [ ] [01. Union-Find](https://www.youtube.com/watch?v=8mYfZeHtdNc&list=PLe-ggMe31CTexoNYnMhbHaWhQ0dvcy43t)
    - [ ] [02. Analysis of Algorithms](https://www.youtube.com/watch?v=ZN-nFW0mEpg&list=PLe-ggMe31CTf0_bkOhh7sa5uqeppp3Sr0)
    - [ ] [03. Stacks and Queues](https://www.youtube.com/watch?v=TIC1gappbP8&list=PLe-ggMe31CTe-9jhnj3P_3mmrCh0A7iHh)
    - [ ] [04. Elementary Sorts](https://www.youtube.com/watch?v=CD2AL6VO0ak&list=PLe-ggMe31CTe_5WhGV0F--7CK8MoRUqBd)
    - [ ] [05. Mergesort](https://www.youtube.com/watch?v=4nKwesx_c8E&list=PLe-ggMe31CTeunC6GZHFBmQx7EKtjbGf9)
    - [ ] [06. Quicksort](https://www.youtube.com/watch?v=5M5A7qPWk84&list=PLe-ggMe31CTeE3x2-nF1-toca1QpuXwE1)
    - [ ] [07. Priority Queues](https://www.youtube.com/watch?v=G9TMe0KC0w0&list=PLe-ggMe31CTducy9LDiGVkdSv0NfiRwn5)
    - [ ] [08. Elementary Symbol Tables](https://www.youtube.com/watch?v=up_nlilw3ac&list=PLe-ggMe31CTc3a8nKRDxFZZrWrBvkc9SG)
    - [ ] [09. Balanced Search Trees](https://www.youtube.com/watch?v=qC1BLLPK_5w&list=PLe-ggMe31CTf7jHH_mFT50kayjCEA6Rhu)
    - [ ] [10. Geometric Applications of BST](https://www.youtube.com/watch?v=Wl30aGAp6TY&list=PLe-ggMe31CTdBsRIw0hXln0hilRs-DqAx)
    - [ ] [11. Hash Tables](https://www.youtube.com/watch?v=QA8fJGO-i9o&list=PLe-ggMe31CTcKxIRGqqThMts2eHtSrf11)
- [ ] [Sedgewick Videos - Algorithms II](https://www.youtube.com/user/algorithmscourses/playlists?flow=list&shelf_id=3&view=50)
    - [ ] [01. Undirected Graphs](https://www.youtube.com/watch?v=GmVhD-mmMBg&list=PLe-ggMe31CTc0zDzANxl4I2MhMoRVlbRM)
    - [ ] [02. Directed Graphs](https://www.youtube.com/watch?v=_z-JsVaUS40&list=PLe-ggMe31CTcEwaU8a1P1Gd95A77HV85K)
    - [ ] [03. Minimum Spanning Trees](https://www.youtube.com/watch?v=t8fNk9tfVYY&list=PLe-ggMe31CTceUZxDesGfHGLE7kcSafqj)
    - [ ] [04. Shortest Paths](https://www.youtube.com/watch?v=HoGSiB7tSeI&list=PLe-ggMe31CTePpG3jbeOTsnGUGZDKxgZD)
    - [ ] [05. Maximum Flow](https://www.youtube.com/watch?v=rYIKlFstBqE&list=PLe-ggMe31CTduQ68XQ-sVj32wYJIspTma)
    - [ ] [06. Radix Sorts](https://www.youtube.com/watch?v=HKPrVm5FWvg&list=PLe-ggMe31CTcNvUX9E3tQeM6ntrdR8e53)
    - [ ] [07. Tries](https://www.youtube.com/watch?v=00YaFPcC65g&list=PLe-ggMe31CTe9IyG9MB8vt5xUJeYgOYRQ)
    - [ ] [08. Substring Search](https://www.youtube.com/watch?v=QzI0p6zDjK4&list=PLe-ggMe31CTdAdjXB3lIuf2maubzo9t66)
    - [ ] [09. Regular Expressions](https://www.youtube.com/watch?v=TQWNQsJSPnk&list=PLe-ggMe31CTetTlJWouM42fyttyKPgSDh)
    - [ ] [10. Data Compression](https://www.youtube.com/watch?v=at9tjpxcBh8&list=PLe-ggMe31CTciifRRo6yY0Yt0mzgIXXVZ)
    - [ ] [11. Reductions](https://www.youtube.com/watch?v=Ow5x-ooMGv8&list=PLe-ggMe31CTe_yliW5vc3yO-dj1LSSDyF)
    - [ ] [12. Linear Programming](https://www.youtube.com/watch?v=rWhcLyiLZLA&list=PLe-ggMe31CTdy6dKzMgkWFuTTN1H8B-E1)
    - [ ] [13. Intractability](https://www.youtube.com/watch?v=6qcaaDp4cdQ&list=PLe-ggMe31CTcZCjluBHw53e_ek2k9Kn-S)

---

## 코딩 문제 연습

이제 당신은 위의 컴퓨터 과학 주제들을 모두 알고 있으므로, 코딩 문제에 답하는 것을 연습할 차례이다.

**코딩 문제 연습은 프로그래밍 문제에 대한 답을 외우는 것이 아니다.**

당신에게 프로그래밍 문제를 푸는 연습이 필요한 이유:
- 문제 인식, 그리고 어떤 자료구조와 알고리즘이 언제 필요한지
- 문제의 조건을 모으기
- 인터뷰를 하듯 당신이 문제를 푸는 과정을 말하기
- 컴퓨터가 아닌 종이나 화이트보드에 코딩하기
- 당신의 풀이의 시간, 공간 복잡도를 제시하기
- 당신의 해답을 테스팅하기


체계적이고 소통하는 인터뷰에서의 문제풀이에 관한 좋은 시작점이 있다. 당신은 프로그래밍 인터뷰 책에서 이 서식을 얻을 수도 있지만, 나는 이 것이 가장 좋다고 본다: [Algorithm design canvas](http://www.hiredintech.com/algorithm-design/)

[My Process for Coding Interview (Book) Exercises](https://googleyasheck.com/my-process-for-coding-interview-exercises/)

집에 화이트보드가 없는가? 그럴 수 있다. 나는 커다란 화이트보드를 가진 괴짜이다. 화이트보드 대신에 상점에서 큰 도화지를 사오자.
소파에 앉아서 연습할 수 있다. 이 것은 내 "소파 화이트보드"이다. 크기 비교를 위해 사진에 펜을 추가하였다. 펜을 쓰면, 곧 지우고 싶어질 것이다.
금방 지저분해 진다.

![my sofa whiteboard](https://dng5l3qzreal6.cloudfront.net/2016/Oct/art_board_sm_2-1476233630368.jpg)

보충:

- [Mathematics for Topcoders](https://www.topcoder.com/community/data-science/data-science-tutorials/mathematics-for-topcoders/)
- [Dynamic Programming – From Novice to Advanced](https://www.topcoder.com/community/data-science/data-science-tutorials/dynamic-programming-from-novice-to-advanced/)
- [MIT Interview Materials](https://web.archive.org/web/20160906124824/http://courses.csail.mit.edu/iap/interview/materials.php)
- [Exercises for getting better at a given language](http://exercism.io/languages)

**읽고 프로그래밍 문제 풀기 (순서대로):**

- [ ] [Programming Interviews Exposed: Secrets to Landing Your Next Job, 2nd Edition](http://www.wiley.com/WileyCDA/WileyTitle/productCd-047012167X.html)
    - answers in C, C++ and Java
- [ ] [Cracking the Coding Interview, 6th Edition](http://www.amazon.com/Cracking-Coding-Interview-6th-Programming/dp/0984782850/)
    - answers in Java

[위의 도서 목록](#book-list)을 보라

## Coding exercises/challenges

당신의 머리가 녹슬었다는 것을 알아차렸다면, 뇌가 다시 일하게 만들어라.
코딩 챌린지를 매일같이 할수있는 한 많이 하라.

- [ ] [How to Find a Solution](https://www.topcoder.com/community/data-science/data-science-tutorials/how-to-find-a-solution/)
- [ ] [How to Dissect a Topcoder Problem Statement](https://www.topcoder.com/community/data-science/data-science-tutorials/how-to-dissect-a-topcoder-problem-statement/)

챌린지 사이트들:
- [LeetCode](https://leetcode.com/)
- [TopCoder](https://www.topcoder.com/)
- [Project Euler (math-focused)](https://projecteuler.net/index.php?section=problems)
- [Codewars](http://www.codewars.com)
- [HackerRank](https://www.hackerrank.com/)
- [Codility](https://codility.com/programmers/)
- [InterviewCake](https://www.interviewcake.com/)
- [Geeks for Geeks](http://www.geeksforgeeks.org/)
- [InterviewBit](https://www.interviewbit.com/invite/icjf)

Maybe:
- [Mock interviewers from big companies](http://www.gainlo.co/)

## 면접 날이 가까워온다면

- [ ] Cracking The Coding Interview Set 2 (videos):
    - [Cracking The Code Interview](https://www.youtube.com/watch?v=4NIb9l3imAo)
    - [Cracking the Coding Interview - Fullstack Speaker Series](https://www.youtube.com/watch?v=Eg5-tdAwclo)
    - [Ask Me Anything: Gayle Laakmann McDowell (author of Cracking the Coding Interview)](https://www.youtube.com/watch?v=1fqxMuPmGak)

## 이력서

- [Ten Tips for a (Slightly) Less Awful Resume](http://steve-yegge.blogspot.co.uk/2007_09_01_archive.html)
- See Resume prep items in Cracking The Coding Interview and back of Programming Interviews Exposed


## 인터뷰가 다가오면 생각해보기

아래의 아이템들에 따른 너가 받을 20개의 인터뷰 질문에 대해 생각하라. 각각 2-3개의 대답을 준비해라.
당신이 성취한 것에 대해 데이터 뿐만 아니라 스토리를 만들어라.

- 왜 이 직업을 원합니까?
- 당신이 풀었던 문제중 힘들었던 문제는?
- 큰 도전에 직면한 적은?
- 최고의/최악의 디자인을 본적이 있는가?
- 현존하는 구글 제품들에 대해 향상시킬수 있는 아이디어
- 개인적으로 일할 때 가장 잘 일하는가? 아니면 팀원으로서 있을 때?
- 어떤 기술과 경험들이 당신의 역할에서 자산이 되었으며 그 이유는?
- 어떤 것이 가장 즐거웠는가 [job x / project y]?
- 무엇이 가장 큰 도전이었는가 [job x / project y]?
- 무엇이 가장 힘들었던 버그였는가? [job x / project y]?
- 무엇을 배웠는가 [job x / project y]?
- 무엇이 향상되었는가 [job x / project y]?

## 면접관에게 질문하기

    내가 했던 질문들 일부분 (대답은 이미 어느정도 알고 있었지만 면접관의 의견이나 팀의 관점을 알고싶었다.):

- 당신의 팀은 어느정도 크기입니까?
- 여러분의 개발 사이클은 어떤 형태입니까? 여러분은 폭포수/스프린트/애자일 모델을 사용합니까?
- 보통 데드라인에 쫓깁니까, 아니면 어느정도 유도리가 있습니까?
- 당신의 팀에서는 결정이 어떻게 이루어집니까?
- 여러분은 한 주에 몇 번 정도 미팅을 합니까?
- 당신은 당신네 업무 환경이 당신이 집중하는 것을 도와준다고 느낍니까?
- 당신은 어떤 일을 하고있습니까?
- 그 일의 어떤 점을 좋아합니까?
- 직장 생활은 어떻습니까?

## 취직에 성공했다면

축하합니다!

- [10 things I wish I knew on my first day at Google](https://medium.com/@moonstorming/10-things-i-wish-i-knew-on-my-first-day-at-google-107581d87286#.livxn7clw)

계속 공부합시다.

절대로 진짜 끝난건 아닙니다.

---

    *****************************************************************************************************
    *****************************************************************************************************


    아래의 모든 것들은 선택 사항이다. 이 것들은 Google의 권장사항이 아니라, 나의 추천사항이다.
    당신은 이것들을 공부함으로써 더 많은 CS 개념들에 대해 알 수 있을 것이며, 소프트웨어 엔지니어링 직업을 준비하는 데에도 도움이 될 것
    이다. 더불어 당신은 훨씬 더 균형 잡힌 소프트웨어 엔지니어가 될 것이다.


    *****************************************************************************************************
    *****************************************************************************************************

---

## 추가적인 책들

- [ ] [The Unix Programming Environment](http://product.half.ebay.com/The-UNIX-Programming-Environment-by-Brian-W-Kernighan-and-Rob-Pike-1983-Other/54385&tg=info)
    - 구관이 명관이다.
- [ ] [The Linux Command Line: A Complete Introduction](https://www.amazon.com/dp/1593273894/)
    - 모던한 선택지
- [ ] [TCP/IP Illustrated Series](https://en.wikipedia.org/wiki/TCP/IP_Illustrated)
- [ ] [Head First Design Patterns](https://www.amazon.com/gp/product/0596007124/)
    - 디자인 패턴에 대한 친절한 소개
- [ ] [Design Patterns: Elements of Reusable Object-Oriente​d Software](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612)
    - "Gang Of Four" 또는 or GOF 로도 알려져있는 책.
    - 디자인 패턴의 정규 교과서
- [ ] [Site Reliability Engineering](https://landing.google.com/sre/book.html)
    - [Site Reliability Engineering: How Google Runs Production Systems](https://landing.google.com/sre/)
- [ ] [UNIX and Linux System Administration Handbook, 4th Edition](https://www.amazon.com/UNIX-Linux-System-Administration-Handbook/dp/0131480057/)

## 추가적으로 배울 것들

- ### 컴파일러
    - [ ] [How a Compiler Works in ~1 minute (video)](https://www.youtube.com/watch?v=IhC7sdYe-Jg)
    - [ ] [Harvard CS50 - Compilers (video)](https://www.youtube.com/watch?v=CSZLNYF4Klo)
    - [ ] [C++ (video)](https://www.youtube.com/watch?v=twodd1KFfGk)
    - [ ] [Understanding Compiler Optimization (C++) (video)](https://www.youtube.com/watch?v=FnGCDLhaxKU)

- ### 부동소수점 수
    - [ ] simple 8-bit: [Representation of Floating Point Numbers - 1 (video - there is an error in calculations - see video description)](https://www.youtube.com/watch?v=ji3SfClm8TU)
    - [ ] 32 bit: [IEEE754 32-bit floating point binary (video)](https://www.youtube.com/watch?v=50ZYcZebIec)

- ### 유니코드
    - [ ] [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets]( http://www.joelonsoftware.com/articles/Unicode.html)
    - [ ] [What Every Programmer Absolutely, Positively Needs To Know About Encodings And Character Sets To Work With Text](http://kunststube.net/encoding/)

- ### 엔디안
    - [ ] [Big And Little Endian](https://www.cs.umd.edu/class/sum2003/cmsc311/Notes/Data/endian.html)
    - [ ] [Big Endian Vs Little Endian (video)](https://www.youtube.com/watch?v=JrNF0KRAlyo)
    - [ ] [Big And Little Endian Inside/Out (video)](https://www.youtube.com/watch?v=oBSuXP-1Tc0)
        - 커널 개발에 대한 굉장히 기술적인 이야기. 대부분의 이야기를 알아듣지 못해도 너무 염려하지 마라.
        - 앞쪽 절반 정도면 충분하다.

- ### Emacs 와 vi(m)
    - Yegge가 오래전 Amazon 채용 포스트에서 제안한 것: 유닉스 기반의 코드 에디터에 익숙해져라.
    - vi(m):
        - [Editing With vim 01 - Installation, Setup, and The Modes (video)](https://www.youtube.com/watch?v=5givLEMcINQ&index=1&list=PL13bz4SHGmRxlZVmWQ9DvXo1fEg4UdGkr)
        - [VIM Adventures](http://vim-adventures.com/)
        - set of 4 videos:
            - [The vi/vim editor - Lesson 1](https://www.youtube.com/watch?v=SI8TeVMX8pk)
            - [The vi/vim editor - Lesson 2](https://www.youtube.com/watch?v=F3OO7ZIOaJE)
            - [The vi/vim editor - Lesson 3](https://www.youtube.com/watch?v=ZYEccA_nMaI)
            - [The vi/vim editor - Lesson 4](https://www.youtube.com/watch?v=1lYD5gwgZIA)
        - [Using Vi Instead of Emacs](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#Using_Vi_instead_of_Emacs)
    - emacs:
        - [Basics Emacs Tutorial (video)](https://www.youtube.com/watch?v=hbmV1bnQ-i0)
        - set of 3 (videos):
            - [Emacs Tutorial (Beginners) -Part 1- File commands, cut/copy/paste, cursor commands](https://www.youtube.com/watch?v=ujODL7MD04Q)
            - [Emacs Tutorial (Beginners) -Part 2- Buffer management, search, M-x grep and rgrep modes](https://www.youtube.com/watch?v=XWpsRupJ4II)
            - [Emacs Tutorial (Beginners) -Part 3- Expressions, Statements, ~/.emacs file and packages](https://www.youtube.com/watch?v=paSgzPso-yc)
        - [Evil Mode: Or, How I Learned to Stop Worrying and Love Emacs (video)](https://www.youtube.com/watch?v=JWD1Fpdd4Pc)
        - [Writing C Programs With Emacs](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#Writing_C_programs_with_Emacs)
        - [(maybe) Org Mode In Depth: Managing Structure (video)](https://www.youtube.com/watch?v=nsGYet02bEk)

- ### 유닉스 커맨드 라인 툴들
    - Yegge가 오래전 Amazon 채용 포스트에서 제안한 것: 나는 아래의 목록을 괜찮은 툴들로 채워넣었다.
    - [ ] bash
    - [ ] cat
    - [ ] grep
    - [ ] sed
    - [ ] awk
    - [ ] curl or wget
    - [ ] sort
    - [ ] tr
    - [ ] uniq
    - [ ] [strace](https://en.wikipedia.org/wiki/Strace)
    - [ ] [tcpdump](https://danielmiessler.com/study/tcpdump/)

- ### 정보 이론 (비디오)
    - [ ] [Khan Academy](https://www.khanacademy.org/computing/computer-science/informationtheory)
    - [ ] 마르코프 과정에 대한 추가적인 내용:
        - [ ] [Core Markov Text Generation](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/waxgx/core-markov-text-generation)
        - [ ] [Core Implementing Markov Text Generation](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/gZhiC/core-implementing-markov-text-generation)
        - [ ] [Project = Markov Text Generation Walk Through](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/EUjrq/project-markov-text-generation-walk-through)
    - 아래의 MIT 6.050J Information and Entropy 시리즈 내용을 보라.

- ### 패리티 & 해밍 부호 (비디오)
    - [ ] [Intro](https://www.youtube.com/watch?v=q-3BctoUpHE)
    - [ ] [Parity](https://www.youtube.com/watch?v=DdMcAUlxh1M)
    - [ ] 해밍 부호:
        - [Error detection](https://www.youtube.com/watch?v=1A_NcXxdoCc)
        - [Error correction](https://www.youtube.com/watch?v=JAMLuxdHH8o)
    - [ ] [Error Checking](https://www.youtube.com/watch?v=wbH2VxzmoZk)

- ### 엔트로피
    - 마찬가지로 아래 비디오를 보라.
    - 정보 이론 비디오를 먼저 볼 것
    - [ ] [Information Theory, Claude Shannon, Entropy, Redundancy, Data Compression & Bits (video)](https://youtu.be/JnJq3Py0dyM?t=176)

- ### 암호학
    - 마찬가지로 아래 비디오를 보라.
    - 정보 이론 비디오를 먼저 볼 것
    - [ ] [Khan Academy Series](https://www.khanacademy.org/computing/computer-science/cryptography)
    - [ ] [Cryptography: Hash Functions](https://www.youtube.com/watch?v=KqqOXndnvic&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=30)
    - [ ] [Cryptography: Encryption](https://www.youtube.com/watch?v=9TNI2wHmaeI&index=31&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)

- ### 압축
    - 정보 이론 비디오를 먼저 볼 것
    - [ ] Computerphile (videos):
        - [ ] [Compression](https://www.youtube.com/watch?v=Lto-ajuqW3w)
        - [ ] [Entropy in Compression](https://www.youtube.com/watch?v=M5c_RFKVkko)
        - [ ] [Upside Down Trees (Huffman Trees)](https://www.youtube.com/watch?v=umTbivyJoiI)
        - [ ] [EXTRA BITS/TRITS - Huffman Trees](https://www.youtube.com/watch?v=DV8efuB3h2g)
        - [ ] [Elegant Compression in Text (The LZ 77 Method)](https://www.youtube.com/watch?v=goOa3DGezUA)
        - [ ] [Text Compression Meets Probabilities](https://www.youtube.com/watch?v=cCDCfoHTsaU)
    - [ ] [Compressor Head videos](https://www.youtube.com/playlist?list=PLOU2XLYxmsIJGErt5rrCqaSGTMyyqNt2H)
    - [ ] [(optional) Google Developers Live: GZIP is not enough!](https://www.youtube.com/watch?v=whGwm0Lky2s)

- ### 네트워크
    - **네트워크 분야 경험이 있거나 시스템 엔지니어가 되려고 한다면 질문이 예상됨.**
    - 그렇지 않다면 알아두면 좋은 정도임
    - [ ] [Khan Academy](https://www.khanacademy.org/computing/computer-science/internet-intro)
    - [ ] [UDP and TCP: Comparison of Transport Protocols](https://www.youtube.com/watch?v=Vdc8TCESIg8)
    - [ ] [TCP/IP and the OSI Model Explained!](https://www.youtube.com/watch?v=e5DEVa9eSN0)
    - [ ] [Packet Transmission across the Internet. Networking & TCP/IP tutorial.](https://www.youtube.com/watch?v=nomyRJehhnM)
    - [ ] [HTTP](https://www.youtube.com/watch?v=WGJrLqtX7As)
    - [ ] [SSL and HTTPS](https://www.youtube.com/watch?v=S2iBR2ZlZf0)
    - [ ] [SSL/TLS](https://www.youtube.com/watch?v=Rp3iZUvXWlM)
    - [ ] [HTTP 2.0](https://www.youtube.com/watch?v=E9FxNzv1Tr8)
    - [ ] [Video Series (21 videos)](https://www.youtube.com/playlist?list=PLEbnTDJUr_IegfoqO4iPnPYQui46QqT0j)
    - [ ] [Subnetting Demystified - Part 5 CIDR Notation](https://www.youtube.com/watch?v=t5xYI0jzOf4)

- ### 컴퓨터 보안
    - [MIT (23 videos)](https://www.youtube.com/playlist?list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [ ] [Introduction, Threat Models](https://www.youtube.com/watch?v=GqmQg-cszw4&index=1&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [ ] [Control Hijacking Attacks](https://www.youtube.com/watch?v=6bwzNg5qQ0o&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh&index=2)
        - [ ] [Buffer Overflow Exploits and Defenses](https://www.youtube.com/watch?v=drQyrzRoRiA&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh&index=3)
        - [ ] [Privilege Separation](https://www.youtube.com/watch?v=6SIJmoE9L9g&index=4&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [ ] [Capabilities](https://www.youtube.com/watch?v=8VqTSY-11F4&index=5&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [ ] [Sandboxing Native Code](https://www.youtube.com/watch?v=VEV74hwASeU&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh&index=6)
        - [ ] [Web Security Model](https://www.youtube.com/watch?v=chkFBigodIw&index=7&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [ ] [Securing Web Applications](https://www.youtube.com/watch?v=EBQIGy1ROLY&index=8&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [ ] [Symbolic Execution](https://www.youtube.com/watch?v=yRVZPvHYHzw&index=9&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [ ] [Network Security](https://www.youtube.com/watch?v=SIEVvk3NVuk&index=11&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [ ] [Network Protocols](https://www.youtube.com/watch?v=QOtA76ga_fY&index=12&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)
        - [ ] [Side-Channel Attacks](https://www.youtube.com/watch?v=PuVMkSEcPiI&index=15&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)

- ### 가비지 콜렉션
    - [ ] [Garbage collection (Java); Augmenting data str (video)](https://www.youtube.com/watch?v=StdfeXaKGEc&list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd&index=25)
    - [ ] [Compilers (video)](https://www.youtube.com/playlist?list=PLO9y7hOkmmSGTy5z6HZ-W4k2y8WXF7Bff)
    - [ ] [GC in Python (video)](https://www.youtube.com/watch?v=iHVs_HkjdmI)
    - [ ] [Deep Dive Java: Garbage Collection is Good!](https://www.infoq.com/presentations/garbage-collection-benefits)
    - [ ] [Deep Dive Python: Garbage Collection in CPython (video)](https://www.youtube.com/watch?v=P-8Z0-MhdQs&list=PLdzf4Clw0VbOEWOS_sLhT_9zaiQDrS5AR&index=3)

- ### 벙렬 컴퓨팅
    - [ ] [Coursera (Scala)](https://www.coursera.org/learn/parprog1/home/week/1)
    - [ ] [Efficient Python for High Performance Parallel Computing (video)](https://www.youtube.com/watch?v=uY85GkaYzBk)

- ### 메시징, 직렬화, 큐잉 시스템
    - [ ] [Thrift](https://thrift.apache.org/)
        - [Tutorial](http://thrift-tutorial.readthedocs.io/en/latest/intro.html)
    - [ ] [Protocol Buffers](https://developers.google.com/protocol-buffers/)
        - [Tutorials](https://developers.google.com/protocol-buffers/docs/tutorials)
    - [ ] [gRPC](http://www.grpc.io/)
        - [gRPC 101 for Java Developers (video)](https://www.youtube.com/watch?v=5tmPvSe7xXQ&list=PLcTqM9n_dieN0k1nSeN36Z_ppKnvMJoly&index=1)
    - [ ] [Redis](http://redis.io/)
        - [Tutorial](http://try.redis.io/)
    - [ ] [Amazon SQS (queue)](https://aws.amazon.com/sqs/)
    - [ ] [Amazon SNS (pub-sub)](https://aws.amazon.com/sns/)
    - [ ] [RabbitMQ](https://www.rabbitmq.com/)
        - [Get Started](https://www.rabbitmq.com/getstarted.html)
    - [ ] [Celery](http://www.celeryproject.org/)
        - [First Steps With Celery](http://docs.celeryproject.org/en/latest/getting-started/first-steps-with-celery.html)
    - [ ] [ZeroMQ](http://zeromq.org/)
        - [Intro - Read The Manual](http://zeromq.org/intro:read-the-manual)
    - [ ] [ActiveMQ](http://activemq.apache.org/)
    - [ ] [Kafka](http://kafka.apache.org/documentation.html#introduction)
    - [ ] [MessagePack](http://msgpack.org/index.html)
    - [ ] [Avro](https://avro.apache.org/)

- ### Fast Fourier Transform
    - [ ] [An Interactive Guide To The Fourier Transform](https://betterexplained.com/articles/an-interactive-guide-to-the-fourier-transform/)
    - [ ] [What is a Fourier transform? What is it used for?](http://www.askamathematician.com/2012/09/q-what-is-a-fourier-transform-what-is-it-used-for/)
    - [ ] [What is the Fourier Transform? (video)](https://www.youtube.com/watch?v=Xxut2PN-V8Q)
    - [ ] [Divide & Conquer: FFT (video)](https://www.youtube.com/watch?v=iTMn0Kt18tg&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=4)
    - [ ] [Understanding The FFT](http://jakevdp.github.io/blog/2013/08/28/understanding-the-fft/)

- ### 블룸 필터
    - m 개의 비트와 k 라는 해시 함수가 주어졌을 때, 블룸 필터의 삽입과 이미 삽입됐는지 확인하는 데에 O(k).
    - [Bloom Filters](https://www.youtube.com/watch?v=-SuTGoFYjZs)
    - [Bloom Filters | Mining of Massive Datasets | Stanford University](https://www.youtube.com/watch?v=qBTdukbzc78)
    - [Tutorial](http://billmill.org/bloomfilter-tutorial/)
    - [How To Write A Bloom Filter App](http://blog.michaelschmatz.com/2016/04/11/how-to-write-a-bloom-filter-cpp/)

- ### HyperLogLog
    - [How To Count A Billion Distinct Objects Using Only 1.5KB Of Memory](http://highscalability.com/blog/2012/4/5/big-data-counting-how-to-count-a-billion-distinct-objects-us.html)

- ### Locality-Sensitive Hashing
    - 문서의 유사도를 결정하기 위해 쓰임
    - 문서나 문자열이 정확하게 같은지 판단하는 MD5나 SHA와 반대되는 개념.
    - [Simhashing (hopefully) made simple](http://ferd.ca/simhashing-hopefully-made-simple.html)

- ### van Emde Boas Trees
    - [ ] [Divide & Conquer: van Emde Boas Trees (video)](https://www.youtube.com/watch?v=hmReJCupbNU&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=6)
    - [ ] [MIT Lecture Notes](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2012/lecture-notes/MIT6_046JS12_lec15.pdf)

- ### Augmented Data Structures
    - [ ] [CS 61B Lecture 39: Augmenting Data Structures](https://youtu.be/zksIj9O8_jc?list=PL4BBB74C7D2A1049C&t=950)

- ### 트라이(Trie)
    - 서로 다른 종류의 트라이가 있음에 주의. Note there are different kinds of tries. Prefix가 있는 것도 있고 없는 것도 있으며 어떤 것은 경로를 추적하기 위해 비트 대신 문자열을 사용한다.
    - 나는 코드를 읽어봤지만 구현하지는 않을 것이다.
    - [ ] [Sedgewick - Tries (3 videos)](https://www.youtube.com/playlist?list=PLe-ggMe31CTe9IyG9MB8vt5xUJeYgOYRQ)
        - [ ] [1. R Way Tries](https://www.youtube.com/watch?v=buq2bn8x3Vo&index=3&list=PLe-ggMe31CTe9IyG9MB8vt5xUJeYgOYRQ)
        - [ ] [2. Ternary Search Tries](https://www.youtube.com/watch?v=LelV-kkYMIg&index=2&list=PLe-ggMe31CTe9IyG9MB8vt5xUJeYgOYRQ)
        - [ ] [3. Character Based Operations](https://www.youtube.com/watch?v=00YaFPcC65g&list=PLe-ggMe31CTe9IyG9MB8vt5xUJeYgOYRQ&index=1)
    - [ ] [Notes on Data Structures and Programming Techniques](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#Tries)
    - [ ] Short course videos:
        - [ ] [Introduction To Tries (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/08Xyf/core-introduction-to-tries)
        - [ ] [Performance Of Tries (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/PvlZW/core-performance-of-tries)
        - [ ] [Implementing A Trie (video)](https://www.coursera.org/learn/data-structures-optimizing-performance/lecture/DFvd3/core-implementing-a-trie)
    - [ ] [The Trie: A Neglected Data Structure](https://www.toptal.com/java/the-trie-a-neglected-data-structure)
    - [ ] [TopCoder - Using Tries](https://www.topcoder.com/community/data-science/data-science-tutorials/using-tries/)
    - [ ] [Stanford Lecture (real world use case) (video)](https://www.youtube.com/watch?v=TJ8SkcUSdbU)
    - [ ] [MIT, Advanced Data Structures, Strings (can get pretty obscure about halfway through)](https://www.youtube.com/watch?v=NinWEPPrkDQ&index=16&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf)

- ### 균형 탐색 트리
    - 최소한 하나의 균형 이진 트리에 해당하는 트리를 숙지해둬라(구현할 줄도 알아야 함):
    - "균형 탐색 트리 중에서, AVL과 2/3 트리는 유행이 지났다. 레드-블랙 트리가 더 유명하다.
        특히 흥미로운 자기-조직적인 데이터 구조로 루트에서 다른 키로 접근하기 위해 회전을 사용하는 splay 트리가 있다." - Skiena
    - 이 중에서 나는 splay tree를 구현하기로 했다. 내가 읽은 바에 의하면, 당신은 면접에서 균형 탐색 트리를 구현하지는 않을 것이다. 하지만 나는 뭔가를 구현하는 상황에 노출되고 그 상황에 맞서고 싶었고, splay tree가 아주 매력적이었다. 또 레드-블랙 트리 코드를 아주 많이 읽었다.
        - splay tree: 삽입, 탐색, 삭제 기능
        당신이 레드-블랙 트리 구현을 끝마쳤다면 이것을 시도해보라:
        - 탐색 및 삽입 기능, 삭제는 논외
    - B-Tree가 큰 데이터 셋에서 널리 쓰이기 때문에 B-Tree에 대해 더 배우고자 했다.
    - [ ] [Self-balancing binary search tree](https://en.wikipedia.org/wiki/Self-balancing_binary_search_tree)

    - [ ] **AVL trees**
        - 실제에서:
            내가 말할 수 있는 것은, AVL 트리가 실제로 많이 쓰이지는 않지만 나는 이게 어디에 쓰여야 하는지는 알 수 있다.
            AVL 트리는 탐색, 삽입, 삭제에 O(log n)의 성능을 내는 또 하나의 구조이다. AVL 트리는 레드-블랙 트리보다 강하게 균형잡혀 있기 때문에 삽입과 삭제는 좀 더 느리지만 탐색은 좀 더 빠르다. 이런 특성 때문에 사전과 같이 한번 만들어지고 나면 재구성되는 일 없이 쓰이는 자료 구조에 어울린다(또는 어셈블러나 인터프리터의 명령 코드에 대한 프로그램 사전 같은 것이 해당됨).
        - [ ] [MIT AVL Trees / AVL Sort (video)](https://www.youtube.com/watch?v=FNeL18KsWPc&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=6)
        - [ ] [AVL Trees (video)](https://www.coursera.org/learn/data-structures/lecture/Qq5E0/avl-trees)
        - [ ] [AVL Tree Implementation (video)](https://www.coursera.org/learn/data-structures/lecture/PKEBC/avl-tree-implementation)
        - [ ] [Split And Merge](https://www.coursera.org/learn/data-structures/lecture/22BgE/split-and-merge)

    - [ ] **Splay trees**
        - 실제에서:
            Splay tree는 주로 캐시, 메모리 할당, 라우터, 가비지 콜렉터, 데이터 압축, 로프(길이가 긴 문자열을 대체하는 자료구조), Windows NT(가상 메모리, 네트워크, 파일 시스템 코드) 등에서 쓰인다.
        - [ ] [CS 61B: Splay Trees (video)](https://www.youtube.com/watch?v=Najzh1rYQTo&index=23&list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd)
        - [ ] MIT Lecture: Splay Trees:
            - 내용이 굉장히 수학적이지만 뒤 쪽 10분 정도는 꼭 볼 것.
            - [Video](https://www.youtube.com/watch?v=QnPl_Y6EqMo)

    - [ ] **레드-블랙 트리**
        - 이것은 2-3 트리의 변형이다 (아래를 보라).
        - 실제에서:
            레드-블랙 트리는 삽입, 삭제, 탐색에서 최악의 경우일 때의 성능을 보장한다.
            이러한 보장은 리얼타임 어플리케이션 같이 시간이 민감한 곳에서 중요할 뿐 만 아니라, 다른 최악의 경우를 보장하는 자료 구조의 구성 요소로 쓰이게끔 한다.
            예를 들어, 계산 기하학에 쓰이는 많은 자료 구조들이 레드-블랙 트리로 만들어질 수 있고, 현재 리눅스 커널의 Completely Fair Scheduler도 레드-블랙 트리를 사용한다. 자바 버전 8의 경우에는 해시맵 컬렉션이 해시코드를 개별 요소로 링크드 리스트에 저장하던 방식에서 레드-블랙 트리를 사용하는 방식으로 변경되었다.
        - [ ] [Aduni - Algorithms - Lecture 4 (link jumps to starting point) (video)](https://youtu.be/1W3x0f_RmUo?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3871)
        - [ ] [Aduni - Algorithms - Lecture 5 (video)](https://www.youtube.com/watch?v=hm2GHwyKF1o&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=5)
        - [ ] [Black Tree](https://en.wikipedia.org/wiki/Red%E2%80%93black_tree)
        - [ ] [An Introduction To Binary Search And Red Black Tree](https://www.topcoder.com/community/data-science/data-science-tutorials/an-introduction-to-binary-search-and-red-black-trees/)

    - [ ] **2-3 탐색 트리**
        - 실제에서:
            2-3 트리는 탐색이 느려진 대신 삽입이 빨라졌다. (AVL 트리에 비해서 높이가 더 높을 수 있기 때문).
        - 2-3 트리는 구현할 때 다른 타입의 노드를 포함하기 때문에, 당신은 2-3 트리를 거의 사용하지 않아야 한다. 대신 사람들은 레드-블랙 트리를 사용하곤 한다.
        - [ ] [23-Tree Intuition and Definition (video)](https://www.youtube.com/watch?v=C3SsdUqasD4&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=2)
        - [ ] [Binary View of 23-Tree](https://www.youtube.com/watch?v=iYvBtGKsqSg&index=3&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [ ] [2-3 Trees (student recitation) (video)](https://www.youtube.com/watch?v=TOb1tuEZ2X4&index=5&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)

    - [ ] **2-3-4 트리 (2-4 트리로도 알려짐)**
        - 실제에서:
            모든 2-4 트리에는 같은 순서로 데이터가 배치된 상응하는 레드-블랙 트리가 존재한다. 2-4 트리에서의 삽입과 삭제는 레드-블랙 트리에서의 색 바꾸기와 회전과 동일하다. 이러한 점이 2-4 트리를 레드-블랙 트리의 밑에 깔려있는 로직을 이해할 수 있게 도와주는 중요한 도구로 만들며, 다른 알고리즘 입문 교과서에서 2-4 트리를 레드-블랙 트리의 바로 앞에서 소개하는 이유이다. **비록 2-4 트리가 실제로는 자주 쓰이지 않더라도 말이다**.
        - [ ] [CS 61B Lecture 26: Balanced Search Trees (video)](https://www.youtube.com/watch?v=zqrqYXkth6Q&index=26&list=PL4BBB74C7D2A1049C)
        - [ ] [Bottom Up 234-Trees (video)](https://www.youtube.com/watch?v=DQdMYevEyE4&index=4&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [ ] [Top Down 234-Trees (video)](https://www.youtube.com/watch?v=2679VQ26Fp4&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=5)

    - [ ] **N-ary (K-ary, M-ary) 트리**
        - 참고: N 이나 K는 가지 수를 가리키는 값임. (최대 가지 수)
        - 이진 트리는 2-ary 트리임. (가지 수 2)
        - 2-3 트리는 3-ary 트리임.
        - [ ] [K-Ary Tree](https://en.wikipedia.org/wiki/K-ary_tree)

    - [ ] **B-트리**
        - 재밌는 사실: 신기하게도 B는 Boeing, Balanced, Bayer(창시자 이름) 등으로 해석할 수 있다.
        - 실제에서:
            B-트리는 데이터베이스에서 널리 쓰인다. 대부분의 현대 파일시스템은 비-트리(또는 그 변형)를 사용한다. 데이터베이스에서의 쓰임 뿐 만 아니라, 파일시스템에서 특정 파일의 임의의 블록에 빠르게 접근하는 데에도 쓰인다. 기본적인 문제는 파일 블록의 주소 i를 디스크 블록(또는 cylinder-head-sector) 의 주소로 변환하는 것이다.
        - [ ] [B-Tree](https://en.wikipedia.org/wiki/B-tree)
        - [ ] [Introduction to B-Trees (video)](https://www.youtube.com/watch?v=I22wEC1tTGo&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=6)
        - [ ] [B-Tree Definition and Insertion (video)](https://www.youtube.com/watch?v=s3bCdZGrgpA&index=7&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [ ] [B-Tree Deletion (video)](https://www.youtube.com/watch?v=svfnVhJOfMc&index=8&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6)
        - [ ] [MIT 6.851 - Memory Hierarchy Models (video)](https://www.youtube.com/watch?v=V3omVLzI0WE&index=7&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf)
                - 아주 흥미로운 자료구조인 cache-oblivious B-트리를 다룬다
                - 앞쪽 37분은 매우 테크니컬하므로 건너뛰어도 된다 (B는 블록 크기, 캐시 라인 크기임)


- ### k-D 트리
    - 직사각형이나 더 높은 차원의 물체에 있는 꼭지점의 개수를 찾는데에 좋다.
    - [ ] [Kd Trees (video)](https://www.youtube.com/watch?v=W94M9D_yXKk)
    - [ ] [kNN K-d tree algorithm (video)](https://www.youtube.com/watch?v=Y4ZgLlDfKDg)

- ### 스킵 리스트
    - "스킵 리스트는 컬트적인 자료 구조이다." - Skiena
    - [ ] [Randomization: Skip Lists (video)](https://www.youtube.com/watch?v=2g9OSRKJuzM&index=10&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [ ] [For animations and a little more detail](https://en.wikipedia.org/wiki/Skip_list)

- ### 네트워크 플로우
    - [ ] [Ford-Fulkerson in 5 minutes (video)](https://www.youtube.com/watch?v=v1VgJmkEJW0)
    - [ ] [Ford-Fulkerson Algorithm (video)](https://www.youtube.com/watch?v=v1VgJmkEJW0)
    - [ ] [Network Flows (video)](https://www.youtube.com/watch?v=2vhN4Ice5jI)

- ### 서로소 집합 & 합집합 찾기
    - [ ] [UCB 61B - Disjoint Sets; Sorting & selection (video)](https://www.youtube.com/watch?v=MAEGXTwmUsI&list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd&index=21)
    - [ ] [Sedgewick Algorithms - Union-Find (6 videos)](https://www.youtube.com/watch?v=8mYfZeHtdNc&list=PLe-ggMe31CTexoNYnMhbHaWhQ0dvcy43t)

- ### 고속 처리를 위한 수학
    - [ ] [Integer Arithmetic, Karatsuba Multiplication (video)](https://www.youtube.com/watch?v=eCaXlAaN2uE&index=11&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [The Chinese Remainder Theorem (used in cryptography) (video)](https://www.youtube.com/watch?v=ru7mWZJlRQg)

- ### 트립
    - 이진 탐색 트리와 힙의 조합
    - [ ] [Treap](https://en.wikipedia.org/wiki/Treap)
    - [ ] [Data Structures: Treaps explained (video)](https://www.youtube.com/watch?v=6podLUYinH8)
    - [ ] [Applications in set operations](https://www.cs.cmu.edu/~scandal/papers/treaps-spaa98.pdf)

- ### 선형 프로그래밍 (비디오)
    - [ ] [Linear Programming](https://www.youtube.com/watch?v=M4K6HYLHREQ)
    - [ ] [Finding minimum cost](https://www.youtube.com/watch?v=2ACJ9ewUC6U)
    - [ ] [Finding maximum value](https://www.youtube.com/watch?v=8AA_81xI3ik)
    - [ ] [Solve Linear Equations with Python - Simplex Algorithm](https://www.youtube.com/watch?v=44pAWI7v5Zk)

- ### 기하학, 볼록 껍질 (비디오)
    - [ ] [Graph Alg. IV: Intro to geometric algorithms - Lecture 9](https://youtu.be/XIAQRlNkJAw?list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&t=3164)
    - [ ] [Geometric Algorithms: Graham & Jarvis - Lecture 10](https://www.youtube.com/watch?v=J5aJEcOr6Eo&index=10&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm)
    - [ ] [Divide & Conquer: Convex Hull, Median Finding](https://www.youtube.com/watch?v=EzeYI7p9MjU&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=2)

- ### 이산 수학
    - 아래 비디오를 보라

- ### 머신러닝
    - [ ] 왜 머신러닝인가?
        - [ ] [How Google Is Remaking Itself As A Machine Learning First Company](https://backchannel.com/how-google-is-remaking-itself-as-a-machine-learning-first-company-ada63defcb70)
        - [ ] [Large-Scale Deep Learning for Intelligent Computer Systems (video)](https://www.youtube.com/watch?v=QSaZGT4-6EY)
        - [ ] [Deep Learning and Understandability versus Software Engineering and Verification by Peter Norvig](https://www.youtube.com/watch?v=X769cyzBNVw)
    - [ ] [Google's Cloud Machine learning tools (video)](https://www.youtube.com/watch?v=Ja2hxBAwG_0)
    - [ ] [Google Developers' Machine Learning Recipes (Scikit Learn & Tensorflow) (video)](https://www.youtube.com/playlist?list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal)
    - [ ] [Tensorflow (video)](https://www.youtube.com/watch?v=oZikw5k_2FM)
    - [ ] [Tensorflow Tutorials](https://www.tensorflow.org/versions/r0.11/tutorials/index.html)
    - [ ] [Practical Guide to implementing Neural Networks in Python (using Theano)](http://www.analyticsvidhya.com/blog/2016/04/neural-networks-python-theano/)
    - 강의:
        - [Great starter course: Machine Learning](https://www.coursera.org/learn/machine-learning)
              - [videos only](https://www.youtube.com/playlist?list=PLZ9qNFMHZ-A4rycgrgOYma6zxF4BZGGPW)
              - see videos 12-18 for a review of linear algebra (14 and 15 are duplicates)
        - [Neural Networks for Machine Learning](https://www.coursera.org/learn/neural-networks)
        - [Google's Deep Learning Nanodegree](https://www.udacity.com/course/deep-learning--ud730)
        - [Google/Kaggle Machine Learning Engineer Nanodegree](https://www.udacity.com/course/machine-learning-engineer-nanodegree-by-google--nd009)
        - [Self-Driving Car Engineer Nanodegree](https://www.udacity.com/drive)
        - [Metis Online Course ($99 for 2 months)](http://www.thisismetis.com/explore-data-science)
    - 참고자료:
        - 책:
            - [Python Machine Learning](https://www.amazon.com/Python-Machine-Learning-Sebastian-Raschka/dp/1783555130/)
            - [Data Science from Scratch: First Principles with Python](https://www.amazon.com/Data-Science-Scratch-Principles-Python/dp/149190142X)
            - [Introduction to Machine Learning with Python](https://www.amazon.com/Introduction-Machine-Learning-Python-Scientists/dp/1449369413/)
        - [Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers)
        - Data School: http://www.dataschool.io/

- ### Go
    - [ ] 비디오:
        - [ ] [Why Learn Go?](https://www.youtube.com/watch?v=FTl0tl9BGdc)
        - [ ] [Go Programming](https://www.youtube.com/watch?v=CF9S4QZuV30)
        - [ ] [A Tour of Go](https://www.youtube.com/watch?v=ytEkHepK08c)
    - [ ] 책:
        - [ ] [An Introduction to Programming in Go (read free online)](https://www.golang-book.com/books/intro)
        - [ ] [The Go Programming Language (Donovan & Kernighan)](https://www.amazon.com/Programming-Language-Addison-Wesley-Professional-Computing/dp/0134190440)
    - [ ] [Bootcamp](https://www.golang-book.com/guides/bootcamp)

--

## 몇몇 주제에 대한 추가 내용

    나는 위에서 이미 이야기한 몇 가지 아이디어들을 강화하기 위해 이 항목을 추가했지만, 이 내용들은 다소 과하기 때문에 위에 직접 추가하지 않았다. 이 주제들은 필요 이상으로 투자하기 쉽다.
    당신이 살아 생전에 취직하고싶은게 아니라면 상관 없겠지만 말이다?

- [ ] **합집합 찾기**
    - [ ] [Overview](https://www.coursera.org/learn/data-structures/lecture/JssSY/overview)
    - [ ] [Naive Implementation](https://www.coursera.org/learn/data-structures/lecture/EM5D0/naive-implementations)
    - [ ] [Trees](https://www.coursera.org/learn/data-structures/lecture/Mxu0w/trees)
    - [ ] [Union By Rank](https://www.coursera.org/learn/data-structures/lecture/qb4c2/union-by-rank)
    - [ ] [Path Compression](https://www.coursera.org/learn/data-structures/lecture/Q9CVI/path-compression)
    - [ ] [Analysis Options](https://www.coursera.org/learn/data-structures/lecture/GQQLN/analysis-optional)

- [ ] **동적 계획법에 대한 추가적인 내용** (비디오)
    - [ ] [6.006: Dynamic Programming I: Fibonacci, Shortest Paths](https://www.youtube.com/watch?v=OQ5jsbhAv_M&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=19)
    - [ ] [6.006: Dynamic Programming II: Text Justification, Blackjack](https://www.youtube.com/watch?v=ENyox7kNKeY&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=20)
    - [ ] [6.006: DP III: Parenthesization, Edit Distance, Knapsack](https://www.youtube.com/watch?v=ocZMDMZwhCY&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=21)
    - [ ] [6.006: DP IV: Guitar Fingering, Tetris, Super Mario Bros.](https://www.youtube.com/watch?v=tp4_UXaVyx8&index=22&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb)
    - [ ] [6.046: Dynamic Programming & Advanced DP](https://www.youtube.com/watch?v=Tw1k46ywN6E&index=14&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)
    - [ ] [6.046: Dynamic Programming: All-Pairs Shortest Paths](https://www.youtube.com/watch?v=NzgFUwOaoIw&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=15)
    - [ ] [6.046: Dynamic Programming (student recitation)](https://www.youtube.com/watch?v=krZI60lKPek&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=12)

- [ ] **그래프 처리 심화 과정** (비디오)
    - [ ] [Synchronous Distributed Algorithms: Symmetry-Breaking. Shortest-Paths Spanning Trees](https://www.youtube.com/watch?v=mUBmcbbJNf4&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=27)
    - [ ] [Asynchronous Distributed Algorithms: Shortest-Paths Spanning Trees](https://www.youtube.com/watch?v=kQ-UQAzcnzA&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp&index=28)

- [ ] MIT **확률** (수학적인 내용을 천천히 진행해서 학습하기 좋다) (비디오):
    - [ ] [MIT 6.042J - Probability Introduction](https://www.youtube.com/watch?v=SmFwFdESMHI&index=18&list=PLB7540DEDD482705B)
    - [ ] [MIT 6.042J - Conditional Probability](https://www.youtube.com/watch?v=E6FbvM-FGZ8&index=19&list=PLB7540DEDD482705B)
    - [ ] [MIT 6.042J - Independence](https://www.youtube.com/watch?v=l1BCv3qqW4A&index=20&list=PLB7540DEDD482705B)
    - [ ] [MIT 6.042J - Random Variables](https://www.youtube.com/watch?v=MOfhhFaQdjw&list=PLB7540DEDD482705B&index=21)
    - [ ] [MIT 6.042J - Expectation I](https://www.youtube.com/watch?v=gGlMSe7uEkA&index=22&list=PLB7540DEDD482705B)
    - [ ] [MIT 6.042J - Expectation II](https://www.youtube.com/watch?v=oI9fMUqgfxY&index=23&list=PLB7540DEDD482705B)
    - [ ] [MIT 6.042J - Large Deviations](https://www.youtube.com/watch?v=q4mwO2qS2z4&index=24&list=PLB7540DEDD482705B)
    - [ ] [MIT 6.042J - Random Walks](https://www.youtube.com/watch?v=56iFMY8QW2k&list=PLB7540DEDD482705B&index=25)

- [ ] [Simonson: Approximation Algorithms (video)](https://www.youtube.com/watch?v=oDniZCmNmNw&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=19)

- [ ] **문자열 대조**
    - [ ] Rabin-Karp (videos):
        - [Rabin Karps Algorithm](https://www.coursera.org/learn/data-structures/lecture/c0Qkw/rabin-karps-algorithm)
        - [Precomputing](https://www.coursera.org/learn/data-structures/lecture/nYrc8/optimization-precomputation)
        - [Optimization: Implementation and Analysis](https://www.coursera.org/learn/data-structures/lecture/h4ZLc/optimization-implementation-and-analysis)
        - [Table Doubling, Karp-Rabin](https://www.youtube.com/watch?v=BRO7mVIFt08&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=9)
        - [Rolling Hashes, Amortized Analysis](https://www.youtube.com/watch?v=w6nuXg0BISo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=32)
    - [ ] Knuth-Morris-Pratt (KMP):
        - [TThe Knuth-Morris-Pratt (KMP) String Matching Algorithm](https://www.youtube.com/watch?v=5i7oKodCRJo)
    - [ ] Boyer–Moore string search algorithm
        - [Boyer-Moore String Search Algorithm](https://en.wikipedia.org/wiki/Boyer%E2%80%93Moore_string_search_algorithm)
        - [Advanced String Searching Boyer-Moore-Horspool Algorithms (video)](https://www.youtube.com/watch?v=QDZpzctPf10)
    - [ ] [Coursera: Algorithms on Strings](https://www.coursera.org/learn/algorithms-on-strings/home/week/1)
        - 초반부는 훌륭하지만, KMP 부분을 지나면서부터는 필요 이상으로 복잡해진다
        - 트라이에 대한 좋은 설명
        - 뛰어넘을 수 있음

- [ ] **정렬**

    - [ ] Stanford lectures on sorting:
        - [ ] [Lecture 15 | Programming Abstractions (video)](https://www.youtube.com/watch?v=ENp00xylP7c&index=15&list=PLFE6E58F856038C69)
        - [ ] [Lecture 16 | Programming Abstractions (video)](https://www.youtube.com/watch?v=y4M9IVgrVKo&index=16&list=PLFE6E58F856038C69)
    - [ ] Shai Simonson, [Aduni.org](http://www.aduni.org/):
        - [ ] [Algorithms - Sorting - Lecture 2 (video)](https://www.youtube.com/watch?v=odNJmw5TOEE&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=2)
        - [ ] [Algorithms - Sorting II - Lecture 3 (video)](https://www.youtube.com/watch?v=hj8YKFTFKEE&list=PLFDnELG9dpVxQCxuD-9BSy2E7BWY3t5Sm&index=3)
    - [ ] Steven Skiena lectures on sorting:
        - [ ] [lecture begins at 26:46 (video)](https://youtu.be/ute-pmMkyuk?list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&t=1600)
        - [ ] [lecture begins at 27:40 (video)](https://www.youtube.com/watch?v=yLvp-pB8mak&index=8&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
        - [ ] [lecture begins at 35:00 (video)](https://www.youtube.com/watch?v=q7K9otnzlfE&index=9&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
        - [ ] [lecture begins at 23:50 (video)](https://www.youtube.com/watch?v=TvqIGu9Iupw&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=10)

## 비디오 시리즈

편히 앉아서 즐겨라. "Netflix and skill" :P

- [ ] [List of individual Dynamic Programming problems (each is short)](https://www.youtube.com/playlist?list=PLrmLmBdmIlpsHaNTPP_jHHDx_os9ItYXr)

- [ ] [x86 Architecture, Assembly, Applications (11 videos)](https://www.youtube.com/playlist?list=PL038BE01D3BAEFDB0)

- [ ] [MIT 18.06 Linear Algebra, Spring 2005 (35 videos)](https://www.youtube.com/playlist?list=PLE7DDD91010BC51F8)

- [ ] [Excellent - MIT Calculus Revisited: Single Variable Calculus](https://www.youtube.com/playlist?list=PL3B08AE665AB9002A)

- [ ] [Computer Science 70, 001 - Spring 2015 - Discrete Mathematics and Probability Theory](https://www.youtube.com/playlist?list=PL-XXv-cvA_iD8wQm8U0gG_Z1uHjImKXFy)

- [ ] [Discrete Mathematics by Shai Simonson (19 videos)](https://www.youtube.com/playlist?list=PL3o9D4Dl2FJ9q0_gtFXPh_H4POI5dK0yG)

- [ ] [Discrete Mathematics Part 1 by Sarada Herke (5 videos)](https://www.youtube.com/playlist?list=PLGxuz-nmYlQPOc4w1Kp2MZrdqOOm4Jxeo)

- [ ] CSE373 - Analysis of Algorithms (25 videos)
    - [Skiena lectures from Algorithm Design Manual](https://www.youtube.com/watch?v=ZFjhkohHdAA&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b&index=1)

- [ ] [UC Berkeley 61B (Spring 2014): Data Structures (25 videos)](https://www.youtube.com/watch?v=mFPmKGIrQs4&list=PL-XXv-cvA_iAlnI-BQr9hjqADPBtujFJd)

- [ ] [UC Berkeley 61B (Fall 2006): Data Structures (39 videos)](https://www.youtube.com/playlist?list=PL4BBB74C7D2A1049C)

- [ ] [UC Berkeley 61C: Machine Structures (26 videos)](https://www.youtube.com/watch?v=gJJeUFyuvvg&list=PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_)

- [ ] [OOSE: Software Dev Using UML and Java (21 videos)](https://www.youtube.com/playlist?list=PLJ9pm_Rc9HesnkwKlal_buSIHA-jTZMpO)

- [ ] [UC Berkeley CS 152: Computer Architecture and Engineering (20 videos)](https://www.youtube.com/watch?v=UH0QYvtP7Rk&index=20&list=PLkFD6_40KJIwEiwQx1dACXwh-2Fuo32qr)

- [ ] [MIT 6.004: Computation Structures (49 videos)](https://www.youtube.com/playlist?list=PLrRW1w6CGAcXbMtDFj205vALOGmiRc82-)

- [ ] [Carnegie Mellon - Computer Architecture Lectures (39 videos)](https://www.youtube.com/playlist?list=PL5PHm2jkkXmi5CxxI7b3JCL1TWybTDtKq)

- [ ] [MIT 6.006: Intro to Algorithms (47 videos)](https://www.youtube.com/watch?v=HtSuA80QTyo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&nohtml5=False)

- [ ] [MIT 6.033: Computer System Engineering (22 videos)](https://www.youtube.com/watch?v=zm2VP0kHl1M&list=PL6535748F59DCA484)

- [ ] [MIT 6.034 Artificial Intelligence, Fall 2010 (30 videos)](https://www.youtube.com/playlist?list=PLUl4u3cNGP63gFHB6xb-kVBiQHYe_4hSi)

- [ ] [MIT 6.042J: Mathematics for Computer Science, Fall 2010 (25 videos)](https://www.youtube.com/watch?v=L3LMbpZIKhQ&list=PLB7540DEDD482705B)

- [ ] [MIT 6.046: Design and Analysis of Algorithms (34 videos)](https://www.youtube.com/watch?v=2P-yW7LQr08&list=PLUl4u3cNGP6317WaSNfmCvGym2ucw3oGp)

- [ ] [MIT 6.050J: Information and Entropy, Spring 2008 (19 videos)](https://www.youtube.com/watch?v=phxsQrZQupo&list=PL_2Bwul6T-A7OldmhGODImZL8KEVE38X7)

- [ ] [MIT 6.851: Advanced Data Structures (22 videos)](https://www.youtube.com/watch?v=T0yzrZL1py0&list=PLUl4u3cNGP61hsJNdULdudlRL493b-XZf&index=1)

- [ ] [MIT 6.854: Advanced Algorithms, Spring 2016 (24 videos)](https://www.youtube.com/playlist?list=PL6ogFv-ieghdoGKGg2Bik3Gl1glBTEu8c)

- [ ] [Harvard COMPSCI 224: Advanced Algorithms (25 videos)](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uP4rJgf5ayhHWgw7akUWSf)

- [ ] [MIT 6.858 Computer Systems Security, Fall 2014](https://www.youtube.com/watch?v=GqmQg-cszw4&index=1&list=PLUl4u3cNGP62K2DjQLRxDNRi0z2IRWnNh)

- [ ] [Stanford: Programming Paradigms (27 videos)](https://www.youtube.com/view_play_list?p=9D558D49CA734A02)

- [ ] [Introduction to Cryptography by Christof Paar](https://www.youtube.com/playlist?list=PL6N5qY2nvvJE8X75VkXglSrVhLv1tVcfy)
    - [Course Website along with Slides and Problem Sets](http://www.crypto-textbook.com/)

- [ ] [Mining Massive Datasets - Stanford University (94 videos)](https://www.youtube.com/playlist?list=PLLssT5z_DsK9JDLcT8T62VtzwyW9LNepV)

- [ ] [Graph Theory by Sarada Herke (67 videos)](https://www.youtube.com/user/DrSaradaHerke/playlists?shelf_id=5&view=50&sort=dd)

## 컴퓨터 공학 코스

- [온라인 CS 코스의 경로](https://github.com/open-source-society/computer-science)
- [CS 코스의 경로 (많은 온라인 강의가 포함되어 있는 경로)](https://github.com/prakhar1989/awesome-courses)
