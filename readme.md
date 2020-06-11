# 多機能 bot

練習としてとりあえずいろんな機能を積んでみる予定。

# 実行方法

1. 依存しているライブラリをインストール

```bash
pip install -r requirements.txt
```

2. 自分の bot トークンを生成された token.yml の main: 項に貼り付ける

```yml
main: ここにトークンを貼り付ける
using: main # main項目のトークンを使う設定。
```

3. python コマンドで main.py を実行する。

```bash
python main.py
```

# todo

- [ ] 独自のコマンドシステム(prefix 可変)を完成させる
- [ ] prefix の後に、コマンドを改行区切りで送信することで、コマンドを順番に実行できるようにする
- [ ] チャンネルを編集する系のコマンドを作ってみる

# 参考にした記事

discord.py の Bot Commands Framework を用いた Bot 開発

- https://qiita.com/Lazialize/items/81f1430d9cd57fbd82fb

# 開発に用いた環境

- Python 3.6.9
- macOS 10.15.5
