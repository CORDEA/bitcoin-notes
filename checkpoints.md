# Checkpoints

- Bitcoin client にハードコードされた値
- 現在ではこれは非推奨となっている
  - https://github.com/bitcoin/bitcoin/issues/7591
- blockchain の最適化と、攻撃防止のために置かれる
- checkpoint が置かれると、client はそれよりも前の blocks を正しいものとして lock する
  - これによりこれらの blocks を fork することができなくなる
