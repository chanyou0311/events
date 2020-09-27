---
theme: gaia
class: lead
paginate: true
backgroundColor: #fff
# backgroundImage: url('https://marp.app/assets/hero-background.jpg')
marp: true
---

# **quicktype を使って爆速で型定義する**

株式会社ガイアックス 中村 優

@chanyou0311

---

# 中村 優

![bg left:30% 90%](https://i.imgur.com/qkrW7fX.png)

- ソーシャルメディアマーケティング事業部
- データ解析基盤の構築、運用
- DDD を Django で実践中

---

## 仕事の特性上、外部APIを触ることが多い

- APIの返り値（JSON）をパースするのが手間
- パースできても補完が効かない
- APIの返り値（JSON）に key があったりなかったりする

---

## quicktype というツール、ご存知ですか？

---

## quicktype

- JSON などのサンプルデータの型を推測し、対応する言語で出力するライブラリ
- npm パッケージとして公開されている
- https://app.quicktype.io/ で Web UI でも使える

---

## Web UI 試してみる

https://app.quicktype.io/

---

## 外部APIを利用する際に便利

- データのクローリング
- OAuth認証のアクセストークン

などなど…

---

## quicktype 便利でした

- ほどよくデータを流し込めば、いい感じに型定義してくれる
- がんばってパースしなくてもよい
- 補完も効いて開発体験が劇的に向上！
