# 🎈 Balloon Burst! (バルーンバースト！)

A simple and fun browser-based balloon-popping game! Tap the balloons to score points before time runs out.
ブラウザで遊べる、簡単で楽しい風船割りゲーム！時間切れになる前に風船をタップしてスコアを稼ごう。

## 🎮 How to Play (遊び方)

### 🇯🇵 日本語

**目的:**
制限時間（30秒）以内にできるだけ多くの風船を割って、ハイスコアを目指しましょう！

**風船の種類と効果:**
- 🎈 **普通の風船 (カラフル):** 基本の風船です。タップして割るとポイントが加算されます。
- ⚠️ **黒い風船 (お邪魔):** 触らないで！割ってしまうと **−20 pts** のペナルティになります。
- ⭐ **金の風船 (レア):** 見つけたらラッキー！ **+5 pts** のボーナスと、残り時間が **+1秒** 延長されます。
- ☠️ **赤い風船 (大外れ):** 絶対に割ってはいけない風船！ **−50 pts** の大減点と、残り時間が **-2秒** 減る特大ペナルティです。
- ✨ **スーパーレア風船:** 滅多にお目にかかれない特別な風船！？割ると超絶ボーナスが…！

**フィーバータイム:**
残り時間が10秒を切ると、風船が大量発生する「フィーバータイム」に突入します。スコアを一気に稼ぐチャンスです！

### 🇬🇧 English

**Objective:**
Pop as many balloons as you can within the time limit (30 seconds) to get the highest score!

**Balloon Types and Effects:**
- 🎈 **Normal Balloons (Colorful):** The standard balloons. Tap to pop them and earn points.
- ⚠️ **Black Balloons (Bad):** Don't touch these! Popping one gives you a **-20 pts** penalty.
- ⭐ **Gold Balloons (Rare):** Lucky find! Grants a **+5 pts** bonus and extends your time by **+1 second**.
- ☠️ **Red Balloons (Super Bad):** Absolute danger! Massive **-50 pts** penalty and decreases your time by **-2 seconds**.
- ✨ **Super Rare Balloon:** A very special balloon that rarely appears. Pop it for an incredible bonus!

**Fever Time:**
When the timer drops below 10 seconds, "Fever Time" begins! Balloons will spawn rapidly, giving you a huge chance to rack up points.

## 🚀 Deployment (デプロイ方法)

This game can be easily hosted on GitHub Pages or any static web server.
このゲームはGitHub Pagesや任意の静的ウェブサーバーで簡単にホスティングできます。

1. Repository root should contain `index.html` and the `images/` directory. (リポジトリのルートに `index.html` と `images/` フォルダを配置します)
2. Deploy the directory as a static site. (ディレクトリを静的サイトとしてデプロイしてください)

## 📁 Project Structure (フォルダ構成)

```text
release_v1.00/
├── index.html       # Main game file (メインのゲームファイル)
├── README.md        # This file (このファイル)
└── images/          # Image assets (画像アセット)
    ├── title.jpg
    ├── super_rare_face.jpg
    └── super_rare_pop.jpg
```
