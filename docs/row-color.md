---
sidebar_position: 7
title: 行ボタンの色
---

# 行ボタンの色を変える

一覧の各行ボタンの色を、状態ごとに変えられます。

**編集場所**：`MatchingGimmick > MatchingTablet > TabletModel > MatchingMenuCanvas > TemplateHolder > PlayerEntryTemplate` の **PlayerEntryController** コンポーネント

| 項目 | 役割 |
|---|---|
| Normal Color | 通常（気になる/同意）の色 |
| Cancel Color | 「間違えた！」時（取り消し可）の色 |
| Locked Color | ロック中のグレー |
| Matched Color | 成立（お楽しみ♡）時の色 |
| Icon Image | 顔アイコンの RawImage（通常そのまま） |
| Button Image | 色を変える対象の背景Image（未指定なら自動取得） |

:::note
行は実行時に複製されます。色は必ず**ひな型（`PlayerEntryTemplate`）側**を編集してください。
:::
