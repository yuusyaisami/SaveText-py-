# SaveText-py-
変数の保存を行うクラスです  
関数に分けられてるので自由に使ってください  
SaveTextはクラス名です  
add関数 : 変数を上書き保存または新しく保存する関数です  
delete関数 : 変数を削除する関数です  
search関数 : 対応する変数のデータを読み取る関数です  
  
## 引数  
add関数はname : 名前、data : データ、path : パスです  
nameには":"を使わないでください  
nameは日本語なども使えます  
delete関数はname : 名前、path : パス  
search関数はname : 名前、path : パス、type : 変数の型  
typeの初期値は"string or bool"です  
出力時にstringまたはboolで出力します  
ほかには int float bool stringがあります  
  
保存時の変数の形は関係ありません  
なので"12" : stringとstring型で保存したデータをsearch関数ではtype : intとすると呼び出すときの形は12 : intです  

# 関数の呼び出し
```
SaveText.add("変数名", "data", "path.txt")
```
```
SaveText.delete("変数名", "path.txt")
```
```
変数 = SaveText.search("変数名", "path.txt")
```
