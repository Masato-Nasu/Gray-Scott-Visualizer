Gray-Scott Visualizer (Minimal Fade-In)

音楽に合わせて生成される Gray-Scott 反応拡散パターン をリアルタイムに可視化する Web アプリです。
ブラウザだけで動作し、GitHub Pages から簡単に公開・体験できます。
📱 PWA対応 — スマホやPCにインストールしてアプリのように使えます！

⚠️ 注意: PWAはシステム上の制約により、画面を完全に消した状態や他アプリを前面に出した状態では再生が止まる場合があります。
（Wake Lock + 減光で「画面点灯のまま」再生するのが安定した使い方です）

特長

🎶 音楽入力対応 — ローカルの音楽ファイルを読み込み、音の特徴量（RMS、スペクトル重心など）に反応

🌊 リアルタイム生成 — Gray-Scott 反応拡散モデルでパターンが進化

🖼️ インタラクティブ — クリックでフィード／キル値にフラッシュ効果（白飛び防止を改善）

📱 ブラウザのみで動作 — 追加インストール不要。スマホ・PC両対応

🧩 PWA対応 — GitHub Pagesから直接インストール可能

インストール方法（PWA）

デモページを開く
👉 https://masato-nasu.github.io/Gray-Scott-Visualizer/

PC (Chrome/Edge)：URLバー右端の「インストール」アイコンをクリック

Android (Chrome)：メニュー「…」→「インストール」または「ホーム画面に追加」

iOS (Safari)：共有ボタン →「ホーム画面に追加」

スクリーンショット

デモページ

https://masato-nasu.github.io/Gray-Scott-Visualizer/

使い方

「SELECT MUSIC FOLDER」から音楽ファイルをまとめて読み込み

PLAY で再生開始

PAUSE / NEXT / PREVIOUS で操作可能

キャンバスをクリックするとパターンが一時的に変調（白飛びを抑えたソフトクリップ処理済み）

開発環境

HTML / CSS / JavaScript

Meyda
 (音声特徴量抽出ライブラリ)

公開方法

このリポジトリを作成し、index.html と screenshot.png をアップロード

GitHub → Settings → Pages から main ブランチを root で公開

数分後に https://ユーザー名.github.io/リポジトリ名/ でアクセス可能

ライセンス

MIT License

English
Gray-Scott Visualizer (Minimal Fade-In)

A real-time Gray-Scott reaction-diffusion visualizer that responds to music.
It runs entirely in the browser and can be easily hosted with GitHub Pages.
📱 PWA Supported — Can be installed on desktop and mobile for an app-like experience.

⚠️ Note: Due to system restrictions, PWAs cannot guarantee continuous playback in the background (when the screen is turned off or another app is foregrounded).
The stable usage is to keep the screen on (dimmed with Wake Lock) while playing.

Features

🎶 Music Input — Load local audio files and react to features like RMS and spectral centroid

🌊 Real-Time Generation — Dynamic Gray-Scott reaction-diffusion patterns

🖼️ Interactive — Click the canvas to trigger flash effects on feed/kill values (with soft-clipped rendering to avoid white-out)

📱 Browser-Only — No installation required, works on both desktop and mobile

🧩 PWA Support — Installable directly from GitHub Pages

Screenshot

Demo Page

https://masato-nasu.github.io/Gray-Scott-Visualizer/

Usage

Load your music files using SELECT MUSIC FOLDER

Press PLAY to start playback

Control with PAUSE / NEXT / PREVIOUS

Click on the canvas to apply temporary flash effects (soft-clipped to avoid white-out)

Tech Stack

HTML / CSS / JavaScript

Meyda
 (Audio feature extraction library)

Deployment

Upload index.html and screenshot.png to this repository

Go to Settings → Pages, set the source to main branch / root

Your app will be live at:
https://username.github.io/repository/

License

MIT License
