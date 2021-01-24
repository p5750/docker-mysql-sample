# docker-mysql-sample

docker-composeでMySQLコンテナを立てる、
[Qiitaに書いた記事](https://qiita.com/p5750/items/c8e20744bd05fe6de8ea) のサンプルコード。


## 実行

```
git clone https://github.com/p5750/docker-mysql-sample
cp .env.sample .env
vim .env   # 適宜編集する
docker-compose up -d
```