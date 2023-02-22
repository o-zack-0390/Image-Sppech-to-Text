# Image-Speech-to-Text
画像ファイルと音声ファイルから文字起こしをする。無料枠を使用しているため以下の制限がある。<br>
<li>画像ファイルはjpgファイルのみ対応</li>
<li>音声ファイルはwavファイルのみ対応</li>
<li>容量200MBとなっているが無料枠なので実際は2M程度</li>
<li>データサイズが無料枠を超過している場合はエラーメッセージを表示</li>
<li>容量が大きいサイズは無料枠を超えないサイズまで分割して使用することになる</li>

<h3>開発背景</h3>
研究のzoomミーティングでは、共有されている画面に書いてあることを必死にメモすることが多く、教授の話をメモすることも多い。<br>
しかし、これらを手書きで行うには限界があり、どうしてもメモできない箇所が毎回あった。<br>
そこで、画像から文字起こしが可能で、音声からも文字起こしができるアプリがあれば便利だと思い開発に至った。<br>
Google社の文字起こしサイトを使用する方法も考えたが、「Google社の無料枠だと使用回数・使用容量に制限が掛かる」という理由から回数に制限がないstreamlitで実装することにした。<br>

<h3>開発言語</h3>
python<br><br>

<h3>ライブラリ</h3>
Tesseract-Ocr<br>
SpeechRecognition<br><br>

<h3>フレームワーク</h3>
Streamlit
