# Personal Apps

個人的な興味・関心で開発しているアプリケーション群です。

## 📱 B2Cアプリケーション

### mirel-platform β - 応援メッセージ収集アプリ（2016） ![Discontinued](https://img.shields.io/badge/status-discontinued-gray)
**概要**: 特定アーティストへの長期留学壮行を目的とした、応援メッセージ収集用Webアプリケーション

**独自機能・特徴**:
- **メッセージの温度感表現** - Googleフォーム等では実現できない感情的な表現力
- **再投稿制御** - 重複や不適切な投稿を防ぐ仕組み
- **認証付き投稿管理** - セキュアな投稿環境の提供
- **代筆ワークフロー** - 複数人での協力的なメッセージ作成フロー

**技術的成果**:
- **独自軽量MVCフレームワーク `mirel-platform`** を開発・実装
- ファンからのメッセージを効率的に集約・編集・贈呈
- 目的達成後、サービス提供を終了

**mirel-platform技術変遷**:
- **v1（2016）**: 完全スクラッチ実装、カスタムルーティング機構
- **v2（2018）**: Spring Boot統合版、現在はProMarkerの基盤技術として活用

**使用技術**: 独自MVC (mirel-platform)、Web技術スタック

### [mochipay](https://github.com/vemic/mochipay)（仮称） ![In Development](https://img.shields.io/badge/status-in%20development-yellow)
**概要**: グループでの支払い管理と旅行計画を効率化するWebアプリケーション

**主要機能**:
- **割り勘管理** - 複数人での支払いを自動計算・精算
  - **割り勘比率設定**: 均等割り、性別比率、カスタム比率、途中参加者対応
  - **支払いステータス管理**: 未払い、支払い済み、確認済みの管理
- **旅程管理** - 旅行やイベントのスケジュール・予算管理
- **グループ協調** - メンバー間でのリアルタイム情報共有
- **支払い履歴追跡** - 詳細な支出記録と分析機能

**技術的特徴**:
- リアルタイム更新機能（WebSocket/Server-Sent Events）
- レスポンシブなユーザーインターフェース

**使用技術**: 非公開

---

## 💡 開発コンセプト

### 課題解決への情熱
- **既存ツールの限界突破**: GoogleフォームやSNSでは実現できない独自機能の開発
- **日常の不便を解決**: 割り勘計算や旅程管理など、身近な課題への技術的アプローチ
- **ユーザー体験最優先**: エンドユーザーの感情的ニーズまで考慮した設計

### 技術的探求心
- **独自フレームワーク開発**: 問題に最適化されたソリューションの創造（mirel-platform）
- **モダン技術の積極活用**: 最新のWeb技術による快適なユーザー体験
- **軽量・効率性**: 必要十分な機能を最小限の技術で実現

### 持続可能な価値創造
- **コミュニティ貢献**: 特定のコミュニティの絆を深める技術活用
- **実用性重視**: 実際に使われ続けるサービスの開発
- **長期的影響**: 一時的なツールではなく、記憶に残る体験の提供

[← Back to Profile](../README.md)
