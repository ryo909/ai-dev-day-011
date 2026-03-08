# Day011 Story — Concept Gap Mapper

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day011専用にテーマをseed固定して再生成時の見た目を安定化
- learning用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: knowledge_gap
- Mechanic: dependency_mapping
- Input/Output: confusion_notes -> gap_map
- Audience Promise: clearer_study_path
- Publish Hook: 何が足りないかを前提マップで見える化
- Complexity Tier: small
- Selected components: none
- Complexity hint: Keep the tool single-purpose and stable. Add at most one safe enhancement component.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day011｜Concept Gap Mapper
つまずきポイントを前提不足として可視化する学習診断ツール。（話題:HN Frontpage）
