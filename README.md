# 『Pythonで学ぶ効果検証入門』ソースコード＆データ配布とサポートページ

本リポジトリは、オーム社から発売中の『[pythonで学ぶ効果検証入門](hogehoge)』のサポートのためのページです。
基本的に書籍で用いた各種分析のソースコードやデータの配布を行なっています。

## アップデート情報

## コードおよび環境
### コード

コードの解説は本書籍をご覧ください。
### 環境
このプロジェクトは以下の環境で動作確認を行っています。
- Python 3.8.5
- pandas >= 2.00
- numpy 1.22.2
- scipy 1.8.0
- matplotlib 3.5.1
- statsmodels 0.14.1
- seaborn 0.12.2
- jupyterlab 4.0.6
- ipython 8.0.1
- linearmodels 4.0.0
- tqdm 4.66.1
- rdrobust 1.2.1
- rddensity 2.4.1

# データ

* [lentaデータセット](https://www.uplift-modeling.com/en/latest/api/datasets/fetch_lenta.html）)
* [臓器提供登録率データセット](https://www.openicpsr.org/openicpsr/project/112543/version/V1/view?path=/openicpsr/112543/fcr:versions/V1/Data-and-Programs-to-be-Posted-Online-&type=folder)

# よくある質問
**Q**：書籍中で使われているコードと本レポジトリで使われているコードに微妙な差があります。

**A**：書籍で示したコードは分かりやすさを重視し、一部実際に実行しているコードと異なる表記をしているところがあります。一方でそれは処理結果に影響を与えるようなものではないため、本レポジトリのコードを正例として利用いただければ幸いです。
