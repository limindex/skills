# LimIndex skills

Claude Code plugin marketplace for skills and plugins by LimIndex.

| Plugin | What it does |
|---|---|
| [white-security](https://github.com/limindex/white-security) | Read-only security review for code your AI coding agent wrote, on request, typically before deploy. Korean or English report. |

## Install (Claude Code)

```
/plugin marketplace add limindex/skills
/plugin install white-security@limindex
```

Update: `/plugin marketplace update limindex`. Auto-update is off by default for third-party marketplaces.

Each plugin is pinned to a release tag and its commit SHA, so an install always gets the reviewed release.

---

## 한국어

LimIndex가 만드는 AI 코딩 도구용 스킬·plugin 모음(Claude Code Marketplace).

| plugin | 설명 |
|---|---|
| [white-security](https://github.com/limindex/white-security) | AI 코딩 도구가 만든 코드를 요청할 때(주로 배포 전) 읽기 전용으로 검토. 한국어·영어 보고. |

설치는 위 명령 두 줄. 업데이트는 `/plugin marketplace update limindex`(외부 Marketplace는 자동 업데이트가 기본으로 꺼져 있음). plugin마다 릴리스 태그와 커밋 SHA로 고정해, 설치하면 항상 검토를 마친 릴리스를 받음.
