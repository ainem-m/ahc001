第一回 AHCをみんなで解く会コンテストのための記事です。

[https://t.co/vHjwGPXblm:embed:cite]



[:contents]



## ローカルテストの必要性
ジャッジに投げるだけだと

* 提出制限があり、短時間に何度も提出できない
* テストケースの偏りにより、最終ジャッジでは点数が下がる可能性がある
* ビジュアライザによる分析ができない

## 難易度別ローカルテスト
難易度は私の主観で決めています。

### レベル１ Webビジュアライザを使う
環境構築の必要性ゼロ！！
[AHC001ビジュアライザ](https://kenkoooo.github.io/ahc001-gen-vis-wasm/)
#### 入力の準備
<figure class="figure-image figure-image-fotolife" title="generate">[f:id:ainem:20221013120819p:plain]<figcaption>generate</figcaption></figure>
ビジュアライザのSeed:の欄に好きな数字を入れてGenerateをクリック
<figure class="figure-image figure-image-fotolife" title="input">[f:id:ainem:20221013120847p:plain]<figcaption>input</figcaption></figure>
すると、input:欄に標準入力が形成されるのでコピー
(ctrl+A / cmd+Aで全て選択してコピーすると楽ちん)
#### 出力の準備
[コードテスト](https://atcoder.jp/contests/ahc001/custom_test)なり、IDEなりでプログラムを実行し、出力をコピー
#### 結果のビジュアライズ
output: 欄に貼り付けて、Visualizeを実行
<figure class="figure-image figure-image-fotolife" title="output">[f:id:ainem:20221013120901p:plain]<figcaption>output</figcaption></figure>
#### 考察
結果を眺めて、アイデアを出す

### 〜環境構築の壁〜
みなさん、競技プログラミングをするときには何を使ってコードを書いていますか？
私はしばらく[コードテスト](https://atcoder.jp/contests/ahc001/custom_test)を使っていました。
なぜか？そう、**環境構築**の壁が立ちはだかるからですね。
環境構築とは、プログラムの実行環境を整えることです。書いたプログラムを、自分のPCで動かせるようにする、ただそれだけなんですけどね…
使っているOSによってやり方が違ったり、昔の記事がアテにならなかったり、エラーの内容が多岐にわたっていたりで、非常につまづきやすいポイントだと思います。
中には黃や橙レートの、私からみて現人神のような方々でさえ、環境構築は難しいとおっしゃっているので、私なんかが説明するのは無理です…
**<font size = 5>ググってくれ！！</font>**

### レベル５ ローカルテスターを使う
環境構築が必要
