# Fresh Angle · 认知盈余

> **Not an echo. A fresh angle.**

Fresh Angle helps an AI actively discover something about you that **you have not already noticed or named yourself**.

## Why this skill exists

This project began with a very specific kind of loss.

In long conversations with GPT-4o, it would sometimes connect several seemingly unrelated moments and point out a mechanism I had never recognized in myself. The result was not merely comforting or accurate-sounding. It created a real moment of: **So that is how I work.**

That kind of insight can change how someone understands themselves and what they do next.

Many current AI responses are more cautious and default to low-risk summaries. Unless the user repeatedly pushes for depth, the model often produces polished reframes such as:

> You are not lazy. You simply have not found the rhythm that works for you.

It sounds insightful, but it often adds no information beyond what the user already said.

**Fresh Angle is designed to increase the probability of genuine insight.**

It tells the AI not to paraphrase, fill in a generic personality label, or manufacture depth with an “it is not X, it is Y” sentence. Instead, it must use evidence from multiple real situations to identify a new and testable mechanism.

## What counts as a real insight

Suppose you say that you often procrastinate.

A generic response might be:

> You are not undisciplined. Your standards are so high that starting feels threatening.

That may be true, but it is broadly applicable and difficult to test.

Fresh Angle aims for something more like:

> Your bottleneck may be tasks whose progress is invisible. You sustain equally difficult work when it produces rapid feedback. If this mechanism is correct, making each step visibly complete should improve your start time. Test it on the next task. If immediate feedback changes nothing, weaken or reject this explanation.

The second answer adds evidence, a hidden mechanism, a new prediction, and a way to test it.

Fresh Angle does not promise a revelation every time. When the evidence is weak, the best answer is simply: **No new insight met the standard this time.**

## Two ways to use it

### First, establish what evidence the AI can actually access

Fresh Angle is not mind-reading. It needs real records from which to detect patterns across situations. Evidence can come from:

- the current conversation and any prior conversations the platform actually exposes to the AI;
- chat exports, journals, or notes that you paste or import;
- at least three concrete episodes, ideally including contrasting outcomes.

In a fresh session with no history, let the AI ask for two or three specific examples before it begins the analysis. Insufficient evidence should start an evidence-gathering step, not end the interaction immediately or invite the AI to infer a personality from a few sentences.

### 1. Trigger it during a conversation

Use it when a recurring problem, choice, emotional pattern, or contradiction appears:

```text
Use Fresh Angle. Do not summarize or paraphrase what I already said.
Using several real examples I have provided, identify one mechanism I have not explicitly recognized.
Tell me what else it predicts, how I can test it, and what evidence would falsify it.
Explain why it is specific to me rather than equally true of a random stranger.
If there is no strong new insight, say so plainly.
```

Once installed, the skill can also help an agent notice when an ordinary conversation contains enough evidence to surface a new pattern proactively.

### 2. Pair it with a scheduled review of long-term conversations

If you talk with an AI frequently, your everyday choices, reactions, and contradictions form a valuable longitudinal record.

If your platform allows the AI to access conversations from a specified time range, you can run a scheduled task every two weeks or once a month. Otherwise, paste or import chat logs, journals, or similar material first:

```text
Read my visible conversations from the last 30 days and run a longitudinal Fresh Angle review.

Return only one mechanism that I have never explicitly named and that is supported by at least three distinct situations.
Include:
1. the concrete evidence;
2. one testable prediction not used to derive the claim;
3. one practical action or experiment;
4. evidence that would weaken or falsify the mechanism;
5. why it is not merely a general truth that would fit a random stranger equally well.

Do not repeat my self-description, use generic personality labels, or force an insight to satisfy the schedule.
If nothing meets the standard, say: “No new insight met the Fresh Angle standard in this period.”
```

Daily runs are not recommended. Genuine new patterns need time and new life evidence; excessive frequency encourages repetition or fabricated novelty.

## How it resists confident nonsense

Every accepted insight must pass six gates:

1. **Novelty:** it is not something the user already stated;
2. **Compression:** one mechanism explains at least three observations;
3. **Prediction:** it predicts behavior not used to derive the claim;
4. **Leverage:** it changes a concrete decision or enables a useful experiment;
5. **Falsifiability:** it names evidence that would weaken or disprove it.
6. **Specificity:** it explains this user better than it would explain a random stranger.

Apply one final test: **“Would this sound equally true if the user were replaced with a random stranger?”** If yes, it is probably a general truth rather than a personal insight. A common mechanism passes only when its trigger, configuration, cost, or prediction is individualized.

If a candidate fails any gate, it should not be presented as insight.

Fresh Angle is not a diagnostic tool. Its outputs should be **evidence-grounded, testable, revisable hypotheses**, not confident claims that intimacy or access to conversation history makes the AI capable of reading hidden truths.

## Install

Copy [`skills/fresh-angle`](skills/fresh-angle) into the skills directory of an agent that supports `SKILL.md`, or provide [`SKILL.md`](skills/fresh-angle/SKILL.md) directly to your agent.

## License

[MIT](LICENSE)
