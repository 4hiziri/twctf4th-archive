# How to deploy
以下のコマンドを実行する。
```sh
cat esc-docker.tar | docker load
./run.sh
```

http://localhost:8080/ でアクセスできる
8080が外からも多分見えるので注意、安全な環境でやろう。
それか仮想マシン使おう。

esc-docker/にDockerfileとかapp本体とかフラグとか置いてある。
