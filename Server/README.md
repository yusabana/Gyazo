社内向けGyazo
===================

Requirement
------------------

- upload.cgiをcgiとして扱えるようにする
- upload.cgiのあるディレクトリをドキュメントルートとする
- upload.cgi の HOST_URL 部分を環境に応じて書き換える


Explanation
------------------

- data, db ディレクトリにはapacheユーザでの書き込み権限を与える
- data ディレクトリは画像が置かれる
