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
公開後は以下の URL からアクセス可能です:

https://ユーザー名.github.io/リポジトリ名/

yaml
コードをコピーする

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
