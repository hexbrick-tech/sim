[English](../en/vol3-basics-of-sim.md) | [READMEへ戻る](../../README.ja.md) | [Vol. 2](./vol2-reflexive-observation-principle.md)

# Vol. 3 — Basics of SIM — 意味付分離法の基礎

## 1. 原理から方法へ

再起観測原理は、観測者が意味へ影響する可能性があるとき、観測がどのように振る舞うべきかを示しました。

差異、不確実性、視点、解釈、権威を、観測可能な区別として保持します。

しかし、区別を保持するだけではまだ十分ではありません。

観測が繰り返し異なるとき、新たな問いが現れます。

> **これらの観測を早急に収束させることなく理解可能にするには、どのような区別が必要なのか。**

Semantic Isolation Method（SIM／意味付分離法）は、この問いから始まります。

SIMは、解釈、評価、実装、Narrativeによる補完によって境界が収束される前に、意味の境界を発見し保持するための方法です。

現実を完全に分離したモデルを作ることが目的ではありません。

意味の区別を十分に観測可能にし、それらを暗黙に置き換えることなく思考を進められるようにすることが目的です。

## 2. 意味付分離とは何か

意味付分離とは、何も関係しなくなるまで概念を切り離すことではありません。

関係が理解される前に、異なる可能性のある意味が区別不能になることを防ぐことです。

たとえば `approval` という一つの語を考えます。

異なる観測では、同じ語が次のような意味で使われるかもしれません。

```text
実行を許可すること
判断を記録すること
責任を割り当てること
法的に認可すること
技術的な状態を遷移させること
```

語は同じです。

意味は同じとは限りません。

逆に、異なる語が同じ基礎的な意味を指している場合もあります。

したがって意味付分離は、語彙だけから始めません。

観測された挙動、発言、判断、期待を理解するために、どの区別を可視のまま保つ必要があるかを問います。

一見同じものをまだ同一として扱うべきでない理由、あるいは一見異なるものが同じ意味に属し得る理由を、ある区別が説明できるようになったとき、意味の境界が発見されます。

## 3. 基本思考サイクル

SIMの基本的な思考サイクルは次のとおりです。

```text
Observation
    ↓
Difference
    ↓
Question
    ↓
Boundary Hypothesis
    ↓
Semantic Probe
    ↓
Re-observation
    ↺
```

これは必須のワークフローエンジンではありません。

繰り返し現れる思考パターンを表現したものです。

サイクルは、一つの観測、矛盾、Unknown、予想外の結果、観測者間の不一致、あるいは探究にすでに存在する問いから始まることがあります。

各段階は重なることがあります。

Probeが即座に新たな問いを露出させることもあります。

一つの問いが複数の差異を露出させることもあります。

再観測によってBoundary Hypothesisが否定され、探究が以前の状態へ戻ることもあります。

SIMを定義するのは、機械的な順序の実行ではなく、意味の区別を保持することです。

## 4. Observation — 観測

Observationとは、対象そのものと暗黙に同一視しないために必要な文脈とともに、探究に利用可能になった対象の表現です。

観測源には、次のようなものが含まれます。

- 人間の直接的な発言
- 挙動
- 文書
- 計測
- 履歴記録
- 実装
- インターフェース
- 例
- 例外
- AIが生成した観測
- 別の文脈から保持された過去の観測

SIMは、情報源の種類だけで普遍的な権威を割り当てません。

実装は「現在何が起きるか」について強い観測源になり得ますが、「なぜそうあるべきか」については何も語らないかもしれません。

仕様は意図された挙動を定義していても、実際のランタイム挙動とは異なるかもしれません。

ある人の発言は、その人自身の意図について権威を持ちながら、より大きなプロセスについては不完全かもしれません。

したがってObservationは文脈を伴います。

少なくとも探究は、次の問いを区別できる状態を保つべきです。

```text
何を観測したのか。
どこから観測したのか。
どの視点から観測したのか。
どのような関連条件の下で観測したのか。
どのような不確実性があるのか。
```

すべての観測について、すべての項目を形式的に記録する必要はありません。

要求は官僚的なものではなく意味的なものです。観測を理解するために必要な情報を暗黙に捨ててはならない、ということです。

## 5. Difference — 差異

DifferenceはSIMの主要なシグナルです。

差異は、たとえば次の間に現れます。

```text
観測 と 観測
語 と 意味
期待された挙動 と 実際の挙動
ルール と 例外
現在 と 過去の状態
観測者 と 観測者
情報源 と 情報源
意図 と 実装
ある文脈 と 別の文脈
```

SIMは差異を即座に誤りとして分類しません。

代わりに、その差異を説明する可能性のある区別が何かを問えるまで保持します。

これは、すべての差異に意味があるということではありません。

ノイズである差異もあります。

偶然の差異もあります。

意味が付与されていない差異もあります。

実際の誤りもあります。

隠れた境界を露出する差異もあります。

どれなのかを、方法は事前には知りません。

だからこそ、差異は解消される前に観測されます。

## 6. Question — 問い

差異は、意味を露出できる問いを生み出したとき有用になります。

SIMで有用な問いは、結論をすぐ求めるより、区別について問う傾向があります。

たとえば、

```text
これは本当に同じものなのか。
この語は、いつ別の意味になるのか。
誰がこれを決めるのか。
この条件を変えると何が変わるのか。
この挙動は要求されているのか、それとも単に実装されているのか。
この例外は同じルールに属するのか。
この出来事の前後には何が存在するのか。
どこまでが観測で、どこからが推論なのか。
そもそもこの差異に意味はあるのか。
```

問いは、欠けている観測を露出させることもあります。

Unknownは単なる空欄ではありません。次にどこを観測すべきかを示す地点になることがあります。

したがってSIMでは、問いを生成することを、答えを持たない失敗ではなく思考の一部として扱います。

良い問いは、存在するかもしれない境界の観測可能性を高めます。

## 7. Boundary Hypothesis — 境界仮説

Boundary Hypothesisは、意味上の区別が存在する可能性についての暫定的な説明です。

まだ定義ではありません。

結論でもありません。

意味の権威でもありません。

たとえば、

```text
Observation:
    あるapprovalは作業開始を許可する。
    別のapprovalはレビューが行われたことだけを記録する。

Boundary Hypothesis:
    どちらもapprovalと呼ばれているが、
    「実行の認可」と「レビューの記録」は
    異なるConceptである可能性がある。
```

この仮説は、可能性のある区別を早すぎる収束から保護しつつ、検討できる程度に具体化します。

有用なBoundary Hypothesisは、反証可能であるべきです。

どのような観測でも説明できる仮説では、意味を分離する力がほとんどありません。

したがって仮説は、その境界が本当に存在するなら何が異なって見えるはずかを示せることが望まれます。

## 8. Semantic Probe — 意味探針

Semantic Probeは、疑われる意味上の区別を観測可能にするための、制御された変化です。

Probeは意味を証明するものではありません。

異なる意味が、異なる観測を生み出し得る状況を作ります。

一般的には、次のような条件を変化させます。

```text
actor       行為者
purpose     目的
timing      タイミング
sequence    順序
state       状態
input       入力
authority   権威
scope       スコープ
exception   例外
terminology 用語
context     文脈
```

Boundary Hypothesisが「認可」と「レビュー記録」を区別しているとします。

たとえば次のようなProbeが考えられます。

```text
レビューは記録されたが認可が拒否された場合、作業を開始できるか。

レビュー記録なしに認可された場合、何が不足していると扱われるか。

同じ行為者が両方を実行できるか。

片方だけが存在することは可能か。
```

答えは境界を支持するかもしれません。

境界を消すかもしれません。

別の境界を露出するかもしれません。

Unknownを露出するかもしれません。

したがってSemantic Probeは、仮説を合格させるためのテストではありません。

**意味上の帰結を観測可能にすること**が目的です。

## 9. Re-observation — 再観測

Probeの後、対象を再び観測します。

しかしRe-observationは、単なる追加サンプルではありません。

観測者はすでに、以前には存在しなかった問いとBoundary Hypothesisを持っています。

したがってSIMは、再観測そのものにも再起観測を適用します。

```text
Earlier observation
        ↓
Boundary Hypothesis
        ↓
Semantic Probe
        ↓
Re-observation
        ↓
以前の観測との差異か。
対象の差異か。
観測者の差異か。
```

観測者は、それまで不可視だった区別に気付くかもしれません。

だからといって、その区別が観測者によって新たに作られたと自動的に結論することはできません。

逆に、その区別が対象に常に存在していたと自動的に結論することもできません。

十分な根拠が得られるまで、その関係自体を観測可能な状態に保ちます。

これによって、SIMという方法自身が、発見したと主張する意味を暗黙に作り出すことを防ぎます。

## 10. Semantic Boundary — 意味の境界

Semantic Boundaryとは、意味を誤って収束させないために保持する価値がある程度まで、安定し有用になった区別です。

境界は、次のようなものを区別することがあります。

- Concept
- 責任
- 状態
- 目的
- 権威
- 文脈
- 時間的な段階
- ルールと例外
- 観測源
- その他、意味へ実質的に影響する次元

Semantic Boundaryは、必ずしもソフトウェア境界、組織境界、文書の章、データEntity、ワークフローのStepではありません。

それらは後からSemantic Boundaryを基にMappingされることがあります。

境界はまず、**意味の区別**として存在します。

これはSIMの中心的な制約です。

> **実装境界がすでに存在するという理由だけで、実装境界から意味の境界を推定してはならない。**

既存の構造はObservationです。

意味の境界を正確に反映しているかもしれません。

複数の意味を一つにまとめているかもしれません。

一つの意味を複数のComponentへ分割しているかもしれません。

歴史的な偶然を保持しているだけかもしれません。

SIMはそれらを観測しますが、自動的な意味の権威は与えません。

## 11. Boundary Stability — 境界の安定性

Boundary Hypothesisは、重要な差異を消すことなく関連する観測を説明できるようになったとき、Semantic Boundaryとして有用になります。

安定していることは、確実であることを意味しません。

現在の探究に対して十分に安定していても、後から改訂される可能性があります。

安定性を示す有用な兆候には、次のようなものがあります。

```text
その区別が繰り返し現れる差異を説明する。
Probeが、その区別と整合する帰結を生む。
観測者が意味を暗黙に変えずにその区別を利用できる。
既知の例外を、区別そのものを壊さず説明できる。
一つの未説明な解釈だけに依存していない。
関連するUnknownが前提で埋められず、明示されている。
```

普遍的な数値閾値はありません。

SIMは意味的真実のスコアリングシステムではありません。

Stabilityは、その区別が探究の中でどれだけ持続して成立しているかについての観測です。

## 12. Unknown / Unresolved / Ambiguous / Conflicting

SIMは、不確実性を構造化された思考状態として保持します。

少なくとも、必要なときには次の状態を区別できるべきです。

```text
Unknown
    意味を判断するために必要な情報が分かっていない。

Unresolved
    関連する観測は存在するが、十分な結論を
    支持するところまで探究が進んでいない。

Ambiguous
    利用可能な観測の下で、複数の意味または解釈が
    依然として成立し得る。

Conflicting
    観測、証拠、または権威が、まだ整合されていない
    非両立な立場を支持している。
```

これらは自動的に修復すべき欠陥ではありません。

状態によって、次の観測の方向が異なります。

Unknownなら、新しい情報が必要かもしれません。

Unresolvedなら、追加の思考やProbeが必要かもしれません。

Ambiguousなら、隠れた境界または文脈不足を示しているかもしれません。

Conflictingなら、視点、権威、時間、スコープを観測する必要があるかもしれません。

四つすべてを単一の `missing` 状態へ変換する方法は、次に何をすべきかという情報を失います。

## 13. Undefined

探究によっては、別の状態が露出します。何かは存在しているが、その意味上の所属をまだ説明できない状態です。

SIMでは、有用な場合これを **Undefined** として表現できます。

たとえば、

```text
ある作業が存在する。
人々がその作業を実行している。
システムもその作業を支援している。
しかし、現在理解されているスコープの中で、
なぜその作業が存在するのかを説明する
観測された業務目的がない。
```

これはUnknownとは異なります。

Unknownは、関連する情報が分かっていない状態です。

Undefinedは、観測された要素を、現在確立されている意味構造の中へ配置できない状態です。

Undefinedは、その要素が不要である証拠ではありません。

次のようなものを露出している可能性があります。

- 未発見のスコープ
- 隠れた依存関係
- 歴史的制約
- 外部の権威
- 監査やコンプライアンス上の目的
- 現在の探究を越えて延びる境界
- すでに存在しない構造から残った意味的残滓

したがってUndefinedは、方向を示すシグナルとして働きます。

> **何かがここに存在する。しかし現在の意味境界では、まだそれがどこに属するのか説明できない。**

適切な応答は、自動的な削除ではなく、さらなる観測です。

## 14. Semantic Authority — 意味の権威

SIMはEvidenceとAuthorityを区別します。

EvidenceはObservationを支持できます。

Authorityは、ある文脈において、誰または何が意味を定義する資格を持つかを決めます。

両者は重なることがありますが、同一ではありません。

たとえば、

```text
Runtime behavior
    システムが現在何をするかについての強いEvidence
    ビジネスConceptが何を意味するかのAuthorityとは限らない

Business rule
    意図されたDomain MeaningについてのAuthorityになり得る
    実装がそれに従っているEvidenceとは限らない

User statement
    個人の意図についてのAuthorityになり得る
    組織全体のPolicyについてのAuthorityとは限らない
```

SIMは普遍的なAuthority hierarchyを課しません。

Authorityの主張が観測可能な状態にあることを要求します。

Semantic Authorityが存在しない、不明、分散している、あるいは競合している場合、その状態自体が探究の一部です。

他のAuthorityが見えないという理由だけで、観測者がAuthorityを継承することはありません。

## 15. Semantic Leakage — 意味漏出

Semantic Leakageは、意味が境界を越え、その越境が観測可能な状態に保たれなかったときに発生します。

典型的には次のような形があります。

```text
interpretation → observation
implementation → requirement
example → rule
current behavior → intended meaning
majority agreement → truth
observer preference → neutrality
hypothesis → definition
narrative completion → fact
```

問題は、これらの遷移が常に不正だということではありません。

解釈が後から定義として採用されることはあります。

実装が意図的に新しいルールを確立することもあります。

仮説が適切な判断を経てAuthorityを得ることもあります。

Semantic Leakageが発生するのは、**その遷移が不可視なとき**です。

したがってSIMは、意味が収束したかだけでなく、どのように、どのAuthorityの下で収束したのかを問います。

可視の遷移は推論できます。

不可視の遷移は、どのようにそこへ入ったかを保持しないまま対象の一部になります。

## 16. 意味付分離は永久的な分離ではない

Isolationは一時的で、目的を持ったものです。

SIMは、すべての区別を永久に分離しておくことを要求しません。

二つのConceptが後から同等だと分かるかもしれません。

Boundary Hypothesisが崩れるかもしれません。

複数のObservationが一つの意味へ収束するかもしれません。

AmbiguityがAuthorityによって解消されるかもしれません。

Differenceに意味上の重要性がないと分かるかもしれません。

Isolationの目的は、収束を**観測可能な推論イベント**として起こすことです。

```text
Distinct
   ↓
Observed relationship
   ↓
Basis for convergence
   ↓
Converged
```

これは次とは異なります。

```text
Distinct
   ↓
Assumed same
```

SIMは分離を統一より好むわけではありません。

**不可視の収束より、観測可能な収束を選びます。**

## 17. 意味付分離は完全性を要求しない

SIMを始める前に、意味モデルが完全である必要はありません。

部分的な観測だけでも差異は露出します。

ワークフローの断片、一つの用語、例外、ユーザーの不満、実装上の挙動、あるいは意見の不一致も、すべて有効な出発点になり得ます。

SIMは局所的に進められます。

```text
利用可能なものを観測する。
分からないものを保持する。
重要な差異を追う。
観測可能になった場所で境界を発見する。
現在の探究に十分なところで止める。
```

このためSIMは、不完全なDomainや、全体構造がまだ理解されていない既存システムにも適用できます。

完全性はApplied Methodの目的になることがあります。

SIMそのものの前提条件ではありません。

## 18. Reverse Inquiry — 逆向探究

思考は、抽象的な意味から具体的な実現へ向かう方向だけに進むとは限りません。

低位の観測によって、それまで不可視だった意味上の問いが露出することがあります。

Conceptual Modelでは一つだったものが、実装では二つのStateとして存在しているかもしれません。

例外が、欠けていた責任を露出するかもしれません。

Data Fieldが、現在の文書では説明されていない区別を保持しているかもしれません。

SIMは、これを **Reverse Inquiry** の起点として扱うことができます。

```text
Lower-level observation
        ↓
Unexpected difference
        ↓
Question about higher-level meaning
        ↓
Observation / Boundary Hypothesis / Probe
```

Reverse Inquiryは、低位の構造へSemantic Authorityを与えません。

与えるのはObservationとしての価値です。

実装は問いを露出できます。

しかし、実装が存在するという理由だけで、その問いへの答えになるわけではありません。

これによってAuthorityの方向を保持しながら、Discoveryは双方向に進むことができます。

## 19. SIMにおける複数視点

複数の視点は、隠れた境界が観測可能になる可能性を高めます。

観測者は、それぞれ異なるEvidence、Purpose、Vocabulary、Experience、Biasを持つため、異なる区別に気付くことがあります。

SIMは、その差異をInputとして利用します。

思考を続ける前に、観測者同士が収束することを要求しません。

有用なパターンは次のように表せます。

```text
Perspective A ─┐
Perspective B ─┼─> Differences ─> Questions ─> Boundary Hypotheses
Perspective C ─┘
```

Consensusが後から有用になることはあります。

しかしConsensusは、文脈とAuthorityによって扱われる結果であって、SIMが意味を発見するための機構ではありません。

複数の観測者は、観測可能な意味空間を広げます。

多数決によってSemantic Boundaryを存在させるわけではありません。

## 20. ObservationとEvaluation

SIMがObservationとEvaluationを分離するのは、両者が異なる問いに答えるからです。

Observationは問います。

> 何が存在し、異なり、欠け、不確実で、説明されていないのか。

Evaluationは問います。

> 何を選び、受け入れ、拒否し、優先し、修正し、変更すべきか。

多くの応用ではEvaluationが必要です。

しかしEvaluationが早すぎると、望ましくないObservationが、その意味上の重要性を理解される前に消されることがあります。

奇妙な実装が、隠れた業務上の区別を露出する前に「悪い設計」と評価されるかもしれません。

例外が、別のScopeを露出する前に「不整合」とされるかもしれません。

二人が同じ語を別の意味で使っていることを露出する前に、不一致が解消されるかもしれません。

したがってSIMは、その区別が重要なとき、EvaluationをObservationより下流に置きます。

これは絶対的な時間順序を作るものではありません。

Evaluation自体がObservation Sourceとなり、新しいCycleを起動することもあります。

重要なのは、EvaluationがObservationを書き換えたことを不可視にしないことです。

## 21. Thinking Core — 思考中核

分野に依存しないSIMのThinking Coreは、次のように要約できます。

```text
Observe
   ↓
Detect Difference
   ↓
Generate Question
   ↓
Form Boundary Hypothesis
   ↓
Probe
   ↓
Re-observe
   ↺
```

このCycleの周囲で、SIMはいくつかの制約を保持します。

```text
Observer remains observable.
観測者は観測可能な状態にある。

Perspective remains distinguishable.
視点は区別可能な状態にある。

Observation remains distinguishable from interpretation and evaluation.
観測は解釈・評価と区別可能な状態にある。

Difference remains information before error.
差異は誤りである前に情報として保持される。

Uncertainty may remain explicit.
不確実性は明示的なまま存在できる。

Meaning is not manufactured merely because it can be explained.
説明可能であるというだけで意味を製造しない。

Semantic authority remains located.
意味の権威の所在を保持する。

Convergence must remain observable.
収束は観測可能でなければならない。

Implementation is evidence before authority.
実装は権威である前にEvidenceである。
```

これがSemantic Isolation Methodの中核です。

それ以外のものはDomainに合わせて適応できます。

Artifactは変わって構いません。

Terminologyは専門化できます。

Roleを導入できます。

Processを形式化できます。

ToolによってObservationやProbeの一部を自動化できます。

しかし、それらがSIMそのものを定義するわけではありません。

それらはThinking Coreの応用です。

## 22. SIMが定義しないもの

SIMは次のものを定義しません。

- ソフトウェアをどうArchitectureすべきか
- 組織をどう構成すべきか
- Business Processをどう最適化すべきか
- あらゆる分野でResearchをどう実施すべきか
- TruthをどうScoreするべきか
- Consensusへどう到達すべきか
- AI Systemをどう実装すべきか
- どのObserverを初期状態で信頼すべきか

Applied Methodは、それらを定義することがあります。

SIMは、その下に意味論的な思考基盤を提供します。

この区別によって、SIMが最初に利用されたDomainの前提をそのまま引き継ぐことを防ぎます。

AI支援開発は起源となった文脈です。

Software Architectureは初期の応用です。

どちらもSIMという方法の定義ではありません。

## 23. 方法から応用へ

SIMは、そのThinking CoreがDomain固有のObservation Source、Authority、Probe、Decisionへ接続されたとき、そのDomainで利用可能になります。

Software Developmentでは、Semantic ProbeとしてRequirementやScenarioを変化させるかもしれません。

Business Analysisでは、Actor、Purpose、Responsibilityを変化させるかもしれません。

Historical Inquiryでは、異なる時代やProvenanceのEvidenceを比較するかもしれません。

AI Reasoningでは、Perspective、Prompt Context、Observer Model、Interpretationを変化させ、その差異を保持するかもしれません。

これらは同じ方法の異なる応用です。

方法がDomainを決めるのではありません。

Domainが、方法をどのように具体化するかを決めます。

Vol. 4では、とりわけ重要な一つのObserverであるAIを扱います。

AIはObservation、Interpretation、Hypothesis、Question、Narrativeを非常に速く、大規模に生成できます。

それはSIMにおいて強力です。

同時に、不可視のSemantic Convergenceを極めて容易にもします。

そこで次巻では、観測者自身が意味へ強い影響を与える存在であるとき、AIはどのように思考すべきかを扱います。
