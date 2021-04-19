# es6-study-4-12-29
JavaScript 学習コース IV > クラスの継承 > メソッドの追加

### 独自のメソッド
継承して作成したクラスにも、メソッドを追加することができる。
```
class Bbb extends Aaa {
  getCcc() {
  *******
  }
}
```
### メソッドの戻り値
メソッドでは、関数と同じように戻り値（例はaaaのageを７倍する）を用いることができる。
下の例は、「Ccc」メソッドの戻り値を、「ccc」という定数に代入している。
```
class Bbb extends Aaa {
  getCcc() {
  return this.age *7;
  }
}
```
```
const aaa = new Aaa(4);
const ccc = bbb.getCcc();
console.log(ccc);
```

## コーディングトレーニング
「FORH」のレイアウト構造をレスポンシブで写経する。
