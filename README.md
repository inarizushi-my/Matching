# マッチングフォームアプリ

このWebアプリは、**演奏者と曲のマッチング**を目的とした登録フォーム＆閲覧サイトです。  
React + Vite + Tailwind CSS を使用して作成されています。

---

## ローカル環境での起動方法

### 必要な環境

- Node.js (v16以上)
- npm

Node.jsが未インストールの場合は、[公式サイト](https://nodejs.org/ja) からインストールしてください。

---

### セットアップ手順

1. **このリポジトリをクローン**

   `git clone https://github.com/inarizushi-my/Matching.git` 
   `cd Matching`

2. **依存パッケージをインストール**

   `npm install`
   
3. **開発用サーバーを起動**

   `npm run dev`

4. **ブラウザでアクセス**

   http://localhost:5173 を開いて確認

---

### ディレクトリ構成（抜粋）

```text
src/
├── components/       # 各コンポーネント（フォーム・リスト・詳細など）
├── data/             # サンプルJSONデータ（仮DBとして使用）
├── pages/            # ホーム画面など
├── App.jsx           # ルーティング設定
└── main.jsx          # エントリーポイント

