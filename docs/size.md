---
sidebar_position: 5
title: サイズ変更
---

# タブレットのサイズ範囲を変える

各プレイヤーがタブレットの大きさを変えられます（角つかみ＝VR／数値入力＝デスクトップ）。製作者は**変えられる範囲**を設定します。

**編集場所**：`MatchingGimmick > MatchingTablet` の **TabletPinchResizer** コンポーネント

| 項目 | 既定 | 役割・変えるとどうなるか |
|---|---|---|
| Tablet Root | `MatchingTablet` | 拡縮する対象。 |
| Handle A / Handle B | ハンドル2つ | 対角コーナーの掴みハンドル。位置はタブレットの角に合わせる。 |
| Handle Visual A / B | — | ハンドルの見た目（任意）。割り当てるとリサイズモード中だけ表示。 |
| Min Scale Factor | 0.5 | サイズの**下限**倍率（数値入力の「1」に対応）。 |
| Max Scale Factor | 2.0 | サイズの**上限**倍率（数値入力の「100」に対応）。 |
| Size Input | 数値入力欄 | 1〜100で大きさを入力する欄（全角数字も認識）。 |
| Mode Label | — | リサイズモードのON/OFF表示（任意）。 |
| Save Persistent | true | サイズを各ユーザーごとに保存するか。 |

:::note
Min / Max を変えると、数値入力の 1〜100 が対応する実サイズの範囲が変わります。
:::
