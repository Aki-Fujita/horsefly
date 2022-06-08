## プログラムの立て方 

1. ファイルをクローン
    ``` bash
    git clone https://github.com/Aki-Fujita/horsefly.git
    ```
    ***
2. 環境の立ち上げ
    ``` bash
    cd horsefly
    docker-compose up -d --build
    ```
    ↑これでコンテナが立っているかを一応
    ```bash
    docker container ls
    ```
    で確認する。python-algoというコンテナが立っていればOK
    ***

3. 作った環境に入る（あと一息！）

   1. 下記のコマンドを入力
    ```bash
    docker-compose exec python-algo bash
    ```
     2. 上記が成功すると `(base)root>>>` みたいな画面が出てくるので、ここからはpythonのスクリプトを実行できる。
      *** 

4. 作業が終了したらちゃんとコミットすること！(自分向け)
    