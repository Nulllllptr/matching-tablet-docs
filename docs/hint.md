---
sidebar_position: 8
title: 起動ヒント
---

# 起動ヒントを変える

入室直後に頭の前へ出る操作ヒントの文言・表示時間を変えられます。

**編集場所**：`MatchingGimmick > HintCanvas` の **StartupHintController** コンポーネント

| 項目 | 既定 | 役割・変えるとどうなるか |
|---|---|---|
| Hint Canvas Group | — | 表示パネル（CanvasGroup付き）。 |
| Hint Text | — | 説明文Text。 |
| 文言（デスクトップ用 / VR用） | — | プラットフォーム別の表示文。召喚操作の案内など。 |
| Distance | 1.0 | 頭の正面どれだけ前に出すか（m）。 |
| Height Offset | 0 | 頭からの高さ補正（m。0で目線）。 |
| Generic Eye Height | 1.4 | Generic時の目線高さ（m）。 |
| Hold Seconds | 3 | 表示し続ける秒数（この後フェード開始）。 |
| Fade Seconds | 1 | フェードアウトにかける秒数。 |
