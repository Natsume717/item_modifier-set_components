# item_modifier-set_components
item_modifierの1項目であるset_componentsのサンプルになります。

詳しくはブログ記事『[【マイクラ】set_componentsでコンポーネント付与【item_modifier】](https://natsumake.com/item_modifier-set_components/)』を参考にしてください。

<h3>概要</h3>
アイテムに対してコンポーネントを適用します。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

ダイヤモンドが64個付与されますので、それを手に持った状態で以下のコマンドを実行します。

```copy
/item modify entity @s weapon.mainhand sample:set_components
```

成功していればfoodが付与され、ダイヤモンドが食べられるようになります。
