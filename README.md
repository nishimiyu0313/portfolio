# ポートフォリオ

## 1. フリマアプリ
ユーザー同士で商品の出品・購入ができるアプリです

**GitHub URL:** https://github.com/nishimiyu0313/yamada-fleamarketapp.git

**使用技術:** PHP, Laravel, Blade, JS, MySQL, mailhog

### 主な機能

- ユーザー登録・ログイン・プロフィール編集・メール認証
- 商品の出品・一覧表示・詳細ページ
- 購入機能・お気に入り機能
- 画像アップロード（フォーム+JS プレビュー）

### 工夫ポイント

- 画面認証により不正アクセスを防止
- テーブルを分け購入履歴を残した

---

## 2. 勤怠管理アプリ
ユーザーの勤怠打刻と管理ができるアプリです

**GitHub URL:** https://github.com/nishimiyu0313/yamada-attendanceapp.git

**使用技術:** PHP, Laravel, Blade, JS, MySQL, mailhog

### 主な機能

- ユーザー登録・ログイン・メール認証
- 管理者とユーザーの権限管理
- 勤怠管理（出勤・退勤・休憩の打刻）
- データ一覧表示
- ユーザーからの勤怠修正申請
- 管理者による認証機能

### 工夫ポイント

- 不正アクセスや情報漏洩防止のため勤怠情報の閲覧、編集時に権限をつけた
- Collection を活用して効率的にデータをループ表示

---

## 3. Todoアプリ（学習中）
フロントは Nuxt + JavaScript、バックエンドは Laravel を使用した Todo アプリです。  
現在、フルスタック開発の理解を深めるために学習・改良を進めています。

**GitHub URL:** https://github.com/nishimiyu0313/yamada-todoapp.git

**使用技術:** Nuxt, JavaScript, Laravel, PHP, MySQL

### 主な機能（学習中）
- タスクの追加・削除・完了状態管理
- API を経由したフロントとバックのデータ連携
- フロントでの動的表示（Nuxt SPA）

### 学習ポイント
- ChatGPT を参考に作成し、コードの理解と改良をしている
- フロントとバックの連携や API の動き、データベース操作の理解を深めている
- 既存コードを改良して徐々に機能を追加予定

## 参考

- コードは各リポジトリの GitHub を参照してください
