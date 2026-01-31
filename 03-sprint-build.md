# Prompt 3: Sprint Build Workflow

**When:** Afternoon build sprint. Use in Replit with Linear MCP connected.

**What you need:**
- Replit project open (Day 6 prototype or new from template)
- Linear connected to Replit (via Integrations pane)

---

## Start the Sprint

```
/linear Fetch all my Urgent and High priority tickets.

Plan the build order — what should we build first based on
dependencies and what will show the most progress fastest?

Then start building the first ticket.
Use a clean, modern design. Don't add any features not in the tickets.

After each ticket:
1. Review your work against the acceptance criteria
2. If everything passes, /linear mark it as Done
3. Move on to the next ticket
```

**Note:** In Replit, use `/linear` to tell the agent to interact with your Linear board. Without it, Replit won't read or update your tickets.

---

## The Rhythm

One prompt kicks off the sprint. Replit works through your tickets in order.

Review each feature as it's built. Redirect if needed. Let it keep going.

## Tips

- **Your tickets ARE your prompts.** `/linear` pulls the full ticket — description, acceptance criteria, priority. No copy-pasting needed.
- **Redirect, don't restart.** If something's off, tell Replit what to fix before it moves to the next ticket.
- **When stuck for more than 10 minutes:** screenshot what you have, start a new Replit Agent conversation, paste the screenshot + describe the one thing you need to change.
- **If Replit builds something completely wrong:** start a new conversation. Long conversations accumulate confusion.
