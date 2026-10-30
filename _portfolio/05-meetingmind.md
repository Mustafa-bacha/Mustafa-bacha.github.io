---
title: "MeetingMind — AI Meeting-to-Action Pipeline"
excerpt: "Transforms messy meeting transcripts into structured decisions, action items, and open questions with confidence scoring and human-in-the-loop escalation. LLaMA 3.3 70B (Groq), Next.js 14, deployed on Vercel."
collection: portfolio
---

MeetingMind converts raw transcripts into ready-to-send Slack/email digests:

* **LLM-powered extraction** of decisions, action items, and open questions (LLaMA 3.3 70B via Groq).
* **Confidence scoring** on every extracted item.
* **Human-in-the-loop escalation** for low-confidence or conflicting outputs — the design lesson: reliable AI systems know when to ask for review.
* Slack-ready summaries and HTML email digests; built with Next.js 14.

[Live demo](https://meetingmind-two-flame.vercel.app) · [Code on GitHub](https://github.com/Mustafa-bacha/meetingmind)
