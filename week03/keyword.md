- `fetch` vs `axios`의 차이점에 대해 자세히 조사하여 아래 토글에 정리해주세요!
    - `fetch` ?
        
        Promise 기반 자바스크립트 내장 라이브러리
        
        기본 응답 결과는 Response 객체로, json으로 바꾸거나 text로 바꾸는 별도의 처리 과정이 필요하다. 2개의 인자를 받는데, 첫 번째 인자는 접근하고자 하는 URL이며 두 번째 인자는 요청의 설정 옵션으로 이는 선택 매개변수이다. 
        
    - `axios` ?
        
        Promise API를 활용하는 HTTP 통신 외부 라이브러리
        
        비동기로 통신 가능 
        
        json을 자동으로 적용해서 promise 객체를 return하기 때문에 reponse 데이터를 다루기 쉽다. 
        
    - `fetch`와 `axios`의 차이
        
        
        |  | fetch | axios |
        | --- | --- | --- |
        | 설치 | 내장 라이브러리 | 패키지 설치 필요 |
        | 호환성 | 대부분 지원하지만 지원하지 않는 버전 존재 | 모던 브라우저에서 모두 지원 |
        | JSON 데이터 자동 변환 | 추가 로직 필요 | 지원 |
        | 요청 취소, 타임아웃 등 기능 | 없음 | 지원 |
        | 요청 인터셉트 | 없음 | 가능 |
        | 데이터 넘기는 방법 | string화 해서 넘김 | 객체로 넘김 |

