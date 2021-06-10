# 画像解析及び解析結果翻訳
##使用したAPI
- Google Vision API(画像解析)
- Google 翻訳API

## プロダクトの紹介
- 任意の画像をアップロードしてください
- 1.画像の要素抽出
- 2.感情分析
- 3.画像に含まれるテキスト検出
- 上記3点、Google Vision APIにて実施
- 4.抽出された要素(最大20個)が英単語で返ってくるので、翻訳
- 上記1点、Google翻訳APIにて実施
## 工夫した点,こだわった点
- 画像分析はほぼ引用です、すみません
- 配列を翻訳するのに苦労しました
- ずっとなんとなくやり過ごしてきてしまった配列と向き合う良い機会になりました
- 翻訳部分はほぼ自力で記述しました
- 日本語がすぐ見えてしまっては面白くないので、クリックで内容確認できるようにしました
## 苦戦した点,共有したいハマりポイントなど
- 翻訳を思い通りに動かすのに数日...
- 関数のことや配列が少し実感を持って理解できてきたような
- でもまだまだやりたかったこと達成できなかったので、実装早く終えられるようにしたい
- 子供の学習ツール想定で、CSSもっとPOPにしたかった
- 翻訳内容がカタカナや難漢字で返却されることが多かったのが予想外！子供向きではない
- あとで自分で見返しても有用.
