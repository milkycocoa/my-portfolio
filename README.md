# StepStamp

## アプリ概要
Next.jsとSupabaseを用いた歩数×スタンプラリーアプリです。

## サイトイメージ
![アプリ画面](https://github.com/milkycocoa/my-portfolio/blob/ff8daea21a39dcd724cac44392ff25b4ac663c6f/docs/%E3%82%A2%E3%83%97%E3%83%AA%E3%81%AE%E3%82%A4%E3%83%A1%E3%83%BC%E3%82%B8%E7%94%BB%E5%83%8F.png?raw=true)

## サイトURL
https://stepstamp-hk.vercel.app/

## 使用技術
- フロントエンド：Next.js 16.2.0 
- バックエンド：Next.js 16.2.0 
- データベース：Supabase
- デプロイ：Vercel
- バージョン管理：Git、GitHub
- テスト・デバッグ：DevTools（Chrome）
- CI/CD：GitHub Actions（ESLint）

## 設計ドキュメント
[要件定義・基本設計・詳細設計の一覧_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1wSdGdiGyU9LGr3rd3vt0u2Dfvs1y3CO5R5jQeLjqeEY/edit?usp=sharing)

詳細設計時のワイヤーフレーム、ER図、ワークフロー図の画像はdocsディレクトリに格納しています。（[こちらからアクセス](https://github.com/milkycocoa/my-portfolio/tree/89cf0ec0115c4bd850cf5e9456c5b7e7eaa60de9/docs)）

## 機能一覧
- サインアップ・サインイン
- トップ画面での歩数表示・入力、今日のスタンプ獲得状況の表示、機能紹介
- プロフィールの編集（名前・アイコン画像）
- スタンプラリーの確認
- 歩数履歴の一覧表示・編集・削除

## テスト・修正の設計及び実施書_Googleスプレッドシート
[テスト・修正の設計及び実施書_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1Wyq0cSCFOK8s8yEVgwP4Drq9fi6H5SyN1-5APync4og/edit?usp=sharing)

## アプリの改善案
[アプリの改善案_Googleスプレッドシート](https://docs.google.com/spreadsheets/d/1rVSzfarbzm_mhnayAZpaIIE5IF1_-IhS2gULpS1DSlE/edit?usp=sharing)

## 備考
[ESLintの実行結果_GitHub Actions](https://github.com/milkycocoa/StepStamp/actions)
- 活用した生成AIとその用途
  - ChatGPT / Copilot：要件定義、設計、各種リサーチ
  - v0：アプリのモック作成
  - GitHub Copilot Chat：ローカル環境でのコードの修正や相談
