# Compound Workflow Sandbox

테스트용 disposable repo. `/Users/mac/workflow.md` v2.1.9의 Appendix A YAML이 실제 GitHub Actions에서 동작하는지 검증.

검증 시나리오:
- SC-A: 라벨 없는 PR → `path-label-valid` 차단
- SC-B: 다중 path 라벨 PR → `path-label-valid` 차단
- SC-C: P6 + 깨진 tasks.md → `tasks-md-valid` 차단
- SC-D: P5+M4 + challenge artifact 없음 → `challenge-pass` 차단
- SC-E: P5+M4 + valid challenge artifact → 통과
- SC-F: P2 hotfix → `codex-review-pass` skip + post-merge audit

검증 완료 후 archive 또는 삭제 예정.

**Codex 호출 정책**: `codex review` 단계는 mock (canned output)로 대체 — 워크플로우 logic만 검증. 실제 codex 호출은 별도 검증.
