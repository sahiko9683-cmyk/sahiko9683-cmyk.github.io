# Biju Cha — Developer Portfolio

바이브코더 & 업무 자동화 개발자 Biju Cha의 개인 포트폴리오 웹사이트 (한국어/영어).

**Live:** https://sahiko9683-cmyk.github.io/

## 주요 기능

- 프로젝트 4종 소개: 실서비스 2개(사이트·코드 링크 포함) + 업무용 내부 도구 2개
- 한국어/영어 언어 전환 (선택 언어 localStorage 저장)
- 스크린리더 접근성: aria-live 언어 변경 알림, 키보드 드롭다운 탐색, 이미지 대체 텍스트
- 반응형 레이아웃 (모바일/태블릿/데스크톱), 다크 테마

## 기술 스택

- 단일 HTML 파일 (인라인 CSS/JS, 의존성 없음)
- GitHub Pages 배포, GitHub Actions CI (HTMLHint)

## 설치 및 실행

```bash
git clone https://github.com/sahiko9683-cmyk/sahiko9683-cmyk.github.io.git
cd sahiko9683-cmyk.github.io
# 로컬 미리보기
python3 -m http.server 8000
# 브라우저에서 http://localhost:8000 접속
```
