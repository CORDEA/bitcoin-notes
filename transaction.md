# Transaction

- 各 block に対する取引
- transaction を検証するため、block には merkle root が保持されている
- transactions がハッシュ化され、ペア化されたものがさらにハッシュ化され、それが最終的に一つになったものが merkle root として保持されている
  - これにより、検証の際に全体のハッシュを必要とせず、完全性の検証が容易となる

## Ref

- http://www.jbonneau.com/doc/BMCNKF15-IEEESP-bitcoin.pdf
- https://bitcoin.org/en/developer-guide#block-chain
- https://bitcoin.stackexchange.com/questions/10479/what-is-the-merkle-root
