# Plain-Language Method

The author's plain-language explanation is the core of this skill. Do not treat it as a formality.

## Default Request

When the user submits a passage without plain-language intent, ask them to fill a table:

| 段落 | 这一段到底想让读者明白什么 | 上一段后读者可能会问什么 | 本段是在回答/排除误解/补充材料/转入下一步 | 最重要的一句话 | 材料或脚注用来证明什么 | 一句普通话怎么说 | 段尾要把读者带向哪里 |
|---|---|---|---|---|---|---|---|
| 第1段 |  |  |  |  |  |  |  |

Explain that the skill pauses before polishing because the goal is to preserve the author's real intention.

## Questions To Ask

- 这一段我到底想让读者明白什么？
- 上一段说完后，读者可能会问什么？
- 这一段是在回答问题、排除误解，还是补充材料？
- 这一段中最重要的一句话是什么？
- 这一段中的案例、文献、规范或脚注是用来证明什么的？
- 如果要用一句很普通的话向同学解释这一段，我会怎么说？
- 这一段最后要把读者带向哪里？

## Evaluate The Plain-Language Explanation

Check whether:

- it is clearer than the original;
- it names a concrete legal task;
- it matches the original paragraph;
- it exposes a missing bridge in the original;
- it includes a key logic that the original has not actually stated;
- it is too broad to guide rewriting.

## When Plain Language Is Clear

Compare it with the original:

- Core meaning present in original?
- Reader transition present?
- Material use explained?
- Judgment strength preserved?
- Any unnecessary concept packaging?
- Any simple idea made needlessly complex?

Then give diagnosis and local expression references.

## When Plain Language Is Vague

Do not rewrite yet. Say what is unclear and ask a targeted question.

Common vague answers:

- "说明制度存在问题" - ask: what problem, for whom, under which rule?
- "体现理论意义" - ask: which legal concept or doctrinal relation changes?
- "承接上文" - ask: what exact question from the previous paragraph is being answered?
- "证明我的观点" - ask: which sentence is the view, and what does the material prove?

## When Plain Language Conflicts With Original

Point out the mismatch:

- The user says the paragraph is about A, but the original mainly argues B.
- The user says the material proves a rule, but the original uses it as background.
- The user says the conclusion is tentative, but the original writes it as certain.

Offer 2-3 possible understandings and ask the author to confirm before rewriting.

## Provisional Diagnosis

If the user asks the agent to diagnose before they provide plain language, it is allowed to infer temporary paragraph intent from the original. Always mark:

"这是基于原文推测的临时理解，需作者确认。"

Do not treat that inferred intent as the author's true intention. Do not use it to generate a final rewrite unless the user confirms it.
