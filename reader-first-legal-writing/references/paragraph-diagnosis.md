# Paragraph Diagnosis

Diagnose each natural paragraph before offering expression references.

## Mandatory Checks

- Does the paragraph have one central judgment?
- Does it answer a question naturally left by the previous paragraph?
- Does the opening merely repeat the section title?
- Does each material item have a stated purpose?
- Does the ending only summarize mechanically?
- Are there stacked judgment sentences without analysis?
- Are there stacked connectors without real progression?
- Are there decorative bridge sentences?
- Does the paragraph repeat the conclusion instead of leading the reader toward it?
- Are some sentences formally correct but unlike something a real author would say?
- Does the paragraph need the author's plain-language explanation before diagnosis can continue?

## Function Labels

Use short labels:

- Background: gives the situation needed to understand the legal issue.
- Tension: shows conflict, mismatch, gap, or risk.
- Object limitation: narrows the research object.
- Concept boundary: defines or distinguishes terms.
- Claim: states the paragraph's legal judgment.
- Material entry: introduces norms, cases, literature, data, or facts.
- Analysis: explains why the material matters.
- Objection response: handles likely misunderstanding or alternative view.
- Limitation: controls scope or judgment strength.
- Transition: prepares the next step.

## Diagnosis Output Fields

For each paragraph, provide:

- central judgment;
- paragraph function;
- reader doubt it should answer;
- whether the answer is explicit;
- material and its use;
- unnatural or stiff sentences;
- AI-tone risk;
- what the author needs to clarify in plain language.

## Common Problems

### Multi-center Paragraph

Symptoms: one paragraph defines a concept, cites literature, states a conclusion, and proposes a solution. Ask the user which job the paragraph should do first.

### Title-Restatement Opening

Symptoms: "本部分将讨论..." or a direct paraphrase of the heading. Replace with the reader's question or the reason the section is necessary.

### Material Dump

Symptoms: several cases, norms, or views appear without explanation. Add purpose before material and inference after material.

### Mechanical Ending

Symptoms: "综上可知" followed by a sentence already stated. Instead, end by naming the remaining problem or boundary.

### Judgment Stack

Symptoms: every sentence is a conclusion. Insert reasons, conditions, evidence, or distinctions.

### Connector Stack

Symptoms: connectors imply order but the logic is only a list. Replace with actual relations: cause, contrast, precondition, exception, consequence, or level shift.

### Decorative Bridge

Symptoms: a sentence sounds polished but does not change what the reader knows. Delete it or make it answer a reader doubt.

### Not Like Human Legal Writing

Symptoms: abstract nouns dominate, no actor or rule appears, and the sentence could fit any topic. Ask what the author would say to a classmate in ordinary Chinese.
