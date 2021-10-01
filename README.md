# IDExtractor
以下の機能を持ったツールを管理するプロジェクト</br>
1.指定した以下の対象から特定のIDの抽出</br>
　抽出するのは接頭辞としてsm,im,td,ncが付き、数字が後に続くID</br>
　誤検知を防ぐため3桁以上のIDのみチェック(3桁未満は2.で個別に追加を推奨)
・ファイル名</br>
・フォルダ名</br>
・ファイルやフォルダへのパス</br>
・ファイルの中身</br>
</br>
2.1.で抽出したIDのリストに対して特定のIDを追加・除外する</br>
</br>
3.クレジット生成の補助をする</br>
・1.2.によってできたIDリストを整列して指定したパターンでテキストを整形する</br>
・1つの段落に対して複数の項目(+詳細)を登録したセットを整列して指定したパターンでテキストを整形する</br>
