# MBSE 海外論文 3本の初期分析

## Question

MBSE に関する海外論文を 3 本選び、初期 wiki として何を押さえるべきかを整理する。

## Selection scope

今回の選定は、次の 3 観点をそれぞれ代表する論文を 1 本ずつ置く方針とした。

1. MBSE の全体像と研究課題
2. MBSE の価値主張の実証性
3. MBSE の実務導入と教育・スキル課題

## Selected papers

### 1. Madni & Sievers (2018)

#### Summary

この論文は、MBSE をなぜ必要とするのか、何が従来の「engineering with models」と違うのか、今どこにいて、何が未成熟なのかを整理するための基礎論文である。

著者は、MBSE を、進化する system model を中心に据えた holistic な systems engineering と捉えている。ここでは system model が single source of truth に近い役割を果たす。

#### What this paper is useful for

- MBSE の定義を雑にしない
- MBSE を単なる作図活動と切り分ける
- 今後の research opportunity を押さえる

#### Takeaways for this wiki

- `concepts/` に MBSE の定義ページを置く価値が高い
- `concepts/` に model, metamodel, ontology, simulation, digital thread などの周辺概念を拡張する余地がある
- MBSE を「ツール導入」だけで語らない前提づくりに向く

### 2. Henderson & Salado (2021)

#### Summary

この論文は、MBSE の価値や利益に関する主張が、どれだけ evidence に支えられているかをレビューしている。

重要なのは、MBSE の価値主張の多くが測定済みの evidence ではなく、perceived evidence に寄っている点である。つまり、MBSE は有望だが、効果が十分に定量実証されたとは言い切れない。

#### What this paper is useful for

- MBSE の ROI 議論を過大評価しない
- 導入提案時に、何が expectation で何が evidence かを分ける
- 評価指標の設計を考える

#### Takeaways for this wiki

- `comparisons/` に document-based SE と MBSE の比較表を作るとき、効果主張の evidence level を列として持たせるべき
- `analyses/` に MBSE の価値評価フレームを作る価値がある
- 実務提案では benefit claim と measured evidence を明確に分離する必要がある

### 3. Brown & Zaidi (2025)

#### Summary

この論文は、MBSE の実務導入と教育のずれを、UK の survey を通じて扱っている。導入障壁として、組織的反対や組織構造、熟練人材不足、ツール利用性が大きいことを示している。

また、behavioural modelling、verification、validation などを教育に含める必要があるとする点が重要である。

#### What this paper is useful for

- MBSE 導入障壁を、方法論だけでなく組織と人材から見る
- 学習コストとツールコストを無視しない
- 教育・育成の論点を MBSE wiki に接続する

#### Takeaways for this wiki

- `concepts/` に adoption barrier を整理するページが必要
- `analyses/` に MBSE 導入を阻害する要因の整理ページを作る価値がある
- workforce, curriculum, skills gap は独立したトピックになりうる

## Comparison

| 観点 | Madni & Sievers (2018) | Henderson & Salado (2021) | Brown & Zaidi (2025) |
| --- | --- | --- | --- |
| 主題 | MBSE の動機・現在地・研究課題 | MBSE の価値主張の evidence | MBSE の導入実態・教育ギャップ |
| 主な価値 | 定義と全体像の整理 | 効果主張の批判的整理 | 現場導入の障壁整理 |
| 実務への効き方 | 何を MBSE と呼ぶかを安定化 | ROI や benefit 議論を引き締める | 人材・組織・教育の論点を見える化 |
| 限界 | 広いが抽象度が高い | 実証不足を示すが即効の導入手順ではない | UK survey であり地域性がある |

## Integrated view

この 3 本を並べると、MBSE の議論は少なくとも 3 層に分かれる。

1. **概念層**
   - MBSE を何として定義するか
2. **価値層**
   - MBSE は何を良くすると言われているか
   - その主張はどこまで実証されているか
3. **導入層**
   - 組織、人材、ツール、教育のどこで詰まるか

MBSE の失敗は、これら 3 層を混同したときに起きやすい。

たとえば、概念が曖昧なまま ROI を語ると、評価対象がぶれる。価値主張だけを先行させると、導入障壁の現実に負ける。逆に、導入論だけを語ると、何のための MBSE なのかが曖昧になる。

## Initial implications for practice

- MBSE 提案では、定義、効果仮説、導入条件を分けて語るべき
- MBSE 効果を語るときは、measured / observed / perceived の区別が必要
- MBSE の普及課題は、方法論の優劣だけでなく、組織構造、人材供給、教育設計にまたがる

## Next pages to create

- `concepts/mbse.md`
- `concepts/adoption-barrier.md`
- `analyses/mbse-value-evidence-framework.md`
- `comparisons/document-based-se-vs-mbse.md`
