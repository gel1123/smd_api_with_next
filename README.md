
## ディレクトリ構成

```
.
├── app
│   ├── be       #<= SpringBootアプリケーションのソースコードと .devcontainer を配置している
│   └── fe       #<= Next.jsアプリケーションのソースコードと .devcontainer を配置している
│
└── docker       #<= 各種コンテナ
    ├── dbclient #<= DBクライアントのコンテナ
    ├── java     #<= Java17のコンテナ
    ├── mysql    #<= MySQLのコンテナ
    └── nextjs   #<= Node16のコンテナ
```

## BE参考

https://github.com/gel1123/smd_api

## FE参考

下記のリポジトリに少し手を加えている ( Next.jsアプリケーションのルートディレクトリを /app 直下にしたなど )

https://github.com/gel1123/docker_on_next

## どこからVSCodeのリモートコンテナを開く？

バックエンドは、 `./app/be` ディレクトリをVSCodeで開いた上で Remote Containers を開く。
フロントエンドは、 `./app/fe` ディレクトリをVSCodeで開いた上で Remote Containers を開く。
