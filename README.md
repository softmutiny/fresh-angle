# 认知盈余 · Fresh Angle

> **Not an echo. A fresh angle.**  
> **不是回声，是新的角度。**

一个要求 AI 产出真正信息增量的个人洞察 Skill。

很多所谓的“深度分析”，只是把用户已经说过的话换成更漂亮的措辞：贴一个人格标签，补几句情绪安慰，再用一句像金句的话收尾。读起来很懂你，却没有增加任何可以验证的新东西。

**认知盈余**要求每条洞察同时具备：

1. **新颖性**：不是用户原话的精致复述；
2. **压缩力**：一个机制能够解释至少三个不同观察；
3. **预测力**：能够预测尚未用于推导结论的行为；
4. **行动杠杆**：能改变一个具体决策、规则、实验或指标；
5. **可证伪性**：明确什么证据会削弱或推翻结论。

五项不能全部通过，就宁可说：**没有发现达到标准的新洞察。**

## 它适合做什么

- 寻找自己尚未意识到的行为机制；
- 检查跨情境反复出现的模式；
- 区分两个表面相似、实际需要不同对策的问题；
- 定期回顾旧假设是否被新证据支持；
- 阻止 AI 用漂亮复述、泛化标签和恭维冒充理解。

它不是心理诊断工具，也不声称能够读取人的“隐藏真相”。输出应当被视为有证据、可检验、允许被推翻的假设。

## 使用

将 [`skills/fresh-angle`](skills/fresh-angle) 文件夹复制到支持 `SKILL.md` 的智能体技能目录中，或直接把其中的 [`SKILL.md`](skills/fresh-angle/SKILL.md) 提供给你的智能体。

示例提示词：

```text
请使用认知盈余，结合我提供的多个真实例子，找出一个我尚未明确说出的机制。
必须给出可验证预测、行动杠杆和证伪条件。没有足够强的洞察就直接说没有。
```

```text
Use Fresh Angle to find one genuinely new, evidence-grounded insight.
Do not paraphrase me. Include a prediction, a decision lever, and a falsifier.
```

## 仓库结构

```text
skills/fresh-angle/
├── SKILL.md
├── agents/openai.yaml
└── references/
    ├── examples.md
    └── evaluation.md
```

## 设计原则

- 一条强洞察胜过一串性格标签；
- 证据不足时保持沉默，也是能力；
- 亲密感、表达自信和历史访问权都不能替代证据；
- 洞见的价值不在于“听起来很深”，而在于它能否改变下一次选择。

English documentation: [README_EN.md](README_EN.md)

## License

[MIT](LICENSE)
