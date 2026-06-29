---
sidebar_position: 4
title: 通知音
---

# 通知音を変える

通知音の素材・音量・種類を設定できます（実際の切替はワールド内の設定タブから各プレイヤーが行います）。

**編集場所**：`MatchingGimmick > MatchingTablet > TabletModel > MatchingMenuCanvas` の **TabletSettingsController** コンポーネント

| 項目 | 役割・変えるとどうなるか |
|---|---|
| Notify Audio | 通知音の AudioSource（`MatchSound`）。ミュート/音量/音源をこれに反映。 |
| Notify Clips | 通知音の候補。**Size を増やしてクリップを入れるだけで音を増やせます**（UIボタンの追加は不要）。 |
| Current Clip Label | 今選んでいる音の名前を表示するText（任意）。 |
| Mute Toggle | ミュート切替。**ONで無音**、OFFで鳴る。 |
| Volume Slider | 通知音量（0〜1）。初期音量はこのスライダーの Value で決まります。 |
| Preview On Change | 通知音を切り替えた瞬間に試聴を鳴らすか。 |
