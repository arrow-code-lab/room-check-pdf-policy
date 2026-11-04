---
issue: 3
pr: 4
flow: ai-default-medium
status: pr-running
outcome: null
evidence:
  spec_status: draft
  has_issue: true
  has_pr: true
  tasks_total: 0
  tasks_done: 0
  integration: none
  open_major: 0
  merged: false
  accepted: false
passed: [triage, requirements, impl, review]
attempts: { impl: 1, review: 1 }
edges:
  triage->requirements: 1
  requirements->impl: 1
  impl->review: 2
  review->impl: 1
  review->pr: 1
artifacts:
  triage:
    - .ai/specs/spec-20261105-002914.md
  requirements:
    - .ai/specs/spec-20261105-002914.md
    - .ai/specs/assets/20261105-002914/review.html
events: 36
---

# Issue #3 の索引

この索引は `events/` から機械的に生成される写しです。手で書き換えないでください（次の記録で上書きされます）。

- 現在地: `pr-running`
- フロー: `ai-default-medium` / 通過: `triage` → `requirements` → `impl` → `review`
- open な指摘: 1 件（Major 以上 0 件）

## open な指摘

- Minor `terms.html:101` 利用規約の同日適用（第 12 条の事前告知を経ない）判断が人の確認待ちのまま … `events/20261104T154801-review.yaml`

## 成果物

- triage: `.ai/specs/spec-20261105-002914.md`
- requirements: `.ai/specs/spec-20261105-002914.md`
- requirements: `.ai/specs/assets/20261105-002914/review.html`

## 直近の経路

- triage → requirements
- requirements → impl
- impl → review
- review ↩ impl（Major 2 件 open（利用規約 第 12 条の事前告知・効力発生日が無い／追跡物に絶対パス））
- impl → review
- review → pr

## 記録（判断・懸念・検証・環境・質問）

- decision [impl] 利用規約の追記は既存動作の説明であり第12条の『変更』（事前告知が要る）に当たらないと判断し、改定履歴で同日適用と明示した。法的判断として人の確認を求める。iOS 版の記載は案Aの範囲外として入れない … `events/20261104T154647-impl.yaml`
