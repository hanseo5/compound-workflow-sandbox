## Path (Section 7 Step 1) — 필수
<P1 rollback / P2 hotfix / P2-backfill / P3 bug / P4 refactor / P5 small / P6 full 중 하나>

## Modifiers (Section 7 Step 2)
- [ ] M1 보안/인증
- [ ] M2 결제
- [ ] M3 규제/감사
- [ ] M4 PII (신규/기존 무관)
- [ ] M5 외부 의존 메이저 업그레이드
- [ ] M6 DB 스키마 변경

## Spec & Tasks (P6 / P2-backfill 만 필수)
- Spec: specs/<NNN>/spec.md  | 또는: N/A (Path: <PN>)
- Tasks: specs/<NNN>/tasks.md | 또는: N/A (Path: <PN>)

## Codex Review

**Path P2 (hotfix)인 경우만**:
- Codex review: post-merge by `<ISO datetime, 머지 +24h 이내>`
- Severity counts: post-merge에 P2-backfill PR에서 채움.

**Path P2 외**:
- P1 (critical): 0  ← waiver 불가
- P2 (high): 0     ← waiver 불가
- P3 (medium): N
- P4 (low): M

## Waiver (medium P3 ≥ 3건 시 필수, P1/P2 waiver 불가)
- 사유:
- 처리 일정:
- 추적 issue:
