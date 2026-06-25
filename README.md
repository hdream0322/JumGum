# JumGum

deurim.com 서비스 점검 시 표시되는 유지보수 페이지입니다.

**🔗 [jumgum.deurim.com](https://jumgum.deurim.com)**

GitHub Pages로 서빙되며, Cloudflare 리디렉션 규칙을 통해 각 서비스에 연결됩니다.

## 점검 시간 변경

`config.json`의 `start`, `end` 값을 수정합니다.

```json
{
  "start": "2026년 6월 25일 (목) 11:00",
  "end":   "2026년 6월 25일 (목) 17:00"
}
```

## 구조

```
index.html   — 점검 페이지 UI
config.json  — 점검 시간 설정
CNAME        — jumgum.deurim.com
```
