# Overview

## この wiki の目的

この wiki は、生のソースから毎回ゼロから再発見するのではなく、LLM によって継続的に統合・更新される永続的な知識ベースを目指す。

## 役割分担

### Human

- ソースを選ぶ
- 重要度を判断する
- 問いを立てる
- 意思決定を行う

### LLM

- 要約を書く
- 関連ページを更新する
- 比較表を作る
- 矛盾や未解決点を洗い出す
- index と log を保守する

## 3 layers

- `raw/` : 原本
- `wiki/` : 統合結果
- `schema/` : 運用ルール

## 運用サイクル

1. source ingest
2. wiki update
3. query and synthesize
4. lint and refine
5. unresolved question tracking

## 成果物の種類

- entity page
- concept page
- analysis page
- comparison page
- unresolved question page
