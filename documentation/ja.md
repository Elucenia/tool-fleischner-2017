<!-- ELUCENIA technical documentation · fleischner-2017 · ja · no clinical/professional/rights approval -->

# Fleischner 2017（充実性肺結節）

[条件・出典・許諾](https://elucenia.org/ja/tools/fleischner-2017)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 結節の平均径（多発の場合は最も疑わしい結節）

`tamanho`

mm · 範囲: 1–30

### 結節数

`num`

- `u` — 単発
- `m` — 多発

### 肺がんリスク

`risco`

- `b` — 低い
- `a` — 高い（喫煙，年齢，曝露，家族歴，肺気腫，上葉）

## 方法の版

Fleischner Society 2017：偶発性充実性結節，平均径丸め；除外条件を保持

## 記載された計算式

平均径 = (長径 + 短径) ÷ 2，最も近いミリメートルに丸める。区分：\< 6 mm（\< 100 mm³），6〜8 mm（100〜250 mm³），\> 8 mm（\> 250 mm³）。

## 限界・対象集団

35歳以上の成人で偶然発見された充実性肺結節を対象とする版です。Fleischner2017の推奨は、肺がん検診、免疫機能が低下している人、既知の原発がんを有する患者には適用されません。亜充実性または部分充実性結節には別のアルゴリズムが必要です。多発結節では、最も疑わしい結節を評価の基準とします。それが必ずしも最大の結節とは限りません。リスク層別化と経過観察の判断には、臨床評価と画像評価が必要です。

## 参考文献

- [MacMahon H et al. Guidelines for management of incidental pulmonary nodules detected on CT images: from the Fleischner Society 2017. Radiology, 2017.](https://doi.org/10.1148/radiol.2017161659)

- [MacMahon et al. Radiology2017, DOI10.1148/radiol.2017161659](https://pubs.rsna.org/doi/full/10.1148/radiol.2017161659)

- [Original sixteen-page RSNA article, institutional copy at University of Wisconsin](https://wiki.radiology.wisc.edu/images/b/b9/Flesichner_Guidelines_2017.pdf)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

定期フォローアップなし

| 結果の詳細 | |
| --- | --- |
| 患者リスク | 低い |
| 四捨五入した平均径 | 4 mm |

35歳未満、既知のがん患者、免疫抑制患者、または肺がん検診には適用しません（Lung-RADS を使用）。


### 2

6～12か月後にCT、その後18～24か月後にCT

| 結果の詳細 | |
| --- | --- |
| 患者リスク | 高い |
| 四捨五入した平均径 | 6 mm |

35歳未満、既知のがん患者、免疫抑制患者、または肺がん検診には適用しません（Lung-RADS を使用）。


### 3

3～6か月後にCT；その後、18～24か月後のCTを考慮

| 結果の詳細 | |
| --- | --- |
| 患者リスク | 低い |
| 四捨五入した平均径 | 7 mm |

35歳未満、既知のがん患者、免疫抑制患者、または肺がん検診には適用しません（Lung-RADS を使用）。


### 4

3か月後のCT、PET-CT、または組織サンプルを考慮

| 結果の詳細 | |
| --- | --- |
| 患者リスク | 低い |
| 四捨五入した平均径 | 10 mm |

35歳未満、既知のがん患者、免疫抑制患者、または肺がん検診には適用しません（Lung-RADS を使用）。

