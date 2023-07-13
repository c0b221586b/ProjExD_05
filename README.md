# ゲーム のタイトル
階段上り（仮）


## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
・主人公キャラクターをキーボード操作し、階段を上っていく縦スクロールゲーム
・クリアはなし、失敗しない限り続いていく

## ゲームの操作方法
・Space押下で向いている方向に一段上る
・左Ctrl押下で向く方向を変換

## ゲームの実装
###共通基本機能
* 主人公キャラクターに関するクラス
* 階段に関するクラス
* 初期の階段を設置
* 階段を３つまで登れる

### 担当追加機能
###方向転換機能
* 左Ctrl押下で向きを変更
* 同時にcountの数値を押下回数に応じて増やす
* countの押下回数を2で割った余りを用いて、あらかじめ作成したこうかとんの向きのリストから画像をもってくる
### ToDo
- []　主人公キャラクターの進行方向の向きの設定
- 
### メモ
* 主人公の向きと動きに関係するcountはクラスの外で定義してある。

