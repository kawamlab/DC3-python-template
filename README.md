# DC3-python-template
devcontainer環境においてdigital curling3 のクライントを作成するためのテンプレートです。

## エラーが出る場合
devcontainerのbuild時にエラーが出る場合があります。
`dc3`という名前のネットワークが存在するか確認してください。

ない場合は、
```bash
docker network create dc3
```
で作成してください。