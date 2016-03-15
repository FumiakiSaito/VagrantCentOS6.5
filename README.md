# VagrantCentOS6.5

vagrant初期化(Vagrantfileの作成)
```
vagrant init
```

ここでvagrantfileの更新を行う  

仮想サーバ起動
```
vagrant up
```

仮想サーバ停止
```
vagrant halt
```

仮想サーバ削除
```
vagrant destroy
```

仮想サーバログイン
```
vagrant ssh
```

`ssh [ホスト名]`できるように.ssh/configに追記
```
vagrant ssh-config --host [ホスト名] >> ~/.ssh/config
```

rootにスイッチ  
```
$ sudo su -
```

##vagrantプラグインに関するコマンド
```
vagrant plugin install <name>
vagrant plugin uninstall <name>
vagrant plugin update [names...]
vagrant plugin list
```
