# Cube Simulator (N x N)

A lightweight, browser-based Cube Simulator that supports various N x N sizes. Play, practice algorithms, and manage your cube state entirely in your web browser.

[日本語版は下部にあります (Japanese version below)](#キューブ-シミュレーター-n-x-n)

## Features
- **N x N Support:** Play with standard 2x2, 3x3, 4x4, 5x5 cubes, or enter a custom size up to 13x13.
- **Move Sequence Execution:** Input standard WCA notation (e.g., `R U R' U' y L'`) to apply moves instantly or step-by-step.
- **State Save & Load:** Save your cube state and move history directly to your browser's LocalStorage, export as a `.txt` file, or generate a text code for easy sharing.
- **Undo & History Tracking:** Keep track of your moves with a comprehensive history panel and an Undo function.
- **Image Copy:** Easily copy the current cube visualization to your clipboard.
- **Multi-language UI:** Automatically supports English and Japanese based on your browser settings.
- **Mobile Ready:** Designed to work smoothly on mobile devices and includes a bridge for [Capacitor](https://capacitorjs.com/) native compilation.

## How to Use
Open [pages](https://gosun-kugi.github.io/cube_NxN/).

Simply clone or download this repository, and open in any modern web browser. No local server or installation is required for basic web usage.

## Acknowledgements
This project uses scrambling algorithms based on [TNoodle](https://github.com/thewca/tnoodle), the official scramble generator of the World Cube Association (WCA). We deeply appreciate the WCA and all the open-source contributors of TNoodle for their fantastic work and dedication to the speedcubing community.

---

# キューブ シミュレーター (N x N)

ブラウザ上で動作する軽量な N x N キューブシミュレーターです。アルゴリズムの練習からパズルの状態管理まで、すべてブラウザ内で完結します。

## 主な機能
- **N x N 対応:** 2x2, 3x3, 4x4, 5x5の標準サイズに加え、最大13x13までのカスタムサイズ(N)で遊べます。
- **回転記号（シーケンス）の実行:** WCA標準の回転記号（例: `R U R' U' y L'`）を入力し、一括実行や1手ずつのステップ実行が可能です。
- **セーブ＆ロード:** パズルの状態や手順の履歴をブラウザ(LocalStorage)に保存できるほか、`.txt` ファイルとしての保存・読み込み、テキストコードとしてのエクスポート/インポートに対応しています。
- **Undo ＆ 履歴パネル:** 実行した手順を履歴パネルで確認でき、Undo（1手戻る）機能も搭載しています。
- **画像コピー:** 現在のキューブの状態を画像としてワンクリックでクリップボードにコピーできます。
- **多言語対応:** ブラウザの言語設定に応じて、英語と日本語のUIが自動で切り替わります。
- **モバイル対応:** スマホやタブレットでも快適に動作する設計となっており、[Capacitor](https://capacitorjs.com/) を利用したネイティブアプリ化にも対応可能な構成です。

## 使い方
[pages](https://gosun-kugi.github.io/cube_NxN/)を開く。

本リポジトリをダウンロードまたはクローンし、任意のモダンブラウザで開くだけで実行できます。ローカルサーバーの立ち上げや特別なインストールは不要です。


## 謝辞
本プロジェクトのスクランブル機能（シャッフルアルゴリズム）には、World Cube Association (WCA) 公式のスクランブル生成プログラムである [TNoodle](https://github.com/thewca/tnoodle) のアルゴリズムを使用（または参考に）しています。WCAならびにTNoodleのオープンソース貢献者の皆様の素晴らしい取り組みと、スピードキューブコミュニティへの貢献に深く感謝いたします。
