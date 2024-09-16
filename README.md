# TypescriptとReactでtodolistを作る

Typescriptを触ってToodolistを作ってみる。  
[参考記事](https://sync-g.co.jp/sjobs/typescript-biginner/)

## 環境構築手順
```
# dockerイメージ構築 ※初回起動時のみ
docker-compose build

# dockerコンテナ起動
docker-compose up -d
```
localhost:3000に接続してReactページが表示されたら成功。

http://localhost:3000/

```
# dockerコンテナ停止
docker-compose stop

# dockerコンテナ削除
docker-compose down
```

## 備忘録
```
# Typescript テンプレート作成コマンド
docker-compose run --rm node sh -c 'npx create-react-app my-app --template typescript'
```
[docker-compose build や upの違い](https://qiita.com/tegnike/items/bcdcee0320e11a928d46)

[DockerでReactとTypeScriptの開発環境構築の仕方](https://note.com/hiropython/n/ne4c5611d1d01)