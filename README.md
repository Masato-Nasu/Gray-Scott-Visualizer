# Gray-Scott Visualizer (Minimal Fade-In)

音楽に合わせて生成される **Gray-Scott 反応拡散パターン** をリアルタイムに可視化する Web アプリです。  
ブラウザだけで動作し、GitHub Pages から簡単に公開・体験できます。  
📱 **PWA対応 (iPhone / Android / PC 全対応確認済み)** — スマホやPCにインストールしてアプリのように使えます！

---

## 特長
- 🎶 **音楽入力対応** — ローカルの音楽ファイルを読み込み、音の特徴量に反応  
- 🌊 **リアルタイム生成** — Gray-Scott 反応拡散モデルでパターンが進化  
- 🖼️ **インタラクティブ** — クリックでフィード／キル値にフラッシュ効果  
- 📱 **PWA対応** — GitHub Pagesから直接インストール可能  
- 🌙 **Wake Lock対応** — 画面が暗転せず連続再生できる（Android/Chrome）  
- 🎧 **Media Session対応** — 通知バー・ロック画面・イヤホンボタンから操作可能。電話着信時もOS側で自動制御され安心

---

## インストール方法（PWA）
1. デモページを開く  
   👉 [https://masato-nasu.github.io/Gray-Scott-Visualizer/](https://masato-nasu.github.io/Gray-Scott-Visualizer/)  
2. **PC (Chrome/Edge)**：URLバー右端の「インストール」アイコンをクリック  
3. **Android (Chrome)**：メニュー「…」→「インストール」または「ホーム画面に追加」  
4. **iOS (Safari)**：共有ボタン →「ホーム画面に追加」  

---

## 制約について（重要）
- このアプリは **PWA（ブラウザアプリ）** として動作します  
- そのため **バックグラウンド再生は不可** です  
- 画面を閉じたり、別アプリに切り替えると音声は停止します  

---

## スクリーンショット

![Gray-Scott Visualizer Screenshot](./screenshot.png)

---

## デモページ

https://masato-nasu.github.io/Gray-Scott-Visualizer/

---

## 使い方
1. 「SELECT MUSIC FOLDER / FILES」から音楽ファイルをまとめて読み込み  
   - **PC**：フォルダを選択（サブフォルダ内も再帰的に読み込み）  
   - **Android**：フォルダ相当のディレクトリ選択が可能  
   - **iPhone/iPad**：ファイルアプリからフォルダを開き、中の曲をまとめて選択可能（フォルダ単位で扱える体験）  
2. **PLAY** で再生開始  
3. **PAUSE / NEXT / PREVIOUS** で操作可能  
4. キャンバスをクリックするとパターンが一時的に変調  

---

## 開発環境
- HTML / CSS / JavaScript  
- [Meyda](https://meyda.js.org/) (音声特徴量抽出ライブラリ)  

---

## 公開方法
1. このリポジトリを作成し、`index.html` と `screenshot.png` をアップロード  
2. GitHub → **Settings → Pages** から `main` ブランチを root で公開  
3. 数分後に `https://ユーザー名.github.io/リポジトリ名/` でアクセス可能  

---

## ライセンス
MIT License

# Gray-Scott Visualizer (Minimal Fade-In)

A **real-time Gray-Scott reaction-diffusion visualizer** that responds to music.  
Runs entirely in the browser and can be easily installed as a PWA via GitHub Pages.  
📱 **PWA Support (Tested on iPhone / Android / PC)** — Works like an app on your device!

---

## Features
- 🎶 **Music Input** — Load local audio files and react to audio features  
- 🌊 **Real-Time Generation** — Dynamic Gray-Scott reaction-diffusion patterns  
- 🖼️ **Interactive** — Click on the canvas to trigger flash effects  
- 📱 **PWA Support** — Installable directly from GitHub Pages  
- 🌙 **Wake Lock** — Prevents screen dimming; keeps music and visuals running (Android/Chrome)  
- 🎧 **Media Session** — Control playback via notifications, lock screen, or headset buttons. Integrates smoothly with phone calls

---

## Installation (PWA)
1. Open the demo page  
   👉 [https://masato-nasu.github.io/Gray-Scott-Visualizer/](https://masato-nasu.github.io/Gray-Scott-Visualizer/)  
2. **PC (Chrome/Edge)**: Click the “Install” icon in the URL bar  
3. **Android (Chrome)**: Menu “⋮” → “Install” or “Add to Home screen”  
4. **iOS (Safari)**: Share → “Add to Home Screen”  

---

## Limitations
- This is a **PWA (Progressive Web App)**  
- **Background playback is not supported**  
- Audio stops if you close the screen or switch to another app  

---

## Screenshot

![Gray-Scott Visualizer Screenshot](./screenshot.png)

---

## Demo Page

https://masato-nasu.github.io/Gray-Scott-Visualizer/

---

## Usage
1. Select music using **SELECT MUSIC FOLDER / FILES**  
   - **PC**: Pick a folder (recursive load of subfolders)  
   - **Android**: Choose a directory  
   - **iPhone/iPad**: Select multiple files from the Files app (works like folder selection)  
2. Press **PLAY** to start playback  
3. Use **PAUSE / NEXT / PREVIOUS** for controls  
4. Click the canvas to apply temporary flash effects  

---

## Tech Stack
- HTML / CSS / JavaScript  
- [Meyda](https://meyda.js.org/) (Audio feature extraction library)  

---

## Deployment
1. Create a repo and upload `index.html` and `screenshot.png`  
2. GitHub → **Settings → Pages** → publish `main` branch / root  
3. After a few minutes your app will be available at:  
   `https://username.github.io/repository/`  

---

## License
MIT License

