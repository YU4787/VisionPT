# SmartVision Inspector PWA

## 아이폰에서 쓰는 방법

1. 이 폴더 안의 파일들을 HTTPS 웹호스팅에 업로드합니다.
   - 추천: Netlify Drop, GitHub Pages, Vercel
2. 아이폰 Safari에서 생성된 HTTPS 주소로 접속합니다.
3. 카메라 권한을 허용합니다.
4. 공유 버튼 → 홈 화면에 추가를 누르면 앱처럼 실행됩니다.

## 파일 구성

- index.html : 검사 프로그램 본체
- manifest.json : 앱 설치 정보
- service-worker.js : 캐시/앱 구동용
- icon-192.png / icon-512.png : 홈 화면 아이콘

## 주의

아이폰에서 카메라는 file:// 또는 단순 파일 미리보기로는 정상 동작하지 않을 수 있습니다.
반드시 HTTPS 주소에서 실행하세요.
