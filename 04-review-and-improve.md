# Prompt 4: Review & Improve

**When:** After building a feature, before marking it done. Or during demo prep.

Inspired by Zevi Arnovitz's multi-model review workflow (PM @ Meta).

---

## Self-Review

Ask the AI that built the feature to review its own work:

```
Review what you just built for [ticket title].

Check:
1. Does it meet all the acceptance criteria?
2. Does it work on mobile (responsive)?
3. Is there anything broken or half-finished?
4. What would you improve if you had 5 more minutes?

Be honest — don't tell me it's great if it's not.
```

## Cross-Model Review (Advanced)

If you have access to multiple AI tools, have a second model review the first model's work:

```
Here's a screenshot of what I built for [feature].
Here's what it should do: [paste acceptance criteria]

What's wrong with this? What's missing?
Be critical — I want to improve it before my demo.
```

Try this in ChatGPT or Gemini if you built with Claude/Replit.

## Learn From Mistakes

When something goes wrong, don't just fix it — understand why:

```
Something went wrong with [describe the issue].

1. What caused this?
2. What should I have done differently in my prompt?
3. How can I avoid this next time?

Explain it to me like I'm not a developer.
```

---

## Tips

- The self-review prompt is powerful because AI models are better at finding problems than preventing them.
- Cross-model review catches things a single model misses — different models have different blind spots.
- The "learn from mistakes" prompt builds your skills over time, not just your product.
