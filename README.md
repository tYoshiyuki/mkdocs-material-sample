# mkdocs-material-sample
Material for MkDocs と PlantUML をローカルで構築する docker-compose のサンプルです

## Feature
- Docker
- docker compose
- Material for MkDocs
- PlantUML
- Windows

## Usage

### 起動方法
- start.bat を実行してください。
	- コンテナの起動後 http://localhost:8000 にアクセスすると、MkDocsにアクセス出来ます。
	- また、http://localhost:8080 にアクセスすると、PlantUML Serverにアクセス出来ます。

### ビルド方法
- build.bat を実行してください。
	- siteフォルダ以下に、静的ファイルが出力されます。

### 停止方法
- stop.bat を実行してください。

## Note
- MkDocsの設定変更には mkdocs.yml を編集してください。
- docsフォルダ以下に、ドキュメントファイルを配置してください。
- スタイルシートは、docs/stylesheets/extra.css で設定してください。

## Demo
- https://tyoshiyuki.github.io/mkdocs-material-sample/

## Memo
- MkDocs Configuration
	- https://mkdocs.readthedocs.io/en/0.10/user-guide/configuration/
- Python Markdown Extensions
	- https://python-markdown.github.io/extensions/
- PyMdown Extensions
	- https://facelessuser.github.io/pymdown-extensions/

