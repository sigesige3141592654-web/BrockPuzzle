# BrockPuzzle
スマホでもできるパズル。答えは１万以上！！
PC版はいつか作る（作らないかも）

## これは何？
このゲームは、複数のピースを動かして盤面に収めるパズルです。
スマホ向けに最適化してあり、タップ・ドラッグ・2本指回転で操作できます。

## ローカルで遊ぶ
ブラウザで `index.html` を開くか、次のコマンドでローカルサーバーを立ち上げて遊べます。

```bash
cd /workspaces/BrockPuzzle
python3 -m http.server 8000
```

その後、ブラウザで `http://localhost:8000` を開いてください。

## GitHub Pages で公開する
1. このリポジトリを GitHub に push します。
2. GitHub のリポジトリ画面で Settings → Pages を開きます。
3. Source を「Deploy from a branch」にし、Branch を `main`、Folder を `/ (root)` に設定します。
4. 保存すると、数十秒後に公開URLが発行されます。

公開URLの例:
https://ユーザー名.github.io/BrockPuzzle/

`index.html` をルートに置いているので、そのまま Pages で公開できます。