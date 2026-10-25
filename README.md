# 차곡지도

장소를 순서대로 담고 상세정보와 함께 링크로 공유하는 디지털 지도 제작 사이트입니다.

## 기능

- 순서 번호가 있는 장소 마커와 방문 순서 연결선
- 장소별 주소, 방문 시간, 설명, 관련 링크 상세보기
- 장소 추가, 수정, 삭제 및 순서 변경
- 장소 검색 또는 지도에서 직접 위치 지정
- URL 파라미터 `map`과 `view=1`로 공유 지도 복원
- 브라우저 저장소에 작성 내용 자동 저장
- 모바일 화면 지원

## 실행 및 배포

빌드가 필요 없는 정적 HTML/CSS/JavaScript 사이트입니다.

로컬에서는 이 디렉터리에서 `python3 -m http.server 8000`을 실행한 후 http://localhost:8000 에 접속합니다.

GitHub Pages 설정에서 **Deploy from a branch**, **main**, **/(root)** 를 선택하면 배포할 수 있습니다.

지도 데이터는 공유 URL에 포함됩니다. 수정 후에는 새 링크를 만들어야 합니다. 매우 긴 메모와 다수의 장소는 URL 길이 제한에 영향을 받을 수 있습니다.

## 외부 서비스 및 라이선스

- Leaflet 1.9.4: BSD-2-Clause. `vendor/LICENSE` 참조.
- 지도 타일: Esri World Street Map (출처는 지도에 표시)
- 장소 검색: OpenStreetMap Nominatim (네트워크 및 서비스 정책에 따라 제한될 수 있음)
- 글꼴: Google Fonts Noto Sans KR

방문 순서 연결선은 실제 도로의 이동 경로가 아닙니다.
