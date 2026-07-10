<div align="center">

# 🗡️ Samurai Prompt Manager

**Stable Diffusion 向けの プロンプト / SDカード管理ツール — プロンプト・モデル・LoRA・生成画像を1つのデスクトップアプリでまとめて整理。**

**A1111 · Forge · SwarmUI · ComfyUI** で利用可能

[![Version](https://img.shields.io/badge/version-14.15.22-2ea3f2)](./CHANGELOG.md)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-444)](#-ダウンロードとインストール)
[![Price](https://img.shields.io/badge/無料-100カードまで-2ecc71)](#-料金とライセンス)
[![Paid](https://img.shields.io/badge/有料-%249.90%20(2台まで)-f59e0b)](https://samuraiya.booth.pm/items/8059288)

[English](./README.md) ｜ **日本語**

[▶ 4分デモを見る](https://youtu.be/lQMfM4adCrY) · [⬇ Boothでダウンロード](https://samuraiya.booth.pm/items/8059288) · [📖 レビュー記事](https://civitai.red/articles/30481)

</div>

<!--
  ヒーロー画像 — カード一覧やモデル画面のワイドなスクショに差し替えてください。
  リポジトリに images/ フォルダを作り、images/hero.png として配置します。
-->
<p align="center">
  <img src="images/hero.png" alt="Samurai Prompt Manager — カード一覧" width="900">
</p>

---

## ✨ 何ができるか

Samurai Prompt Manager は、散らかったプロンプトのテキストファイル・モデルフォルダ・スクショの山を、検索できるビジュアルなライブラリに変える **ローカル完結型のデスクトップアプリ**（Electron）です。データはすべて **手元のPC内**（IndexedDB / OPFS）に保存され、クラウドアカウントは不要です。

- 🗂️ **カードライブラリ** — 作業を種類別カードで整理：**プロンプト・LoRA・キャラクター・SDプリセット・テンプレート・ワークフロー・Embedding・FramePack・動画**。カテゴリ / お気に入り / ピン / スマートフォルダ / 種類の一括変換に対応。
- 🖼️ **メタデータの自動抽出** — PNG / JPEG / WebP（や動画）を入れるだけで生成情報を読み取り。**A1111 / Forge・SwarmUI・ComfyUIワークフロー・InvokeAI・NovelAI・Fooocus** の各形式に対応。
- 🛰️ **Civitai連携** — ローカルのモデルフォルダをスキャンして **Civitaiと照合**し、トリガーワード・ベースモデル・プレビュー画像・バージョン情報を自動取得。ベースモデル絞り込み、NC（商用利用不可）フィルタ、更新検出、ワンクリックの **一括「設定を全リセット＆再取得」** も。
- 🎛️ **手持ちのモデル・LoRAをそのまま利用** — 今使っているものを指定するだけ（事前スキャンが必要）。モデル数は **制限なし**。
- 🎨 **AI画像編集** — A1111 / Forge に対する **インペイント / アウトペイント** を内蔵（ComfyUIバックエンドは実験的）。任意の画像からの Auto Tag（**WD14オフライン** または AI Vision）、ControlNet ポーズ固定、LoRA 挿入、和訳をインライン表示するタグチップ。
- 🤖 **AIアシスト** — タグ生成・不足補完、プロンプト分析、そして **Gemini / DeepL / Ollama / MyMemory** による翻訳。
- 🔎 **意味検索** — キーワードだけでなく「意味」でカードを検索（埋め込みベース）。
- 🏷️ **タグ辞書・グループ** — 再利用できるユーザータグ、グループ管理、お気に入り。
- 💾 **堅牢なバックアップ** — ライブラリ全体をエクスポート/復元。数GB級の画像ライブラリは自動で分割され、大容量でもきちんと保存・復元できます。
- 🌐 **多言語UI** — 日本語 / 英語 ＋ 他5言語、動的翻訳キャッシュ付き。

<!--
  スクリーンショット — images/ に3枚入れると下の表に表示されます。
  おすすめ：1) カード/モデル一覧、2) Civitai検索と照合、3) AI画像編集（インペイント）。
-->
## 📸 スクリーンショット

| カード・モデル一覧 | Civitai検索と照合 | AI画像編集（インペイント） |
|---|---|---|
| ![カード・モデル一覧](images/cards.png) | ![Civitai検索](images/civitai.png) | ![AI画像編集](images/ai-edit.png) |

---

## 🎥 動画デモ（4分）

サムネイルをクリックするとYouTubeで再生できます：

[![Samurai Prompt Manager デモ](https://img.youtube.com/vi/lQMfM4adCrY/0.jpg)](https://youtu.be/lQMfM4adCrY)

---

## 💳 料金とライセンス

| | 無料版 | 有料ライセンス |
|---|---|---|
| **カード** | **100枚**まで | **無制限** |
| **モデル / LoRA** | 無制限 | 無制限 |
| **利用台数** | — | **2台** |
| **価格** | 無料 | **$9.90** |

無料版はカードを **100枚**まで保存できます。上限に達すると新規保存はできません（既存カードの削除・スロット再利用は可能）。100枚を超えて管理したい場合に有料ライセンスが必要です。

➡️ **[Boothで無料版 / 有料版を入手](https://samuraiya.booth.pm/items/8059288)**

---

## ⬇️ ダウンロードとインストール

ビルド済みパッケージは **[Booth](https://samuraiya.booth.pm/items/8059288)** で配布しています。

| OS | 形式 |
|---|---|
| **Windows 10 / 11** | ポータブル `.exe`（x64） |
| **macOS** | `.dmg`（Intel **および** Apple Silicon） |
| **Linux** | `AppImage` / `.deb`（x64） |

ダウンロードして起動し、モデルフォルダを指定（初回スキャン）するだけ。ライブラリと設定は手元のPC内に保存されます。

---

## 🔄 アップデート方針

- **次のメジャー版（v16 目安）まで無料アップデート**予定。
- 購入者はプロジェクトのページで紹介される場合があります。
- 反応が少ない場合は開発を停止する可能性があります — ライセンス購入が継続開発の直接の支えになります。

**SDカード方式は現時点で安定しており、おすすめです。** ComfyUI連携は現在調整を進めています。

---

## 📖 関連記事

詳細なレビュー・解説は Civitai.red で公開しています：

🔗 **<https://civitai.red/articles/30481>**

---

## ℹ️ サポートと範囲について

アクティブに開発している個人プロジェクトです。あらかじめご了承ください：

- **返金不可**、**個別のサポート・問い合わせ対応は保証していません。**
- 現在 **コラボ依頼は受け付けていません。**
- 開発は自己資金で行っているため、**購入は本当にありがたく**、継続の力になります。🙏

---

<div align="center">

Stable Diffusion コミュニティのために · [Booth](https://samuraiya.booth.pm/items/8059288) · [デモ](https://youtu.be/lQMfM4adCrY) · [記事](https://civitai.red/articles/30481)

</div>
