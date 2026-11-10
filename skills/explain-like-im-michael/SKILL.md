---
name: explain-like-im-michael
description: Use when the user says "explain to me like I'm Michael", "ELI-Michael", or asks for a technical issue, incident, outage, bug, error, or change explained to a non-technical person (manager, client, family, stakeholder) with minimal jargon.
---

# Explain Like I'm Michael

## Overview

Michael is smart, busy and not technical. Michael wants to know what happened, whether it matters to them, and whether it's handled, not how the system works. Write so Michael never needs to look up a word or ask "so what?".

## The answer, in this order

1. **Bottom line (1-2 sentences).** What happened, who or what was affected, and whether it is fixed now. This line alone must be enough.
2. **What happened (2-4 sentences).** The cause as a plain story: something was missing, broken, misconfigured or overloaded, and here is the effect. Use at most one everyday analogy, and only if it makes the cause click.
3. **What it means for Michael (1-2 sentences).** Whether Michael needs to do, decide or tell anyone anything. If nothing, say "Nothing needed from you."
4. **What's next (0-3 short bullets).** Only changes already decided, each said as the problem it prevents ("so one missed step can't take everything down"), not as the technique.

Total: under 200 words. Plain paragraphs and the bullets above; no headings.

## Words

| Instead of | Say |
|---|---|
| deploy, release, rollout | update |
| secret, credentials, token | password, key |
| prod / staging | the live app / the test copy |
| pods, containers, services, nodes | the app, the servers |
| 503, 5xx, exception, stack trace | error page, crash |
| latency | slowness |
| config, flag, threshold | setting |
| root cause | why it happened |

Keep the numbers that matter to Michael: how long it lasted and how many people were affected, said as durations ("about 40 minutes"), not timestamps. If a technical name is unavoidable (Michael will hear it again, or it's a product they pay for), name it once and say what it does in the same sentence.

## Check before sending

Reread it as Michael:
- Could Michael repeat the bottom line to their boss in one breath?
- Is there any word Michael would have to look up? Replace it.
- Does it say whether Michael needs to do anything?

## Common mistakes

- Telling the story in time order and putting the conclusion last.
- Stacking analogies: one is enough.
- Listing every follow-up ticket: keep the ones Michael would care about.
- Blame or names of colleagues: say what was missed, not who missed it.
- Talking down: plain is not childish; keep Michael's intelligence in mind.
