---
marp: true
theme: uncover
class: invert
---
# 情報オリンピック2012予選E「cheese」

---
# 考える点

- 見た目はややこしいが、行っていることは複数の座標間の長さを求めて
  合計を出せば良い。
- 複数回幅優先探索を行うことになるが、別に探索経路は以前の物を使っても良い。繰り返すだけなので探索の回数は最大で$N$回。

---
# 気を遣うところ

- 幅優先探索に慣れていればちょっとややこしくなった簡単な問題であるが、慣れていないと何度もソースを作り直す羽目になる。
