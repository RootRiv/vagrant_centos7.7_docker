# READ ME

CentOS 上に Docker をインストールした仮想環境を作るための Vagrantfile です

## 使い方

1. virtual box と vagrant をインストール
1. このリポジトリを Clone してくる
1. Vagrantfile のあるディレクトリで vagrant up
1. vagrant ssh
1. docker コマンドが使えていれば成功

## フォルダの同期が上手くいかないとき

```CMD
 vagrant plugin install vagrant-vbguest
 vagrant vbguest
 vagrant reload
 vagrant provision
 vagrant ssh
```

上記コマンドでできるはずです
