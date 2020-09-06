# docker-jekyll

## Usage

```
docker-compose up
open http://localhost:4000/
```

## Note

### Init log

コンテナ内に入る
```
docker-compose exec service_jekyll sh
```

コンテナ内で初期化
```
jekyll new . --force
```

