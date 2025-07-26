# OSS & Projects

オープンソースライブラリとプロジェクトの詳細情報です。

## 🎯 Main Projects

### [ProMarker](https://github.com/vemic/promarker) ![Release Candidate](https://img.shields.io/badge/status-release%20candidate-blue)
**業務機能スケルトン生成ツール**

FreeMarkerベースのテンプレートに対し、辞書情報を流し込むことで、業務機能のスケルトンを生成するWebアプリケーション。

**特徴:**
- 独自のFunction Resolverによって柔軟かつシンプルな構造を実現
- intra-mart実装の定型パターンに対応
- 案件内・案件間での資材自動生成を可能にする
- 拡張可能な構成（画面項目スケルトン生成は今後対応予定）
- 先行リリース版として実用レベルで稼働中

**技術スタック**: Java, FreeMarker, Spring Boot

---

### [Function Resolver](https://github.com/vemic/function-resolver) ![Release Candidate](https://img.shields.io/badge/status-release%20candidate-blue)
**動的式評価エンジン**

ProMarker内部で使用されるコア技術。

**特徴:**
- 式展開において辞書データや条件式を動的に評価
- 柔軟かつ分かりやすいテンプレート定義を実現
- 他のプロジェクトでも再利用可能な汎用ライブラリ
- ProMarkerと同様に先行リリース版として実用レベルで稼働中

**技術スタック**: Java

---

### [SeasarBatis](https://github.com/vemic/seasarbatis) ![Alpha](https://img.shields.io/badge/status-alpha-red)
**軽量O/Rマッピングライブラリ**

iBATIS/MyBatisをSeasar2で活用するための軽量マッピングライブラリ。

**特徴:**
- Seasar2のDIコンテナとの親和性
- 軽量でシンプルな構成
- 既存システムへの導入が容易
- 現在アルファ版として開発・検証中

**技術スタック**: Java, MyBatis, Seasar2

---

### [AppRunner](https://github.com/vemic/apprunner) ![In Development](https://img.shields.io/badge/status-in%20development-yellow)
**UI自動操作ツール (with Selenade)**

ノンコードによるUI自動操作/テストツール。

**特徴:**
- プログラミング不要の直感的なUI操作定義
- 継続的なテスト自動化に対応
- Webアプリケーションの回帰テストを効率化
- 現在開発中、機能拡張を継続実施

**技術スタック**: Java, Selenium

---

## 📈 Impact & Metrics

- **ProMarker**: 社内複数案件で活用、開発工数20-30%削減を実現
- **SeasarBatis**: レガシーシステムのモダナイゼーションで活用
- **AppRunner**: 回帰テスト自動化により品質向上とリリース頻度向上に貢献

[← Back to Profile](../README.md)
