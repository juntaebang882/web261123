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

