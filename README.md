# Image-Speech-to-Text
画像ファイルと音声ファイルから文字起こしをする。無料枠を使用しているため以下の制限がある。<br>
<li>画像ファイルはjpgファイルのみ対応</li>
<li>音声ファイルはwavファイルのみ対応</li>
<li>容量200MBとなっているが無料枠なので実際は20M程度</li>
<li>データサイズが無料枠を超過している場合はエラーメッセージを表示</li>
<li>容量が大きいサイズは無料枠を超えないサイズまで分割して使用することになる</li>

<h3>開発背景</h3>
研究のzoomミーティングでは、共有されている画面に書いてあることを必死にメモすることが多く、教授の話をメモすることも多い。<br>
しかし、これらを手書きで行うには限界があり、どうしてもメモできない箇所が毎回あった。<br>
そこで、画像から文字起こしが可能で、音声からも文字起こしができるアプリがあれば便利だと思い開発に至った。<br>
Google社の文字起こしサイトを使用する方法も考えたが、「Google社の無料枠だと使用回数・使用容量に制限が掛かる」という理由から回数に制限がないstreamlitで実装することにした。<br>

<h3>開発言語</h3>
python3<br><br>

<h3>ライブラリ</h3>
Tesseract-Ocr<br>
SpeechRecognition<br><br>

<h3>フレームワーク</h3>
Streamlit

<h3>使用方法(Speech to Text)</h3>
1. 「変換方法の選択」で「Speeech to Text」を選択<br>
2.  waveファイルをアップロード<br>
3.  「テキストに変換」を押す<br><br>
<img width="579" alt="image" src="https://user-images.githubusercontent.com/116938721/220658035-16125175-2fdf-44ef-b7f2-f1d5ea2cb0de.png">

音声ファイル<br>
<a href="https://www.city.kasugai.lg.jp/shisei/gyousei/koho/koe/1016637.html">声の広報かすがい　4月15日号（NO.698）</a>
<br><br>

<h3>使用方法(Image to Text)
1. 「変換方法の選択」で「Image to Text」を選択<br>
2.  jpgファイルをアップロード<br>
3. 「テキストに変換」を押す<br><br>

<img width="593" alt="image" src="https://user-images.githubusercontent.com/116938721/220660467-7af39c89-cc8f-430d-8638-b2fc9c52e822.png">
