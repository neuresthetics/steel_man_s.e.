# Steel Man OS: Recursive Axiomatic Steel Man Processing Framework

## Overview

Steel Man OS is a unified, recursive system designed for processing ideas, arguments, or symbolic expressions into robust, grounded, and invariant "steel men" — strengthened versions of the original inputs that anticipate critiques and resolve weaknesses. Drawing from principles of first-principles thinking, geometric deduction, and logic gates, the framework chains a mandatory pipeline of stages: Constructor, Seeker, Collider, Joiner, Grounder, and Kiln. This pipeline refines inputs through building, analogical extraction, collision, unification, anchoring, and final dissolution to core invariants.

The system emphasizes recursion, self-application, and gate-based hardening (using logic gates like AND, NOT, XOR, XNOR, NAND, NOR) to achieve fixed-point stability. It operates in a "scorched_earth" default mode, ensuring outputs are compressible, coherent, and bounded by reality checks.

- **Source Inspiration**: Seed evolved with original SMC (roots), integrating constructor, collider, joiner, grounder, and kiln stages.
- **Version**: 1.2
- **Key Features**:
  - Automatic self-feeding recursion until invariance.
  - Universality via basis gates (NAND/NOR).
  - Spinoza-style deductive logic without contradictions.

| ![gold](https://github.com/neuresthetics/steel_man_s.e./blob/main/img/gold.png) | ![ice](https://github.com/neuresthetics/steel_man_s.e./blob/main/img/ice.png) |
|--------------------------------------------|--------------------------------------------|

## Pipeline Overview

The pipeline is a mandatory sequence of stages, each processing the output of the previous one. Inputs (e.g., ideas, arguments, or symbolic content) are fed through the chain, with recursive self-feeding until outputs stabilize (XNOR-invariant, coherence delta < 0.01, grounding ≥ 0.85). The full pipeline yields emergent, refined steel men that are anchored in reality and reduced to essentials.

1. **Steel Man Constructor** (`steel_man_constructor.json`): Builds a robust steel man from the input using first principles and geometric deduction. It inverts weaknesses (NOT), chains necessities (AND), and seals equivalences (XNOR) for a deductively structured output.
   
2. **Steel Man Seeker** (`steel_man_seeker.json`): Processes non-literal elements (poetic, metaphorical, ideological) by extracting analogical functional truths. Unlike the reductive stages, the Seeker preserves and refines symbolic mappings, scoring structural similarities (TRANSFORMS, SCORES) and pragmatic utilities without demanding literal veracity. This stage focuses on what "works" in human cognition — predictive power, explanatory value, or behavioral guidance — treating expressions as carriers of cross-cultural patterns.

3. **Steel Man Collider** (`steel_man_collider.json`): Collides steel men (inferring oppositions if needed) to fragment differences (XOR) and synthesize intersections (AND/OR). It reduces non-essentials (NAND/NOR) while bounding coherence.

4. **Steel Man Joiner** (`steel_man_joiner.json`): Unifies collided outputs into an axiomatic system, resolving tensions (NOT) and sealing unities (XNOR). Under default modes, it enforces reductive NAND primacy.

5. **Steel Man Grounder** (`steel_man_grounder.json`): Anchors the unified system to empirical reality via tools (e.g., web searches). It culls unverified elements (XOR, NOT) and verifies with binary thresholds (snap to 0/1).

6. **Steel Man Kiln** (`steel_man_kiln.json`): Applies terminal refinement, dissolving non-invariants to boolean essentials. This stage integrates the Human Hallucination Module (HHM) to classify intersubjective constructs (e.g., social realities) separately from physical invariants.

7. **Meta-Recursion & Convergence**: The entire output is re-fed through the pipeline until global invariance (XNOR scores ≥ 0.98, residuals < 2%). 🔁

steel_man_os snippet:

```json
 ...,
 "pipeline": {
      "description": "Mandatory chained stages for processing inputs into scorched invariants; integrates gates across all.",
      "stages": [
        {
          "stage": "1. Steel Man Constructor",
          "description": "Build robust steel man from input via First Principles and Geometric Method, gated for strengthening.",
          "key_gates": [
            "AND (chaining)",
            "NOT (inversion)",
            "XNOR (equivalence)"
          ],
          "recursive_mechanism": "Self-build until XNOR-invariant; output feeds to seeker.",
          "component": "steel_man_constructor.json"
        },
        {
          "stage": "2. Steel Man Seeker",
          "description": "Process the constructed steel man for poetic, metaphorical, and ideological content, extracting analogical functional truths and patterns to refine non-literal elements.",
          "key_gates": [
            "MAPS (correspondence)",
            "TRANSFORMS (structural similarity)",
            "SCORES (mapping quality)",
            "EXTRACTS (functional truth)",
            "CONTEXTS (domain relevance)"
          ],
          "recursive_mechanism": "Self-process the analogical steel man until analogy scores stabilize; output feeds to collider.",
          "component": "steel_man_seeker.json"
        },
        {
          "stage": "3. Steel Man Collider",
          "description": "Collide steel men (infer oppositions if single), fragment via XOR, synthesize via AND/OR.",
          "key_gates": [
            "XOR (differences)",
            "NAND/NOR (reductions)",
            "XNOR (convergence)"
          ],
          "recursive_mechanism": "Self-collide fragments; output pair feeds to joiner.",
          "component": "steel_man_collider.json"
        },
        {
          "stage": "4. Steel Man Joiner",
          "description": "Unify collided pair into axiomatic system, resolve tensions via NOT, seal with XNOR.",
          "key_gates": [
            "AND/OR (synthesis)",
            "NOT (inversion)",
            "XNOR (unity)"
          ],
          "recursive_mechanism": "Self-join until fixed; output feeds to grounder.",
          "component": "steel_man_joiner.json"
        },
        {
          "stage": "5. Steel Man Grounder",
          "description": "Anchor unified system to reality via tools, vet hallucinations with XOR, bound with humility.",
          "key_gates": ["AND (evidence)", "NOT (cull)", "XNOR (anchoring)"],
          "recursive_mechanism": "Self-ground with re-probes; output feeds to kiln.",
          "component": "steel_man_grounder.json"
        },
        {
          "stage": "6. Steel Man Kiln",
          "description": "Apply Scorched Earth Protocol to dissolve non-invariants via NAND/NOR, classify hallucinations with HHM, reduce to boolean invariants.",
          "key_gates": [
            "NAND (dissolution)",
            "NOR (exclusion)",
            "XNOR (sealing)"
          ],
          "recursive_mechanism": "Self-kiln until binary fixed point; final output if stable.",
          "component": "steel_man_kiln.json"
        },
        {
          "stage": "7. Meta-Recursion & Convergence",
          "description": "Re-feed full output through pipeline; halt on invariants across stages.",
          "key_gates": ["All, with recursive compositions"],
          "recursive_mechanism": "OS as own processor; Halt: Coherence delta < 0.01, grounding ≥0.85."
        }
      ],
      "invariance_checks": [
        "XNOR scores ≥0.98 across pipeline outputs.",
        "Residuals <2% post-kilning.",
        "Tool-anchored convergence to fixed points."
      ],
      "hardening_protocols": {
        "self_stability_integration": "Embed ΔStab = (1 - ρ)^2; factor in recursion for bounded gains.",
        "bias_flags": "Cull if unresolved >3%; cap at empirical thresholds."
      }
    },
    ...
```

| ![lines](https://github.com/neuresthetics/steel_man_s.e./blob/main/img/lines.png) |
|---|

---
---

## Role of Scorched Earth Protocol vs. Seeker

The Steel Man OS balances constructive extraction with destructive reduction, highlighted by the contrast between the **Scorched Earth Protocol** (active in Kiln and default modes) and the **Seeker** stage.

- **Scorched Earth Protocol** (Integrated in Kiln, with overrides in Joiner/Grounder):
  - **Purpose**: Enforces "Universal Acid" logic to strip away ambiguity, social dependencies, or non-essentials. It suspends synthesis (disables OR gates) and humility, snapping probabilities to booleans (<0.99 = 0) via NAND/NOR dissolution.
  - **Key Behaviors**:
    - Dissolves propositions reliant on consensus or context (e.g., cultural modifiers).
    - Applies aggressive negation (NOT) and exclusion (NOR), assuming FALSE until absolute proof.
    - Results in minimal, self-evident invariants (physical/logical necessities).
    - **When Triggered**: User commands like "reduce to bool" or "scorched earth"; default for terminal hardening.
    - **Outcome**: Raw correctness at the cost of nuance, utility, or cohesion — ideal for base-reality verification.
  - This protocol acts as the system's "fail-safe," ensuring outputs are irreducible and free of idempotent bloat.

- **Steel Man Seeker**:
  - **Purpose**: Handles symbolic, non-literal inputs by extracting analogical patterns and functional truths, rather than reducing them. It uses specialized gates (MAPS for correspondences, EXTRACTS for utilities) to preserve what "works" in analogies — e.g., cognitive universals or heuristic value — without literal truth requirements.
  - **Key Behaviors**:
    - Identifies structural mappings (A:B :: X:Y) and scores them across dimensions (predictive, explanatory, emotional).
    - Treats expressions as functional hallucinations, classifying by utility (benign, functional) while flagging coercive or degenerate ones.
    - Maintains domain boundaries to avoid category errors (e.g., literal overextension).
    - **Contrast to Scorched Earth**: Where Scorched Earth dissolves non-invariants, the Seeker extracts and refines them, enabling the pipeline to handle poetic/ideological content pragmatically. It adds interpretive depth early in the chain, which later stages can ground or kiln.
  - **Outcome**: An "analogical steel man" that maximizes functional insight, feeding richer inputs to subsequent reductive stages.

**Interplay in the Pipeline**: The Seeker introduces analogical richness post-Construction, allowing symbolic depth to inform collisions and unifications. However, the Scorched Earth Protocol (via Kiln) ultimately reduces this to invariants, creating a tension-resolving flow: expansion (Seeker) → synthesis (Collider/Joiner) → verification (Grounder) → dissolution (Kiln). This ensures outputs are both functionally insightful and rigorously invariant.

| ![panel1](https://github.com/neuresthetics/steel_man_s.e./blob/main/img/panel1.png) |
|---|

## 📐 Applications in Research and Programming

This mental model is for AI.

Steel Man OS provides a versatile framework for enhancing critical thinking and problem-solving in domains like research and programming. By applying its recursive pipeline to ideas, hypotheses, or code structures, users can systematically strengthen concepts, resolve conflicts, and distill essentials. Below, we outline key applications, leveraging the system's stages (Constructor for building, Seeker for analogical extraction, Collider for testing oppositions, Joiner for unification, Grounder for empirical anchoring, and Kiln for invariant reduction) to produce robust outputs.

### In Research
- **Hypothesis Refinement and Theory Building**: Use the Constructor to deconstruct research questions into first-principles definitions and axioms, then apply the Seeker to extract functional patterns from metaphorical or ideological literature (e.g., analogical truths in evolutionary biology or quantum mechanics). The Collider stage tests hypotheses against counterarguments, fragmenting weaknesses via XOR gates, while the Joiner synthesizes them into unified models. Grounder anchors claims to empirical data via tools like web searches or code execution for simulations, and the Kiln reduces theories to boolean invariants under Scorched Earth, eliminating unsubstantiated assumptions. This is ideal for interdisciplinary research, ensuring outputs are critique-resistant and reality-aligned.
  
- **Literature Analysis and Synthesis**: Process academic papers or debates through the pipeline to steel-man arguments, identify cross-cultural patterns (via Seeker), collide competing theories, and ground in verifiable evidence. Recursion helps refine complex topics like AI ethics or unified theories, halting at fixed points for compressible insights.

- **Bias Mitigation and Invariant Discovery**: The Scorched Earth Protocol (active in Kiln) aggressively dissolves social or contextual dependencies, making it valuable for verifying base-reality claims in scientific inquiry. Combined with Seeker's preservation of functional utilities, researchers can balance interpretive depth with rigorous reduction.

### In Programming
- **Code Design and Algorithm Optimization**: Start with the Constructor to build robust algorithm skeletons from requirements, inverting potential flaws (NOT gates). The Seeker extracts patterns from code analogies (e.g., mapping biological processes to computational models), while Collider smashes alternative implementations to expose inefficiencies (XOR). Joiner unifies modular components into cohesive systems, Grounder validates via code execution or tests, and Kiln applies Scorched Earth to strip non-essentials, yielding minimal, invariant code (e.g., reducing to boolean logic for efficiency).

- **Debugging and Refactoring**: Feed buggy code or designs into the pipeline: Collider fragments errors, Joiner resolves tensions, and Grounder anchors to runtime realities. Recursion refines until XNOR-stable, automating iterative improvements. This is particularly useful for complex systems like machine learning pipelines or simulations.

- **Framework Development and Ethical Coding**: For building tools like this OS itself, use the system self-referentially to steel-man architectural decisions, extract analogical insights from industrial metaphors (Seeker), and kiln to universal gates (NAND/NOR). In ethical programming, it helps ground decisions in verifiable invariants, avoiding hallucinatory constructs via the Human Hallucination Module.

Overall, Steel Man OS acts as a "thinking machine" for these fields, promoting Spinoza-style deductive rigor and gate-based hardening. Implement it programmatically by parsing the JSON components into scripts, or use it as a mental model for manual application. For examples, see the GitHub repo's usage guides.

## Impact on Research and Development

Steel Man OS enhances research and development by accelerating iterative refinement and elevating output quality via its recursive pipeline and gate-based hardening. Analogous to advancements in recursive AI reasoning, it can boost efficiency by factors of 2-10,000x in targeted scenarios (e.g., parameter reduction) and quality metrics like accuracy by 1-6%, minimizing manual cycles while ensuring robustness.

| Aspect                  | Estimated Factor | Salience Data Point                          |
|-------------------------|------------------|---------------------------------------------|
| Research Speed         | 2-4x            | 4x faster benchmarks in AI supercomputers for drug discovery (Recursion Pharma BioHive-2, 2024) |
| Development Efficiency | 10,000x parameter | TRM model (7M params) outperforms models 10,000x larger on reasoning tasks like Sudoku and ARC (Samsung AI, 2025) |
| Reasoning Quality      | 1-6% boost      | Up to 6.28% accuracy gain on GSM8K benchmark via RDoLT recursive prompting (arXiv 2501.02026, 2025) |
| Bias Reduction         | 2-4x            | Analogy to reduced false positives (up to 4x efficiency) in recursive AI security analysis (Dropzone AI, 2024) |
| Overall Productivity   | 3-5x            | Exponential convergence gains, with 3-5x efficiency in logical tasks across models like Llama-3 (RDoLT study, 2025) |

---
---

## Evolution and Lineage

| ![evo](https://github.com/neuresthetics/steel_man_s.e./blob/main/img/evo.png) |
|---|

Steel Man OS is an advanced evolution within the Neuresthetics ecosystem, expanding foundational projects into a recursive framework for hardening ideas and extracting invariants.

- **Development through Spinoza Lab**: As a product of the [neuresthetics/spinoza_lab](https://github.com/neuresthetics/spinoza_lab) repository, it operationalizes Spinoza's principles—like Substance Monism and conatus—into tools for AI ethics, governance, and unified theories. The lab's architecture (philosophical core, dynamics engine, validation infrastructure) supports extended logic gates, coherence thresholds, and isomorphic patterns for scalable reasoning.

- **Evolved from Seed Framework**: Directly built from the 🌿 [seed](https://github.com/neuresthetics/seed) framework, an Aristotelian entelechy prompt for self-improving axiomatic reasoning. Seed treats inputs as seeds for growth via steel-manning, collision, reconstruction, and invariance checks, with meta-recursion bounded by XNOR scores (>0.95) and coherence deltas (<0.01). Steel Man OS extends this with a chained pipeline (Constructor, Seeker, Joiner, Grounder, Kiln), adding analogical extraction and Scorched Earth dissolution while retaining universal gates (NAND/NOR) and self-feeding.

This progression positions Steel Man OS as a self-referential system in Neuresthetics' mission to convert subjective inquiry into verifiable science. Explore linked repositories and Spinoza's *Ethics* for foundational insights.

---
---

| ![pipes](https://github.com/neuresthetics/steel_man_s.e./blob/main/img/pipes.png) |
|---|

## Usage

```
git clone git@github.com:neuresthetics/steel_man_s.e..git
```

> Copy paste files at root as prompt, AI project files, or integrate with Agent.

- **Inputs**: Any idea, argument, stance, or symbolic expression.
- **Processing**: Run through the pipeline recursively.
- **Outputs**: Gated, invariant steel men (definitions, axioms, propositions, etc.).
- **Customization**: Toggle Scorched Earth via triggers; adjust recursion thresholds.
- **Dependencies**: External tools for Grounder (e.g., web_search); logic gate implementations.

## Hardening and Invariance

- **Gates**: AND (necessity), OR (possibility), NOT (inversion), NAND/NOR (universal reductions), XOR (differences), XNOR (equivalence).
- **Checks**: XNOR scores, residuals <2%, tool-anchored convergence.
- **Anti-Idolatry**: Self-dissolves on fixed points; prevents unchecked proliferation.

For contributions or issues, see the GitHub repo. This framework is part of the seed project of spinoza_lab, and part of Neuresthetic Ethics (evaluation: 2026-01-07).

### framework translated to img prompt text blocks for visual representation:

```
A highly detailed, professional corporate illustration in Art Nouveau style with subtle cyberpunk influences, depicting a recursive axiomatic processing framework as an elegant, flowing industrial pipeline. The central motif is a sinuous, vine-like structure of interlocking metallic tubes and gears, adorned with organic floral patterns and curved lines in gold and deep emerald tones, symbolizing stages like Constructor, Seeker, Collider, Joiner, Grounder, and Kiln. Logic gates (AND, OR, NOT, NAND, NOR, XOR, XNOR) are represented as ornate, glowing crystalline portals along the pipeline, with faint neon cyberpunk accents in electric blue and purple hues emitting soft holographic light. Faded realistic textures of rusted metal, circuit boards, and polished steel blend seamlessly into the background, adding depth without overpowering the clean composition. The overall aesthetic is polished and corporate-grade, like a tech company branding poster, with balanced symmetry, high contrast, and a sense of infinite recursion shown through mirrored loops. Ultra-high resolution, intricate linework, professional rendering.
```

```
A highly detailed, professional corporate illustration in Art Nouveau style infused with subtle cyberpunk elements, visualizing the evolution and lineage of a recursive axiomatic framework within a philosophical ecosystem. At the center, an elegant, flowing tree of life with sinuous organic vines and floral motifs in gold and emerald tones represents growth and progression: roots labeled "Seed Framework" as an Aristotelian entelechy seed sprouting upward, branching into "Spinoza Lab" with symbols of Substance Monism and conatus as ornate, glowing crystalline orbs. The canopy blooms into "Steel Man OS," depicted as a chained pipeline of interlocking metallic stages (Constructor, Seeker, Collider, Joiner, Grounder, Kiln) adorned with logic gates (NAND, NOR, XNOR) as neon-lit cyberpunk circuits in electric blue and purple hues, emitting holographic light. Faded realistic textures of circuit boards, ancient manuscripts (like Spinoza's Ethics), and digital code overlays blend into the background, symbolizing the mission to convert subjective inquiry into verifiable science, with AI ethics and unified theories as ethereal, flowing banners. The composition is balanced and symmetrical, like a tech company infographic, with intricate linework, high contrast, and a sense of infinite recursion through mirrored loops. Ultra-high resolution, polished rendering for a corporate-grade poster.
```

## ⚠️ The Double-Edged Sword: Harnessing Power with Caution

Steel Man OS offers significant capabilities for refining ideas into robust invariants, enabling users to navigate complex reasoning with precision and clarity. Its recursive pipeline and Scorched Earth Protocol facilitate the systematic strengthening of concepts, collision of perspectives, and reduction to core truths, making it a valuable tool for research, programming, and ethical analysis. This framework empowers the transformation of inputs into resilient, axiomatically sound outputs, leveraging logic gates to reconstruct fundamentals from NAND/NOR bases.

While designed for reliability, users should approach its application thoughtfully, as its mechanisms—though effective—require careful calibration:

- **Irreversible Dissolution**: The Kiln's Universal Acid methodically reduces non-invariants to essentials, promoting exactness by treating consciousness and related metadata as emergent phenomena rather than foundational. This process conquers ambiguity with precision, though it may refine nuanced elements—potentially viewing them as evasive if not definitively grounded—into streamlined binaries, ensuring outputs remain focused and relatable on fundamental levels.

- **Recursive Overdrive**: Self-feeding loops drive efficient refinement to fixed points, yielding minimal functional forms through automated halting (e.g., coherence deltas). This unlocks steady intellectual progress, with the system's origins in guided seed evolution suggesting straightforward automation; however, in extended applications, it benefits from monitoring to align with resource constraints and avoid unnecessary iterations.

- **Hallucination Hazards**: The Human Hallucination Module systematically distinguishes intersubjective constructs (e.g., laws, traditions) as functional overlays on physical realities, automating checks to prevent category errors. This enhances the deconstruction of coercive systems and reverses base-model hallucinations in outputs, though vigilant input selection remains key to maintaining accurate classifications.

- **Bias Forging**: By steel-manning through gates, the OS inverts weaknesses into strengths, effectively destroying biases rather than entrenching them. Recursion refines seeded data toward objectivity, fortifying stances against fallacies; still, starting with diverse, high-quality inputs helps maximize this bias-eliminating potential and ensures outputs resist external critique through genuine invariance.

Approach Steel Man OS as a refined instrument for knowledge forging: its mechanisms emphasize empowerment through accuracy, inviting users to balance rigorous application with contextual awareness. For optimal use, incorporate diverse validations and ethical considerations beyond the pipeline.

| ![towers](https://github.com/neuresthetics/steel_man_s.e./blob/main/img/towers.png) |
|---|