# GSA Infoteam Frontend Study

2020년 기준, 프런트 엔드 교육 자료 저장소입니다.

```JSX
import React from 'react';
import notify from './notify';

const App = () => {
  handleClick = () => {
    notify();
  };

  return (
    <div>
      <button onClick={this.handleClick}>Click Me</button>
    </div>
  );
}

export default App;
```

## 시작하기에 앞서

-   [2020년 기준 웹 개발자 로드맵](https://github.com/devJang/developer-roadmap?fbclid=IwAR3caSuOSA71kwoisWbsVLykQglLW03l9dHvSCkk4cIdTIUvMF0F4xB1onY)을 읽어보고 와주세요. 이 모든 내용을 다 알 필요는 없지만 자신의 지식이 어떻게 연결될 수 있는 지 아는 것은 중요합니다.
-   교육 자료에 의문사항이나 오타는 GitHub Issue를 작성해주시거나 슬랙, 카카오톡으로 알려주세요.

## 교육 일정

- 강의
    - 매주 목요일 21:30분 회의 이후에 진행할 예정입니다.
    - 시작은 저번 과제 리뷰와 질문으로 시작하며, 좀 더 크고 개념적인 것을 위주로 다룹니다.
    - 중간에는 새로운 개념과 요소들을 소개합니다.
    - 마지막에는 과제 줘야하는 것이 있으면 과제를 줍니다.

- 레시(ZOOM, Live Share)
    - 매주 수요일 21:30분 예정입니다.
    - 강의 시간에 주어진 과제대로 작성한 코드를 리뷰할 예정입니다.
    - 과제를 하거나 공부를 하면서 막힌 것에 대해 질문을 받습니다.
    - 여러사람에게 공통적으로 나온 의문사항에 대해 보충 설명을 하고, 필요할 시 다음 주 강의 첫 시간에서도 다룹니다.
- 과제
    - 강의에서 배운 내용에 따라 저희가 적절한 과제를 준비해서 내드릴려고 합니다.
    - 강의 진도 기준으로 2주 앞선 분량까지 준비할 계획입니다.
    - 과제의 듀는 레시 시간이 어떻게 결정되냐에 따라 다르지만, 대충 월화가 될 것 같습니다.

## 목차

- [x] 유용한 링크 소개 : 알아두면 좋은 뉴스레터, 추천하는 도서, 사이트들을 소개합니다.
- [x] 개발 환경 설정 : Git 설치, VS Code 및 확장기능 설치, 브라우저의 개발자 도구 사용방법, 기초 HTML 태그 사용방법을 다룹니다.
- [ ] Git과 GitHub : 파일 버전 관리 시스템을 사용해야 하는 이유, Git의 기능(push, pull, branch, stash 등)과 GitHub의 기능을 알아봅니다.
- [ ] HTML/CSS/JS : 웹 페이지를 만드는 이 3가지 구성요소에 대해 더 심도깊게 다룹니다.
- [ ] 정적인 페이지 만들기(Jekyll, HTML/CSS/JS)
- [ ] Node.js와 패키지 매니저
- [ ] 최신 라이브러리 사용해보기(React)
- [ ] 예쁘고 편하게 짜보기(Sass, CSS-in-JS)

