---
issue: 3
pr: 4
flow: ai-default-medium
status: impl-running
outcome: null
evidence:
  spec_status: draft
  has_issue: true
  has_pr: true
  tasks_total: 0
  tasks_done: 0
  integration: none
  open_major: 2
  merged: false
  accepted: false
passed: [triage, requirements, impl]
attempts: { impl: 1 }
edges:
  triage->requirements: 1
  requirements->impl: 1
  impl->review: 1
  review->impl: 1
artifacts:
  triage:
    - .ai/specs/spec-20261105-002914.md
  requirements:
    - .ai/specs/spec-20261105-002914.md
    - .ai/specs/assets/20261105-002914/review.html
events: 20
---

# Issue #3 の索引

この索引は `events/` から機械的に生成される写しです。手で書き換えないでください（次の記録で上書きされます）。

- 現在地: `impl-running`
- フロー: `ai-default-medium` / 通過: `triage` → `requirements` → `impl`
- open な指摘: 9 件（Major 以上 2 件）

## open な指摘

- Minor `index.html:111` 「端末内のすべてのデータを削除するには」が、共有・保存先へ渡した PDF まで消えるように読める … `events/20261104T154201-review.yaml`
- Minor `.ai/work/3/events` decision / concern の event が 0 件 … `events/20261104T154202-review.yaml`
- Major `.ai/specs/spec-20261105-002914.md:19` 追跡物（spec と確認ページ）に開発機の絶対パスが入っている … `events/20261104T154209-review.yaml`
- Major `terms.html:34` 利用規約を改定したのに、第 12 条が約束する変更内容と効力発生日の事前告知が無い … `events/20261104T154412-review.yaml`
- Minor `index.html:111` 削除の制約を明記した改定を、10 章が約束する「重要な変更の告知」なしで出している … `events/20261104T154413-review.yaml`
- Minor `index.html:93` 5 章の保持期間の終わりに「ストレージを消去」が無く、7 章と揃っていない … `events/20261104T154414-review.yaml`
- Minor `terms.html:46` 利用規約 第 3 条の追記がプライバシーポリシーへリンクしていない … `events/20261104T154415-review.yaml`
- Minor `index.html:111` 物件・号室の個別削除は物件管理モードだけの機能だが、モードを書いていない … `events/20261104T154416-review.yaml`
- Minor `index.html:65` 加速度センサーの段落が権限一覧と「これらの権限で扱うデータは…」の間に入り、指す範囲が曖昧 … `events/20261104T154417-review.yaml`

## 成果物

- triage: `.ai/specs/spec-20261105-002914.md`
- requirements: `.ai/specs/spec-20261105-002914.md`
- requirements: `.ai/specs/assets/20261105-002914/review.html`

## 直近の経路

- triage → requirements
- requirements → impl
- impl → review
- review ↩ impl（Major 2 件 open（利用規約 第 12 条の事前告知・効力発生日が無い／追跡物に絶対パス））
