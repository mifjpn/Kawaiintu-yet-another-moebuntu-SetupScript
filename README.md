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

以下に、GitHub等のREADMEに適した自然な英語訳を作成しました。OSS（オープンソースソフトウェア）のカルチャーに合わせた、親しみやすくかつ技術的に正確な表現にしています。
🌈 Kawaiintu (Post-Moebuntu) Setup Helper

    The legitimate successor to Moebuntu. A safe, smart, and above all, KAWAII Ubuntu customization tool.

🎬 Watch it in Action!
✨ Color Theme Switching Demo

Watch on YouTube Shorts →
🎨 9 Beautiful Color Themes

Kawaiintu features 9 sophisticated color variations.
Switch to a perfectly unified kawaii world with just one click.
✨ What's New in Kawaiintu!
🎓 Evolved "Sophisticated Kawaii"

Transitioning from the overly sweet design of traditional Moebuntu to a more refined, "clean and cute" aesthetic. Modern elegance that is easy to use for daily tasks.
🔧 Fully Automated (Python-driven)

    Everything from color generation to setup is automated.

    No manual work in Illustrator required.

    Dangerous hardcoded settings are completely eliminated.

    Safe, Easy, and Reliable.

🛡️ Safe and Secure Design

Designed to absolutely never break system files. No more worrying about "messing up your PC" when customizing.
📁 Unified, Beautiful Icons

Eliminated the mixture of line art and color icons in the file manager. Everything is now harmonized with matching color schemes.
🎨 Fully Applied Application Themes

Automatically applies the system theme to modern applications like GIMP. The kawaii aesthetic is maintained even when you open apps.
🖼️ Super Easy Login Screen Customization

No complicated configuration files needed. Just drag & drop your favorite image, and Kawaiintu will automatically apply it to the login screen.
🚀 Fully Compatible with Ubuntu 26.04 LTS

Optimized for the latest GNOME desktop environment. All the latest features are fully supported.
🚀 Quick Start
Requirements

    Ubuntu 26.04 LTS (Optimized for this version)

Installation Guide
1️⃣ Download

From your browser, go to the Release page and download scripts.tar.xz.
2️⃣ Extract

Double-click scripts.tar.xz or use the archive manager to extract it.
3️⃣ Run

Open the extracted scripts folder, right-click Kawaset → select "Run as a Program"!

🎉 The Kawaiintu Setup Helper menu will open.
📖 How to Use (Details)
⚠️ MUST READ: Always start with "base setting (Do first!)"

When the menu opens, please execute "base setting (Do first!)" first.

This step will open gnome-shell-extension-manager:

    Search for "User Themes" in the "Browse" tab.

    Click "Add" to install.

    Move to the "Installed" tab and toggle "User Themes" to ON.

    Close the window.

✅ After this setup, themes will be applied correctly.
🎨 Apply Themes
Color Theme

Just choose your favorite color from the menu. Window themes and Shell themes will be applied automatically.
🖼️ Login Screen (GDM) Customization

You can also customize the login screen while applying a theme:

    Enter Y to change the login screen.

    Drag & drop your favorite image file → Automatically converted and applied.

    Alternatively, select Kawaiintu's default kawaii illustration or a simple black background.

🎨 Icons

Easily apply or remove Kawaii icon packs.
🥾 Plymouth (Boot Screen)

Set up a kawaii spinner screen for OS boot. Custom images can also be used.
🖥️ Wallpaper

Freely customize your desktop background. Supports drag & drop. Automatically applied to both Light and Dark modes.
🔌 Application Settings
Firefox

    Switch between Snap and Deb versions (Deb version is recommended).

File Manager

    Install, configure, or remove Nemo / Thunar.

    Includes custom action presets, such as "Open in Terminal".

Media Player

    Easily remove unnecessary apps like VLC.

🔊 Sound

Choose from multiple Kawaii sound themes:

    Amateur Voice Actor version

    Maid version

    Sci-Fi version

    Hatsune Miku version

    etc.

Easy removal of custom sounds.
🔄 Revert to Default

Select "remove Kawaiintu/Moe-theme" to safely remove all customizations and revert to the default Ubuntu (Yaru) theme.
⚠️ Known Issues
User Themes Extension in VirtualBox Environments

In very rare cases, the User Themes extension may not become active immediately.
Solution: Apply it manually from GNOME Tweaks or restart the system.
Issues After Ubuntu Upgrades

If you upgraded Ubuntu without doing a clean install, the initial setup might fail.

Solution:
Bash

sudo apt remove gnome-shell-extension-manager
sudo apt install gnome-shell-extension-manager

After doing this, please run the base setup again.
📝 License & Developer Info

This setup helper is released under the MIT License.

Feel free to fork, modify, and translate it! Please go ahead and create a version in your local language.
Credits

    Core Themes, Plymouth, Icons: Toy (Original Creator of Moebuntu)

    Kawaiintu Transformation, Automation System, Python Compilation: Mifjpn

Important Request

When forking, please do not include theme files directly in the repository. Set them up to be dynamically downloaded from GitHub.
🌍 Community

    GitHub Issues: Bug reports & feature requests

    GitHub Discussions: General chat, usage examples, customization sharing

    YouTube Shorts: Check out demo videos for operational flow

💝 Respect for Moebuntu

Kawaiintu is the legitimate successor that brings the nostalgic Moebuntu into the latest Ubuntu environment (26.04 LTS) with love and respect.

We have evolved the "Kawaii Ubuntu" worldview created by Moebuntu into something safer, smarter, and easier for everyone to use.

Please enjoy the newly reborn, safe, and smart world of Kawaiintu! 🌈✨
