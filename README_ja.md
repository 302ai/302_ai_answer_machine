# <p align="center"> 📝 AI 解答機 🚀✨</p>

<p align="center">AI解答機は写真撮影、写真のインポート、テキスト入力という3つの方法で問題を提出でき、AIが詳細な解答プロセスを生成し、文脈に基づいて追加質問することもできます。</p>

<p align="center"><a href="https://302.ai/ja/tools/answer/" target="blank"><img src="https://file.302.ai/gpt/imgs/github/20250102/72a57c4263944b73bf521830878ae39a.png" /></a></p >

<p align="center"><a href="README_zh.md">中文</a> | <a href="README.md">English</a> | <a href="README_ja.md">日本語</a></p>


![](docs/302_AI_Answer_Machine_jp.png)

[302.AI](https://302.ai/ja/)の[AI 解答機](https://302.ai/ja/tools/answer/)のオープンソース版です。
302.AIに直接ログインすることで、コード不要、設定不要のオンライン体験が可能です。
あるいは、このプロジェクトをニーズに合わせてカスタマイズし、302.AIのAPI KEYを統合して、自身でデプロイすることもできます。

## インターフェースプレビュー
写真ギャラリーからのインポートまたはカメラ撮影で画像をアップロードできます。
![](docs/302_AI_Answer_Machine_jp_screenshot_01.png)

テキストで問題を入力することができます。
![](docs/302_AI_Answer_Machine_jp_screenshot_02.png)     

AIが分析と手順の説明を含む詳細な解答プロセスを生成します。AIの回答に対して追加質問をすることができ、AIは文脈に基づいて回答します。
![](docs/302_AI_Answer_Machine_jp_screenshot_03.png)     

すべての問題と解答は練習帳に保存され、いつでも復習できます。
![](docs/302_AI_Answer_Machine_jp_screenshot_04.png)

## プロジェクトの特徴
### ✏️ 問題のアップロード
写真撮影、写真のインポート、テキスト入力の3つの方法で問題を提出できます。
### ✒️ 問題の解答
AIを使用して詳細な解答プロセスを生成します。
### 📖 履歴記録
すべての問題記録は練習帳に保存され、簡単に参照できます。
### 💬 追加質問
AIに追加質問をすることができ、現在の問題の文脈に基づいて回答します。
### 🌓 ダークモード
ダークモードをサポートしており、あなたの目を保護します。
### 🌍 多言語サポート
- 中国語インターフェース
- 英語インターフェース
- 日本語インターフェース


## 🚩 将来のアップデート計画
- [ ] 大規模な問題データベースの作成
- [ ] より多くの問題タイプのサポート



## 🛠️ 技術スタック

- **フレームワーク**: Next.js 14
- **言語**: TypeScript
- **スタイリング**: TailwindCSS
- **UIコンポーネント**: Radix UI
- **状態管理**: Jotai
- **フォーム処理**: React Hook Form
- **HTTPクライアント**: ky
- **国際化**: next-intl
- **テーマ**: next-themes
- **コード規約**: ESLint, Prettier
- **コミット規約**: Husky, Commitlint

## 開発&デプロイ
1. プロジェクトのクローン
```bash
git clone https://github.com/302ai/302_ai_answer_machine
cd 302_ai_answer_machine
```

2. 依存関係のインストール
```bash
pnpm install
```

3. 環境設定
```bash
cp .env.example .env.local
```
必要に応じて`.env.local`の環境変数を修正してください。

4. 開発サーバーの起動
```bash
pnpm dev
```

5. プロダクションビルド
```bash
pnpm build
pnpm start
```


## ✨ 302.AIについて ✨
[302.AI](https://302.ai/ja/)は企業向けのAIアプリケーションプラットフォームであり、必要に応じて支払い、すぐに使用できるオープンソースのエコシステムです。✨
1. 🧠 包括的なAI機能：主要AIブランドの最新の言語、画像、音声、ビデオモデルを統合。
2. 🚀 高度なアプリケーション開発：単なるシンプルなチャットボットではなく、本格的なAI製品を構築。
3. 💰 月額料金なし：すべての機能が従量制で、完全にアクセス可能。低い参入障壁と高い可能性を確保。
4. 🛠 強力な管理ダッシュボード：チームやSME向けに設計 - 一人で管理し、多くの人が使用可能。
5. 🔗 すべてのAI機能へのAPIアクセス：すべてのツールはオープンソースでカスタマイズ可能（進行中）。
6. 💪 強力な開発チーム：大規模で高度なスキルを持つ開発者集団。毎週2-3の新しいアプリケーションをリリースし、毎日製品更新を行っています。才能ある開発者の参加を歓迎します。
