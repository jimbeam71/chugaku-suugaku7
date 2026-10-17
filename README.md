# 中学数学 レベル7（データの活用）

公開URL: https://chugaku-suugaku7.senta1111.workers.dev/

- 配信するのは `public/index.html` の1枚だけ（KaTeXの式表示も中に入っている）。
- 内容: 代表値 / 度数分布 / 四分位数と箱ひげ図。全7ステップ・49問。ヒストグラムと箱ひげ図は SVG を自動で描いている。
- 問題を直す・足すとき: `tools/gen7.js` を直す。
  1. `cd tools`
  2. `node gen7.js`（`src/data.js` を作る）
  3. `node check.js`（ALL OK が出ること）
  4. `node build.js --repo`（`tools/public/index.html` を作る）→ `public/index.html` に置きかえる
