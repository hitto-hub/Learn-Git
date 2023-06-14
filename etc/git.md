# git

<details>
<summary><h2>gitを使う(VScode編)</h2></summary>

[こっち](start-VScode.md)見ましょう
</details>

<details>
<summary><h2>gitを使う(コマンド編)</h2></summary>
echo "# example" >> README.md

Gitを始める呪文
> .gitというディレクトリが作成される

```bash
git init
```

現在あるファイルの**README.md**をステージに追加
> git add . とするとすべてのファイルがステージに追加される

```bash
git add README.md
```

コミットメッセージを記入

```bash
git commit -m "first commit"
```

mainブランチに切り替え

```bash
git branch -M main
```

アップロード先を教える

```bash
git remote add origin https://github.com/hitto-hub/example.git
```

Githubにpush

```bash
git push -u origin main
```

</details>

## memo

[gitの改行コードについて](https://qiita.com/uggds/items/00a1974ec4f115616580)
