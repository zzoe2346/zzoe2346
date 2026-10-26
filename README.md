## 안녕하세요, 정성훈입니다 👋

서버를 만드는 개발자입니다. 느린 쿼리의 실행계획을 열어보거나, 동시에 들어온 요청이 왜 꼬였는지 따라가 보는 일을 좋아합니다.

만들면서 고민한 것과 그때 내린 결정은 [블로그](https://jeongseonghun.com)에 남깁니다.
요즘은 AI 에이전트와 함께 만들면서, 어디까지 맡기고 무엇을 직접 확인해야 하는지 실험하고 있습니다.

<br>

## 요즘 하는 것

- **책먹자** — 책에 형광펜 친 페이지를 찍으면 문장을 정리해 주는 앱의 서버를 만들 준비를 하고 있어요. 지금은 기획과 설계 단계예요.
- **DB로 만드는 작업 큐** — `FOR UPDATE SKIP LOCKED`로 작업 큐를 직접 만들며 중복 실행과 장애 복구를 공부하고 있어요.

<br>

## 만든 것

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle" width="140">
        <a href="https://github.com/zzoe2346/MyCodingTest_BACKEND">
          <img src="https://github.com/user-attachments/assets/2cfa5d66-5018-49d2-bcc5-6c7ae81a0a6f" width="90" alt="My Coding Test 로고"><br>
          <strong>My Coding Test</strong>
        </a>
      </td>
      <td valign="middle">
        백준에서 푼 문제를 모아 오답노트로 복습하는 서비스.<br>
        처음엔 한 덩어리였던 코드를 멀티 모듈로 나누면서 경계를 어디에 그을지 오래 고민했어요. (<a href="https://jeongseonghun.com/posts/Dev-refactoring-mycodingtest-with-ddd-and-multi-module">그 과정</a>)<br>
        <sub><a href="https://github.com/zzoe2346/MyCodingTest_BACKEND">Backend</a> · <a href="https://github.com/zzoe2346/MyCodingTest_FE">Frontend</a> · <a href="https://github.com/zzoe2346/MyCodingTest_Connector">Extension</a></sub>
      </td>
    </tr>
    <tr>
      <td align="center" valign="middle" width="140">
        <a href="https://github.com/zzoe2346/url-shortener-system"><strong>URL Shortener</strong></a>
      </td>
      <td valign="middle">
        책에서 본 URL 단축기를 직접 만들고 부하를 걸어 본 프로젝트.<br>
        DB 저장을 비동기로 바꿔 처리량을 올렸더니, 이번엔 큐가 넘치고 저장 실패는 어떻게 하나라는 질문이 따라왔어요.
      </td>
    </tr>
  </tbody>
</table>

<br>

## AI와 같이 만든 도구

공부하면서 필요해서 만든 것들이에요. 구현은 에이전트에게 맡기고, 범위를 정하고 결과를 검증하는 건 제가 했어요.

| | 이름 | 한 줄 소개 |
| :---: | --- | --- |
| <img src="https://raw.githubusercontent.com/zzoe2346/kkokkomu/main/Artwork/AppIcon/Preview/AppIcon-white.png" width="32" alt="꼬꼬무 아이콘"> | [꼬꼬무](https://github.com/zzoe2346/kkokkomu) | 개념을 내 말로 설명하면 꼬리 질문이 이어지는 macOS 앱 |
| <img src="https://raw.githubusercontent.com/zzoe2346/baeuja/main/Artwork/AppIcon/Preview/AppIcon-default.png" width="32" alt="배우자 아이콘"> | [배우자](https://github.com/zzoe2346/baeuja) | 궁금한 주제로 교재와 퀴즈를 만드는 macOS 앱 |
| <img src="https://raw.githubusercontent.com/zzoe2346/mindmap/main/Artwork/AppIcon/Preview/AppIcon-web.png" width="32" alt="mindmap 아이콘"> | [mindmap](https://github.com/zzoe2346/mindmap) | 로그인 없이 쓰는 마인드맵 앱 |
| | [study-tui](https://github.com/zzoe2346/study-tui) | 터미널에서 공부하는 교재 앱 |

<br>

가끔은 쓰던 라이브러리에 작은 PR을 보내기도 해요 — [Spring Framework](https://github.com/spring-projects/spring-framework/pulls?q=is%3Apr+author%3Azzoe2346), [Spring REST Docs](https://github.com/spring-projects/spring-restdocs/pulls?q=is%3Apr+author%3Azzoe2346)

📮 tjdgns5506@gmail.com
