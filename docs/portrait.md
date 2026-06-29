---
sidebar_position: 6
title: 顔アイコン
---

# 顔アイコンを調整する

一覧に出る顔アイコンの精度・人数・写りを変えられます。

**編集場所**：`MatchingGimmick > PortraitCapture` の **PortraitCaptureManager** コンポーネント

| 項目 | 既定 | 役割・変えるとどうなるか |
|---|---|---|
| Capture Camera | `CaptureCamera` | 撮影用カメラ（普段OFF）。 |
| Menu Controller | `MatchingMenuCanvas` | 撮影後に一覧の再描画を依頼する先。 |
| Slot Count | 30 | 同時に顔を出せる**最大人数**。増やすとメモリ消費増。 |
| Texture Size | 256 | 顔の解像度。上げると綺麗だが重い。 |
| Head Up Offset | 0.1 | 注視点を頭のどれだけ上にするか（m）。顔の写り位置調整。 |
| Camera Distance | 0.5 | 顔からカメラまでの距離（m）。寄り/引きの調整。 |
| Generic Eye Height | 1.4 | Genericアバター時の目線高さ（m）。 |
| First Shot Delay | 3 | 入室後、最初に撮るまでの遅延（秒）。 |
| Reshoot Interval | 10 | 在室者を撮り直す間隔（秒）。 |

:::note
顔がズレる→ Head Up Offset / Camera Distance、粗い→ Texture Size を調整。
:::
