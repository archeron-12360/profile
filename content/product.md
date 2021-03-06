---
title: "Product"
date: 2022-04-02T23:39:39+09:00
draft: false
---

## 開発したプロダクト

- [みんなのTODOリスト](https://everyone-todo.herokuapp.com/todo/)
  - `Python`, `Django`で開発したタスク管理Webアプリケーション
  - [経歴](https://archeron-12360.github.io/profile/about/#2-%E7%B5%8C%E6%AD%B4)に記載した通り、2020年9月から6ヶ月間、`Python`を使って、有志の学生3人1組で競う大学のアプリ開発コンテストにて開発
  - ### このアプリでできること
    - 会員登録/ログイン機能があり、会員登録をすると`カード`(`TODOリスト`の中のTODO)を他のメンバー(一緒に作業をしている人など)と共有ができます。
      - 例えば、就活に関するTODOを管理したい場合は、`TODOリスト`名は「就活でやるべきこと一覧」になり、`カード`は「●●株式会社のESを書く」「●●株式会社の説明会に参加する」などTODOの具体的な内容を書くことになります。
    - 既存のタスク管理アプリ[Trello](https://trello.com/)のように「カンバン方式」という形で「やらなければならないこと」「実行中のこと」「完了していること」を横並びにすることで、タスクの状態がひと目で確認できます。
    - `TODOリスト`の中の`カード`を手動で移動させる(ドラッグ＆ドロップ)ことで、`カード`を自由に並べ替えることができます
    - `TODOリスト`の中の`カード`を手動で移動させるだけではなく、自分で「設定」をすれば、自動で移動させることもできます。
      - 「設定」：`TODOリスト`に`カード`を追加する＞`カード`を編集する＞タグを設定する＞`TODOリスト`の一覧画面に戻ると、同じタグがつけられた`カード`は自動的に同じ`TODOリスト`にまとめられる。
        - 例えば、`カード`に「就活でやるべきこと一覧」というタグを設定すると、その`カード`は「就活でやるべきこと一覧」という`TODOリスト`の中に自動的に移動します。
      - ※上記のドラッグ&ドロップ機能は`Vue.js`のバグが発生したため現在修正中です

- [sonayell](http://sonayell-v2.herokuapp.com/)
  - `PHP`, `Laravel`で開発した中古の防災用品を出品・購入できるWebアプリケーション
  - ロードマップは[こちら](https://handsome-aardwolf-1e7.notion.site/4986c50038d048aba66a62e3cdbf0b35?v=269eb199cb404318a80c636c12617a62)
  - [経歴](https://archeron-12360.github.io/profile/about/#2-%E7%B5%8C%E6%AD%B4)に記載した通り、2022年2月から現在、PHPを使って、個人にて開発中
  - ### このアプリでできること
    - 会員登録/ログイン機能があり、会員登録をすると商品の出品ができます
    - 出品された防災商品を（テストモードで）購入できます
    - 商品を探す際にキーワード検索ができます
    - 商品を探す際に「水・食事・衣料品・装備・衛生・救急・防寒・その他」などカテゴリ別に検索ができます
    - 商品を購入すると、インターネット上での決済を管理できるサービス[PAY.JP](https://pay.jp/)に自動的に反映されます（これはユーザー向けの機能ではなく、管理者向けの機能です）
