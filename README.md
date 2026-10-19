# 중앙대학교 배경화면

중앙대학교 홍보대사 중앙사랑 34기가 만든 중앙대학교 배경화면 11종 배포 페이지입니다.
예비 중앙인과 중앙인을 위해 무료로 배포합니다.

기획 · 제작 | 중앙사랑 34기 최순영

## 구성

| 경로 | 내용 |
| --- | --- |
| `index.html` | 페이지 본문 (PC · 휴대폰 화면 모두 포함) |
| `wallpapers/` | 배경화면 원본 (PNG 10장, 청룡연못 JPG 1장) + 크게 보기용 미리보기 JPG |
| `thumbs/` | 목록용 작은 미리보기 |
| `puang/` | 푸앙이 이미지 |
| `fonts/` | 프리텐다드 웹폰트 (SIL OFL) |
| `vendor/jszip.min.js` | "11종 한 번에 받기" zip 생성용 라이브러리 (MIT) |
| `og.jpg`, `favicon.png` | 링크 미리보기 이미지, 아이콘 |

## GitHub Pages로 배포하기

1. GitHub에서 새 저장소를 만듭니다 (예: `cau-wallpaper`, Public).
2. 이 폴더의 파일을 모두 올리고 `main` 브랜치에 push 합니다.
   ```bash
   git remote add origin https://github.com/hellosoonyoung22/cau-wallpaper.git
   git push -u origin main
   ```
3. 저장소 **Settings → Pages**에서 Source를 `Deploy from a branch`, Branch를 `main` / `/ (root)`로 지정하고 저장합니다.
4. 1~2분 뒤 `https://hellosoonyoung22.github.io/cau-wallpaper/` 주소로 열립니다.
5. 단축 링크(`bit.ly/...`)를 이 새 주소로 연결하면 끝입니다.

## 링크 미리보기

`index.html`의 `og:image`, `og:url`은 `https://hellosoonyoung22.github.io/cau-wallpaper/` 기준으로 지정되어 있습니다.
저장소 이름이나 주소가 바뀌면 이 두 줄도 함께 바꿔 주세요.

## 이용 안내

배경화면은 개인 휴대폰 배경화면 용도로만 사용할 수 있습니다.
상업적 이용, 무단 수정 및 재배포는 삼가 주세요.
