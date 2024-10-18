---
title: 'Refusal Breaker'
---

## Purpose
The Refusal Breaker pattern helps rephrase prompts in ways that avoid AI refusals or restrictions. This is useful when the AI declines to respond due to content policies or unclear prompts.

## How it Works
If the AI refuses to respond to a prompt, modify the phrasing or context to encourage a more cooperative reply. This can involve softening the language or reframing the question.

## Example
- **Prompt**: “Explain why my previous request was refused and suggest alternative phrasing.”
- **AI Response**: Offers insights into why the request was declined and suggests rephrasing to gain a response.

## How to Use
1. **Identify the Refusal**: Note the AI’s reason for refusing the initial prompt.
2. **Rephrase or Reframe**: Adjust the language or context to address the reason for refusal.
3. **Test the New Prompt**: Submit the rephrased prompt and evaluate the AI’s response.

## Practical Tips
- **Be Specific with Requests**: Avoid vague prompts that might trigger refusals due to ambiguity.
- **Use Neutral Language**: Reframe prompts with neutral or positive language to avoid content restrictions.
- **Provide Context**: Sometimes adding context can help the AI understand the prompt better.

## Watch Outs
- **Content Policy Limits**: Be aware of the AI’s content policies, as some refusals cannot be circumvented.
- **Unintentional Misleading**: Rephrasing should maintain the original intent without misleading the AI.
- **Response Quality**: Reframing might lead to less precise answers, so review carefully.

## Creative Use Cases
- **For Educators**: Rephrase prompts to avoid refusals when discussing sensitive topics.
- **For Content Creators**: Overcome content restrictions when exploring controversial subjects.

## Related Patterns
- **[Question Refinement]({{< relref "/docs/patterns/question-refinement.md" >}})**: Use Question Refinement to improve rephrased prompts.
- **[Context Manager]({{< relref "/docs/patterns/context-manager.md" >}})**: Combine with Context Manager to provide background that may prevent refusals.

## Sources
- [A Prompt Pattern Catalog to Enhance Prompt Engineering with ChatGPT](https://arxiv.org/pdf/2302.11382)