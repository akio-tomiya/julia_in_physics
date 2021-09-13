「Julia in Physics 2021」とはオンラインWeb会議システムを利用した研究会です。

世話人:　富谷昭夫（大阪国際工科専門職大学）、永井佑紀（原子力機構）（順不同)

# 概要
[Julia](https://julialang.org/) は2018年にバージョン1が公開されたオープンソースの科学技術計算言語で、
Fortranの様に高速でかつPythonの様に生産性の高い言語である [[リンク](https://www.geidai.ac.jp/~marui/julialang/why_we_created_julia/index.html)]。
Julia は様々な分野において活用が始まっている。
本研究会では、主に物理研究においてのJulia の使用例や高速化手法について議論する。
また可視化、微分方程式の数値解法、統計・機械学習分野への応用例や実装例も議論の対象とする。
Julia を使ってみたい学部生/大学院生や興味のある研究者などの積極的な参加を歓迎します。

# 日時
2021/9/3(金)
13:30 ~ 

# 場所
Zoom

* ZoomのミーティングURLは、先着順500名様に限り、登録されたメールアドレスに送信されます。転載・転送は控えてください。
* URLが掲載されたメールは当日の朝までに送られます。

* 参加時の表示名は「登録時の名前＠登録した機関名」に設定してください。
* ノイズを防ぐためのミュートへご協力ください。
* 講演中はミュートで、質問は質疑の時間でお願いします。

# 議論場所

議論用の掲示板としてGithub discussions を用意しています。<br> 
[こちらからどうぞ](https://github.com/akio-tomiya/julia_in_physics/discussions)。

# 動画
[Youtube](https://www.youtube.com/playlist?list=PLckfF2jwCK3esroJw1B5WI9Xz7BJkDGMR)
の再生リストです。

# プログラム

講演はYoutube にアップロード予定(許可が出た講演のみ)。

### 0. 趣旨説明
講演者: 富谷 昭夫 <br>
講演時間: 13:30-13:35, 5分<br> 

## チュートリアル講演

### 1. "いまから使えるJulia言語"
講演者: 佐藤 建太 <br>
所属: 理化学研究所 生命機能科学研究センター <br>
主な著書: 1から始めるJuliaプログラミング [[Amazon](https://www.amazon.co.jp/1%E3%81%8B%E3%82%89%E5%A7%8B%E3%82%81%E3%82%8B-Julia%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0-%E9%80%B2%E8%97%A4-%E8%A3%95%E4%B9%8B/dp/433902905X) ],
[[コロナ社(電子版あり)](https://www.coronasha.co.jp/np/isbn/9784339029055/) ]<br>
Twitter: [bicycle1885](https://twitter.com/bicycle1885) <br>
講演時間: 13:35-14:10, 30分 +5分(質疑)<br> 
[スライド](https://www.bicycle1885.org/slides/2021/juliainphysics2021/#1)<br> 
講演動画: [Youtube](https://www.youtube.com/watch?v=4QBiTilaGgw&list=PLckfF2jwCK3esroJw1B5WI9Xz7BJkDGMR&index=1&t=196s)<br>
概要: 
Juliaをいまから使い始めるのに必要最低限の知識を概説する。Juliaの特徴と構文からはじめ、基本機能である型システムと多重ディスパッチを紹介し、標準ライブラリと外部パッケージでそれらがどう活用されているかを解説する。
<br> 

### 2. jupyterとGoogle colabで使うjulia入門
講演者: 長瀬 伊織 <br>
所属: 東北大学 理学研究科 <br> 
Twitter: [benkyouaho](https://twitter.com/benkyouaho) <br>
講演時間: 14:10-14:35, 20分+5分(質疑)<br> 
[スライド](https://drive.google.com/file/d/19C366zcp3K5w6GhY0Y45iZjzJS0WdbHr/view), 
[colabで使うJuliaのデモ](https://colab.research.google.com/drive/1a7XdlEM5HkkSxwJmjMxnpTFsSjK5m2jX?usp=sharing)<br> 
講演動画: [Youtube](https://www.youtube.com/watch?v=qNZcgHeSot8&list=PLckfF2jwCK3esroJw1B5WI9Xz7BJkDGMR&index=2)<br>
概要: 本講演では、jupyter-notebookや Google colaboratoryについての説明や、それらでjulia言語を用いる方法について説明していく。これらのipynb形式は必ずしも必要ではないが、教育やコードの公開で使われることが多いので、実際に触れてみることを推奨します。 <br> 

### 3. "Fortran から始めるJulia"
講演者: 永井 佑紀 <br>
所属: 原子力機構 システム計算科学センター、理化学研究所 革新知能統合センター<br>
講演時間: 14:35-15:00, 20分 +5分(質疑)<br> 
講演動画: [Youtube](https://www.youtube.com/watch?v=88P5kOy4E78&list=PLckfF2jwCK3esroJw1B5WI9Xz7BJkDGMR&index=3&t=3s)<br>
概要: 
本チュートリアルでは、数値計算をFortran言語を用いて行ってきた研究者を主に対象として、Julia言語の紹介を行う。特に、Fortranとの違いについて述べるとともに、FortranコードをJuliaコードに書き換える方法について述べる。<br>
また、チュートリアル講演中にリアルタイムでFortranのコードをJuliaのコードの書き換えるライブコーディングを行う予定である。<br>
[特設サイト：Fortranから始めるJulia](https://cometscome.github.io/JuliaFromFortran/build/)<br>

### 4. Zygote.jl/ Flux.jl のお話
講演者: 寺崎 敏志 <br>
所属: AtelierArith <br> 
講演時間: 15:00-15:35, 30分 +5分(質疑)<br> 
[スライド](https://atelierarith.github.io/zygote_flux_tutorial/#1), 
[講演資料](https://github.com/AtelierArith/zygote_flux_tutorial)<br> 
Youtubeへの掲載はありません<br> 
概要: 関数に対しその導関数を数値計算する自動微分は今日の機械学習・深層学習において
重要な要素技術になっている. 本チュートリアルでは自動微分をサポートする Zygote.jl 
を紹介する. 
さらにその上に構築されている機械学習ライブラリとして Flux.jl を紹介する. <br> 

### 休憩 10分

## 一般講演

<s>(プログラムはまだ確定していません。スケジュールは追って連絡いたします。)</s>

- 12分(発表)+2分(質疑)+1分(交代)
- 最大8人程度 (応募者が多数の場合には世話人が審査しますのでご容赦ください。)
- 研究内での使用例でなく、実装例のみでも良いとします。
- <s>下記のフォームよりご応募ください。</s> 締め切りました

### (招待講演) 1. "Juliaで解くThomas-Fermi方程式"
講演者: 川井 弘之 <br>
所属: 放送大学教養学部教養学科 <br>
講演時間: 15:45-16:00<br> 
[スライド](Kawai.pdf) <br>
講演動画: [Youtube](https://www.youtube.com/watch?v=YkH56AjKTZA&list=PLckfF2jwCK3esroJw1B5WI9Xz7BJkDGMR&index=4)<br>
概要: Juliaによって，Thomas-Fermi方程式を，狙い撃ち法と有限要素法を組み合わせて数値的に解く方法を説明する。
なお本講演は，Juliaの知識を前提としないので，幅広い参加者の方に聴いて頂ければ幸いである。 <br> 

### (招待講演) 2. "Juliaを用いたNMRスペクトルシミュレーション"
講演者: 與儀 護 <br>
所属: 琉球大学理学部 <br>
講演時間: 16:00-16:15<br> 
[スライド(pdf)](Julia_in_Physics_yogi.pdf)<br>
[スライド(アニメーションあり)](https://docs.google.com/presentation/d/e/2PACX-1vSklLYStE5spZCpKQI3ZUwOWxoVCu5gThBpGNvK2j-nrAudaobhXGb07fzO-ZRGv1YvdhF-29Z9LBuc/pub?start=true&loop=false&delayms=60000) <br>
講演動画: [Youtube](https://www.youtube.com/watch?v=TdZFuv8CIgI&list=PLckfF2jwCK3esroJw1B5WI9Xz7BJkDGMR&index=5)<br>
概要: 核磁気共鳴（NMR）は磁性や超伝導などの固体物性に関する研究手法の一つである。実験で得られたスペクトルの解析には、種々の相互作用を考慮した核スピンハミルトニアンの厳密対角化が用いられる。本講演ではJuliaを用いたシミュレーション例について概説する。 <br> 

### (招待講演) 3. "LatticeQCD.jlで始める格子QCD"
講演者: [富谷 昭夫](http://www2.yukawa.kyoto-u.ac.jp/~akio.tomiya/)<br>
所属: 大阪国際工科専門職大学 <br>
講演時間: 16:15-16:30<br> 
講演動画: [Youtube](https://www.youtube.com/watch?v=R5bNW6aEkuI&list=PLckfF2jwCK3esroJw1B5WI9Xz7BJkDGMR&index=6)<br>
概要: 
QCD(Quantum Chromo-dynamics)は原子核内部を記述する第一原理的な理論である。格子QCDは、そのための理論的枠組であるが計算コストが非常に高い事が知られている。
本講演では、Julia で実装された格子QCDの公開コードである[LatticeQCD.jl](https://github.com/akio-tomiya/LatticeQCD.jl)を紹介する。
<br>

### 4. スパコン・GPUでJuliaを使う：cTPQ状態法を舞台に
講演者: 山田 昌彦 <br>
所属: 大阪大学・基礎工学研究科 <br>
講演時間: 16:30-16:45<br> 
[スライド](yamada_julia.pdf) <br>
講演動画: [Youtube](https://www.youtube.com/watch?v=MhGcm5KMW4c&list=PLckfF2jwCK3esroJw1B5WI9Xz7BJkDGMR&index=7)<br>
概要: 
Juliaの魅力の一つはそのマルチプラットフォーム性にあり、スパコン・GPUでも大規模並列化したコードが容易に記述できる点にある。
今回はSU(N)ハイゼンベルク模型をcTPQ状態法を用いて有限温度計算するプログラムを例として、MPI.jlやCUDA.jlの使い方を解説する。<br>

### 休憩 10分

### 5. ShellModel.jl: Julia言語を用いた原子核理論のためのCI計算コード
講演者: 吉田 聡太<br>
所属: 宇都宮大学<br>
講演時間: 16:55-17:10<br> 
講演動画: [Youtube](https://www.youtube.com/watch?v=c2XILu5IJqI&list=PLckfF2jwCK3esroJw1B5WI9Xz7BJkDGMR&index=8)<br>
概要: 
核子の多体系である原子核は、核力にまつわる原理的困難から定量的な理解・理論予測が非常に難しい系である。
そうした原子核の静的な性質(核構造)を理論的に調べる上で、配置間相互作用法(CI計算)は必須のアプローチとなる。
講演ではJulia言語を用いた計算コード[ShellModel.jl](https://github.com/SotaYoshida/ShellModel.jl) について[https://arxiv.org/abs/2105.08256](https://arxiv.org/abs/2105.08256) とあわせて紹介する。<br>

### 6. juliaによる二次光学応答の実装とその可視化	
講演者: 吉井 真央 <br>
所属: 東京大学物理工学専攻 <br>
講演時間: 17:10-17:25<br> 
講演動画: [Youtube](https://www.youtube.com/watch?v=tH1tgYw9030&list=PLckfF2jwCK3esroJw1B5WI9Xz7BJkDGMR&index=9)<br>
概要: 
julia言語では * と . を上手く使う事によって感受率テンソルをすっきりと記述することができます。
本講演では簡単なモデルに対する実装例を紹介します。<br>

### 7. 次世代型CMB観測実験のための全天スキャンシミュレータ
講演者: 髙瀬 祐介<br>
所属: 岡山大学<br>
講演時間: 17:25-17:40<br>
講演動画: [Youtube](https://www.youtube.com/watch?v=KD5pPg0XNsM&list=PLckfF2jwCK3esroJw1B5WI9Xz7BJkDGMR&index=10)<br>
概要: 
宇宙背景放射などの観測を行うためには検出器に取り付けたアンテナを回転させることで空の一部・もしくは全域をスキャンする必要がある．
本講演では観測衛星による空のスキャンを高速に行い，
時系列データを取得する[Falcons.jl](https://github.com/yusuke-takase/Falcons.jl.git)を紹介する.<br>

### Closing remarks (5分)

# 参加<s>or 登壇</s>応募フォーム

参加したい方は下記よりお申し込みください。
<s>登壇希望の方は、必要情報をご入力ください。</s> (登壇者募集は締め切りました。)
参加URLのついたアナウンスのメールを送信します。<br>
 
<center>
<a href="https://docs.google.com/forms/d/e/1FAIpQLSeZFI5S7xPB9LpY_72m1EGJQrnyFoXN2lrNj6sXep8iETjFPQ/viewform">登録フォーム</a>
</center> 
<br>
(締切は前日の夜11時までとします)

# 連絡先

akio[ _ AT _ ]yukawa.kyoto-u.ac.jp




