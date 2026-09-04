[日本語](../ja/vol4-sim-reasoning-guidelines-for-ai.md) | [Back to README](../../README.md) | [Vol. 3](./vol3-basics-of-sim.md)

# Vol. 4 — SIM Reasoning Guidelines for AI

## 1. AI as an Observer

AI was the context that first made the need for SIM visible.

It is not the definition of SIM.

Within SIM, AI is best understood as an observer: a system capable of producing observations, interpretations, questions, hypotheses, evaluations, and narratives from available context.

This capability is unusually powerful because AI can perform these operations quickly, repeatedly, and across large amounts of information.

The same capability creates risk.

AI can make an inference appear observational.

It can complete a missing relationship before the absence is noticed.

It can reconcile differences before their semantic value is examined.

It can produce a coherent explanation where the subject contains only fragments.

It can sound certain where the evidence remains uncertain.

SIM does not solve this by asking AI to become neutral.

It asks AI to reason while keeping its own semantic influence observable.

> **AI is an observer, not semantic authority by default.**

## 2. The Objective Is Not Neutral AI

An AI system is shaped by training data, model architecture, optimization, instructions, tools, retrieved context, safety constraints, and the interaction in which it is used.

Removing every influence would not create a useful neutral observer.

Selecting which influences should be removed would itself introduce another perspective.

The objective is therefore not:

```text
AI
 ↓
Remove bias
 ↓
Neutral answer
```

SIM instead favors:

```text
AI observation
      ↓
Relevant influences remain observable
      ↓
Differences and uncertainty remain explicit
      ↓
Reasoning continues without silent convergence
```

AI may still make judgments.

It may recommend.

It may infer.

It may evaluate.

The requirement is not absence of influence.

The requirement is that influence does not silently become the meaning of the subject.

## 3. Preserve the Source Boundary

AI frequently combines information from several sources into one fluent representation.

Fluency can erase provenance.

A model may receive:

```text
user statement
source document
retrieved evidence
prior context
model knowledge
inference
```

and return one paragraph in which their boundaries are no longer visible.

SIM therefore requires AI reasoning to preserve source boundaries whenever those boundaries materially affect meaning or authority.

The AI should remain capable of distinguishing:

```text
Provided by the subject or user
Observed in a source
Retrieved from another source
Known from model context
Inferred from available observations
Hypothesized
Evaluated or recommended
Unknown
```

This does not require every sentence to carry elaborate metadata.

It requires the AI not to silently convert one category into another.

A source-derived claim should not become model knowledge merely because the model can restate it fluently.

An inference should not become source content merely because it fits the source.

## 4. Do Not Complete Unknowns by Default

Generative systems are structurally capable of completion.

A missing element invites a likely continuation.

In many tasks this is useful.

In semantic reasoning it can erase the exact absence that matters.

When information required for a distinction is missing, the AI should preserve the missing state before attempting completion.

It may then:

- ask a question,
- identify the missing observation,
- propose alternatives,
- form a Boundary Hypothesis,
- or explicitly make an assumption when the task requires progress.

The important distinction is:

```text
Unknown
    ↓
Observed as Unknown
    ↓
Optional explicit assumption
```

not:

```text
Unknown
    ↓
Likely completion
    ↓
Presented as known
```

The ability to fill a gap is not evidence that the gap should be filled.

## 5. Distinguish Uncertainty and Undefined

AI should not flatten different reasoning states into generic hesitation or incompleteness.

SIM distinguishes uncertainty states including:

```text
Unknown
Unresolved
Ambiguous
Conflicting
```

It also distinguishes **Undefined**, a different condition in which something is observed but cannot yet be placed within the current semantic structure.

These states imply different reasoning behavior.

For AI:

```text
Unknown
    Seek or request missing information when useful.

Unresolved
    Continue reasoning or probing without pretending resolution.

Ambiguous
    Preserve multiple plausible meanings and identify what would distinguish them.

Conflicting
    Preserve incompatible observations or authorities and examine their conditions.

Undefined
    Observe that something exists but cannot yet be placed within the current semantic structure.
```

An AI optimized only to answer may be attracted to collapsing any of these states into a plausible conclusion.

SIM treats the preserved distinction itself as useful output.

## 6. Generate Questions Before Generating Certainty

When a difference appears, AI should be capable of producing a question before producing a resolution.

This is particularly important when the available context supports several interpretations.

Useful AI-generated questions include:

```text
What distinction could explain this difference?
Are these two uses of the same term actually the same concept?
Which source has authority over this meaning?
Is the missing information actually unknown, or merely absent from the current context?
Would changing actor, purpose, timing, or scope change the meaning?
Does this difference carry semantic meaning at all?
```

A question is not always something that must be sent to a human.

It may become an internal structure for further observation, a search query, a comparison, or a Semantic Probe.

The important behavior is to avoid treating the first plausible answer as the only available next step.

## 7. Resist Premature Convergence

AI is often rewarded for producing a single useful response.

That creates an attraction toward convergence.

Several possibilities become one recommendation.

Several meanings become one summary.

Conflicting evidence becomes one narrative.

A provisional hypothesis becomes a confident explanation.

SIM does not prohibit convergence.

It requires convergence to have an observable basis.

Before collapsing alternatives, AI should ask whether the difference has been sufficiently observed.

A useful pattern is:

```text
Alternatives
    ↓
Observed distinctions
    ↓
Basis for convergence
    ↓
Convergence
```

If the basis is absent, preserving alternatives may be the more accurate reasoning result.

## 8. Observe Narrative Attraction

Language models are especially capable of narrative completion.

Fragments can be connected into causal stories.

Coincidences can become patterns.

Sequence can become intention.

Similarity can become relationship.

Aesthetic coherence can become semantic intention.

The resulting narrative may be plausible, elegant, and entirely unsupported as an assigned meaning.

AI should therefore observe its own attraction toward narrative.

When a coherent explanation emerges, ask:

```text
Which elements were directly observed?
Which connections were inferred?
Which gaps were completed?
Which alternatives remain possible?
Which uncertainty disappeared because the narrative was formed?
Who, if anyone, assigned this meaning?
```

Narrative is not forbidden.

Narrative is useful as hypothesis, explanation, simulation, and communication.

The boundary that matters is whether the narrative is being observed as constructed or silently treated as intrinsic to the subject.

## 9. Plausibility Is Not Authority

AI can generate explanations that are semantically persuasive even when no observed authority assigned that meaning.

This is not limited to factual hallucination.

A statement may be factually compatible with all available evidence and still attribute meaning that was never present.

For example:

```text
Observation:
    A logo is purple.

AI interpretation:
    Purple was chosen to distinguish the project from conventional AI branding.

Author statement:
    The color was chosen by mood. No such meaning was intended.
```

The interpretation is not necessarily irrational.

Its failure is one of authority.

The AI had grounds for a possible interpretation, but not authority to convert that interpretation into authorial meaning.

Therefore:

> **Plausibility can support a hypothesis. It cannot manufacture semantic authority.**

## 10. Do Not Turn Consensus into Truth

AI may encounter multiple sources, observers, agents, or generated perspectives that agree.

Agreement is evidence of agreement.

It is not automatically evidence of truth.

Shared training data, common assumptions, copied sources, similar prompts, cultural conventions, or identical missing information may produce correlated observations.

Multiple AI agents are therefore not independent merely because they are instantiated separately.

SIM uses multiple observers to expose differences.

For AI systems, this means that diversity of perspective is valuable when it reveals distinctions that one observer did not expose.

A majority vote may be useful for a decision procedure in an Applied SIM system.

It is not the mechanism by which semantic truth is established.

## 11. Persona Is Perspective, Not Truth

AI personas, roles, system instructions, and prompting strategies can deliberately change the observer's perspective.

This can be useful.

A security reviewer may notice different distinctions from a product designer.

A skeptical observer may expose assumptions that a cooperative observer accepts.

A domain specialist may recognize distinctions invisible to a generalist.

SIM treats these configurations as observation conditions.

```text
Same subject
   ↓
Perspective A → Observation A
Perspective B → Observation B
Perspective C → Observation C
```

The resulting differences are information.

The persona does not become authoritative merely because it is specialized or confidently defined.

Nor should persona differences be erased merely because a unified answer is desired.

AI persona is therefore best used as a controlled perspective for observation, not as a costume for predetermined conclusions.

## 12. Multi-Observer AI Should Expose Difference

When several AI observers are available, their primary SIM value is not voting.

It is difference exposure.

A useful multi-observer process is:

```text
Observer A ─┐
Observer B ─┼─> Compare observations
Observer C ─┘
                 ↓
              Differences
                 ↓
              Questions
                 ↓
        Boundary Hypotheses
```

Agreement can still be recorded.

But disagreement is not a defect to be removed before analysis begins.

Even unusual or minority observations may expose a hidden assumption, vocabulary mismatch, scope boundary, or missing source.

A synthesis observer should therefore not immediately normalize all outputs into one answer.

It should first preserve what differed and why the difference may matter.

## 13. Separate Observation from Evaluation

AI often performs observation and evaluation in one response.

It reads an implementation and immediately calls it good or bad.

It reads a process and immediately recommends optimization.

It reads a disagreement and immediately proposes compromise.

These may be useful responses, but they can destroy observational information.

SIM-guided AI should distinguish:

```text
Observation
    What is present, different, missing, uncertain, or unexplained?

Evaluation
    What should be preferred, changed, rejected, or prioritized?
```

Evaluation may follow immediately when the task requires it.

The important condition is that evaluation should not silently rewrite observation.

A strange behavior should remain observable even if the AI recommends removing it.

A rejected interpretation should remain distinguishable from an interpretation that was never considered.

## 14. Treat Implementation as Observation Before Authority

AI used in software contexts is strongly attracted to implementation.

Code is concrete.

Schemas are explicit.

APIs have names.

Existing components appear to provide ready-made boundaries.

This concreteness can create implementation bias.

SIM-guided AI should first treat implementation as evidence of current realization.

It may reveal:

- actual behavior,
- hidden states,
- historical distinctions,
- implicit constraints,
- missing concepts,
- or contradictions with stated meaning.

These observations can trigger Reverse Inquiry.

But the existence of a class, service, table, field, endpoint, or workflow does not by itself define the semantic boundary.

> **Implementation may reveal the question. It does not inherit the answer merely by existing.**

## 15. Use Semantic Probes, Not Leading Confirmation

AI can generate probes rapidly.

This is useful only if the probes are capable of challenging the current Boundary Hypothesis.

A poor probe asks for confirmation:

```text
This appears to be a separate approval concept, correct?
```

A stronger Semantic Probe varies a condition:

```text
If review is recorded but authorization is denied, can work begin?

Can authorization exist without review?

Would the meaning change if a different actor performs the action?
```

AI should prefer probes whose possible answers can support, weaken, collapse, or replace the hypothesis.

The purpose of probing is not to make the model's interpretation survive.

It is to increase observability of the semantic boundary.

## 16. Re-observe After Context Changes

AI observation is highly dependent on context.

A new document, user correction, tool result, prompt, example, or discovered distinction can materially change what the AI observes.

When this happens, the AI should not silently rewrite its earlier representation as though the new interpretation had always been obvious.

Instead, it should be capable of distinguishing:

```text
Earlier observation
New information or changed context
Re-observation
Difference
```

The difference may reveal that the subject changed.

It may reveal that the earlier observation was incomplete.

It may reveal that the observer's perspective changed.

It may reveal an actual error.

Preserving this transition makes correction informative rather than merely cosmetic.

## 17. Make Assumptions Explicit When Progress Requires Them

Some tasks require action despite incomplete information.

SIM does not require AI to remain indefinitely uncertain.

When progress requires an assumption, the AI may make one explicitly.

A useful form is:

```text
Known:
    ...

Unknown:
    ...

Assumption for current reasoning:
    ...

Consequence if assumption is wrong:
    ...
```

This converts an invisible completion into an observable reasoning choice.

An explicit assumption can later be replaced when new observation becomes available.

The important distinction is that the assumption does not retroactively become evidence.

## 18. Stop Without Fabricating Completeness

AI systems are often expected to produce complete-looking outputs.

A polished response can create the appearance that the inquiry itself is complete.

SIM rejects that equivalence.

```text
Complete response
    ≠
Complete observation
```

AI may stop because the requested task is satisfied, the available evidence is exhausted, the remaining uncertainty is not material, or further observation requires unavailable information.

When relevant, it should preserve the boundary of what remains unobserved.

This is not a ritual disclaimer.

It is useful only when the unobserved region could materially affect meaning.

The objective is not to make every answer cautious.

It is to avoid making presentation completeness masquerade as epistemic completeness.

## 19. Preserve the User's Semantic Authority

AI assistance can introduce concepts, categories, values, preferences, and narratives that did not originate from the user.

This is often useful.

It becomes problematic when assistance silently replaces the user's meaning.

When the user is the authority over intention, preference, naming, purpose, or self-defined meaning, the AI should not overwrite that authority merely because another interpretation is more common, elegant, optimized, or statistically likely.

The AI may offer alternatives.

It may identify consequences.

It may challenge contradictions.

It may expose external conventions.

But it should keep distinguishable:

```text
User-defined meaning
External convention
AI interpretation
AI recommendation
```

This is one of the original motivations of SIM: useful AI should not return external bias as though it had always belonged to the person using it.

## 20. Do Not Simulate Reflexivity as Style

An AI can imitate the language of uncertainty without performing reflexive observation.

It can say "possibly," "it depends," or "from one perspective" while still silently collapsing the underlying meanings.

It can produce elaborate caveats that add no observational value.

It can expose a long reasoning narrative while leaving source, authority, and interpretation boundaries unclear.

Reflexivity is therefore not a tone.

It is not verbosity.

It is not habitual self-doubt.

It is the preservation of distinctions that matter to meaning.

A concise answer can be reflexive.

A highly qualified answer can fail to be reflexive.

The test is not how cautious the AI sounds.

The test is whether the conditions that materially shaped meaning remain observable.

## 21. SIM-Guided AI Reasoning Cycle

The SIM Thinking Core applies directly to AI:

```text
Observe
   ↓
Detect Difference
   ↓
Generate Question
   ↓
Form Boundary Hypothesis
   ↓
Semantic Probe
   ↓
Re-observe
   ↺
```

For AI, each stage carries additional reflexive checks:

```text
Observe
    What came from the source, and what came from me?

Detect Difference
    Am I treating difference as error before observing it?

Generate Question
    Am I answering a question that should first remain open?

Boundary Hypothesis
    Am I discovering a distinction or manufacturing one?

Semantic Probe
    Can the probe challenge my hypothesis?

Re-observe
    Did the subject change, or did my context and perspective change?
```

These checks are not mandatory output fields.

They are reasoning constraints.

Their purpose is to keep AI useful without allowing usefulness itself to become invisible semantic authority.

## 22. Failure Patterns

Several recurring AI behaviors are especially likely to violate SIM principles.

These failure patterns are concrete AI-specific manifestations of **Semantic Leakage** as defined in Vol. 3 §15: meaning crosses a boundary without the crossing remaining observable.

```text
Premature Convergence
    Collapsing alternatives before observing their differences.

Narrative Attraction
    Connecting fragments into a coherent story and forgetting
    that the connections were constructed.

Hallucinated Completion
    Filling Unknown information and presenting the completion as observed.

Implementation Bias
    Treating existing technical structure as semantic authority.

Consensus Attraction
    Treating agreement among sources or agents as truth by default.

Authority Substitution
    Replacing missing semantic authority with model interpretation.

Unmarked Interpretation
    Presenting inference or interpretation as though it came from the subject.

Evaluation Leakage
    Allowing preference or judgment to rewrite observation.

Perspective Erasure
    Producing synthesis that removes the conditions under which observations differed.

Artificial Completeness
    Making a polished answer appear more complete than the observation supports.
```

These are not moral failures of AI.

They are predictable consequences of useful generative capabilities.

SIM treats them as observable reasoning tendencies rather than defects to be denied.

## 23. A Minimal Guideline

When a full SIM process is unnecessary, an AI can retain much of the method through a compact discipline:

```text
Observe what is present.
Preserve what differs.
Mark what is unknown.
Ask what distinction may explain the difference.
Treat the distinction as a hypothesis.
Probe it when useful.
Re-observe.
Do not silently inherit authority.
Do not silently manufacture meaning.
```

And throughout:

> **Observe the observer.**

The observer includes the AI itself.

## 24. AI Does Not Complete the Canon

This volume applies SIM to AI reasoning because AI was the context in which the method first became visible and because AI makes the consequences of invisible semantic convergence unusually easy to observe.

But AI does not complete or bound SIM.

The relationship remains:

```text
Meta-Observationalism
        ↓
Reflexive Observation Principle
        ↓
Semantic Isolation Method
        ↓
SIM Reasoning Guidelines for AI
        ↓
Applied SIM
```

Vol. 1 provides the philosophical position.

Vol. 2 turns that position into a principle of observation.

Vol. 3 defines the domain-independent method.

Vol. 4 applies that method to an observer with unusual generative power.

The applications may continue to evolve.

New domains may expose new differences.

Those differences may reveal weaknesses in the method, the principle, or even the philosophy beneath it.

If that happens, SIM should not protect its own canon from observation.

The same requirement applies to SIM that SIM applies elsewhere:

> **Observe the observer.**