# fashion-x-images

X（Twitter）予約投稿用の画像置き場。Buffer が公開URL（raw.githubusercontent.com）から画像を取得する。

## フォルダ構成

```
2026/
└── 2026-11-16_week/      # 週の月曜日の日付 + _week
    ├── 1116-morning.jpg  # 月曜 朝（独白）
    ├── 1116-noon.jpg     # 月曜 昼（独白）
    └── 1116-night.jpg    # 月曜 夜（アフィリエイト）
test/                     # 動作確認用（本番の投稿には使わない）
```

- ファイル名は `MMDD-<枠>.<拡張子>`。枠は `morning` / `noon` / `night`
- 投稿の時刻になるまで、該当の画像を削除・移動しない（Buffer が公開時に取得する）
- 画像は加工せず、元のまま置く

## 公開URL

```
https://raw.githubusercontent.com/registersub95-a11y/fashion-x-images/main/<パス>
```
