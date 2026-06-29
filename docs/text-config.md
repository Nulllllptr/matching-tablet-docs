---
sidebar_position: 2
title: 文言・タブ名
---

# 文言・タブ名を変える

ボタンやタブの文字を変えられます。

**編集場所**：`MatchingGimmick > MatchingTablet > TabletModel > MatchingMenuCanvas` の **MatchingTextConfig** コンポーネント

| 項目 | 既定 | どこに表示される |
|---|---|---|
| Label Interested | 気になる | ユーザー一覧：未操作の行ボタン |
| Label Mistake | 間違えた！ | 「気になる」を押した後（取り消し可）の表示 |
| Label Matched | お楽しみ♡ | 相互成立（押せない）時の表示 |
| Label Consent | 同意 | いいね一覧：未同意の行ボタン |
| Label Consent Done | 同意済 | 同意済（押せない）の表示 |
| Tab User List Name | ユーザー一覧 | タブ名 |
| Tab Interested In Me Name | 気になられてる人 | タブ名 |

:::note
タブ名（Tab ～ Name）は、`MatchingMenuController` のタブ名Text参照（Tab User List Label / Tab Interested In Me Label）を割り当てている場合のみ反映されます。
:::
