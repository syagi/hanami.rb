## 成果物

- application url
  - not deploy⊂(・8・)⊃

- github repository url
  - https://github.com/ota42y/hanami_todo_app

## 何を作ったか?

- TODOアプリ
  - 基本はチュートリアルのbookをtodoに変えただけ

## 工夫した or 苦労した or ハマったところ

- チュートリアルにないものがだいぶハマる
  - /todos/:idのパスを作るとき
  - 上記のパスが含まれているときのviewのテストがparmsを参照して何故かこける
    - 実際には動作するので問題ないため、テストの仕方の問題っぽい

## Hanamiについて

### Pros

- 何処に何を書けば良いかがしっかりと決められているのは良い
  - かなり強い規約
  - 巨大になった際に効果を発揮しそう

### Cons

- 一つの機能実装のために変更する場所が多い
- テストの書き方が特殊っぽい(なれていないだけの可能性は高い)
- 情報が少ない

## Railsと比較した場合の感想

- Railsと同等の機能程度しか触れなかったのでいまいち
- hanamiで1から作るよりかは、既にあるアプリを書き直す際にhanamiにするのがよさそう
  - ある程度巨大にならないと作業量の多さに見合わない気がする
  

## 実際に業務で利用したいと思ったか?

1. いいえ
2. まだ、Railsアプリを捨ててまで乗り換える価値があるかの確証が持てていない

## その他 感想（本イベントについてでも何でも）

- 強制的にしっかりと手を動かす時間を取れたのはとても良い
- twitterのハッシュタグをプロジェクターでだしっぱにしておくと、コミュニケーションとして良かったのでは
