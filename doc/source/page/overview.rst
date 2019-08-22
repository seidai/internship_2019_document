================================================
どう実現するか
================================================

システムの全体図
================
.. image:: /img/chapcher1.png
   :scale: 100%
   :height: 400px
   :width: 800px
   :align: left

| 上記のシステムを開発するために、
| 今回は「Google Homeチーム」「ドローンチーム」の２チームに分かれて作業をします。
| ※チーム分けは後ほど行います。


データベースのイメージ
===========================
.. image:: ../img/realtimeDatabase.png
  :scale: 100%
  :height: 400px
  :width: 800px
  :align: left



使うもの
================

| 【Google Homeチーム】

 * ノートPC（Windows10）
 * マウス
 * 電源ケーブル（ノートPC用）

 * Google Home mini
 * 電源ケーブル（Google Home用）


| 【ドローンチーム】

 * ノートPC（Windows10）
 * マウス（Raspberry Pi用）
 * 電源ケーブル（ノートPC用）

 * ドローン (Parrot Mambo)
 * バッテリー（ドローン用）
 * バッテリー充電器（ドローン用）

 * Raspberry Pi 3 B+
 * 電源ケーブル（Raspberry Pi用）
 * キーボード（Raspberry Pi用）
 * マウス（Raspberry Pi用）
 * ディスプレイ（Raspberry Pi用）

 * LANケーブル


今回は、コントローラーを使わずに声でドローンを操作できるようにします。
