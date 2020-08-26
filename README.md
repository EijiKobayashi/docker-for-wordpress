# docker-for-wordpress

docker
WordPress + MySQL + phpMyAdmin の環境構築

- docker
- WordPress
- MySQL
- phpMyAdmin

## 設定

Docker Desktop をインストールしてください。

[Docker Desktop](https://www.docker.com/products/docker-desktop)

---

## 使い方

#### 構築

プロジェクトディレクトリに移動して

```
$ docker-compose build --no-cache
```

#### 起動

- Web: http//localhost:3000/
- phpMyAdmin: http://localhost:8080/

```
$ docker-compose up -d
```

#### 状態

```
$ docker-compose ps
```

#### 終了

```
$ docker-compose down
```

#### コンテナの削除

```
$ docker rm -f [コンテナID]
```

#### コンテナIDの一覧取得

```
$ docker ps -a
```
