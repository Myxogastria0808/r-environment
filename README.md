# R 4.3.3 の環境

使用したイメージ: r-base:4.3.3

URL: (https://hub.docker.com/layers/library/r-base/4.3.3/images/sha256-fd808d8a2743369426ac4ec6f5dcb753c147f9d95bf58f20478583afa196c684?context=explore)[https://hub.docker.com/layers/library/r-base/4.3.3/images/sha256-fd808d8a2743369426ac4ec6f5dcb753c147f9d95bf58f20478583afa196c684?context=explore]

## Setup

```shell
docker compose up -d
```

## コンテナに入る

```shell
docker compose exec r-env /bin/bash
```

## `~.R`ファイルの実行

hello.R の場合

```shell
Rscript hello.R
```
