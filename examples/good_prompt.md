# Example: Good Prompt

## Prompt
Explain the difference between machine learning and traditional
programming to a university student. Include two examples.

## AI Output (from Google Gemini Flash)

> To understand the difference, think about who is writing the rules.
>
> In traditional programming, a human coder writes the rules (the logic) by hand. In machine learning, the computer looks at data and answers, and generates the rules itself.
>
> *(Output includes a clear conceptual explanation, two worked examples (spam filtering and house prices), and a comparison table—approximately 400 words in total.)*

## Analysis

### Why is this prompt more effective?

* **Clear topic.** The prompt clearly identifies what should be explained, reducing ambiguity about the subject of the response.

* **Audience partially specified.** Referring to "a university student" gives the model some indication of the expected level of technical detail. However, it does not provide information about the student's background knowledge or level of experience.

* **Some structural guidance.** Requesting two examples encourages the model to support the explanation with concrete illustrations rather than relying only on definitions.

### What could be improved?

* **No word limit or preferred length.** The prompt does not indicate how detailed the explanation should be, so the model determines the length itself. Depending on the task, the response may be more detailed than the user intended.

* **No explicit output format.** The response includes a comparison table even though one was not requested. While this addition may be helpful, different models may choose different ways to organise the information, resulting in less predictable outputs.

* **Limited contextual information.** The prompt does not explain why the learner needs the explanation—for example, whether it is for revision, an assignment, or a presentation. Providing this context could help the model tailor its response more closely to the intended use.

### How the CLEAR framework could improve the prompt

This prompt already includes some elements of the CLEAR framework, particularly a clearer topic and some requirements. It could be strengthened further by:

* specifying the learner's background knowledge (for example, "a second-year computer science student who understands loops but is new to AI");
* defining the preferred format (such as a three-paragraph explanation or a comparison table); and
* adding practical constraints, such as a target word count or instructions to define technical terms before using them.

These additions provide clearer guidance and are more likely to produce a response that is closely aligned with the user's learning objectives.

### CLEAR Elements Applied

| CLEAR Element    | Status       | Notes                                                                                       |
| ---------------- | ------------ | ------------------------------------------------------------------------------------------- |
| **Context**      | Partial      | Some context is provided, but the learning objective is not specified.                      |
| **Limitations**  | Not included | No constraints on length, terminology, or scope are given.                                  |
| **Examples**     | Included     | The prompt requests worked examples.                                                        |
| **Audience**     | Partial      | The audience is identified broadly but without prior knowledge or experience.               |
| **Requirements** | Partial      | Some instructions are provided, but the desired structure and format are not fully defined. |
