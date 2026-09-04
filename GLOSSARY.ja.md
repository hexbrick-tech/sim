[English](./GLOSSARY.md) | [READMEへ戻る](./README.ja.md)

# SIM Concept Index / Glossary — 概念索引・用語集

この文書は、SIM原典のためのナビゲーションおよび用語索引です。

各巻で定義された概念や境界を置き換えるものではありません。用語、翻訳上の選択、対比関係、原典上の位置を観測しやすくすることを目的とします。

英語版原典をCanonicalとし、ここに記載する日本語はこのリポジトリにおける公式な翻訳対応です。

## 主要Concept

| English term | 日本語 | 短い説明 | 重要な対比 | Canonical location |
| --- | --- | --- | --- | --- |
| Meta-Observationalism | メタ観測主義論 | ObservationだけでなくObserverや関連する観測条件も観測可能に保つ哲学的立場。 | 相対主義ではなく、Perspective-free Observerを作る試みでもない。 | [Vol. 1](./docs/ja/vol1-meta-observationalism.md) |
| Reflexive Observation | 再帰観測 | Observationを、そのObservationを生み出したObserver、Perspective、Condition、Actへ折り返すことができる観測。 | **Reflexive** はObservation / Observerそのものを観測することに関係する。**Recurrent Observation**とは異なる。 | [Vol. 2](./docs/ja/vol2-reflexive-observation-principle.md) |
| Recurrent Observation | 再起観測 | Observation、Difference、Question、Probe、Resultなどが次のObservation CycleへのInputとなり、観測が再び起動すること。 | **Recurrent** はFeedbackやRe-entryによって観測が再び起きることに関係する。それ自体はObserverを観測することを意味しない。 | [Vol. 3 §3](./docs/ja/vol3-basics-of-sim.md#3-基本思考サイクル) |
| Observation | 観測 | 対象そのものへ不可視に置き換わらないための文脈とともに、探究で利用可能になった対象の表現。 | Interpretation、Evaluationと区別する。 | [Vol. 3 §4](./docs/ja/vol3-basics-of-sim.md#4-observation--観測) |
| Difference | 差異 | ErrorやMeaningへ分類される前に観測される、SIMの主要なSignal。 | 差異は誤りである前に情報である。 | [Vol. 3 §5](./docs/ja/vol3-basics-of-sim.md#5-difference--差異) |
| Boundary Hypothesis | 境界仮説 | Semantic Distinctionが存在する可能性についての暫定的な仮説。 | まだDefinition、Conclusion、Semantic Authorityではない。 | [Vol. 3 §7](./docs/ja/vol3-basics-of-sim.md#7-boundary-hypothesis--境界仮説) |
| Semantic Probe | 意味探針 | 疑われるSemantic Distinctionの帰結を観測可能にするためのControlled Variation。 | HypothesisをChallengeするものであり、通過させるためのConfirmationではない。 | [Vol. 3 §8](./docs/ja/vol3-basics-of-sim.md#8-semantic-probe--意味探針) |
| Re-observation | 再観測 | Question、Hypothesis、Probe、Context Change、新しいEvidenceなどの後に再び行われるObservation。 | Recurrent / Reflexive Observationに参加し得るが、どちらとも同一ではない。 | [Vol. 3 §9](./docs/ja/vol3-basics-of-sim.md#9-re-observation--再観測) |
| Semantic Boundary | 意味の境界 | Meaningを誤って収束させないために保持する価値がある程度まで安定し有用になったDistinction。 | Software、Organization、Document、DataのBoundaryと自動的に同一ではない。 | [Vol. 3 §10](./docs/ja/vol3-basics-of-sim.md#10-semantic-boundary--意味の境界) |
| Unknown | 未知 | Meaningを判断するために必要なInformationが分かっていない状態。 | Undefinedとは異なり、Unknownは知識の不足に関係する。 | [Vol. 3 §12](./docs/ja/vol3-basics-of-sim.md#12-unknown--unresolved--ambiguous--conflicting) |
| Unassigned | 未割当 | 観測された要素について、その意味をどのように扱うかがまだ決定されていない一時的な観測状態。 | 終端ではない。解決とは意味を必ず付与することではなく、意味の扱いを決めること。 | [Vol. 3 §12](./docs/ja/vol3-basics-of-sim.md#unassignedと意味の扱い) |
| Meaning Not Required | 意味付与不要 | 現在の文脈ではSemantic Meaningを付与する必要がないと判断された正規の終端。 | Undefinedとは異なり、通常はFurther Observationを要求しない。 | [Vol. 3 §12](./docs/ja/vol3-basics-of-sim.md#unassignedと意味の扱い) |
| Undefined | 未定義 | 何かは観測されているが、現在確立されたSemantic Structureの中へまだ配置できない状態。 | UnknownおよびMeaning Not Requiredとは異なる。UndefinedはさらなるObservationの方向を示すSignalであり、不要である証拠ではない。 | [Vol. 3 §13](./docs/ja/vol3-basics-of-sim.md#13-undefined) |
| Semantic Authority | 意味の権威 | 対象となるMeaningを定義する資格を持つ人、Source、Process、Context。 | EvidenceはObservationを支持してもSemantic Authorityを持たないことがある。 | [Vol. 3 §14](./docs/ja/vol3-basics-of-sim.md#14-semantic-authority--意味の権威) |
| Semantic Leakage | 意味漏出 | MeaningがBoundaryを越え、その越境が不可視になった状態。 | Transitionそのものが必ず不正なのではなく、不可視になることが問題。 | [Vol. 3 §15](./docs/ja/vol3-basics-of-sim.md#15-semantic-leakage--意味漏出) |
| Reverse Inquiry | 逆向探究 | Lower-level ObservationがHigher-level MeaningへのQuestionを露出すること。 | Lower-level Realizationが得るのはObservationとしての価値であり、Semantic Authorityではない。 | [Vol. 3 §18](./docs/ja/vol3-basics-of-sim.md#18-reverse-inquiry--逆向探究) |
| The Right Not to Mean | 意味を持たない自由 | ObserverがInterpretationを構築できるというだけで、観測可能なDifferenceへAssigned Semantic Meaningを要求しない原理。 | ObserverへのConstraintでありReasoning Stateではない。ここでの `Right` は主として法的権利を意味しない。 | [Vol. 1 §8](./docs/ja/vol1-meta-observationalism.md#8-意味を持たない自由) |
| Applied SIM | SIMの応用 | SIM原典を具体的なProcedure、Artifact、Role、Constraintへ適用した独立したDomain-specific Work / Method。 | Applied SIMは基礎原典そのものではなく、Applied SIMであるという理由だけで原典文書の改変配布物になるものでもない。 | [Prologue §7](./docs/ja/prologue.md#7-simとapplied-sim) |

## 意味の扱いに関する境界

次の語は意図的に異なるConceptです。

```text
Unassigned / 未割当
    意味の扱いがまだ決定されていない
    一時的なObservation State

Meaning Not Required / 意味付与不要
    現在の文脈ではMeaningを付与する必要がない
    正規の終端

Undefined / 未定義
    現在のSemantic Structureでは所属を説明できない
    通常はFurther Observationへ探究を向ける

The Right Not to Mean / 意味を持たない自由
    ObserverへのConstraint
    構築可能という理由だけでMeaningを強制しない
```

## 翻訳上の境界: Recurrent と Reflexive

**Recurrent Observation** と **Reflexive Observation** は意図的に異なるConceptです。

```text
Recurrent Observation / 再起観測
    Observationが次のObservationへInputされる
    時間的・Process的な再起動 / Re-entry

Reflexive Observation / 再帰観測
    ObservationをObserverまたは観測条件へ折り返す
    ObservationそのものがObservation対象になる
```

したがって、この原典において `再起` と `再帰` は表記ゆれではありません。異なるConceptを示す正規語彙です。

## 翻訳上の境界: The Right Not to Mean

**The Right Not to Mean** の公式日本語訳は **意味を持たない自由** とします。

ここでの `right` は、意味を付与しないことの正当性を保護するための語であり、主として法的権利を意味するものではありません。日本語では、強制的な意味付与からの自由を強調するため `自由` を採用します。

## このIndexの使い方

用語の不整合が見つかった場合、正規化する前に、そのDifferenceが次のどれであるかを観測します。

1. 意図されたSemantic Distinction
2. 公式な翻訳上の選択
3. 翻訳またはTerminology上のDefect
4. さらなるObservationを必要とするUnresolved Difference

この区別を観測する前に用語をNormalizeしません。
