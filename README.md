# minwoosung.github.io

성민우(MinWoo Sung) 개인 소개 페이지. 빌드 과정 없는 단일 정적 HTML 사이트입니다.

## 구성

| 파일 | 설명 |
| --- | --- |
| `index.html` | 소개 페이지 본문 + CSS 인라인 (자체 완결, 의존성 없음) |
| `resume.md` | 이력서 원본 소스 (요약본) |

## 로컬에서 보기

```bash
open index.html
```

## 배포 (GitHub Pages)

1. GitHub에 `minwoosung.github.io` 이름으로 **public 리포지토리** 생성
2. 아래 명령으로 push

   ```bash
   git remote add origin https://github.com/minwoosung/minwoosung.github.io.git
   git push -u origin main
   ```

3. 저장소 **Settings → Pages** 에서 Source 를 `main` 브랜치 `/ (root)` 로 지정
4. 몇 분 뒤 `https://minwoosung.github.io` 에서 확인

> `<username>.github.io` 이름의 리포지토리는 별도 설정 없이도 root 페이지로 자동 배포됩니다.

## 아직 채울 항목

`index.html` 상단 `.contacts` 영역에 주석 처리된 GitHub / 휴대전화 링크와,
`resume.md` 의 `_직접 입력_` 항목(거주지·학력·어학 등)은 원하는 정보로 채워주세요.
