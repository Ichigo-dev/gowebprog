01goroutine  
  goroutine1 リスト9.1 9.2
  goroutine2 リスト9.3の前のリスト
  goroutine3 リスト9.3
  goroutine4 リスト9.4
  goroutine5 リスト9.5
  goroutine6 ループを100回
02waitgroup
  waitgroup1 リスト9.6
  waitgroup2 カウンタを減算し忘れた場合
03channel_wait リスト9.7
04channel_message
  channel_message1 リスト9.8
  channel_message2 バッファ付きチャネル
05channel_select
  channel_select1 リスト9.9
  channel_select2 defaultブロック
  channel_select3 リスト9.10
06channel_shared
07mosaic_original リスト9.11〜9.17
    1. go build
    2. ./07mosaic_original
    3. http://127.0.0.1:8080  をオープンしファイルを指定
08mosaic_concurrent リスト9.18〜9.1
    1. go build
    2. ./08mosaic_concurrent 
    3. 「Mosaic server started.」を待ってhttp://127.0.0.1:8080  をオープンしファイルを指定  （大きなファイルを指定するとエラーになります。1024x768ぐらいならば大丈夫ですが、この倍だとエラーになります）
