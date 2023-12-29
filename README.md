# Dockerの仕組み
<img src = "https://y-ohgi.com/introduction-kubernetes/1_introduction/imgs/vm-docker.png" width = "50%">
Dockerはコンテナ型仮想化技術を実現するもの(上記では右の図)
メリット:
    ・どのコンピューター上でも同じ環境を作ることができる
    ・OSの指定・ミドルウェアのインストール環境設定がコード化されているので再利用・バージョン管理・配布が容易


# Dockerの基本的なコマンド
docker pull [イメージ名]
    docker hubからイメージを入手する

docker images
    イメージの一覧を表示する

docker rmi [イメージ名]
    イメージを削除する

docker run [オプション]
    コンテナの作成から実行までする

docker start [コンテナ名]
    コンテナを実行する

docker stop [コンテナ名]
    コンテナを停止する

docker rm [コンテナ名]
    コンテナを削除する

docker ps
    起動中のコンテナの一覧を表示する

exec -it [コンテナ名] bash
    コンテナの中に入る