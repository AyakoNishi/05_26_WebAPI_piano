# 課題：03 Web audio API ～piano

デプロイ先：https://ayakonishi.github.io/02_26_JankenBaseball/

## プロダクトの紹介
- Web audio API を利用して、ブラウザでピアノを作りました。（コピペです）

## 工夫した点，こだわった点
- <audio>ではなく、Web audio API を使用すること
- ドラムや他の楽器も考えたけれど、ピアノであることにこだわりました

## 苦戦した点，共有したいハマりポイントなど
- まず、Web audio API を使っているサンプルを探すこと-> <audio>を使っていたり、Web audio API の説明が波形とか内部構造の説明になって、よく判らなかったこと -> 案１、案２をここでボツ
- map API を使用して、宇宙の画像と重ねる案を考えたが、思ったより天体の API がない、Google sky は面白くない -> 案３ボツ
- 調べ物に明け暮れて、週が明ける -> もう一度 Web audio API 方面に舵を切る -> ピアノのサンプルがあったので作ってみる -> １音階だけでなくもう少し広げたかったし、全画面でなく真ん中に持ってきたかったが、何故か<div>で囲むとsolid が消える   <= イマココ
- ここまでの記述の通り、まず使いたいAPIの使い勝手がよくなく、サンプルコードもあまり見つからなかったということが、苦戦した点でした
- サンプルの音源がちょっと危険そうだったので、他から取ってきたら、音鳴らないし
- コード元ネタ：https://liginc.co.jp/284679
- 音源元ネタ：https://maoudamashii.jokersounds.com/
- コピペのまんまですみません