# 교사개발자의 날: 학과 간 교류수업 이야기

종로산업정보학교 관광일본어과와 AI컴퓨터과의 교류수업 경험을 소개하는 9장 웹 프레젠테이션입니다. 기존 혹등고래 PPTX의 캐릭터 이미지·내용·10분 발표자 노트를 바탕으로 복원했습니다.

## 실행

`index.html`을 브라우저에서 엽니다. 별도 설치나 빌드가 필요 없습니다. `assets` 폴더를 함께 유지하세요. 모든 이미지가 포함된 단일 HTML 버전도 별도로 제공합니다.

## 발표 조작

- 방향키, Page Up/Down, 스페이스: 슬라이드 이동
- Home/End: 첫 장/마지막 장
- N: 발표자 노트 열기·닫기
- F 또는 전체화면 버튼: 전체화면 진입·해제
- Escape: 노트 닫기, 브라우저 전체화면 해제
- 하단 점: 원하는 장으로 이동
- 터치: 좌우 스와이프로 이동, 세로 스크롤로 내용 확인

스페이스는 화면의 일반 영역에 초점이 있을 때 다음 장으로 이동합니다. 버튼이나 링크에 초점이 있으면 해당 항목을 실행합니다. 발표자 노트는 전체화면에서도 청중에게 보이므로 실제 발표 중에는 닫아 두세요.

## 원본 수업 웹앱

- [관광일본어과 1반: 일본 문화 체험](https://memilmuk82.github.io/memilmuk82-tour_Jap_Webapp/)
- [관광일본어과 2반: 여행 회화 퀴즈](https://memilmuk82.github.io/tourism-japanese-ai-quiz/)

4·5장의 화면과 ‘실제 웹앱 열기’ 버튼이 각 원본으로 연결됩니다. 캡처는 2026-10-30 크롬에서 실제 공개 웹앱을 열어 촬영했으며, 활동 영역만 잘라 사용했습니다. 학생 작품 화면으로 제시하지 않습니다.

## GitHub Pages

독립된 공개 저장소에서 발표자료를 관리하며, GitHub Pages로 정적 파일을 게시합니다.

저장소: [memilmuk82/teacher-developer-day-2026](https://github.com/memilmuk82/teacher-developer-day-2026)

발표 열기: [교사개발자의 날 웹 프레젠테이션](https://memilmuk82.github.io/teacher-developer-day-2026/)

1. 공개 저장소를 만들고 이 폴더의 내용물을 저장소 최상위에 올립니다.
2. `main` 브랜치에서 `index.html`, `assets/`, `.nojekyll`을 유지합니다.
3. Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save를 선택합니다.
4. Pages 배포가 끝나면 게시된 화면과 두 원본 링크를 다시 확인합니다.

게시 설정은 `main` 브랜치의 `/(root)`입니다. 수정한 파일을 이 브랜치에 푸시하면 다시 게시됩니다.

[GitHub 공식 Pages 게시 설정 안내](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## 구성

- `index.html`: 9장 슬라이드, 발표자 노트, 조작 기능
- `assets/`: PPTX의 기존 고래 PNG 8종 및 실제 웹앱 캡처 2장
- `.nojekyll`: 정적 파일 게시 표시

외부 라이브러리·외부 폰트·빌드 과정 없이 동작합니다. 원본 수업 웹앱으로 이동할 때는 인터넷 연결이 필요합니다. 한국어 글꼴은 기기의 기본 글꼴을 사용하므로 기기마다 자간·줄바꿈이 조금 달라질 수 있습니다.
