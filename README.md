# Pair Shot

2枚の横4:3写真を上下に並べ、1枚の縦2:3画像として保存するカメラ体験のプロトタイプです。

## Prototype

- iPhone縦持ちのまま横4:3でプレビュー
- シャッターを2回押して1組を完成
- 1枚目と2枚目の間で前面 / 背面カメラを切替可能
- 1枚目を画面上段に残したまま2枚目を撮影
- 2枚を1600 x 2400のJPEGへ結合
- iPhoneでは「保存 / 共有」から共有シートを開き、「画像を保存」で写真ライブラリへ保存可能
- ホーム画面追加に対応するPWA構成
- バックエンド / ログイン / DBなし

## GitHub Pages

GitHub Pagesを有効にする場合:

1. Repository **Settings**
2. **Pages**
3. Build and deployment の Source を **Deploy from a branch**
4. Branch を **main**、folder を **/(root)**
5. Save

公開URLは通常:

`https://kanipaseri.github.io/pair-shot/`

カメラAPIはHTTPS環境が必要なので、GitHub Pages上で試してください。

## Notes

この版は撮影体験の検証を優先したプロトタイプです。ブラウザからiOS写真ライブラリへ無操作で直接書き込むことはできないため、保存時はiOS共有シートを使用します。
