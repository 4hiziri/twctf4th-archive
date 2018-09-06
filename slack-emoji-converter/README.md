# How to deploy
以下のコマンドを実行する。
```sh
cat esc-docker.tar | docker load
```

ビルドするなら以下
```sh
cd esc-docker
docker build -t esc-docker .
```

起動は`./run.sh`にまとめたので実行するだけ。

http://localhost:8080/ でアクセスできる。  
8080が外からも多分見えるので注意、安全な環境でやろう。  
それか仮想マシン使おう。  

esc-docker/にDockerfileとかapp本体とかフラグとか置いてある。
