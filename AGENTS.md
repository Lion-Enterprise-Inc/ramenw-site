# RAMEN W shared project packet

このリポジトリはClaude Code専用でもCodex専用でもない。作業者は、開始時に次を読む。

1. `C:\dev\shingo-brain\SOUL.md`
2. `C:\dev\shingo-brain\INDEX.md`
3. `C:\dev\shingo-brain\ai-work\LEDGER.md`
4. `C:\dev\shingo-brain\projects\ramen-w.md`

案件パケットの正本は `projects\ramen-w.md`。`owner_ai` は現在の表示情報であり、作業可否を制限しない。Claude CodeでもCodexでも、同じ案件ファイル・同じ実装repo・同じ検収条件を使う。

作業開始前に、次を実行して正本repoと現在のGit状態を確認する。

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File C:\dev\shingo-brain\scripts\brain-project-preflight.ps1 -Path (Get-Location).Path
```

資料置き場は `C:\dev\hp-projects\ramen-w`。実装の正本はこのリポジトリであり、資料置き場のREADMEを実装状態の正本として扱わない。

変更後は、案件ファイルに記載された現在地・決定事項・要確認・完了条件と照合する。公開・外部送信は髙橋さんの明示GOなしに行わない。
