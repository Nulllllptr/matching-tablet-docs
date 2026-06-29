---
sidebar_position: 9
title: 召喚エリア
---

# 召喚できる場所を限定する

タブレットを召喚できる範囲を、特定エリア内だけに制限できます（未設定なら常にどこでも召喚可）。

**編集場所**：`MatchingGimmick > SummonArea` の **SummonAreaChecker** コンポーネント

- このオブジェクトに付いている **コライダー（トリガー）の大きさ・位置**で、召喚を許可する範囲を決めます。
- 範囲を変えたい時は、`SummonArea` の Box Collider などの **Size / Center**、またはオブジェクトの位置・スケールを調整します。

## 有効化のしかた

1. `MatchingGimmick > MatchingTablet > SummonController` の **MenuSummonController** の **Summon Area** 欄に、この `SummonArea` を割り当てる。
2. 割り当てると、エリア内にいる時だけ召喚できるようになります。
3. 制限を外したい場合は、Summon Area を **None（空）** にすればどこでも召喚可に戻ります。
