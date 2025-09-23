# Gray-Scott Visualizer (Minimal Fade-In)

音楽に合わせて生成される **Gray-Scott 反応拡散パターン** をリアルタイムに可視化する Web アプリです。  
ブラウザだけで動作し、GitHub Pages から簡単に公開・体験できます。

---

## 特長
- 🎶 **音楽入力対応** — ローカルの音楽ファイルを読み込み、音の特徴量（RMS、スペクトル重心など）に反応  
- 🌊 **リアルタイム生成** — Gray-Scott 反応拡散モデルでパターンが進化  
- 🖼️ **インタラクティブ** — クリックでフィード／キル値にフラッシュ効果  
- 📱 **ブラウザのみで動作** — 追加インストール不要。スマホ・PC両対応  

---

## スクリーンショット

![Gray-Scott Visualizer Screenshot](./screenshot.png)

---

## デモページ

https://masato-nasu.github.io/Gray-Scott-Visualizer/

---

## 使い方
1. 「SELECT MUSIC FOLDER」から音楽ファイルをまとめて読み込み  
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

---

# English

## Gray-Scott Visualizer (Minimal Fade-In)

A **real-time Gray-Scott reaction-diffusion visualizer** that responds to music.  
It runs entirely in the browser and can be easily hosted with GitHub Pages.

---

## Features
- 🎶 **Music Input** — Load local audio files and react to features like RMS and spectral centroid  
- 🌊 **Real-Time Generation** — Dynamic Gray-Scott reaction-diffusion patterns  
- 🖼️ **Interactive** — Click the canvas to trigger flash effects on feed/kill values  
- 📱 **Browser-Only** — No installation required, works on both desktop and mobile  

---

## Screenshot

![Gray-Scott Visualizer Screenshot](./screenshot.png)

---

## Demo Page

https://masato-nasu.github.io/Gray-Scott-Visualizer/

---

## Usage
1. Load your music files using **SELECT MUSIC FOLDER**  
2. Press **PLAY** to start playback  
3. Control with **PAUSE / NEXT / PREVIOUS**  
4. Click on the canvas to apply temporary flash effects  

---

## Tech Stack
- HTML / CSS / JavaScript  
- [Meyda](https://meyda.js.org/) (Audio feature extraction library)  

---

## Deployment
1. Upload `index.html` and `screenshot.png` to this repository  
2. Go to **Settings → Pages**, set the source to `main` branch / root  
3. Your app will be live at:  
   `https://username.github.io/repository/`  

---

## License
MIT License
