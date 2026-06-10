# 🌈 Kawaiintu (Post-Moebuntu) Setup Helper

> Moebuntu の正統後継者。安全で、スマートで、そして何より**可愛い** Ubuntu カスタマイズツール

---

## 🎬 Watch it in Action!

### ✨ カラーテーマ切り替えデモ
[![Kawaiintu Theme Demo](https://img.youtube.com/vi/FO4BmporPio/maxresdefault.jpg)](https://www.youtube.com/shorts/FO4BmporPio)

**[YouTube Shortsで動画を見る →](https://www.youtube.com/shorts/FO4BmporPio)**

---

## 🎨 9 つの美しいカラーテーマ

<img src="https://raw.githubusercontent.com/mifjpn/Kawaiintu-yet-another-moebuntu-MifjpnsOriginal/main/themes/background.jpg" width="600" alt="Kawaiintu Theme Background">

Kawaiintu は **9 つの洗練されたカラーバリエーション**を備えています。  
ワンクリックで完全に統一された可愛い世界観に切り替わります。

---

## ✨ Kawaiintu のここが新しい！

### 🎓 進化した「大人の可愛さ」
従来の Moebuntu の甘すぎるデザインから、より洗練された「スッキリとした可愛さ」へ。普段使いしやすい、モダンなエレガンス。

### 🔧 完全自動化（Python 駆動）
- カラー生成から全ての設定まで自動化
- イラストレーターでの手作業は不要
- 危険なハードコード設定も完全廃止
- **安全・簡単・確実**

### 🛡️ 安心・安全設計
システムファイルを絶対に壊さない設計。カスタマイズしても「パソコンがおかしくなる」心配はもう要りません。

### 📁 統一された美しいアイコン
ファイルマネージャーの線画とカラーアイコンの混在を解消。全てが統一感のある「色仲間」に。

### 🎨 アプリのテーマも完全反映
GIMP などの最新アプリも、システムのテーマに合わせて自動適用。アプリを開いても可愛い世界観が保たれます。

### 🖼️ ログイン画面のお着替えが超簡単
難しい設定ファイルは不要。好きな画像をドラッグ&ドロップするだけで、Kawaiintu が自動でログイン画面に適用します。

### 🚀 Ubuntu 26.04 LTS ���全対応
最新の GNOME デスクトップ環境に最適化。最新機能も全てサポート。

---

## 🚀 クイックスタート

### 必要な環境
- **Ubuntu 26.04 LTS**（このバージョンに最適化）

### インストール手順

#### 1️⃣ ダウンロード
ブラウザで [Release](https://github.com/mifjpn/Kawaiintu-yet-another-moebuntu-SetupScript/releases) ページから `scripts.tar.xz` をダウンロードしてください。

#### 2️⃣ 解凍
`scripts.tar.xz` をダブルクリックするか、アーカイブマネージャーで解凍します。

#### 3️⃣ 実行
解凍した `scripts` フォルダを開いて、**`Kawaset`** を右クリック → **「プログラムとして実行」** を選ぶだけ！

🎉 **Kawaiintu Setup Helper** のメニューが開きます。

---

## 📖 使用方法（詳細）

### ⚠️ 必読：最初は必ず「base setting (Do first!)」から

メニューが開いたら、**まず最初に「base setting (Do first!)」を実行してください。**

この手順では `gnome-shell-extension-manager` が開きます：

1. **「Browse」** タブで "User Themes" を検索
2. **「Add」** をクリックしてインストール
3. **「Installed」** タブに移動して、"User Themes" を **ON** に切り替え
4. ウィンドウを閉じる

✅ このセットアップ後、テーマが正しく反映されるようになります。

### 🎨 テーマ適用

#### カラーテーマ
メニューから好きな色を選ぶだけ。ウィンドウテーマと Shell テーマが自動で適用されます。

#### 🖼️ ログイン画面（GDM）のカスタマイズ
テーマ適用中に、ログイン画面もカスタマイズできます：

- `Y` を入力してログイン画面を変更
- **好きな画像ファイルをドラッグ&ドロップ** → 自動変換・適用
- または、Kawaiintu のデフォルト可愛いイラストか、シンプルな黒背景を選択

#### 🎨 アイコン
Kawaii アイコンパックの適用・削除が簡単。

#### 🥾 Plymouth（ブートスクリーズ）
OS 起動時の可愛いスピナー画面を設定。カスタム画像も使用可能。

#### 🖥️ ウォールペーパー
デスクトップ背景も自由にカスタマイズ。ドラッグ&ドロップ対応。ライト/ダークモード両方に自動適用。

### 🔌 アプリケーション設定

#### Firefox
- Snap 版 ↔️ Deb 版 を切り替え（Deb 版推奨）

#### ファイルマネージャー
- **Nemo** / **Thunar** のインストール・設定・削除
- ターミナルで開く等、カスタムアクションもプリセット

#### メディアプレイヤー
- 不要な VLC などを簡単削除

### 🔊 サウンド

複数の Kawaii サウンドテーマから選択：
- アマチュア声優版
- メイド版
- SF 版
- 初音ミク版
- など

カスタムサウンドの削除も簡単。

### 🔄 元に戻す

**「remove Kawaiintu/Moe-theme」** を選択すれば、全てのカスタマイズが安全に削除され、デフォルト Ubuntu（Yaru）に戻ります。

---

## ⚠️ 既知の問題

### VirtualBox 環境での User Themes 拡張
ごく稀に、User Themes 拡張がすぐに有効にならないことがあります。  
**対処法：** GNOME Tweaks から手動で適用するか、システムを再起動してください。

### Ubuntu アップグレード後の問題
クリーンインストールせずに Ubuntu をアップグレードした場合、初期セットアップが失敗することがあります。

**対処法：**
```bash
sudo apt remove gnome-shell-extension-manager
sudo apt install gnome-shell-extension-manager
```

その後、base setup を再実行してください。

---

## 📝 ライセンス & 開発者向け情報

このセットアップヘルパーは **MIT ライセンス** で公開されています。

**フォーク・改造・多言語化は自由です！** ぜひあなたのローカル言語版を作ってください。

### クレジット
- **コア テーマ・Plymouth・アイコン：** Toy（Moebuntu オリジナル作成者）
- **Kawaiintu 化・自動化システム・Python コンパイル：** Mifjpn

### 重要なお願い
フォークした際は、テーマファイルをリポジトリに含めず、**GitHub から動的にダウンロード** する設定にしてください。

---

## 🌍 コミュニティ

- **GitHub Issues：** バグ報告・機能リクエスト
- **GitHub Discussions：** 雑談・使用例・カスタマイズ共有
- **YouTube Shorts：** デモ動画で操作イメージを確認

---

## 💝 Moebuntu への敬意

Kawaiintu は、懐かしの Moebuntu への敬意と愛を持ちながら、最新の Ubuntu 環境（26.04 LTS）に対応させた**正統後継者**です。

Moebuntu が作ってくれた「可愛い Ubuntu」という世界観を、さらに安全で、スマートで、多くの人が使いやすい形に進化させました。

---

**新しく生まれ変わった、安全でスマートな Kawaiintu の世界をぜひお楽しみください！** 🌈✨
