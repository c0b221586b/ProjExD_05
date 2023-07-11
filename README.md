# ゲーム のタイトル
階段上り（仮）

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公キャラクターをキーボード操作し、階段を上っていくゲーム
クリアはなし、失敗しない限り続く

## ゲームの操作方法
スペースキー押下で向いている方向に一段上る

## ゲームの実装
###共通基本機能
* 主人公キャラクターに関するクラス
* 階段に関するクラス

### 担当追加機能
* スコア・タイマー機能　村重
* 方向転換機能          横川
* 無限スクロール機能    竜崎
* 階段の生成機能        三宅
* 落下時処理機能        町田

### ToDo
- [ ]　主人公キャラクターがジャンプするときの判定
- [ ]  変数名の統一

### メモ
* すべてのクラスに関係する関数は，クラスの外で定義してある
