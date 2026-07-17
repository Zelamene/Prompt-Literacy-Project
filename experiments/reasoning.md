# Experiment: Reasoning

## Objective

Explore how different prompt structures influence the clarity and completeness of AI-generated explanations for a multi-step reasoning task.

## Prompt Progression

### Initial Prompt

> If a train leaves Cape Town at 8am travelling 100 km/h and another leaves Johannesburg at 10am travelling 120 km/h, which arrives first in Bloemfontein?

### Revised Prompt

> Solve the following problem step by step: (same problem).

### Improved Prompt

> Solve the following travel problem. Explain your solution step by step, state any assumptions you make, and present the final answer clearly. (Same problem text.)

### Final Prompt

> You are a maths tutor explaining a relative-speed problem to a first-year university student. Solve the following problem by:
>
> 1. Stating any assumptions.
> 2. Calculating the travel time for Train A.
> 3. Calculating the travel time for Train B.
> 4. Comparing the results and stating the conclusion.
>
> After completing the solution, explain how the answer could be checked or verified. (Same problem text.)

## Analysis

The initial prompt asks for a correct answer but provides little guidance on how the response should be presented. As additional instructions are included, the prompt becomes more structured by specifying:

* the role of the AI (a maths tutor);
* the intended audience (a first-year university student);
* the organisation of the response; and
* the inclusion of assumptions and a verification step.

These additions encourage a response that is easier to follow and more suitable for learning, rather than simply providing a final answer.

## Key Findings

For problems involving multiple steps, prompts that specify the audience, structure, and level of explanation generally produce responses that are easier to understand and evaluate. Including assumptions and a method for checking the answer can also help users assess the reliability of the solution.

## Takeaway

When asking AI to solve a multi-step problem, clearly specify the level of explanation, the intended audience, and the structure of the response. If appropriate, ask the AI to identify any assumptions and explain how the final answer can be verified.

## Survey Connection

Several participants in the EMZAMS AI survey reported using AI to check answers or explain difficult concepts. This experiment illustrates how structured prompts can encourage explanations that are easier to review and evaluate, rather than relying only on the final answer.
