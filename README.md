# SPEEDRUN


## 起動

`docker-compose up` すると 5000番でHTTP Serverが動く仕組み


## 問題の登録

`/tasks/` 以下をみて適当に合わせてくれ

## operation

`docker-compose exec app sqlite3 ./db/database.sqlite` とかするとsqlite開けるのでそこからやると良い

ローカルディレクトリに `./db/database.sqlite` があるのでそっちsudoで触ってもいい

### adminを作る

- `user.is_admin` を `1` にする


