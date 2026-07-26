# timezine — 발행 레포 (publishing only)

> Timezine(Time+Magazine) — 동남아 의류·섬유 산업 흐름을 시간축으로 축적하는 회고형 정보 매거진.
> 이 레포는 **발행물 전용**이다. 수집·추출·DB·빌드는 로컬 작업장(`cowork_timezine`)에서 돌고,
> 산출물(`index.html` + `issues/` 스냅샷)만 여기로 실려 Vercel로 서빙된다.

- `index.html` — 최신 누적호 (매일 08:30 로컬 launchd `com.timezine.publish`가 갱신)
- `issues/timezine_issue_YYYY-MM-DD_HHMM.html` — 시간 박힌 누적 스냅샷 (append-only, 삭제 안 함)
- `vercel.json` — 정적 서빙 설정 (cleanUrls, 5분 캐시)

원칙: **여기서는 아무것도 만들지 않는다.** 소스 수정·빌드·이슈 관리 전부 작업장 소관.

---
초기 구성: 2026-07-26 | 작성: 코코 (Claude Code, claude-opus-5[1m]) | 결정: 준
