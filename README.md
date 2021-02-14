
[ ISSUE ]

-고객 요청사항 중 특이사항-

A. 광고
  반영 x
  이유: 비지니스 모델에 광고 수입도 포함되어 있을 것이라 예상되고 고객의 요청사항과 
  상충될 것으로도 예상이 되어 비지니스모델 건들지 않기로 결정

만약 적용한다면? (옵션 3개)
  1. 광고 모두 제거
    - 광고 요청 API를 사용하지 않는다.

  2. 광고 등장 횟수 줄이기
    -  광고 API로 광고 정보들을 받아온 후 4순번마다 등장하던 광고를 5-6 혹은 그 이상의 번째로 배치한다. 
    v-if="(idx + 1) % 3 === 0" 부분을 조정하여 광고 등장 횟수 조정 가능

  3. 광고 가리기
    - 광고를 가리는 클릭이벤트를 설정한 후에 state값에 true를 설정 후 광고 컴포넌트인 <Ads>를 <div>태그로 감싼 후 v-if를 사용하여 태그 조건부 렌더로 구현

B. 드래그 copy & paste
  - 저작권 침해 우려로 드래그 기능 및 마우스 우클릭 방지 설정

C. 고객 요청 사항 중 "다 좋은데 글 우측 위에 있는 숫자가 뭔가요?"
  - hover로 해당 숫자 정보 나타냄.

D. 고객 요청 사항 중 
  1. 이메일과 작성일이 밑에 나왔으면 좋겠어요.
  2. 이메일이 맨위에 있으니까 작성하신 분이 누군지 잘보여서 너무 좋아요! cs* 멘토님 정말 친절하시고 짱입니다!!!

- 두개의 의견을 고려하여 아래 작성날짜와 함께 유저 email을 삽입, 댓글도 마찬가지.


E. 나머지

반응형, 로딩 이미지 등 기타 기능 및 CSS 설정 완료