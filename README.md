# Github上に配置したnpmパッケージをインストールするテスト

個人的に作成したnpmパッケージを`npm i`したい場合、公式のnpmリポジトリに登録するのもあれなので個人のGithubに配置して使えばいい。

## 手順

+ npmパッケージとして利用可能な状態でGithubにpush
+ `npm i`する

例えば本リポジトリの場合

```
npm i https://github.com/ryou/npm_private_package_test.git
```

すればいける。簡単。
