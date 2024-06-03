## サービス概要

Organic Checkは、ユーザーがオーガニック製品を探し、共有するためのアプリです。
検索機能やレビュー機能を活用して、ユーザーが信頼できるオーガニック製品を見つける手助けをします。

## このサービスへの思い・作りたい理由

私は、スーパーなどで買い物をするとき、できるだけ添加物の少ない商品を選ぶようにしています。
この傾向は最近、多くの人にも広がっていると感じています。

例えば、私はよく納豆を買いますが、添加物が少ない納豆の方が人気があります。
価格は高めですが、健康に気を使う人が増えているようです。

しかし、スーパーで買えるオーガニック製品は限られており、求める商品を見つけるのが難しいと感じました。

このアプリを通じて、より多くのオーガニック製品に出会える機会を提供し、健康的なライフスタイルをサポートしたいと思います。

## ユーザー層について
【ユーザー層】
健康に気を使っている人

【理由】
このユーザー層を選んだ理由は、彼らが添加物の少ない商品を探す機会が多いと感じたからです。

## サービスの利用イメージ
ユーザーはアプリを開き、検索バーに欲しいオーガニック製品のキーワードを入力します。
検索結果から製品を選択し、詳細情報やレビューを閲覧します。
また、自分の好みや体験を共有するためにレビューや投稿を行うこともできます。

## ユーザーの獲得について
Xやスクール内のコミュニティでの宣伝

## サービスの差別化ポイント・推しポイント
本サービスの差別化ポイントは、オーガニック製品に特化した検索機能と信頼性の高いレビュー評価システムです。
また、ユーザー同士の交流を促進するコミュニティ機能も魅力の一つです。

## 機能候補
MVPリリース時には、製品検索、製品詳細表示、ユーザー登録・ログイン、レビュー投稿、お気に入り登録などの基本的な機能を実装する予定です。
その後、より高度な機能として、推奨製品の表示やユーザー間の交流を促進する機能を追加していきたいと思います。

## 機能の実装方針予定
APIとして「Open Food Facts」や「Edamam API」を活用し、オーガニック製品の情報を取得します。
レビューシステムには「ActAsTaggable gem」を使用し、タグ付けされたレビューを実装します。
また、画像のアップロードには「Active Storage」を使用します。