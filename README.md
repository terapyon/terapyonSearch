# terapyonSearch
Podcast voice search system


# システム構成

## 構成要素

- 音声toテキスト: ローカル実行
- 検索インデックスDB: RDBMS
- 検索インデックス化: Lambda? or ローカル, SQLAlchemy
- 検索: AWS Lambda, SQLite3 execute() join or 複数テーブル


## 利用技術

- 音声toテキスト: whisper
- 形態素解析: MeCab+IPAdicが現実的, Ginzaはデータ量が大きい模様
- RDBMS: SQLite
- AWS Lambda
- AWS EFS (S3 or ...)
- APIサーバ: Flask

