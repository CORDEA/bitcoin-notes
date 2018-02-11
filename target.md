# Target

- 全ての Bitcoin client が共有する 256 bit の値
- block の hash はこの target 以下でないといけない。
  - target は小さいほど block の生成が難しくなる
- miner は繰り返し hash を計算して正解を見つけるが、この正解は hash が target よりも小さい値であることが条件となる
- この値は難易度に影響するため、 2 週間に一度修正される
  - 概ね 10 分に一度 block が生成される難易度に調整される


## Value

- target 以下でないといけないとはどういうことか
  - https://www.anintegratedworld.com/what-does-hash-lower-than-a-bitcoin-target-mean-with-example/