# 설치된 외부 스킬 목록

이 저장소의 `.claude/skills/`에 넣어 둔 스킬입니다. 이 저장소로 Claude Code 세션을 열면 자동으로 불러옵니다.
가져온 날짜: 2026-11-09 (각 저장소 최신 커밋 기준)

| 출처 (GitHub) | 커밋 | 넣은 스킬 | 하는 일 |
|---|---|---|---|
| pbakaus/impeccable | cf7ea4a | `impeccable` | AI 티 나는 화면 디자인 점검·수정 |
| Nutlope/hallmark | 407fa68 | `hallmark` | AI 티 나는 디자인 잡기, 테마 제안 |
| D4Vinci/Scrapling | c5121c7 | `scrapling` | 웹페이지 내용 수집 (사용 전 `pip install scrapling` 필요) |
| obra/superpowers | 22f0b46 | `brainstorming`, `writing-plans`, `executing-plans` 등 15개 | 질문 → 설계 → 계획 → 개발 순서로 일하기 |
| mattpocock/skills | 4ae2317 | `grill-me`, `to-spec`, `teach`, `handoff` 등 23개 (engineering·productivity) | 개발자의 일하는 순서 |
| mromidev/claude-animated-shorts | e3b817b | `cartoon-3d-short` | 입체 만화 쇼츠 제작 (Remotion 필요) |

## 넣지 않은 것
| 저장소 | 이유 |
|---|---|
| pingdotgg/t3code | 스킬이 아니라 별도 앱 |
| thedotmack/claude-mem | 백그라운드 프로그램과 훅이 있어야 동작함 |
| milind-soni/OpenMausBot | 직접 실행하는 봇 프로그램 |
| Donchitos/Claude-Code-Game-Studios | 게임 개발 전용 프로젝트 템플릿 (에이전트 49개·훅이 저장소 전체 동작을 바꿈) |
| 자미두수 (9위) | 요청에서 제외 |

## 참고
- `mattpocock/skills`의 `code-review`, `tdd`는 이름이 겹치지 않아 그대로 넣었고, `superpowers`와 겹치는 스킬은 없습니다.
- `cartoon-3d-short`의 `references/`(다른 채널 영상 캡처 등)는 원작자가 "공개 금지"로 적어 두어 넣지 않았습니다.
- 라이선스 원문: `.claude/licenses/`
