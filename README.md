# テスト駆動開発インフラのサンプル
- ansible-playbookプロビジョニング
- serverspecテストコード


## プロビジョニング
```
$ ansible-playbook -i hosts webapp.yml
```

## テスト
dockerコンテナにアタッチ後
```
rake spec:webapp
```
