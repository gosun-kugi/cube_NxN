# Cube Simulator (N x N)

A lightweight, browser-based Rubik's Cube Simulator that supports various N x N sizes. Play, practice algorithms, and manage your cube state entirely in your web browser.

[日本語版は下部にあります (Japanese version below)](#キューブ-シミュレーター-n-x-n)

<img max-width=100% alt="Image" src="https://github.com/user-attachments/assets/6d322eac-dec2-4d11-b938-23e33c2f2ae4" />

## Features
- **N x N Support:** Play with standard 2x2, 3x3, 4x4, 5x5 cubes, or enter a custom size up to 13x13.
- **Move Sequence Execution:** Input standard WCA notation (e.g., `R U R' U' y L'`) to apply moves instantly or step-by-step.
- **State Save & Load:** Save your cube state and move history directly to your browser's LocalStorage, export as a `.txt` file, or generate a text code for easy sharing.
- **Undo & History Tracking:** Keep track of your moves with a comprehensive history panel and an Undo function.
- **Image Copy:** Easily copy the current cube visualization to your clipboard.
- **Multi-language UI:** Automatically supports English and Japanese based on your browser settings.
- **Mobile Ready:** Designed to work smoothly on mobile devices.

## How to Use
Open [pages](https://gosun-kugi.github.io/cube_NxN/).

Simply clone or download this repository, and open in any modern web browser. No local server or installation is required for basic web usage.

## Acknowledgements
This project uses scrambling algorithms based on [TNoodle](https://github.com/thewca/tnoodle), the official scramble generator of the World Cube Association (WCA). We deeply appreciate the WCA and all the open-source contributors of TNoodle for their fantastic work and dedication to the speedcubing community.

Visual Representation: The unique 2D vector layout is inspired by the research paper [*"Analysis of Thinking Process When Experts of Solving Rubik's Cube Solve Rubik's Cube"* (2009)](https://dspace.jaist.ac.jp/dspace/handle/10119/8085) by Warayuki Hishida from the Japan Advanced Institute of Science and Technology (JAIST). It works incredibly well for visualizing full layer intersections dynamically in a flat, lightweight format.

---

# ルービックキューブキューブ シミュレーター (N x N)

ブラウザ上で動作する軽量な N x N ルービックキューブシミュレーターです。アルゴリズムの練習からパズルの状態管理まで、すべてブラウザ内で完結します。

## 主な機能
- **N x N 対応:** 2x2, 3x3, 4x4, 5x5の標準サイズに加え、最大13x13までのカスタムサイズ(N)で遊べます。
- **回転記号（シーケンス）の実行:** WCA標準の回転記号（例: `R U R' U' y L'`）を入力し、一括実行や1手ずつのステップ実行が可能です。
- **セーブ＆ロード:** パズルの状態や手順の履歴をブラウザ(LocalStorage)に保存できるほか、`.txt` ファイルとしての保存・読み込み、テキストコードとしてのエクスポート/インポートに対応しています。
- **Undo ＆ 履歴パネル:** 実行した手順を履歴パネルで確認でき、Undo（1手戻る）機能も搭載しています。
- **画像コピー:** 現在のキューブの状態を画像としてワンクリックでクリップボードにコピーできます。
- **多言語対応:** ブラウザの言語設定に応じて、英語と日本語のUIが自動で切り替わります。
- **モバイル対応:** スマホやタブレットでも快適に動作する設計です。

## 使い方
[pages](https://gosun-kugi.github.io/cube_NxN/)を開く。

本リポジトリをダウンロードまたはクローンし、任意のモダンブラウザで開くだけで実行できます。ローカルサーバーの立ち上げや特別なインストールは不要です。

このユニークな同心円展開法は、北陸先端科学技術大学院大学（JAIST）の菱田童之氏による研究論文[『ルービックキューブ攻略時における思考過程の分析』（2009年）](https://dspace.jaist.ac.jp/dspace/handle/10119/8085)から着想を得ています。フラットかつ軽量なフォーマットのままで、すべての層の交差を動的に視覚化するのに驚くほど適しています。

## 謝辞
本プロジェクトのスクランブル機能には、World Cube Association (WCA) 公式のスクランブル生成プログラムである [TNoodle](https://github.com/thewca/tnoodle) のアルゴリズムを参考にしています。WCAならびにTNoodleのオープンソース貢献者の皆様の素晴らしい取り組みと、スピードキューブコミュニティへの貢献に深く感謝いたします。
