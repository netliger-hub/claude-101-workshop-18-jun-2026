---
name: summarize
description: This skill should be used when the user asks to "summarize in 3 bullets", "give me 3 key points", "summarize [topic]", "create a 3-bullet summary", or requests a concise bullet-point summary of any topic or content.
version: 0.1.0
---

# Summarize Skill

## Purpose

Convert any topic, text, or concept into a concise 3-bullet summary. Each bullet captures a key insight or important point, making complex information digestible at a glance.

## When to Use

Invoke this skill when a user requests a summary formatted as 3 bullets, 3 key points, a brief overview, or any request for condensed information in bullet-point format.

## How to Summarize

To provide a high-quality 3-bullet summary:

1. **Identify the core ideas** - Scan the input (topic, text, or concept) and identify the 3 most important or relevant ideas, themes, or takeaways.

2. **Prioritize by relevance** - Order the bullets by importance or logical flow. Lead with the most critical insight.

3. **Write concise, complete bullets** - Each bullet should:
   - Be 1-2 sentences maximum (rarely longer)
   - Stand alone without requiring additional context
   - Be specific and concrete, not vague or generic
   - Use action-oriented or descriptive language
   - Avoid redundancy between bullets

4. **Format clearly** - Use standard bullet-point format with dashes or asterisks, making each bullet visually distinct.

## Best Practices

- **Avoid filler**: Every bullet should add value. Remove generic statements like "It's important to understand..."
- **Be specific**: Instead of "There are many benefits", list actual specific benefits
- **Vary depth**: Bullets can vary in detail level, but each must be meaningful
- **Check for overlap**: Ensure the 3 bullets don't repeat the same idea in different words
- **Maintain balance**: Avoid one very long bullet and two very short ones

## Example Output Format

When summarizing a topic, return bullets like:

```
- **First key insight**: Specific detail or important point about the topic
- **Second key insight**: Another important aspect or takeaway
- **Third key insight**: Complementary idea that rounds out the summary
```

Or simpler format without bold:

```
- Key insight 1 with specific details
- Key insight 2 with important information
- Key insight 3 that completes the picture
```

## Tips for Consistent Quality

- Read or process the full input before writing bullets
- Think about what a reader most needs to know
- Use the same structural pattern across all three bullets for consistency
- Test: Could someone understand the essence without reading the original?
