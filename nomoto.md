# 注文画面作成
ディクショナリを使い料理名前と値段が書かれたメニュー表を作成せよ。  
所持金は1000円~2000円以内でランダムで決まる。  
番号を入力すると所持金から注文した料理の値段が引かれる。  
注文した料理はpopを使いメニュー表から消えるようにする。  
全ての料理を注文すると「全て売り切れました」と表示される、  
途中で所持金がなくなると「お金がなくなりました」と表示される。  
注文した料理が所持金より高い金額だと「お金が足りません」と表示する

### 実行例

```
メニュー表
0 うどん 200 円
1 ペペロンチーノ 280 円
2 かつ丼 320 円
3 味噌ラーメン 300 円

所持金 1983 円
購入したいメニュー番号を入力してください>>0
うどん を購入しました

メニュー表
0 ペペロンチーノ 280 円
1 かつ丼 320 円
2 味噌ラーメン 300 円

所持金 1783 円
購入したいメニュー番号を入力してください>>1
かつ丼 を購入しました

メニュー表
0 ペペロンチーノ 280 円
1 味噌ラーメン 300 円

所持金 1463 円
購入したいメニュー番号を入力してください>>0
ペペロンチーノ を購入しました

メニュー表
0 味噌ラーメン 300 円

所持金 1183 円
購入したいメニュー番号を入力してください>>0
味噌ラーメン を購入しました

全て売り切れました
```
