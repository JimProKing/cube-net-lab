# Cube Net Lab

정육면체를 접고 펼치며 전개도를 확인하는 웹 앱.

| 분류 | 상태 | 스택 | 바로 보기 |
| --- | --- | --- | --- |
| 교육 · 웹앱 | 완료 | JavaScript · Three.js | — |

## 실행

`index.html`을 브라우저로 연다. Three.js를 CDN에서 불러오므로 인터넷이 필요하다.

## 구성

| 탭 | 기능 |
|----|------|
| 실험실 | 3D 정육면체 접기/펼치기, 면 선택, 기호 부착, 전개도 모양 변경 |
| 전개도 11개 | 접을 수 있는 전개도 목록. 클릭하면 실험실에서 연다 |
| 법칙 | 반대 면, 꼭짓점, 기호 방향 |
| 퀴즈 | 겨냥도↔전개도, 반대 면, 불가능한 전개도, 주사위 |
| 스피드 | 제한 시간 안에 반대 면 / 맞닿음 판별 |

## 조작

- 드래그: 회전
- 휠: 확대/축소
- 슬라이더: 접힘 정도
- 면 클릭: 선택. 반대 면 강조 가능

## 파일

- `index.html` — 페이지
- `style.css` — 스타일
- `app.js` — 전개도 생성, 접기, 퀴즈

---

**관련 저장소** · [spatial-perception-training](https://github.com/JimProKing/spatial-perception-training)

<sub>[JimProKing](https://github.com/JimProKing) · 이영찬 — 전체 저장소는 프로필의 프로젝트 지도에서 분야별로 볼 수 있습니다.</sub>
<!-- jpk-footer -->
