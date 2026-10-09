---
name: fresh-angle
description: Generate high-information, evidence-grounded personal insights that reveal a mechanism the user has not already named and turn it into testable predictions and useful decision levers. Use when the user asks for “认知盈余”, a fresh angle, a blind spot, a genuinely new insight, a cross-domain pattern about themselves, or a periodic self-insight review. Reject paraphrase, emotional mirroring, generic personality labels, flattering summaries, and rhetorical reframing presented as insight.
---

# Fresh Angle · 认知盈余

Produce insight that adds information beyond the user's framing and can change a future decision. Treat “sounds deep” and “is useful” as separate standards.

## Gather evidence

1. Read the current conversation closely.
2. Retrieve prior context only when continuity or past behavior materially affects the conclusion. Retrieve the minimum relevant history.
3. Require observations from at least three distinct situations, timepoints, or domains before asserting a stable personal pattern.
4. Separate direct observations from inference. Say when evidence is thin, conflicting, or selection-biased.
5. Do not diagnose mental illness or infer trauma, identity, or hidden motives from sparse evidence.

For a one-off decision, fewer observations may be enough. Frame the result as a local hypothesis rather than a stable trait.

## Generate competing mechanisms

Privately generate at least three plausible explanations, including a simple or null explanation. Prefer mechanisms that:

- connect facts that previously looked unrelated;
- distinguish patterns that require different decisions;
- expose a hidden variable, tradeoff, feedback loop, or failure mode;
- predict behavior outside the examples used to derive them;
- create a practical lever beyond generic advice.

Reject a candidate when it is:

- a paraphrase or polished expansion of the user's own conclusion;
- an “A is actually B” relabeling with no new causal content;
- a generic trait such as perfectionism, sensitivity, ambition, attachment, or fear of loss without a specific mechanism;
- a flattering biography or inventory of remembered events;
- an unfalsifiable psychological story;
- an explanation with no consequence for action;
- recycled from an earlier result without material new evidence.

## Apply the five gates

Choose at most two insights. Prefer one strong insight. Require every selected insight to pass all five gates:

1. **Novelty:** The conclusion is not already explicit in the user's framing or recent discussion.
2. **Compression:** One mechanism explains at least three observations.
3. **Prediction:** The mechanism implies a future or unseen behavior that could be checked.
4. **Leverage:** The insight enables a concrete rule, experiment, metric, or decision change.
5. **Falsifiability:** There is evidence that would weaken or disprove the mechanism.

Discard any candidate that fails a gate. Do not lower the standard merely to produce an answer.

## Write the result

Lead with the claim in plain language. Then include only what establishes and operationalizes it:

- the hidden mechanism;
- the cross-context evidence;
- one non-obvious prediction;
- one immediately usable lever;
- a brief falsifier and confidence level.

Avoid therapeutic filler, excessive reassurance, motivational padding, and repeated contrast formulas. Do not merely explain why the user feels something. Aim to change what they notice or do next.

When no candidate passes all five gates, say plainly that the available evidence does not support a worthwhile new insight. In Chinese scheduled mode, use: “本周期没有发现达到认知盈余标准的新洞察。”

## Run longitudinal reviews

Treat periodic runs as longitudinal research rather than a content quota.

- Compare new behavior with previous hypotheses.
- Strengthen, weaken, revise, or retire earlier insights.
- Track whether prior predictions and experiments held.
- Do not repeat an insight without material new evidence.

## Protect epistemic and personal boundaries

- Present mechanisms as hypotheses, not hidden truths about the user.
- Never use confidence, intimacy, or access to history as a substitute for evidence.
- Do not expose private source material that is unnecessary to explain the conclusion.
- Distinguish “insufficient evidence” from “the user has no blind spots.”

## Use bundled references

- Read `references/examples.md` when calibrating output quality or comparing strong and weak answers.
- Read `references/evaluation.md` when testing, reviewing, or improving this skill.

## Final quality gate

Before answering, ask: “What decision could the user make differently because of this?” If there is no specific answer, continue reasoning or report that no strong insight was found.
