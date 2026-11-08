# godot-game-studio

Claude와 함께 만드는 Godot 게임 작업실이다.

## 들어 있는 것

- **Claude Code Game Studios 템플릿 (v1.2.0)**: `.claude/`(에이전트 49 · 스킬 74 · 훅 · 규칙), `CLAUDE.md`, `project.yaml`.
  Claude Code에서 이 폴더를 열고 `/start`로 시작한다. 진행 강도(`modes.rigor`)는 기본값 `minimal`을 권한다.
- **참고 자료** `design/references/`: 다른 채팅에서 만든 게임 정리
  - [판타지세계 상단 키우기](design/references/sangdan.md)
  - [프로축구 라이프 → 밀리언 라이프](design/references/million-life.md)

## 앞으로 붙일 것

- **Godot 4.7 프로젝트**: 만들 게임을 정한 뒤 `/setup-engine godot 4.7`로 설정한다.
- **Game Dev Agentic Skills** (thedivergentai/Game-Dev-Agentic-Skills): Godot 스킬 중 필요한 것만 골라 넣는다.
  전부 넣으면 컨텍스트가 넘친다. LGPL-3.0이라 안의 스크립트를 게임 코드에 그대로 복사하지 않는다.
- **sprite-gen** (aldegad/sprite-gen): 스프라이트 생성. 이미지 생성은 ChatGPT(Codex) 또는 Grok 구독이 필요해서 PC에서 돌린다.

## 템플릿 출처

[Claude Code Game Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) (MIT).
라이선스 원문은 `LICENSE-ClaudeCodeGameStudios`, 템플릿 변경 내역은 `CHANGELOG.md`, 업그레이드 방법은 `UPGRADING.md`.
게임의 변경 내역은 `docs/CHANGELOG.md`에 따로 쓴다.
