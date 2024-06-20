## 介護施設Webサイト制作
TypeScriptとReactの学習を目的に、介護施設の架空のWebサイトを制作しました。この Webサイトは、モダンでレスポンシブなWebアプリケーションを構築しています。
あくまでTypeScriptとReactの学習のためであるため、Webサイト内のコンテンツやデザインは簡単な内容となっています。

## Webサイト制作の概要
このWebサイトでは、最新のWeb技術を活用して高齢者やその家族にとって使いやすく、情報が豊富な Webサイトを作成することを意識して制作しました。

#### ユーザーエクスペリエンスの向上
- 直感的なナビゲーション
  サイト内を簡単に移動できるように、直感的でわかりやすいナビゲーションメニューを設置しました。

- レスポンシブデザイン
  モバイルデバイスからデスクトップまで、どのデバイスでも快適に閲覧できるように、レスポンシブデザインを採用しています。各デバイスに応じたレイアウトの調整を行い、ユーザーエクスペリエンスを最適化しました。

#### 主要なページ内容・機能

- ホームページ
  お知らせ・健進会について・施設のご案内・採用情報・お問い合わせのコンテンツを掲載しています。

- 健進会について
  健進会の理念・理事長の挨拶・法人概要・交通アクセスを掲載しています。

- 施設のご案内
  健進会が運営する施設をご紹介しています。

- 採用情報
  健進会が求める人材・各職種のインタビュー・募集概要を掲載しています。応募を検討している方に対して、具体的な職務内容や職場環境を伝えることを目指しています。

- お問い合わせ
  サイト訪問者が質問や相談を簡単に送信できるように、シンプルで使いやすいお問い合わせフォームを実装しています。

#### 技術スタック
- TypeScript
- React
- CSS
- Vercel

Reactを使用して、コンポーネントベースのモジュール化されたコードを実現しています。これにより、コードの再利用性とメンテナンス性が向上しました。また、TypeScriptを使用することで、静的型付けによるエラー検出が可能となり、より堅牢で信頼性の高いコードを作成することができました。CSSは CSS Modulesを用いて、スタイルの管理とコンポーネントの分離を効率化しています。また、レスポンシブデザインを容易に実現するために、メディアクエリを活用しています。

## Web サイト制作の進め方
#### 要件定義
1. ユーザーグループ
   老年者、家族、施設スタッフなど、異なるユーザーグループに対応するための異なるコンテンツと機能を提供する。

2. 情報提供
   施設の概要、サービス、設備、料金体系などの詳細な情報を提供する。
   よく検索されるキーワードに基づいた FAQ（よくある質問）セクションを用意する。

3. お問い合わせと予約
   オンラインで問い合わせや見学予約ができる専用フォームを用意する。

4. スタッフ情報
   スタッフのプロフィールや担当業務などを掲載し、利用者や家族が信頼できる環境であることを感じられるようにする。

5. セキュリティとプライバシー
   個人情報の取り扱いに関するプライバシーポリシーを公開し、安全な通信手段（SSL など）を使用してユーザーデータを保護する。

#### モックアップ作成
Figmaを使って、サイトマップやデザインカンプ、モックアップを作成しました。これにより、視覚的なイメージを具体化し、デザインのフィードバックを得ることができました。

**サイトマップ**
![sitemap-1](https://github.com/kakuta0915/kenshinkai/assets/107552595/1c442f10-88f6-49d4-a1a4-600c118fc24f)

**ワイヤーフレーム**
![kenshinkai-wf](https://github.com/kakuta0915/kenshinkai/assets/107552595/f1b73003-3e9e-4f70-814f-c94641c70daa)


**デザインカンプ**
![Uploading kenshinkai-design-comp.png…]()
![kenshinkai-design-tokens](https://github.com/kakuta0915/kenshinkai/assets/107552595/c05f38dd-1da3-4cfa-ab7c-382c8156ad61)


#### 開発段階
再利用可能な React コンポーネントを設計・実装しました。各コンポーネントは独立しており、必要に応じて他のコンポーネントに組み込むことができます。

#### デプロイ
Vercelを利用して、プロジェクトをインターネット上にデプロイしました。

## 制作を終えて
このWebサイト制作を通じて、TypeScriptとReactの深い理解と実践的なスキルを習得することができました。また、モダンな Webアプリケーションの開発プロセス全体を経験することで、実際の業務における即戦力となる能力を身につけました。
