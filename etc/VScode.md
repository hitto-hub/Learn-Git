# Visual Studio Codeの便利

## ショートカット

- Ctrl + Enter　カーソル行の下に空行を挿入
- Ctrl + Shift + Enter　カーソル行の上に空行を挿入
- Alt + ↑/↓　カーソル行／選択行をまるごと移動(複数行対応)
- Alt + Shift + ↑/↓　カーソル行／選択行をまるごとコピー(複数行対応)
- Ctrl + L　行選択してカーソルを下の行に移動。つまり連続して押していくと１行ずつ行選択が増えていく。
- Shift + Alt + A　選択範囲をコメントアウトする。（外す時も同じ）
- Ctrl + K * Ctrl + C　選択行をまるごとコメントアウトする。
- Ctrl + K * Ctrl + C　選択行のコメントアウトを外す。
- Ctrl + / 選択行をまるごとコメントアウトを外す、つける。
- Alt + Ctrl + ↑/↓ マルチカーソルを上/下に広げる。
- Ctrl + Shift + K 現在選択している行を削除する。

> - Ctrl + C　選択範囲をコピー。非選択状態で使用すると行コピーになる
> - Ctrl + X　選択範囲を切り取り。非選択状態で使用すると行切り取りになる
> - Ctrl + BS　単語の部分削除（カーソル位置より左側）
> - Ctrl + Del　単語の部分削除（カーソル位置より右側）
> - Ctrl + Home/End　ファイルの先頭/末尾に移動（pageup/pagedownと同じ）
> - Home/End　行頭/行末に移動。

## 便利情報

git clone でいちいち保存場所選択めんどくさいですよね～
そんなあなたに

```bash
C:/Users/ユーザー名/AppData/Roaming/Code/User/settings.json
```

↑↓同じ

```bash
%APPDATA%/Code/User/settings.json
```

内にある

```bash
"git.defaultCloneDirectory": ""
```

のダブルクオーテーション内にデフフォルトで開きたいパスを指定してあげる

> ワンポイント
>
> - \バックスラッシュじゃなくて/スラッシュのほうがいいです
> - ctrl + f でファイル内検索できる

例)

```bash
"git.defaultCloneDirectory": "C:/Users/hitto/Codes"
ユーザー名=hitto
```

みたいな感じです
