# やすらぎ茶舗 — サンプルホームページ

ローカルで開くだけのシンプルな静的サイトです。

使い方:

- ブラウザで直接開く (エクスプローラーから `index.html` をダブルクリック)
- PowerShell から開く:

```powershell
Start-Process .\index.html
```

- ローカルサーバーで確認する（推奨）:

```powershell
cd .\
python -m http.server 8000
# ブラウザで http://localhost:8000 を開く
```

必要なファイル:

- `index.html` — ページ本体
- `styles.css` — スタイル
- `assets/cup.svg` — プレースホルダー画像

カスタマイズ案:

- メニューや商品一覧を増やす
- 画像を差し替える（`assets/` に追加）
- SNSリンクやGoogleマップ埋め込みを追加
