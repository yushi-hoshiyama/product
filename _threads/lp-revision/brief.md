# LP表現改訂 — Brief

## 目的

`compliance.md` 5章のチェックリスト7項目を実LP (`lp.delne.jp`) に反映するための、
**具体的な書き換え案** を作成する。

## スコープ

- 現行LP原稿の問題箇所の特定 (compliance.md 5章ベース)
- 各項目に対する **before / after** 形式の書き換え案
- 修正の優先度 (🔴 高 / 🟡 中 / 🟢 低) ごとの実装スケジュール案

**注**: LP実物の改訂作業はオノゴロ側 (本スレッドは書き換え案の作成まで)

## スコープ外

- LP全体のリニューアル (本スレッドはコンプラベースの部分修正のみ)
- 新規セクション追加・新規訴求軸の追加 → 統合企画スレッドへ上申
- 広告コピー・SNS投稿文 → 他スレッド

## 既定モード

**壁打ちモード** で進める ([`_threads/consulting-mode.md`](../consulting-mode.md) 参照)。
ユーザー = シニアコンサルタント / 意思決定者、Claude = アナリスト兼スパーリングパートナー。
決め打ちで答えない、質問先行、批判的検証、決定事項は明示。

## 必読ファイル

- `CLAUDE.md`
- `projects/delne/product/summary.md`
- `projects/delne/marketing/strategy/compliance.md` (**特に5章**)
- `_threads/README.md`
- `_threads/consulting-mode.md`
- `_threads/active.md`
- `_threads/lp-revision/log.md`

## 成果物の格納場所

`projects/delne/marketing/lp/revision-proposals-<date>.md`

## 成果物のフォーマット (推奨)

````markdown
# LP表現改訂提案 (compliance.md 5章ベース)

作成日: YYYY-MM-DD

## 項目1: 「認知症進行抑制機能を持つ音声会話AI」

- **場所**: 第2期新機能セクション
- **課題**: 「進行抑制」効果の断定 (景表法・薬機法リスク)
- **Before**: <現行表現>
- **After 案1**: <書き換え案>
- **After 案2**: <代替案>
- **推奨**: 案1
- **優先度**: 🔴 高
- **備考**: <補足>

(以下同形式で項目2〜7)
````

## 完了定義

- compliance.md 5章の7項目すべてに対して書き換え案を作成
- 統合企画スレッドのレビューを受け、`_threads/active.md` 上で承認を得る
- 成果物を `projects/delne/marketing/lp/` に格納

## 他スレッドへの依頼が想定される事項

- **統合企画**: 修正の最終承認、複数案がある場合の優先度判断、新規セクション提案の判断
- **ブランドガイド**: トーン&マナー方針が確定したら参照
