Attention
GAN
Autoregresive
MOE
Mamba
Autogen





# TODO
Project 3: Meeting notes → action items pipeline — lighter, faster

Total effort: ~8-12 hours spread over the project
Simpler because it's mostly single-pass text processing — no real back-and-forth conversation loops needed between agents
Breakdown:
AutoGen basics + setup: 2-3 hrs
Building the 3 agents (extract decisions → extract action items → draft email): 3-4 hrs
Testing with sample transcripts, fixing prompt issues: 2-3 hrs
Polish (maybe add Slack/email push): 2-3 hrs

Project 2: Invoice/email triage system — more effort, more depth

Total effort: ~15-20 hours
More complex because it needs human-in-the-loop handling, structured data extraction (dates/amounts need parsing logic, maybe regex or a schema), and realistic categorization logic
Breakdown:
AutoGen basics + setup: 2-3 hrs
Classifier agent + testing categories: 3-4 hrs
Data extractor (structured output, handling messy invoice text): 4-5 hrs
Responder + human-in-the-loop flow (the actual AutoGen differentiator): 4-5 hrs
Testing with varied sample data, debugging edge cases: 3-4 hrs

Given your 3-week light-effort constraint, here's how I'd sequence it:

If you can only do maybe 30-45 min/day for 3 weeks (roughly 10-15 hrs total), that's a perfect fit for Project 3 first. You'll finish it comfortably, have something demoable, and build AutoGen fundamentals without pressure.

Then when you have more time freed up, move to Project 2 — you'll already know AutoGen's patterns, so the extra complexity (structured extraction + human-in-loop) will go faster than the raw hour estimate suggests, maybe 12-15 hrs instead of 20 since you're not learning the framework from scratch anymore.

That sequencing also tells a nice story in interviews: "I built a simple pipeline first, then a more complex human-in-the-loop system" shows deliberate skill progression rather than one isolated project.

Want me to break Project 3 into a day-by-day 3-week micro-plan (like 20-30 min tasks) so it fits your daily bandwidth?