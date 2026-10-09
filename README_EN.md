# Fresh Angle · 认知盈余

> **Not an echo. A fresh angle.**

Fresh Angle is an agent skill for producing personal insights with actual information gain.

Many AI “insights” simply restate what the user already said in more polished language. Fresh Angle rejects elegant echoes, generic personality labels, flattering summaries, and unfalsifiable stories.

Every accepted insight must pass five gates:

1. **Novelty:** add a conclusion the user has not already stated;
2. **Compression:** explain at least three observations with one mechanism;
3. **Prediction:** imply a specific, checkable behavior;
4. **Leverage:** change a decision, rule, experiment, or metric;
5. **Falsifiability:** name evidence that would weaken the claim.

If no candidate passes all five gates, the agent should say that the evidence does not support a worthwhile new insight.

## Use it for

- finding a mechanism you have not already named;
- detecting patterns across situations or time;
- distinguishing similar-looking problems that require different decisions;
- revisiting earlier hypotheses as new evidence arrives;
- preventing polished paraphrase from being presented as understanding.

Fresh Angle is not a diagnostic tool and does not claim privileged access to hidden truths. Its outputs are evidence-grounded hypotheses that should remain testable and revisable.

## Install and use

Copy [`skills/fresh-angle`](skills/fresh-angle) into the skills directory of an agent that supports `SKILL.md`, or provide [`SKILL.md`](skills/fresh-angle/SKILL.md) directly to your agent.

Example prompt:

```text
Use Fresh Angle to find one genuinely new, evidence-grounded insight.
Do not paraphrase me. Include a prediction, a decision lever, and a falsifier.
Say so plainly if the evidence is insufficient.
```

## License

[MIT](LICENSE)
