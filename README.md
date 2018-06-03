
### 管理するもの
---
1. package
    - starをつけたpackage (atom.ioのユーザーページで管理)
        - インストールしたパッケージにstarをつける
        ```
        apm star --installed
        ```
        - starしたパッケージのインストール
        ```
        apm stars --install
        ```
2. 設定
    - ./markdown-writer-links.cson
    - /keymap.cson
    - ./config.cson
    - /github.cson
    - ./snippets.cson
    ```
    $ find . -name '*.cson' | grep -v package
    ./markdown-writer-links.cson
    ./keymap.cson
    ./config.cson
    ./projects.cson  除外　端末固有
    ./github.cson
    ./snippets.cson
    ```
3. 起動スクリプト
    - init.coffee
