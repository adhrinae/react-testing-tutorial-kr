# React testing tutorial 번역 저장소

- Robin Wieruch의 [React testing tutorial](https://www.robinwieruch.de/react-testing-tutorial)을 번역하는 저장소입니다.

- 본문 안에 이미지가 몇 개 있으나 가능한 한 원본 그림파일을 바로 가져다 쓰기보다 직접 구현해보면서 알맞은 그림파일을 CDN에 업로드하고 그 URL을 연결하는 것이 더 좋으리라 생각합니다.

- `original.md` 파일의 frontmatter는 삭제하지 않고, 추후 개별 블로그의 SEO 용도로 참고하는데 사용할 수 있도록 남겨두었습니다.

- 본문은 Jekyll 용 마크다운 처리 문법이 들어있고, 그 안에 일부 코드 라인을 강조하는 구문이 있으나 일반 마크다운에는 적용되지 않아 주석처리 해 두었습니다.

- 번역은 서론을 `ch00.md` 로, 이후 대단락별로 `ch12.md` 까지 만들어서 챕터별로 진행했습니다.
  - 맨 마지막 정리하는 문단은 `ch12.md` 파일에 포함되면 된다고 생각합니다.
  - 챕터별로 나누는 이유는 결과물을 보고 Gitbook으로 배포하기 위함입니다.

---

## 목차

1. [서문](translations/ch00.md)
2. [테스트를 위한 간단한 리액트 애플리케이션 설정하기](translations/ch01.md)
3. Mocha & Chai

   1. [리액트에서 Mocha와 Chai 설정하기](translations/ch02.md)
   2. [리액트 State 변경을 단위 테스트하기](translations/ch03.md)
4. Enzyme

   1. [리액트에 Enzyme 테스트 설정하기](translations/ch04.md)
   2. [Enzyme으로 리액트 테스트하기 - 리액트 컴포넌트를 단위, 통합 테스트하는 방법](translations/ch05.md)
5. Sinon
   1. [리액트에서 Sinon 테스트 설정하기](translations/ch06.md)
   2. [Sinon으로 리액트 테스트하기 - 비동기 코드를 테스트하는 방법](translations/ch07.md)
6. Jest
   1. [리액트에서 Jest 설정하기](translations/ch08.md)
   2. [Jest로 리액트 테스트하기 - 컴포넌트 스냅샷 테스트](translations/ch09.md)
7. E2E 테스트
   1. [Cypress.io를 활용한 리액트 전체 테스트](translations/ch10.md)
8. CI와 테스트
   1. [리액트 컴포넌트 테스트와 CI(Continuous Integration)](translations/ch11.md)
   2. [Coveralls로 리액트 컴포넌트의 테스트 커버리지 확인하기 + 후기](translations/ch12.md)

