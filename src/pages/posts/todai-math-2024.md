---
layout: "../../layouts/MarkdownLayout.astro"
title: "「東大理系数学2024」解いてみた"
date: "2024年6月30日"
pubDate: "2024-06-30"
update: ""
description: "テスト用に、以前noteに投稿した記事を載せてみます。"
tags: ["大学受験", "数学", "2024"]
---

テスト用に、以前 note に投稿した記事を載せてみます。

家庭教師をやりたいと思ってリハビリ程度に解いてみたやつです。
<br><br><br>
![五月祭準備中の東大本郷キャンパス安田講堂前](../../assets/images/IMG_4662.JPG)

<span class="img-des" style="margin-top: 10px;"><i class="ri-arrow-up-line"></i>&nbsp;五月祭準備中の東大本郷キャンパス安田講堂前</span>
<br><br><br>
<span class="font-medium" style="font-size: 20px">【講評】東大理系数学 2024</span>
<br><br>
<span class="font-medium" style="font-size: 20px">第 1 問</span>
<br><br>
まずは素直に問題の状況把握をします。角度に関する条件から各ベクトルについて内積を用いるのは自然な発想でしょう。直交座標でいくか極座標でいくかなどのバリエーションはありますが、あとは条件から得られた不等式を変形させていくだけの問題です。
<br><br>
第 1 問で多くの受験生が解いている可能性が高いですし、確実に取っておきたいですね。
<br><br><br>
<span class="font-medium" style="font-size: 20px">第 2 問</span>
<br><br>
初めに各設問に一通り目を通すことが望ましいです。(3)で関数の最大最小が聞かれていることから、(1)で (第 1 次導関数) $${=0}$$ の解を聞く理由も自ずと分かってきます。初めに最後の設問まで見ておくことで一連の流れを頭に入れながらスムーズに問題を解くことができます。
<br><br>
(1)では $${f(x)}$$ は非積分関数に絶対値がありそのままでは積分できないので、定石通り絶対値を外すことを考えます。解いてみると積分可能な形が綺麗に出てきます。あとは置換積分を用いて答えを導くことができます。
<br><br>
この時点で $${x=tanα}$$ を境に第 1 次導関数の符号が負から正に変化することが分かります。ここまで先を見据えておく必要はないと思いますけどね。
<br><br>
(2)は素直に $${tanα}$$ の値を求めるだけです。わざわざ設問を作る必要があるのかと思ってしまうような問いです。
<br><br>
(3) $${f'(x)}$$ の符号変化から $${x=tanα}$$ で $${f(x)}$$ が最小値を取るのはすぐに分かるでしょう。あとは最大値をどちらの端点で取るかということですが、それぞれ $${f(x)}$$ の値を求めるとそこまで厳密な評価をすることなくその答えが分かります。最小値は計算ミスをしないように慎重に求めましょう。
<br><br><br>
<span class="font-medium" style="font-size: 20px">第 3 問</span>
<br><br>
設問に目を通した印象から対称性を用いる確率漸化式の問題だと考えられます。
<br><br>
(1), (2)は実験をすることで見えてきます。(2)は対称性を素直に記述すれば大丈夫だと思います。
<br><br>
(3) いつも通り各点に存在する確率を文字でおくと 4 つの漸化式が出てきます。漸化式を解くことが目的なので、文字を減らすことを考えます。適当な 2 式を足し合わせることで、 $${n}$$ の偶奇によりあるいくつかの点に存在する確率の和が一定であるという式が出てきます。これを用いれば一つの文字に関する漸化式を導くことができ、定石通りに解くことで答えを求めることができます。
<br><br>
$${n}$$ の偶奇による場合分け、対称性は確率漸化式では定番です。たくさん問題を解いて慣れておきましょう。
<br><br><br>
<span class="font-medium" style="font-size: 20px">第 4 問</span>
<br><br>
とりあえず与えられた条件を文字式に変換することを考えます。
<br><br>
(1) 解き方は色々ありますが、僕は共通接線の方向ベクトルが、円 $${C_t}$$ と接点を通る直線の法線ベクトルとなっていると考えこの直線の方程式を求めることで $${c(t)}$$ を導きました。 $${\{{r(t)}\}^2}$$ は三平方の定理から求めます。
<br><br>
(2)もまず条件を式で表します。円 $${C_t}$$ が点 $${(3, a)}$$ を通るという条件を式にすると $${t}$$ に関する 4 次式が出てきます。結局、 $${a}$$ が $${0 < a < f(3)}$$ のある値を取るときにこの式を満たす $${t}$$ $${(0<t<4)}$$ がいくつ存在するかという問題に帰結することができました。
<br><br>
この 4 次式は具体的に求められているので、定数分離しグラフを書いて解の配置をしていきます。 $${a}$$ による場合分けはありますがそこまで難易度は高くないと思います。
<br><br><br>
<span class="font-medium" style="font-size: 20px">第 5 問</span>
<br><br>
回転体の体積を求める問題です。
<br><br>
ある軸をとりそれに垂直な方向に微小部分の体積を足し合わせていくことが定石ですが、今回は x 軸方向に足していくことになります。 $${t}$$ $${(0< t<1)}$$ をおき、三角形 $${ABD}$$ の周および内部を $${x=t}$$ で切断したときの線分を x 軸中心に回転させたときにそれが通過する部分を考えます。
<br><br>
線分を回転させるときは線分と軸との最短距離が重要になります。線分の方程式はどこで切っても同じなので最短距離が端点であるときと端点以外の場合で場合分けするのが良いでしょう。
<br><br>
計算量はありますがシンプルな問題設定なので取っておきたい問題です。
<br><br><br>
<span class="font-medium" style="font-size: 20px">第 6 問</span>
<br><br>
前半で具体的に実験しそれが一般に言えることを示す問題です。
<br><br>
(1) $${f(x)=x(x^2+10x+20)}$$ と因数分解すると、これが素数になるには $${x}$$ あるいは $${x^2+10x+20}$$ が $${\pm1}$$ であることが必要です。また、 $${x}$$ が負のときは $${x^2+10x+20}$$ が負であることが必要です。
<br><br>
このように考えると $${n}$$ は 3 つ求められます。
<br><br>
(2) (1)と同様に考えます。 $${f(n)}$$ が素数になる $${n}$$ は 6 個以下であることはすぐに分かりますが、それをいかに 3 つ以下にするかという問題です。そこでこの 6 つのうち一番満たしにくいものを考えます。
<br><br>
制約の強い条件は、「 $${x^2+ax+b=\pm1}$$ を満たす $${x}$$ が符号を許して素数となる」ことが挙げられます。（整数解を持つ上にここで $${n}$$ が最大 4 つ考えうるため）
<br><br>
この 2 式を変形すると 2 式がそれぞれ素数解を持つことに矛盾が生じ、この部分で $${n}$$ は最大 4 つにまで減らすことができます。
<br><br>
あとは 3 つにまで減らせれば良いのですが、色々やってみるしかない感じはあると思います。考えてみると、「 $${n=\pm1}$$ で $${g(n)}$$ が素数」の下で「 $${x^2+ax+b=1}$$ （ $${x^2+ax+b=-1}$$ も同様）が素数解を 2 つ持つ」ことが起こり得ないことが分かります。（つまり $${n}$$ は 3 個以下）
<br><br>
整数問題は難しくなりがちです。ある式変形をするだけで簡単に解けるのにそれに気づけなかった場合や、色々試した上結局解けず時間を無駄にする場合が多々あります。もちろん解けるように練習することは大事ですが、試験では戦略的に飛ばすなどの選択も必要だと思います。（今回のように他の大問で計算量が多いなどの場合は尚）
<br><br><br>
<span class="font-medium" style="font-size: 20px">総評</span>
<br><br>
今年度は近年の東大理系数学の中でもそこそこ簡単な部類に入ると思います。上位に食い込むには 6(2)以外は完答することが望ましいです。一方、各大問計算量は少なくなく計算力が求められていたように感じました。普段から速くかつ間違えずに計算することを心がけたいです。
