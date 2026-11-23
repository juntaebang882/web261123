# 12주차 수업 실습

- 이름 : 방준태
- 저장소 : https://github.com/아이디/web261123
- 사이트 주소 : https://아이디.github.io/web261123/

## 구현 내용
- `input` 이벤트 기반 실시간 영화 제목 검색 (`#q`)
- `change` 이벤트 기반 정렬 적용 (`#sort`, 인라인 `onchange` 제거)
- 검색과 정렬 상태를 동시에 유지하는 `getView()` 통합 처리
- 보드(`.board`) 이벤트 위임을 통한 찜 버튼(`.like`) 토글 및 찜 개수(`#likeCount`) 갱신
- 검색 결과 0건일 때 빈 결과 안내 문구(`.state-empty`) 표시
- `Escape` 키 입력 시 검색창 초기화 및 전체 목록 복원

## 생성형 AI 사용 내역
- 질문 요지 : 12주차 수업 실습 안내서(단계 1~8)에 맞춘 `index.html`, `style.css`, `data.js`, `app.js` 코드 구성 요청
- 답변 요약 : `addEventListener`, `getView()`, 이벤트 위임 찜 기능, 빈 결과 상태, `Escape` 키 처리가 반영된 4개 파일 코드를 제공받음
- 채택 여부 : 채택 (저장소 루트에 반영 후 동작 및 콘솔 오류 여부 검증 완료)
