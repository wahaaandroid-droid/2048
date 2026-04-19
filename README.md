# 2048 クローン（Vercel）

`index.html` のみの静的サイトです。Vercel にデプロイすると URL から遊べます。

## デプロイ手順（推奨: GitHub 連携）

1. このフォルダを Git リポジトリにして GitHub に push する。
2. [Vercel](https://vercel.com) にログインし、「Add New… → Project」でリポジトリを Import する。
3. **Framework Preset** は **Other** のまま（または自動検出に任せる）。
4. **Root Directory** はこのリポジトリがゲーム一式のルートならそのまま。
5. **Build Command** / **Output Directory** は空でよい（ビルド不要）。
6. Deploy を実行する。完了後に表示された URL でプレイ可能。

## CLI でデプロイする場合

```bash
cd 2048クローン
npx vercel
```

本番反映:

```bash
npx vercel --prod
```

初回はブラウザまたはトークンで Vercel にログインが必要です。
