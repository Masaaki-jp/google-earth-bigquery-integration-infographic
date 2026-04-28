# Earth Engine & BigQuery Integration Infographic (`earth-bq-viz`)

## 概要 (Overview)
Google Earth Engine（GEE）の持つペタバイト級の地球空間データと、データウェアハウスであるBigQuery、そしてVertex AIを連携させたアーキテクチャの優位性を解説するシングルページ・インフォグラフィックです。

従来の煩雑なデータ移行（ETLパイプライン）を排除して業務プロセスを抜本的に改善（BPR）し、SQLを用いた直接クエリからAIプロトタイピングまでをシームレスに繋ぐ「Unified AI Workflow」を視覚的に表現しています。

## 特徴 (Features)
このアプリケーションは、以下の5つのセクションで構成され、スクロールに沿って直感的にストーリーを伝えます。

* **Planetary-Scale KPIs**: 1000以上のデータセット、80PB超のデータ規模、そして最大の利点である「ETLゼロ」をハイライト。
* **Data Catalog Breakdown**: 光学画像、レーダー（SAR）、気候データなど、即座にクエリ可能なデータの内訳をドーナツチャートで可視化。
* **Eliminating the ETL Bottleneck**: 従来のサイロ化されたアーキテクチャと、統合型GeoAIの処理時間を比較。ETL排除による圧倒的な時間短縮をスタックドバーチャートで証明します。
* **Industry Applications**: 農業の収量予測から気候テック、サプライチェーンまで、産業別のユースケースをランキング形式で提示。
* **Unified AI Workflow**: GEE（データソース）→ BigQuery（特徴量抽出）→ Vertex AI（予測モデリング）へと至る一連のアーキテクチャ図解。

## 技術スタック (Tech Stack)
Node.jsなどのビルド環境を一切必要としない、極めて軽量でシンプルな構成を採用しています。Chromebookなどのローカルリソースが限られた環境でも、即座に検証・改修が可能です。

* **HTML5 / CSS3**
* **Tailwind CSS** (CDN) - 迅速なUI構築とレスポンシブ対応
* **Chart.js** (CDN) - インタラクティブなグラフ描画
* **Google Fonts** (Space Grotesk, Inter) - モダンなタイポグラフィ

## 使い方 (Usage)
依存パッケージのインストールやビルドプロセスは不要です。

1. 本リポジトリをローカルにクローンします。
   ```bash
   git clone [https://github.com/Masaaki-jp/earth-bq-viz.git](https://github.com/Masaaki-jp/earth-bq-viz.git)
