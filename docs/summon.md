---
sidebar_position: 3
title: 召喚・しまう・投げ
---

# 召喚・しまう・投げを調整する

タブレットの出し方・戻し方・投げ具合を変えられます。

**編集場所**：`MatchingGimmick > MatchingTablet > SummonController` の **MenuSummonController** コンポーネント

| 項目 | 既定 | 役割・変えるとどうなるか |
|---|---|---|
| Home Transform | `MenuHome` | しまう／自動帰還で戻る定位置。 |
| Summon Area | — | 召喚を許可するエリア。未設定なら常に召喚可。→ [召喚エリア](./summon-area) |
| Forward Distance | 0.6 | 召喚時、体の前にどれだけ出すか（m）。 |
| Spawn Height | 1.2 | 召喚時の高さ（m・足元基準）。 |
| Rotation Offset Euler | (0,0,0) | 召喚時の向き補正。傾けて出したい時に。 |
| Desktop Summon Key | E | デスクトップの召喚キー。 |
| Desktop Return Key | None | デスクトップの「しまう」キー。None で無効。割り当てると離れた場所からも戻せます。 |
| Double Click Interval | 0.4 | VR：左トリガー・ダブルクリックの判定時間（秒）。 |
| Return Distance | 3.0 | 自動帰還：プレイヤーがこの距離以上離れたら戻る（m）。 |
| Away From Home Distance | 0.5 | 定位置から離れたと判定する距離（m）。 |
| Throw Boost | 1.5 | 投げる強さの倍率。大きいほど飛びます（2.0〜3.0で強め）。 |

:::note
さらに飛ばしたい場合は `MatchingTablet` の Rigidbody の Mass（軽く）・Drag（小さく）も効きます。
:::
