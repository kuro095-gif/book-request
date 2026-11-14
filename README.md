# 연구회 도서구매신청

- `index.html` — 회원 신청 화면
- `admin.html` — 관리자 화면 (비밀번호 로그인)
- `config.js` — Apps Script API 주소 (배포 후 한 번만 수정)

이 저장소에는 화면만 있어요. 저장과 도서 검색은 구글 시트에 붙인 Apps Script(Code.gs)가 맡고, 카카오 API 키도 그쪽 스크립트 속성에만 보관합니다.

## 주소

- 회원: `https://<계정>.github.io/<저장소>/`
- 특정 연구회(일자)를 미리 골라 둔 링크: `https://<계정>.github.io/<저장소>/?r=회차ID`
- 관리자: `https://<계정>.github.io/<저장소>/admin.html`

## Apps Script 코드를 고쳤을 때

[배포 → 배포 관리 → 편집(연필) → 버전: 새 버전 → 배포]로 올리면 API 주소가 바뀌지 않아요.
[새 배포]로 올리면 주소가 바뀌니 `config.js`도 같이 고쳐야 합니다.
