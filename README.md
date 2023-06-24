# はじめに

本リポジトリは、PHP を使って気象 API を用いたアプリケーション作成を目的としたリポジトリである。

# 背景

「ひなたデジタルアカデミア 2023」という、気象 API を利用したアプリケーションを開発するイベントがあり、カリキュラムが 23 年 7 月から 24 年 3 月、全 23 回に渡って行われる予定である。  
このイベントに参加する予定だったが、ET ロボコン、卒業研究、アルバイトなど、現在開発中のものを考慮すると 24 年 3 月まで開発を続けることは難しいと判断したため、自分のペースで個人的に開発しようと考えた。

# 環境構築

Git で本リポジトリをクローン。

```
git clone https://github.com/ykimura0726/PHP-Weather
```

docker-compose.yml からコンテナの構築。  
--verbose オプションでログをターミナルに出力し、--no-cache オプションでキャッシュを使わずにコンテナを構築する。

```
docker-compose --verbose build --no-cache
```

# 参考文献

-[【簡単】Docker で PHP と MySQL の環境構築【コンテナ仮想化](https://nyanblog2222.com/programming/cmd/5184/)
