# ai-keiei-sanbo

AI経営参謀プロジェクト。Claude Codeを使って開発を学ぶためのプロジェクトです。

## 開発環境

- プラットフォーム: Windows 10
- シェル: PowerShell / Bash

## プロジェクト構成

```
ai-keiei-sanbo/
├── CLAUDE.md                                     # このファイル
├── .gitignore
└── 事業検証レポート_MeetMemo_2026-06-03.md       # MeetMemo事業検証レポート
```

## 成果物ログ

| 日付 | ファイル | 内容 |
|------|---------|------|
| 2026-06-03 | 事業検証レポート_MeetMemo_2026-06-03.md | 課題仮説・市場規模・競合調査・差別化ポイントをまとめた事業検証レポート |

## Git運用ルール

- **コードを変更するたびに、必ずGitHubにプッシュする**
- コミットメッセージは変更内容を日本語で簡潔に記述する
- リモートリポジトリ: `git@github.com:akihiro14/ai-keiei-sanbo.git`

### コミット・プッシュの手順

```bash
git add .
git commit -m "変更内容の説明"
git push origin main
```

## CLAUDE.mdの更新ルール

- 回答（実装・変更）のたびにこのファイルを更新する
- 新しい技術スタック・設計方針・ルールが加わったら追記する
