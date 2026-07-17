# Example: Excellent Prompt (CLEAR Framework)

## Prompt

You are a computer science tutor helping a second-year university student who understands loops, functions, and basic data structures but has never studied AI.

Explain the difference between machine learning and traditional programming using the following structure:

1. One-sentence definition of each approach.
2. A simple analogy (not a technical one—use something from everyday life).
3. One concrete code-like example of each approach solving the same problem (for example, recognising handwritten digits).
4. A table comparing the two approaches across three dimensions:
   - How the solution is created
   - How it handles new data
   - When each approach is better
5. One common misconception about machine learning that beginners often have.

Write in clear, conversational English. Do not use jargon without defining it. Keep the total response between **400 and 500 words**.

After your explanation, add a one-sentence summary that a student could use to explain the difference to a friend.

---

## AI Output (from ChatGPT)

> **1. One-sentence definitions**
>
> **Traditional programming:** A programmer writes explicit instructions (rules) that tell the computer exactly how to solve a problem.
>
> **Machine learning:** A computer learns patterns from examples (data) so it can make predictions or decisions without being given every rule directly.
>
> **2. A simple analogy**
>
> Imagine teaching someone to sort fruit. With traditional programming, you hand them a checklist: "If it is round and orange, put it with the oranges. If it is long and yellow, put it with the bananas." They can only follow the rules you wrote. With machine learning, you show them hundreds of examples of correctly sorted fruit. Over time, they notice the patterns themselves and can sort new fruit, even if it looks slightly different from the examples they have seen before.
>
> **3. Code-like example: Recognising handwritten digits**
>
> Suppose we want a computer to recognise whether a handwritten image is the digit **7**.
>
> **Traditional programming:**
>
> ```
> function isSeven(image):
>     if has_horizontal_top(image) and has_diagonal_line(image) and not has_closed_loop(image):
>         return true
>     else:
>         return false
> ```
>
> **Machine learning:**
>
> ```
> training_data = many_images_with_correct_labels()
> model = train(training_data)
> prediction = model.predict(new_image)
> ```
>
> Instead of writing rules, we provide many labelled examples (images with the correct digit). During training (the process of learning from data), the model discovers patterns that help it recognise new handwritten digits.
>
> **4. Comparison table**
>
> | Aspect | Traditional Programming | Machine Learning |
> |--------|-------------------------|------------------|
> | How the solution is created | The programmer writes the rules step by step. | The algorithm learns patterns from training data. |
> | How it handles new data | Works well only if the new data fits the programmed rules. Unexpected cases usually require updating the code. | Uses learned patterns to make predictions on new data, even when examples are not identical to the training data. |
> | When it is better | Best when the rules are clear and predictable, such as calculating tax or sorting numbers. | Best when the rules are too complex to write by hand, such as recognising handwriting, speech, or faces. |
>
> **5. A common misconception**
>
> A common misconception is that machine learning "thinks" like a human. In reality, it does not understand ideas or reason in the same way people do. It identifies statistical patterns in data and uses those patterns to make predictions. If the training data is poor or incomplete, the model can make incorrect predictions even if it performed well during training.
>
> **One-sentence summary:** Traditional programming solves problems by following rules written by a programmer, while machine learning solves problems by learning those rules from examples in data.

---

## Analysis

### Why this prompt works well (CLEAR applied)

- **Context:** The model is given a clear role ("a CS tutor") and a specific student profile ("a second-year student who understands loops but not AI"). This allows the explanation to build on the learner's existing knowledge and makes the response feel more like a guided tutoring session.

- **Limitations:** Instructions such as "do not use jargon without defining it," "write between 400 and 500 words," and "use clear, conversational English" help keep the explanation focused and accessible. These constraints reduce the likelihood of the response becoming unnecessarily technical or overly detailed.

- **Examples:** The prompt explicitly requests an analogy and code-like examples. These concrete examples help connect abstract concepts to familiar ideas, making the explanation easier to understand.

- **Audience:** Rather than simply requesting an explanation for "a student," the prompt identifies the learner's background knowledge. This allows the model to skip concepts the student already understands (such as loops) and focus on the comparison between traditional programming and machine learning.

- **Requirements:** The prompt specifies the exact structure of the response, including one-sentence definitions, an analogy, a code example, a comparison table, a common misconception, and a summary. Providing these expectations reduces the need for the model to infer what the user wants and generally results in a more organised and targeted response.

### What this experiment demonstrates

- **Consistency:** Clearly structured prompts are more likely to produce responses that follow a similar structure and address the requested topics. While different AI models—or even repeated responses from the same model—may vary in wording, examples, or emphasis, the overall organisation tends to remain more consistent.

- **Self-review:** The prompt requests a one-sentence summary at the end. Reviewing this summary gives the learner a quick way to check whether the main idea matches the rest of the explanation. Although this does not verify factual accuracy, it encourages the learner to reflect on whether the response addressed the original question.

- **Organisation:** By requesting specific sections—definitions, an analogy, code examples, a comparison table, a misconception, and a summary—the prompt produces a response that is easier to navigate than a single block of text. The learner can quickly locate the information they need without reading the entire response.

### Survey Connection

Participants in the EMZAMS AI survey reported using AI to explain difficult concepts, while some also described responses as being too generic or not addressing what they wanted to learn. This example illustrates how providing clear context, identifying the audience, and specifying the desired structure can help produce responses that are more focused on a learner's needs.