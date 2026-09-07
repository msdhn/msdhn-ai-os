# AIS-OS Intake

This is the source-of-truth file for your AIOS. Fill it in by typing, voice-pasting (Wispr Flow / OS dictation), or running `/onboard` for a guided conversation. Whichever mode, this file is what `/onboard` reads to scaffold your Day-1 setup.

**Hard cap: 7 questions.** Each answerable in under 60 seconds. Don't overthink — you can edit and re-run `/onboard` any time.

---

## Q1 — Who are you, what do you sell, who do you sell it to?

Identity, offer, ICP. One paragraph each is fine.

```
I'm an experienced cloud, data, and AI platform engineer with a strong background in
enterprise architecture, software engineering, MLOps, and building scalable platforms in
regulated environments such as banking.

Alongside my full-time role, I'm building a personal AI consulting practice focused on
helping organizations adopt AI in a practical, secure, and production-ready way. Services:
AI and GenAI strategy, AI platform architecture, enterprise AI integration, agentic AI
solutions, MLOps/LLMOps, cloud-native AI platforms, and technical advisory.

Target clients are primarily small and medium-sized companies, startups, and enterprise
teams that want to use AI but need help moving from experimentation and proofs of concept
to reliable production systems. Especially organizations that already have cloud, data, or
software platforms and want to integrate AI into their products, internal workflows, or
engineering processes.

Positioning: less about building chatbots, more about helping businesses design the
underlying architecture, platforms, governance, integrations, and engineering practices
required to make AI genuinely useful and sustainable.
```

---

## Q2 — Paste 1-2 things you've written recently. Don't edit them.

An email, a LinkedIn post, a DM, a doc — anything that sounds like you when you're not trying. **Paste verbatim.** Do not type these mid-conversation with Claude — chat-shaped samples are worse than no samples (voice contamination).

```
Sample 1 — LinkedIn post

Today I explored LangChain4j and started building a hands-on understanding of how
LLM-powered applications can be integrated into Java ecosystems.
What stood out:
• Seamless integration with Spring Boot
• Built-in support for chat memory and conversational context
• Interface-based AI services for LLM interactions
• Tool calling to integrate with external systems
• Structured outputs and validation for safer AI interactions
• Pluggable support for multiple LLM providers
Great to see the Java ecosystem evolving towards enterprise-grade AI applications.
```

```
Sample 2 — Email to a colleague

Hi Alex,

Can we check the recent production data for drift against the training dataset, especially
for the key features?

It would also be good to confirm whether this is affecting model performance before
considering retraining.

Thanks,
```

---

## Q3 — What are your 2-3 biggest priorities for the next 90 days?

Quarterly priorities. Not yearly aspirations. Things that, if not done by July, would make you say "I wasted Q2."

```
1. Define the offer — By September 30, publish a one-page AI consulting service menu with
   3 clearly defined services, target client, problem solved, typical deliverables, and a
   simple starting price or engagement model. Done when the one-pager is live and can be
   sent directly to a prospective client.

2. Build credibility and create opportunities — By December 6: publish 8 substantive
   LinkedIn posts (enterprise AI, GenAI architecture, AI platforms, agentic AI,
   MLOps/LLMOps); have 12 conversations with potential clients or introducers; secure at
   least one paid consulting engagement (assessment, workshop, or advisory is fine). Done
   when 8 posts published, 12 conversations completed, 1 paying client secured.

3. Build a repeatable consulting system — By December 6, create and use these three
   workflows end-to-end at least once each:
   - Lead -> Discovery -> Proposal: capture a lead, prep the discovery call, document the
     problem, generate a professional proposal.
   - AI Architecture Assessment: collect client current-state, identify gaps, evaluate
     options, produce an architecture/recommendation document.
   - Knowledge -> Content: turn technical notes, research, or project experience into a
     LinkedIn post or client-facing insight using the AI OS.
   Done when all three exist inside the AI OS and each has run end-to-end at least once.
```

---

## Q4 — Where does revenue actually land, and where is it tracked?

Multiple answers OK. Stripe? Skool? GoHighLevel? QuickBooks? A spreadsheet?

```
QuickBooks — invoicing and tracking invoiced vs. paid. (Consulting practice is
pre-revenue; QuickBooks is the chosen system of record.)
```

---

## Q5 — Where do you talk to customers, your team, and the outside world day-to-day?

Email (which one — Gmail / Outlook)? Slack? Teams? DMs (Skool / Discord / iMessage)? Phone?

```
Outlook email + LinkedIn DMs. Client and prospect conversations happen in both. LinkedIn
is also the primary channel for posting and building credibility.
```

---

## Q6 — Where do meeting recordings, notes, and important docs live?

Granola? Otter? Fireflies? Google Drive? Notion? Dropbox? A folder on your desktop you keep meaning to organize?

```
OneDrive — docs, notes, and research. No dedicated meeting-recording/transcription tool
yet. This AI OS repo is the working second brain.
```

---

## Q7 — What's the one task that eats your week, and where do you currently track work?

The single biggest time-suck or recurring drudgery. Plus where tasks/projects live (ClickUp / Asana / Linear / Notion / a notebook).

```
Biggest time-suck: keeping up with AI tooling and news — the field moves fast and staying
current eats time without a system for it.

Tasks/projects tracked in: Microsoft To Do.

(Consulting practice is just starting — workflows and volume are still forming.)
```

---

When this file is filled, run `/onboard` (or re-run it) and the wizard will scaffold your Day-1 file set: `context/`, `references/voice.md`, populated `connections.md`, and a filled `CLAUDE.md`.
