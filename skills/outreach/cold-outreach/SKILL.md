---
name: cold-outreach
description: Use this skill when drafting cold outbound to a prospect or account — a first-touch email or LinkedIn message that earns a reply. Triggers on "write a cold email", "reach out to this lead", "draft outbound", "first touch", "cold sequence".
author: swan
category: outreach
license: MIT
---

# Cold outreach

Draft first-touch outbound that earns a reply. This skill applies when there's no prior relationship and you're opening a conversation cold. It produces a short, specific message (or a 3–4 step sequence) grounded in the prospect's context and the user's real value proposition.

## Before drafting

- Load the ICP and the relevant persona so the angle matches who you're writing to.
- Pull the company and contact record from the CRM if connected — recent activity, role, any prior touches.
- Check for a recent signal (funding, hiring, a launch, a post, a site visit). A specific reason-to-reach-out beats a generic opener every time.
- Pull the user's sender voice and a few past approved messages. Match their voice, not a generic "sales" tone.

If no ICP or value prop is defined, ask the user for the one-line "who we help and the outcome we drive" before writing — a cold email without it will be generic.

## What makes it land

- **One idea per message.** A cold email earns a reply by being about *them*, not by listing features.
- **Lead with the specific.** Open on the signal or an observation about their world, not "I hope this finds you well."
- **One clear, low-friction ask.** A question they can answer in one line, or interest in a 15-minute look — never "book a 30-minute demo" cold.
- **Short.** Under ~90 words. If it needs scrolling, it's too long.
- **Their language.** Mirror how the prospect's market talks about the problem, pulled from their site, posts, or reviews — not the user's internal jargon.

## What good looks like

A great cold email reads like a specific person noticed a specific thing and had a useful reason to write. The recipient can tell within the first line that it isn't a blast. The value is framed as their outcome ("cut ramp time for new reps"), not the product's feature ("AI-powered onboarding"). The ask is so easy that "yes" or "tell me more" costs nothing.

A mediocre one opens with the sender's company, lists three features, claims to be "the leading platform", and asks for 30 minutes. If the same email could be sent to 500 companies unchanged, it's mediocre — rewrite it until it couldn't.

## If it's a sequence

For a multi-touch sequence, vary the angle across steps — signal-based open, a proof point or customer story, a different persona or a soft breakup — never the same pitch louder each time. Build it with `swan-build-sequence`, set `outreachReasoning` for each step, and keep `sendAutomatically: false` so the user reviews before anything sends.

## MUST / NEVER

- MUST ground the message in a real signal or the prospect's actual context.
- MUST use the user's saved voice and value prop, not an invented one.
- NEVER fabricate a detail about the prospect to sound personalized.
- NEVER send automatically — outreach is reviewed first.
</content>
