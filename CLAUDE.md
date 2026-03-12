# MassTracker — Claude 작업 지침

## 커밋 & 푸시
- 코드 수정이 완료되면 확인 없이 바로 커밋하고 `origin main`에 푸시한다.

## Bash 명령
- `date`, `sed` 등 파일 수정·시스템 조회 명령은 확인 없이 바로 실행한다.

## 프로토타입 파일 수정 규칙
- `prototype/weight-chart.html`을 수정할 때마다 헤더의 수정 날짜를 현재 일시로 갱신한다.
- 현재 일시(KST): `TZ='Asia/Seoul' date '+v-%y%m%d-%H%M-kst'`로 확인 후 아래 줄을 업데이트한다.
  ```html
  <div class="update-info">v-YYMMDD-HHMM-kst</div>
  ```
