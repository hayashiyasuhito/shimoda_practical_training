# shimoda_practical_training

## 入力ファイルの作成
- 入力するcsvファイルは、海底から上がってくるときのデータのみに整形する必要があります。深度や塩濃度、turbidityの値を見て、海底から表層まで(空中に出る直前まで)のデータを切り出し、別ファイルとして保存してください。
- 実習では、湾内と外海の2カ所で測定する場合が多いかと思います。それぞれ、20201126_uchi.csvや20201126_soto.csvのようなファイル名で保存してください

## jupyter notebook上での作業
- 2つめのcellでcsvファイルを読み込みます。ディレクトリは自分で直してください
- 3つめのcellを実行すると、それなりにまとまったグラフが出てきます。suptitleの中身とfnameをそれなりに直してください。

## 和田先生による説明
CTDセンサー、海洋学で必須。赤が外海、青が湾内。縦軸は深さ。5つのグラフなにかを順に説明。クロロフィルは植物プランクトンの量を示す。湾の中と外海を比較していこうと思う。例えば水温、湾の外2.1.5℃、湾の中〇〇℃。特に湾の中の表面、水温が低い。このデータ、塩分と比べてみる。湾の外は変化が少ない。湾内、表面で低い値。この違いはおそらく、わんのなかの奥に川がある。いのうざわがわ。そこの川の水が入ってきている影響だといえる。真水は海水より軽いので、特に塩分の低い水が海の表面をすべることで。今気温、11月、十何度。川の水は気温を強く反映。表面の水、冷たい。河川から流入したんだろう。河川から入ってきた水、栄養塩が多い。それらは植物プランクトンの栄養になる。→クロロフィル濃度が上昇。栄養塩で植物pルアンクトンの活性が増加して増殖したと思われる。クロロフィル、内海、下のほうが濃い。珪藻とかは栄養塩が多いと増えやすいが、遊泳性を持たないので湾の中のように波が落ち着いている環境では下に落ちていく。下にたまる。底にたまった植物プランクトンの値を平って高い値が出ているのであろう。下のほうに有機物の粒子が溜まっていくことで、濁度も海底で増加していることが見て取れる。ドレッジで見れた黒い泥、ああいうのは撒きあがりやすい。DOを見てみると、湾の中と外で違うのがわかる。湾の中で表層で高いのは、光合成によって生産されたものであろう。彼らが死んだり落ちて行ってしたにたまると、バクテリアが有機物を消費して酸素も消費される。このとき表層と底で水が混ざったらいいんだけど、塩分が低い河川水のため混ざらず、下でバクテリアによる消費が多い状態に。表層の水は冷たいが、温度より塩濃度のほうが効いているのであろう
ベントスの中で酸素に弱いやつ、シズクガイとか。湾内でよくみられる。このような環境パラメータに対して指標生物がどんなものだったか、見てみます。
港のこれ。スピオ科と差し歯誤解。かなり特定の種類に偏っている。
外海とか、いろいろ。
一般に環境がきつい状態、なにかしらどーんと一気に変わる状態、生物多様性が落ちるとされる。つくば２とかのあたり、波とかも入ってこず海底に沈殿。海底が貧酸素に。生物にとってきつい環境。
湾内のほうみてみても、著しく酸素が落ちているわけではなかった。そのため生物相にもあまり聞いていないのだろう
