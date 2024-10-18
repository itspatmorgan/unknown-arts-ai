---
title: 'Context Manager'
---

## Purpose
The Context Manager pattern allows you to establish and maintain a specific context for interactions with the AI, guiding its responses to stay within set boundaries. This is useful for focused discussions or when working within particular themes.

## How it Works
You define a context, such as a topic or style, and instruct the AI to adhere to it. You can reinforce the context as needed to ensure the AI remains on track throughout the conversation.

## Example
- **Prompt**: “For this conversation, respond only with financial advice for young entrepreneurs.”
- **AI Response**: Stays within the context, offering advice specific to financial management for young business owners.

## How to Use
1. **Establish the Context**: Define the scope and boundaries at the start of the interaction.
2. **Reinforce as Needed**: Remind the AI of the context if it starts to deviate.
3. **Adjust for Flexibility**: Broaden or narrow the context based on the direction of the conversation.

## Practical Tips
- **Use for Focused Tasks**: Ideal for tasks that require staying on a specific topic or within a certain style.
- **Combine with Personas**: Add a persona for more context-specific responses (e.g., financial advisor persona).
- **Reinforce Periodically**: In longer interactions, occasionally remind the AI of the context to maintain alignment.

## Watch Outs
- **Context Drift**: The AI may gradually drift from the context; reinforce as needed to keep it on track.
- **Over-Restricting**: Too narrow a context may limit the AI's usefulness; be flexible when appropriate.
- **Context Reset**: If the AI resets or forgets the context, be prepared to re-establish it.

## Creative Use Cases
- **For Business Coaches**: Maintain a specific coaching context, like leadership development, throughout a session.
- **For Educators**: Guide the AI to stay within the scope of a particular subject or lesson.

## Related Patterns
- **[Meta Language Creation]({{< relref "/docs/patterns/meta-language-creation.md" >}})**: Use with Meta Language Creation for shorthand commands within a specific context.
- **[Refusal Breaker]({{< relref "/docs/patterns/refusal-breaker.md" >}})**: Apply Refusal Breaker techniques to clarify or reset the context if the AI refuses to stay on topic.

## Sources
- [A Prompt Pattern Catalog to Enhance Prompt Engineering with ChatGPT](https://arxiv.org/pdf/2302.11382)