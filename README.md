[日本語](./README.ja.md)

<p align="center">
  <img src="./assets/sim_logo.png" alt="Semantic Isolation Method" width="320">
</p>

# Semantic Isolation Method

**Documents defining a generic semantic reasoning method for observing bias, preserving uncertainty, and discovering semantic boundaries.**

Semantic Isolation Method (SIM) is a generic method for reasoning about meaning without prematurely resolving differences, uncertainty, or observer bias.

SIM began from a question about AI bias: systems that are useful precisely because they draw on knowledge, optimization, and prior context may also return influences that did not originate from the person using them. Attempts to eliminate such bias introduce another problem — deciding what counts as bias, neutrality, or correctness is itself an act of observation and interpretation.

SIM therefore does not begin by trying to eliminate bias. It begins by making observation itself observable.

> **Observe the observer.**

From this foundation, SIM treats differences as information before treating them as errors, preserves uncertainty as an explicit state, and isolates semantic boundaries before allowing interpretation, evaluation, or implementation to collapse them.

## Canonical Structure

This repository contains the foundational documents of SIM.

| Volume | Title | Role |
| --- | --- | --- |
| Prologue | **[Origin and Position of SIM](./docs/en/prologue.md)** | Why SIM exists and how the philosophy, principle, and method relate |
| Vol. 1 | **[Meta-Observationalism](./docs/en/vol1-meta-observationalism.md)** | Philosophical foundation |
| Vol. 2 | **[Reflexive Observation Principle](./docs/en/vol2-reflexive-observation-principle.md)** | Principle of observing both the subject and the act of observation |
| Vol. 3 | **[Basics of SIM (Semantic Isolation Method)](./docs/en/vol3-basics-of-sim.md)** | Domain-independent semantic reasoning method |
| Vol. 4 | **[SIM Reasoning Guidelines for AI](./docs/en/vol4-sim-reasoning-guidelines-for-ai.md)** | Guidance for applying SIM to AI reasoning |

Terminology, official translation mappings, and important concept contrasts are indexed in the **[Concept Index / Glossary](./GLOSSARY.md)**. The index does not replace definitions in the canonical volumes; it points back to their canonical locations.

The English documents are canonical. Japanese documents are official translations. If a semantic difference is introduced through translation, the English version takes precedence until the difference is explicitly resolved.

## SIM and Applied Methods

SIM itself is not a software-development process, business-analysis technique, architecture method, or AI workflow.

Those may be derived as **Applied SIM** methods. They can introduce procedures, artifacts, roles, and domain-specific constraints while remaining grounded in the principles defined here.

Applied SIM is a separate work that applies this canon rather than, merely by being Applied SIM, a modified distribution of the canonical documents. The NoDerivatives condition is therefore not intended to prohibit independently written Applied SIM methods as such.

AI-assisted development was the context in which SIM first emerged, but it does not define the scope of the method.

## Version 0

The foundational documents are designated **Version 0**.

Version 0 does not mean preliminary, unstable, or incomplete. It identifies the foundational layer from which applied forms of SIM are derived.

Historically, applied forms of SIM appeared before this foundation was explicitly isolated. Version 0 records the principles that were discovered underneath those applications.

## License

The documents in this repository are licensed under the **Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)** license.

You may share and cite these documents with appropriate attribution. Modified versions may not be distributed under the terms of this license.

See [LICENSE](./LICENSE) for details.
