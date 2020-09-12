# Scrapboxで書いたシェーダをCCaptureでキャプチャする

以下でUserScriptのコードを用意しているが、CCaptureでのアニメーションキャプチャはwebmでしかできなかった。  
+ gifでやる場合はworkerを使う必要があるが、そのソースコードがjsと認識されずにリジェクトされてしまった
https://scrapbox.io/src-wintyo/%E3%82%B7%E3%82%A7%E3%83%BC%E3%83%80%E3%83%BC%E8%A1%A8%E7%A4%BA  

※なお、webmでダウンロードしてからgifに変換した場合、画像が荒くなったり、framerateがおかしくなったりするため実用的ではなかった。  

そこでこのリポジトリではgifでアニメーションキャプチャできるようにした。  
