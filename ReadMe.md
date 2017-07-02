## The Smart Fly

- 遺伝的アルゴリズム([GA](http://www.sist.ac.jp/~kanakubo/research/evolutionary_computing/genetic_algorithms.html))を使ったシミュレーションゲーム
- Unity WebGL上で動きます．

### 目的
- 蚊が人の血を好んでいきます，しかし限られた生命(lifetime)の中障害物を超えて，未知の目的に達成するのは難しい．ここで生物進化の力(遺伝的アルゴリズム)を用いて，蚊の大家族がどう進化していき，最終的に人の血を吸える「エリート蚊」が誕生する一部始終をシミュレーションで再現します．

### 遊び方
1. 数値(Population size[個体群]，crossover rate[交差確率]，mutaton rate[突然変異確率],lifetime)を設定して, saveを押してください．標準設定は以下になります．
   - Population size: 100
   - crossover rate: 0.8
   - mutation rate: 0.01
   - lifetime: 300
2. startして，初期の蚊達が生み出されます. クリックで石を配置して，ハエの通行を邪魔できます．
3. 蚊は進化の力で人に届く経路を学習していきます．(難しいすぎる経路だと学習が遅くなる，簡単なトンネルが学習しやすい.)
4. 交差確率や個体群などの数値を変更する事で, 各パラメータが生物進化に対する影響の理解が理解せ来ます．
