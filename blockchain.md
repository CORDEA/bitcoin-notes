# Blockchain

- Bitcoin のコアイノベーション
- hash の計算にその前の hash を利用する
- peer to peer の使用する
- 参加者は次の block (hash) を計算し、新しい block を追加する
  - 不正な block は拒否される
- ほぼ同時に block が見つけられた場合、一時的に fork が発生する
  - これは最終的に必ずどちらかが選ばれるように作られる
  - deep fork を防ぐ方法として、 bitcoin client には checkpoints がハードコードされている
- blockchain には必ずしも bitcoin のような miner が必要な訳ではない
  - miner は次の block を他の miner よりも先に探索し、金銭報酬を得る


## Block

block には以下が含まれる
- timestamp
- previous hash

Bitcoin の場合はさらに以下が含まれる
- version
- transactions
- bits
- nonce
