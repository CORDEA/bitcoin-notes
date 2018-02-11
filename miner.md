# Miner

- 難易度を調整された hash (SHA-256) を計算し、正解を探し当てる行為
- 概ね 10 分に一度 block が生成される難易度に調整される
- 他の参加者よりも先に見つけ、周りに公開する必要がある
  - 一番最初に見つけた参加者が金銭報酬を得ることができる
  - この報酬は必須ではないが、参加者に対する報酬がなければ block を見つけるメリットがない

## Calculation

- 単純な方法としては、nonce をインクリメントしながら hash を計算していく方法がある

## Ref

- http://www.jbonneau.com/doc/BMCNKF15-IEEESP-bitcoin.pdf
