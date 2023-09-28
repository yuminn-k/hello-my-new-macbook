# how-i-met-my-laptop

新しいMacBookを購入した記念に**開発環境設定を自動で行う**shell scriptを作成しました。<br>
次のようなツールをインストールします。

| Tool name     | 비고                                 |
| ------------- | ------------------------------------ |
| node          | @18                                  |
| nvm           |                                      |
| vscode        | 拡張プログラムまで含め                |
| KakaoTalk     |                                      |
| Slack         |                                      |
| Discord       |                                      |
| RunCat        | CPU使用量などを表示してくれる生産性向上アプリ |
| Amphetamine   | MacBookの画面が消えないようにするアプリ    |
| Monosnap      | スクリーンキャプチャアプリ                       |
| postman       |                                      |
| sourcetree    |                                      |
| google-chrome |                                      |
| iterm2        |                                      |
| Fig           | gitコマンドを自動補完してくれるアプリ      |

## 🚨 ご注意!

`.zshrc`に私のニックネームが書かれています。<br>
下のコードから私のニックネームを消して、使用する方のニックネームに変更してください！
https://github.com/yuminn-k/hello-my-new-desktop/blob/861a79039ac8bf8390d3748af45727c3389080f4/zsh/.zshrc#L108-L110

## setting

1️⃣ ターミナルで下記のコマンドを入力したらgitをインストールします。

```
git --version
```

2️⃣ git cloneコマンドを実行して開発環境スクリプトをコピーします。

```
git clone https://github.com/yuminn-k/hello-my-new-desktop.git
```

3️⃣ 開発環境を自動的に設定します。

```
./hello-my-new-desktop/install.sh
```

🛠 この時、権限の問題でinstall.shが実行されない場合は？

1️⃣ フォルダに入ります。

```
cd hello-my-new-desktop
```

2️⃣ 実行権限を修正します。

```
chmod +x install.sh
```

3️⃣ 実行します。

```
./install.sh
```
