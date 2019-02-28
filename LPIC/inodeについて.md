# inodeについて

Linuxにおいて、ファイルの属性情報を格納しているデータをinodeと呼ぶ。  
inode番号はそのinodeの識別番号のことを指す。  

inodeには以下の内容が記述される。  
- ファイルの実体が存在する場所
- アクセス権
- 最終更新日時
- ファイルサイズ
- inode番号

これらは`ls`コマンドの`-l`オプションで表示することができる。  
inode番号も表示したい場合は`-i`オプションを付ける

例：
```
$ls -li package-lock.json
8610665059 -rw-r--r-- 1 Soya staff 199946 11 18 17:41 package-lock.json
```

参考：https://wa3.i-3-i.info/word14803.html
