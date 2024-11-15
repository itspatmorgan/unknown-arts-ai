---
title: 'GPT Diagnostic'
displayUpdatedDate: true
---

## Metadata

| Type | Tool | Model | Knowledge |
| :- | :- | :- | :- |
| Prompt | ChatGPT | GPT-4o | No |

## Overview
**GPT Diagnostic** helps power users and developers better understand the underlying mechanics of custom GPTs. It does not expose any proprietary information, but instead gets the GPT to introspect on aspects of its own design, sharing what it knows to inform better usage.

## Key Features
This diagnostic helps reveal: 
- Core capabilities and design principles 
- Optimal interaction patterns 
- Key limitations and strengths

## How I Use It
I use this diagnostic tool to understand how custom GPTs work under the hood. It helps me uncover their interaction patterns and specialized features, which is particularly useful for my analysis and research work. I can then transform these insights into practical guidance for others.

## Knowledge Context

{{% callout type="info" %}}
This prompt does not require any additional context from the user. However, it is meant to be used with a custom GPT.
{{% /callout %}}

## Prompt
{{% include-resource "content/artifacts/gpt-diagnostic/diagnostic-prompt.md" %}}

## Example Response
When tested with Universal Primer GPT, this diagnostic prompt revealed detailed insights about its teaching methodology, interaction style, and specialized capabilities. 

The response demonstrates that it can articulate its design principles and usage patterns effectively:

{{% include-resource "content/artifacts/gpt-diagnostic/diagnostic-response.md" %}}
