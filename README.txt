お世話ゲーム 最終アンケート public フォルダ

このフォルダをそのまま GitHub Pages / Netlify / Firebase Hosting などの public としてアップロードできます。

構成
- index.html：アンケート本体
- assets/pets/：50種類の相棒シルエット画像
- assets/pets/pet_silhouette_map.js：画像名の対応表

使い方
1. public フォルダを公開先に置く
2. Google Apps Script に送信する場合は、index.html 内の GAS_ENDPOINT にURLを入れる
3. ゲーム終了画面から次のように開く
   ./survey/index.html?research_id=XXXX&condition_id=C1&character_id=pet_01&language=ja

注意
- 「お世話相性度 59%」のような単一スコアは表示しない設定です。
- 結果画面では、お世話プロフィール8軸と、相棒シルエット、ひとことメッセージだけを表示します。
