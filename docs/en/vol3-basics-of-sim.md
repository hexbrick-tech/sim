[日本語](../ja/vol3-basics-of-sim.md) | [Back to README](../../README.md) | [Vol. 2](./vol2-reflexive-observation-principle.md)

# Vol. 3 — Basics of SIM (Semantic Isolation Method)

## 1. From Principle to Method

The Reflexive Observation Principle establishes how observation should behave when the observer may affect meaning.

It preserves differences, uncertainty, perspective, interpretation, and authority as observable distinctions.

But preserving distinctions is not yet enough.

When observations repeatedly differ, a new question appears:

> **What distinction would make these observations intelligible without prematurely collapsing them?**

Semantic Isolation Method begins with that question.

SIM is a method for discovering and preserving semantic boundaries before those boundaries are collapsed by interpretation, evaluation, implementation, or narrative completion.

Its purpose is not to produce a perfectly isolated model of reality.

Its purpose is to make semantic distinctions observable enough that reasoning can proceed without silently replacing them.

## 2. What Semantic Isolation Means

Semantic isolation does not mean separating concepts until nothing relates to anything else.

It means preventing meanings that may be distinct from becoming indistinguishable before their relationship is understood.

Consider a word such as `approval`.

Different observations may use the same word for:

```text
permission to proceed
record of a decision
assignment of responsibility
legal authorization
technical state transition
```

The word is the same.

The meanings may not be.

Conversely, different words may refer to the same underlying meaning.

Semantic isolation therefore does not begin from vocabulary alone.

It asks what distinctions must remain visible for the observed behavior, statements, decisions, or expectations to make sense.

A semantic boundary is discovered when a distinction explains why apparently similar things should not yet be treated as the same, or why apparently different things may belong to the same meaning.

## 3. The Basic Reasoning Cycle

The basic SIM reasoning cycle is:

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

This is not a mandatory workflow engine.

It is a representation of a recurring reasoning pattern.

The cycle may begin from a single observation, a contradiction, an unknown, an unexpected result, a disagreement between observers, or a question already present in the inquiry.

Steps may overlap.

A probe may reveal a new question immediately.

A question may expose several differences.

Re-observation may invalidate the boundary hypothesis and return the inquiry to an earlier state.

The method is defined by preservation of semantic distinctions, not by mechanical execution of a sequence.

## 4. Observation

Observation is any representation of the subject that is available to the inquiry together with enough context to avoid silently treating it as the subject itself.

Observation sources may include:

- direct human statements,
- behavior,
- documents,
- measurements,
- historical records,
- implementations,
- interfaces,
- examples,
- exceptions,
- AI-generated observations,
- or previous observations preserved from another context.

SIM does not assign universal authority to any source type.

An implementation may be authoritative about what currently happens while remaining silent about why it should happen.

A specification may define intended behavior while differing from runtime behavior.

A person's statement may be authoritative about their intention while incomplete about a larger process.

Observation therefore carries context.

At minimum, the inquiry should remain capable of distinguishing:

```text
What was observed?
From where?
From what perspective?
Under what relevant conditions?
With what uncertainty?
```

Not every observation requires a formal record of every field.

The requirement is semantic, not bureaucratic: information necessary to understand the observation must not be silently discarded.

## 5. Difference

Difference is the primary signal of SIM.

A difference may appear between:

```text
observation and observation
word and meaning
expected and actual behavior
rule and exception
current and historical state
observer and observer
source and source
intention and implementation
one context and another
```

SIM does not immediately classify the difference as an error.

Instead, the difference is held long enough to ask what kind of distinction may explain it.

This does not imply that every difference is meaningful.

Some differences are noise.

Some are accidental.

Some have no assigned semantic meaning.

Some are genuine errors.

Some reveal hidden boundaries.

The method does not know which in advance.

That uncertainty is precisely why the difference is observed before it is resolved.

## 6. Question

A difference becomes useful when it generates a question that can expose meaning.

Useful SIM questions tend to ask about distinctions rather than immediately ask for conclusions.

For example:

```text
Are these actually the same thing?
When does this word mean something different?
Who decides this?
What changes if this condition changes?
Is this behavior required or merely implemented?
Does this exception belong to the same rule?
What exists before and after this event?
Which part is observed and which part is inferred?
Does this difference carry semantic meaning at all?
```

Questions may also expose missing observation.

An Unknown is not merely an empty field. It may indicate the exact place where the next useful observation should occur.

SIM therefore treats question generation as part of reasoning, not as a failure to have an answer.

A good question increases the observability of a possible boundary.

## 7. Boundary Hypothesis

A Boundary Hypothesis is a provisional explanation that a semantic distinction may exist.

It is not yet a definition.

It is not a conclusion.

It is not semantic authority.

For example:

```text
Observation:
    Some approvals allow work to begin.
    Other approvals only record that review occurred.

Boundary Hypothesis:
    "Authorization to act" and "record of review"
    may be distinct concepts even though both are called approval.
```

The hypothesis protects the possible distinction from premature convergence while making it concrete enough to examine.

A useful Boundary Hypothesis should be capable of being challenged.

If every possible observation can be explained by the hypothesis, it has little power to isolate meaning.

The hypothesis should therefore suggest what would look different if the boundary were real.

## 8. Semantic Probe

A Semantic Probe is a controlled variation used to test whether a suspected semantic distinction becomes observable.

A probe does not prove a meaning.

It creates a situation in which different meanings may produce different observations.

Common forms include changing:

```text
actor
purpose
timing
sequence
state
input
authority
scope
exception
terminology
context
```

Suppose a Boundary Hypothesis distinguishes authorization from review record.

Possible probes include:

```text
If the review is recorded but authorization is denied, can work begin?

If authorization is granted without a review record, what is considered missing?

Can the same actor perform both?

Can one exist without the other?
```

The answers may support the boundary.

They may collapse it.

They may reveal a different boundary.

They may expose an Unknown.

A Semantic Probe is therefore not a test whose purpose is to make the hypothesis pass.

Its purpose is to make semantic consequences observable.

## 9. Re-observation

After a probe, the subject is observed again.

But re-observation is not simply another sample.

The observer now carries a question and a Boundary Hypothesis that were not present before.

SIM therefore applies reflexive observation to the re-observation itself.

```text
Earlier observation
        ↓
Boundary Hypothesis
        ↓
Semantic Probe
        ↓
Re-observation
        ↓
Difference from earlier observation?
Difference in the subject?
Difference in the observer?
```

The observer may now notice a distinction that was previously invisible.

That does not automatically mean the distinction was newly created by the observer.

Nor does it automatically mean the distinction always existed in the subject.

The relationship remains observable until there is enough basis to say more.

This prevents the method itself from silently authoring the meaning it claims to discover.

## 10. Semantic Boundary

A Semantic Boundary is a distinction that has become sufficiently stable and useful to keep meanings from being incorrectly collapsed.

A boundary may distinguish:

- concepts,
- responsibilities,
- states,
- purposes,
- authorities,
- contexts,
- temporal phases,
- rules and exceptions,
- observation sources,
- or other dimensions that materially affect meaning.

A semantic boundary is not necessarily a software boundary, organizational boundary, document section, data entity, or workflow step.

Those may later be mapped from it.

The boundary exists first as a distinction in meaning.

This is a central constraint of SIM:

> **Semantic boundaries should not be inferred from implementation boundaries merely because implementation boundaries already exist.**

Existing structures are observations.

They may reflect semantic boundaries accurately.

They may combine several meanings.

They may split one meaning across several components.

They may preserve historical accidents.

SIM observes them without granting them automatic semantic authority.

## 11. Boundary Stability

A Boundary Hypothesis becomes useful as a Semantic Boundary when it can explain relevant observations without requiring important differences to be erased.

Stability does not mean certainty.

A boundary may be stable enough for the current inquiry while remaining revisable.

Useful indicators of stability include:

```text
The distinction explains repeated differences.
Probes produce consequences consistent with the distinction.
Observers can use the distinction without silently changing its meaning.
Known exceptions can be described without destroying the distinction.
The boundary does not depend only on one unexplained interpretation.
Relevant Unknowns are explicit rather than filled by assumption.
```

There is no universal numerical threshold.

SIM is not a scoring system for semantic truth.

Stability is an observation about how well a distinction continues to survive inquiry.

## 12. Unknown, Unresolved, Ambiguous, and Conflicting

SIM preserves uncertainty as structured reasoning state.

At minimum, several forms should remain distinguishable when relevant:

```text
Unknown
    Information required to determine meaning is not known.

Unresolved
    Relevant observations exist, but the inquiry has not yet
    supported a sufficient conclusion.

Ambiguous
    More than one meaning or interpretation remains plausible
    under the available observations.

Conflicting
    Observations, evidence, or authorities support incompatible
    positions that have not been reconciled.
```

These states are not defects to be automatically repaired.

They guide observation differently.

Unknown may call for new information.

Unresolved may call for additional reasoning or a probe.

Ambiguous may indicate a hidden boundary or insufficient context.

Conflicting may require examination of perspective, authority, time, or scope.

A method that converts all four into a single `missing` state loses information about what should happen next.

## 13. Undefined

Some inquiries expose a different condition: something is present, but its semantic belonging cannot yet be explained.

SIM may represent this as **Undefined** when useful.

For example:

```text
A task exists.
People perform it.
The system supports it.
But no observed business purpose explains why it belongs
within the currently understood scope.
```

This is not the same as Unknown.

Unknown means that relevant information is not known.

Undefined means that the observed element cannot currently be placed within an established semantic structure.

Undefined is not evidence that the element is unnecessary.

It may reveal:

- an undiscovered scope,
- a hidden dependency,
- a historical constraint,
- an external authority,
- an audit or compliance purpose,
- a boundary extending beyond the current inquiry,
- or semantic residue from a structure that no longer exists.

Undefined therefore acts as a directional signal:

> **Something is here, but the current semantic boundaries do not yet explain where it belongs.**

The appropriate response is further observation, not automatic deletion.

## 14. Semantic Authority

SIM distinguishes evidence from authority.

Evidence can support an observation.

Authority determines who or what is entitled to define a meaning within a context.

These often overlap, but they are not identical.

For example:

```text
Runtime behavior
    strong evidence of what the system currently does
    not automatically authority for what the business concept means

Business rule
    possible authority for intended domain meaning
    not automatically evidence that implementation follows it

User statement
    possible authority for personal intention
    not automatically authority for organization-wide policy
```

SIM does not impose one universal authority hierarchy.

It requires authority claims to remain observable.

When semantic authority is absent, uncertain, distributed, or conflicting, that condition is part of the inquiry.

The observer does not inherit authority merely because no other authority is visible.

## 15. Semantic Leakage

Semantic Leakage occurs when meaning crosses a boundary without the crossing remaining observable.

Common forms include:

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

The problem is not that these transitions are always invalid.

An interpretation may later be accepted as a definition.

An implementation may intentionally establish a new rule.

A hypothesis may become authoritative after an appropriate decision.

Semantic Leakage occurs when the transition is silent.

SIM therefore asks not only whether meanings converge, but how they converged and under what authority.

A visible transition can be reasoned about.

An invisible transition becomes part of the subject without preserving how it arrived there.

## 16. Semantic Isolation Is Not Permanent Separation

Isolation is temporary and purposeful.

SIM does not require every distinction to remain separate forever.

Two concepts may later be shown to be equivalent.

A Boundary Hypothesis may collapse.

Several observations may converge on one meaning.

An ambiguity may be resolved by authority.

A difference may be shown to have no semantic significance.

The purpose of isolation is to ensure that convergence happens as an observable reasoning event.

```text
Distinct
   ↓
Observed relationship
   ↓
Basis for convergence
   ↓
Converged
```

This is different from:

```text
Distinct
   ↓
Assumed same
```

SIM does not prefer separation over unity.

It prefers observable convergence over silent collapse.

## 17. Semantic Isolation Does Not Require Completeness

A semantic model does not need to be complete before SIM can begin.

Partial observations are enough to expose differences.

A fragment of workflow, a single term, an exception, a user complaint, an implementation behavior, or a disagreement may all be valid starting points.

SIM can proceed locally:

```text
Observe what is available.
Preserve what is unknown.
Follow differences that matter.
Discover boundaries where they become observable.
Stop when the current inquiry is sufficient.
```

This makes SIM compatible with incomplete domains and existing systems whose full structure is not yet understood.

Completeness may be an objective of an applied method.

It is not a prerequisite of SIM itself.

## 18. Reverse Inquiry

Reasoning does not always move from abstract meaning toward concrete realization.

Sometimes a lower-level observation exposes a semantic question that was previously invisible.

An implementation may contain two states where the conceptual model has one.

An exception may reveal a missing responsibility.

A data field may preserve a distinction that no current document explains.

SIM allows this to trigger **Reverse Inquiry**.

```text
Lower-level observation
        ↓
Unexpected difference
        ↓
Question about higher-level meaning
        ↓
Observation / Boundary Hypothesis / Probe
```

Reverse Inquiry does not grant lower-level structures semantic authority.

It grants them observational value.

The implementation may reveal a question.

It does not answer that question merely by existing.

This preserves the authority direction while allowing discovery to move in either direction.

## 19. Multiple Perspectives in SIM

Multiple perspectives increase the chance that hidden boundaries become observable.

Different observers may notice different distinctions because they carry different evidence, purposes, vocabulary, experience, or biases.

SIM uses these differences as input.

It does not require observers to converge before reasoning can continue.

A useful pattern is:

```text
Perspective A ─┐
Perspective B ─┼─> Differences ─> Questions ─> Boundary Hypotheses
Perspective C ─┘
```

Consensus may eventually be useful.

But consensus is an outcome governed by context and authority, not the mechanism by which SIM discovers meaning.

Multiple observers expand the observable semantic space.

They do not vote semantic boundaries into existence.

## 20. Observation and Evaluation

SIM separates Observation from Evaluation because they answer different questions.

Observation asks:

> What is present, different, missing, uncertain, or unexplained?

Evaluation asks:

> What should we prefer, accept, reject, prioritize, correct, or change?

Evaluation is necessary in many applications.

But if evaluation begins too early, undesirable observations may disappear before their semantic significance is understood.

A strange implementation may be labeled bad design before it reveals a hidden business distinction.

An exception may be called inconsistency before it reveals another scope.

A disagreement may be resolved before it reveals that two people use the same word differently.

SIM therefore keeps evaluation downstream from observation when the distinction matters.

This does not create an absolute temporal rule.

Evaluation itself may become an observation source and trigger another cycle.

The important condition is that evaluation does not silently rewrite what was observed.

## 21. The Thinking Core

The domain-independent thinking core of SIM can be summarized as:

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

Around this cycle, SIM preserves several constraints:

```text
Observer remains observable.
Perspective remains distinguishable.
Observation remains distinguishable from interpretation and evaluation.
Difference remains information before error.
Uncertainty may remain explicit.
Meaning is not manufactured merely because it can be explained.
Semantic authority remains located.
Convergence must remain observable.
Implementation is evidence before authority.
```

This is the core of Semantic Isolation Method.

Everything else may be adapted to the domain.

Artifacts may change.

Terminology may be specialized.

Roles may be introduced.

Processes may be formalized.

Tools may automate parts of observation or probing.

None of those define SIM itself.

They are applications of the thinking core.

## 22. What SIM Does Not Define

SIM does not define:

- how software should be architected,
- how organizations should be structured,
- how business processes should be optimized,
- how research should be conducted in every discipline,
- how truth should be scored,
- how consensus should be reached,
- how AI systems should be implemented,
- or which observer should be trusted by default.

Applied methods may define such things.

SIM provides a semantic reasoning foundation beneath them.

This distinction protects SIM from inheriting the assumptions of the first domains in which it was used.

AI-assisted development was an origin context.

Software architecture was an early application.

Neither is the definition of the method.

## 23. From Method to Application

SIM becomes useful in a domain when its thinking core is connected to domain-specific observation sources, authorities, probes, and decisions.

In software development, a Semantic Probe might vary a requirement or scenario.

In business analysis, it might vary actor, purpose, or responsibility.

In historical inquiry, it might compare evidence from different periods or provenance.

In AI reasoning, it might vary perspective, prompt context, observer model, or interpretation while preserving the differences produced.

These are different applications of the same method.

The method does not determine the domain.

The domain determines how the method is instantiated.

Vol. 4 examines one especially important observer: AI.

AI can generate observations, interpretations, hypotheses, questions, and narratives at unusual speed and scale.

That makes it powerful within SIM.

It also makes invisible semantic convergence unusually easy.

The next volume therefore asks how an AI should reason when the observer itself is one of the strongest sources of semantic influence.
