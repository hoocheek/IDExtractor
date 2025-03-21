# IDExtractor
以下の機能を持ったツールを管理するプロジェクト</br>
1.指定した以下の対象から特定のIDの抽出</br>
　sm,im,td,ncが先頭に付き、数字が後に続くIDを抽出する</br>
　誤検知を防ぐため3桁以上のIDのみチェック</br>
・ファイル名</br>
・フォルダ名</br>
・ファイルやフォルダへのパス</br>
・ファイルの中身</br>
例: Aviutlで編集したプロジェクトを保存したaupファイル、idをメモしたテキストファイル、それらを置いているフォルダ丸ごと、などからsm〇〇などを抽出<br>
</br>
2.1.で抽出したIDのリストに対して個別で特定のIDを指定して追加・除外できる</br>
</br>
3.1.2.によって指定されたIDに関する情報をニコニコ( https://www.nicovideo.jp )から取得</br>
　取得した情報はクレジット生成の補助に利用できる</br>
　取得した情報はIDライブラリに保存されるため次回以降の通信は省略可能</br>
　通信する/しないは左上歯車マークのオプションから指定可能
</br>
4.クレジット生成の補助をする</br>
・1.2.によってできたIDリストを整列して指定したパターンでテキストを整形する</br>
・1つの段落に対して複数の項目(+詳細)を登録したセットを整列して指定したパターンでテキストを整形する</br>

# 利用方法
1.ページ上部の「▼Code」を押下し「Download ZIP」を選択することでダウンロードできます<br>
2.解凍して NiconicoIDExtractor.exe をそのまま実行してください<br>
3.簡単な説明書を入れてあります(下記動画などもあります)

# その他　ツールについて
ver0.2.12時点でニコニ・コモンズから制作者の情報が得られないため、制作者欄を空のままとしています。<br>
申し訳ありませんが情報を得る手段の検討が付くまで今しばらくお待ちください。<br>
<br>
更新履歴や旧バージョンのダウンロード:<br>
　https://github.com/hoocheek/IDExtractor/releases<br>
　※実行ファイルの情報は同フォルダ内に生成される NiconicoIDExtractor.exe.Config へ保存されます<br>
　　移行したいバージョンの実行ファイルと同じフォルダへコピーすることでデータを引き継げます<br>
ニコニコ動画:<br>
(ver 0.0.x 時点の情報)<br>
　機能説明: https://www.nicovideo.jp/watch/sm39420176 <br>
　忙しい人向け簡単な使い方: https://www.nicovideo.jp/watch/sm39420769<br>
　ver 0.2.6 時点の更新まとめ: https://www.nicovideo.jp/watch/sm39836480<br>
<br>
　ご利用いただけた場合は上記動画をコンテンツツリーに<br>
　登録していただけるととても喜びます(登録は強制ではありません)。<br>
<br>
開発者: ほおちく(twitter: @hoo_tiku)
