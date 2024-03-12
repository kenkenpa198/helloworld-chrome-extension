# helloworld-chrome-extension

![image](img/image.png)

## Setup

[バージョン](chrome://settings/help) :

```text
Chrome は最新の状態です
バージョン: 122.0.6261.112（Official Build） （64 ビット）
```

1. 当リポジトリを clone しておく。

    ```shell
    git clone ...
    ```

2. Chrome の [拡張機能設定画面](chrome://extensions/) ([chrome://extensions/](chrome://extensions/)) を開く。
3. 画面右上部の `デベロッパー モード` を有効化する。
4. 画面上部の `パッケージ化されていない拡張機能を読み込む` をクリックする。
5. clone したリポジトリの `my-extension/` を指定する。
6. 拡張機能が追加される。
7. 拡張機能を起動し、`Hello world!` が表示されれば成功。

※ 拡張機能を更新した場合、設定画面の `更新` をクリックして再読み込みする必要がある。

## Reference

- [とほほのChrome拡張機能開発入門 - とほほのWWW入門](https://www.tohoho-web.com/ex/chrome_extension.html)
- [マニフェスト - アイコン  \|  Extensions  \|  Chrome for Developers](https://developer.chrome.com/docs/extensions/reference/manifest/icons?hl=ja)
