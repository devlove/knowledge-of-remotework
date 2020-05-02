# VPNからゼロトラストに移行する

![イメージ](https://d2l930y2yx77uc.cloudfront.net/production/uploads/images/23745917/picture_pc_198adf800329c9d5bc02dc12be3a6bbe.png)

## コンテキスト

- 企業内ネットワークは、境界防御が当たり前になっている
- スマートフォンの普及や働き方改革で、VPNを導入した企業は多い
- コロナの影響で、多数の社員のリモートワークが一気に必要になった

## 問題

- どこからでも、楽で安全に社内のデータにアクセスしたい

## フォース

- 複雑
  - 複数の拠点、データセンターをつなぐ企業内ネットワークは、すでに複雑
  - VPNでネットワーク境界が増えて、さらに複雑
- 手間
  - 毎回VPNに接続する必要がある
  - 状況に応じて、VPNを切断し、再接続などネットワークを意識する必要がある
- 遅い
  - 接続人数が多いと通信が遅くなる
- つながらない
  - 社内ではつながるが、VPNではつながらないことが増える
- 危ない
  - ネットワークごとに信頼するので、境界内に侵入されらもろい
  - VPN接続は信頼するネットワークを追加している
  - 接続する端末が感染していたら、すぐに境界内に侵入されてしまう

## 解決策

- ゼロトラストなアプローチに移行する

## 結果

- 複雑
  - 考える対象がネットワークからアプリケーションに変わる
- 手間
  - 社内でも社外でも、変わらないアクセス方法
- 遅い
  - 人数が増えても、変わらない通信速度
- つながらない
  - 社内でも社外でも、変わらない通信ルール
- 危ない
  - 誰が、どんな状態のどの端末で、いつ、どこのネットワークから、どのアプリケーションにアクセスするセッションなのかを検証


## 参考

- ‪[VPNからゼロトラストへの移行を考える｜諏訪真一](https://note.com/suwash/n/na22941028e38‬)
- [ゼロトラストの開拓者--21世紀フォックス](https://japan.zdnet.com/article/35134505/)
- [シンプルに考えよう Zero Trust Network](https://www.slideshare.net/ryukiyoshimatsu/zero-trust-network)
- [Zero Trust Network アーキテクチャ](https://www.slideshare.net/YukioIto1/zero-trust-network)
- [Zero Trust上から見るか？下から見るか？](https://speakerdeck.com/ken5scal/zero-trustshang-karajian-ruka-xia-karajian-ruka)
- [ゼロトラスト超入門](https://booth.pm/ja/items/1318558)
