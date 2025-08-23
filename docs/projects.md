# OSS & Projects

オープンソースライブラリとプロジェクトの詳細情報です。

## 🎯 Main Projects

### [jackson-databind-jsonc](https://github.com/vemic/jackson-databind-jsonc) ![Stable](https://img.shields.io/badge/status-stable-brightgreen)
Jacksonの `JsonMapper` を拡張し、**JSONC（コメント付きJSON）** を扱えるようにするラッパーライブラリ。  
`.jsonc` ファイルを通常の `ObjectMapper` と同様に読み書き可能。  
設定ファイルやサンプルデータを扱う場面での開発効率を高めます。

**技術スタック**: Java, Jackson

---

### [SeasarBatis](https://github.com/vemic/seasarbatis) ![Alpha](https://img.shields.io/badge/status-alpha-red)
Seasar2のEOL後も既存資産を活かすための、iBATIS/MyBatisラッパーライブラリ。  
S2JDBCライクなSQLファイル実行（selectBySqlFile）、クエリビルダー、バッチ処理、トランザクション管理などをMyBatis環境に補完。  
既存コードとの連続性を保ちつつ、モダナイズを支援。  

**技術スタック**: Java, MyBatis, Seasar2

---

### [ProMarker](https://github.com/vemic/promarker) ![Release Candidate](https://img.shields.io/badge/status-release%20candidate-blue)
テンプレートと辞書情報を組み合わせて、機能単位のスケルトンや定型的な  
ディレクトリ構成・ソースコード・初期データを自動生成するWebアプリケーション。  
FreeMarkerを活用し、パターン定義による効率的な資材生成を実現。Spring Boot 3系・Java 21対応。  
主な機能: テンプレート管理・コード生成、ファイル管理（アップロード/ダウンロード/バッチ処理）、認証（JWT/OAuth2）、API連携、拡張可能なモジュール設計。

**技術スタック**: Java, Spring Boot, FreeMarker, Selenide, JWT, OAuth2, MySQL

---

### [Function Resolver](https://github.com/vemic/function-resolver) ![Release Candidate](https://img.shields.io/badge/status-release%20candidate-blue)
Java APIとテキスト関数を接続するプラグイン型の動的式評価エンジン。  
関数呼び出しを柔軟にJavaメソッドへマッピングでき、テンプレート展開や条件式評価などに利用可能。  
他プロジェクトへの組み込みも容易。  
現状、ProMarkerに組み込まれています。  

**技術スタック**: Java

---

### [AppRunner/Selenade](https://github.com/vemic/apprunner) ![Discontinued](https://img.shields.io/badge/status-discontinued-gray)
SelenideベースのWeb UI自動操作・テストツール。  
ノーコードで操作定義が可能で、回帰テストや自動化を目的に開発を進めていましたが、  
価値を感じにくくなったため開発を中止しました。

**技術スタック**: Java, Selenide

---

## 📈 Impact & Metrics

- **ProMarker**: 実際の複数案件で活用し開発立ち上げを効率化  
- **jackson-databind-jsonc**: JSONC対応の軽量ユーティリティとして公開  
- **SeasarBatis**: 検証中  

---

[← Back to Profile](../README.md)
