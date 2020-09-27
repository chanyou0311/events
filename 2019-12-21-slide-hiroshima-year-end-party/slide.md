---
marp: true
theme: gaia
class: lead
paginate: true
---

# 今日ここにくるに至ったまでの話

@chanyou0311

---

# はじめまして！

---

## 完全に自己紹介系の LT です

---

<!-- _class: default -->

# Nakamura Yu

![bg right:30% width:300px](https://avatars3.githubusercontent.com/u/12185831?s=460&v=4)

```py
class NakamuraYu:
    age = 22
    username = "chanyou0311"
    company = "株式会社ガイアックス"
    languages = [
        "Python",
        "Javascript",
    ]
    frameworks = [
        "Django",
        "Nuxt.js",
    ]
```

---

<!-- _class: default -->

# 最近勉強していること

- ドメイン駆動設計
- Python with Type Hints
- FaaS

---

<!-- _class: default -->

# 最近は型を書かないと気がすまないｗ

```py
from typing import List


class NakamuraYu:
    age: int = 22
    username: str = "chanyou0311"
    company: str = "株式会社ガイアックス"
    languages: List[str] = [
        "Python",
        "Javascript",
    ]
    frameworks: List[str] = [
        "Django",
        "Nuxt.js",
    ]
```

---

<!-- _class: default -->

# お仕事

### SNS マーケティングの支援事業

![bg width:200px](https://pngimg.com/uploads/twitter/twitter_PNG9.png)

![bg width:200px](https://en.facebookbrand.com/wp-content/uploads/2019/04/f_logo_RGB-Hex-Blue_512.png)

![bg width:200px](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/599px-Instagram_icon.png)

---

<!-- _class: default -->

# お仕事

### SNS マーケティングの支援事業 **の支援**

![bg width:200px](https://pngimg.com/uploads/twitter/twitter_PNG9.png)

![bg width:200px](https://en.facebookbrand.com/wp-content/uploads/2019/04/f_logo_RGB-Hex-Blue_512.png)

![bg width:200px](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/599px-Instagram_icon.png)

---

## 今年の 3 月まで呉高専の学生だった

会社に「広島でリモートワークさせてくれ〜」
と言ったら OK 出たので広島に住んでいます

---

まじめな課題感

### 学生の時にエンジニアのイメージがつかず、キャリアの選択肢の狭さを感じた

たまたま東京のエンジニアと知り合って、具体的なイメージが湧いた

---

## どうにかしたいと思って広島に残ろうと思った

---

## まずは広島のコミュニティにどっぷり浸かろう

---

# あんま知らない…

---

# connpass-feeder

---

<!-- _class: default -->

## connpass-feeder

connpass の情報を定期的に取得して、新規 or 更新イベントを Slack に通知してくれる Google Apps Script

clasp 使って Typescript で実装した

---

![height:700px](https://user-images.githubusercontent.com/12185831/71283061-70a8b480-23a2-11ea-8d3d-3a13e3ceb9db.png)

---

<!-- _class: default -->

## 仕組み

connpass には webhook API がないので、6 時間おきにポーリングしてスプレッドシートに保存

- スプレッドシートに `event_id` が存在していなければ新規イベント判定
- `event_id` が存在している場合は `updated_at` を比較して更新イベント判定

---

![height:550px](https://user-images.githubusercontent.com/12185831/71281556-8ff31200-23a1-11ea-903e-a2817a3abd12.png)
5 月頃から稼働して、200 件超えのデータが蓄積
※ 県外のイベントも紛れ込んでいる

---

![bg width:90%](https://hiroshima.pycon.jp/2019/static/images/ogimage.png)
![bg width:90%](https://www.pref.hiroshima.lg.jp/uploaded/image/343380.png)

---

## エンジニアめっちゃいるやん！

フリーランスや、リモートワーカー
地元の受託開発企業や巨大ベンチャー、スタートアップ
尖った大学生も大勢

#### ただ学生のときに出会える動きがとれてなかっただけやー

---

### 通知のおかげで、あったかいコミュニティが多数あることを知りました

---

そんなこんなで通知で気づいたのが…

![image](https://user-images.githubusercontent.com/12185831/71282843-51118c00-23a2-11ea-99e1-15e81a9b0f12.png)

## 行くしかない！！

---

# 今日ここにくるに至ったまでの話

@chanyou0311

でした！
