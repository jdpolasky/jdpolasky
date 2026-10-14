# The system that became its own project

*What building my own AI system taught me about adding AI to a business.*

In the spring of 2026 I built an AI chief of staff to run my own work. It kept my calendar, my commitments, and my rules for how I like to work, and it gave me a brief every morning. I published a starter version, people used it, and I used mine every day.

Then I kept adding to it. Memory tiers. Hooks on every step of a session. Scheduled jobs that ran before I woke up. Dashboards. Logs. Every addition made sense on the day I made it. By summer my private build was over five thousand files.

It broke quietly. Jobs failed and nothing told me. Once I found a scheduled morning brief that had been failing for eleven days. I was spending more time fixing the system than using it. It was supposed to help me run my work, and it had become a second job.

In July 2026 I tore it down and rebuilt it around one rule: cut first. Everything that matters lives in plain files a person can open and read. Anything that breaks and nobody misses gets retired instead of watched. Every job I kept shows a sign that it ran, so a failure can't hide. The new version, [chief-of-staff-2](https://github.com/jdpolasky/chief-of-staff-2), is about 35 files. It does more for me than the five-thousand-file version did.

## What this means for a business

The same thing can happen to a business starting on AI. A tool gets added for email, another for scheduling, another for reports. Each one looks like a win on the day it's bought. A year later nobody knows what's connected to what, a few things fail quietly every week, and someone on the team spends half their time keeping it all running.

So here's how I work now, with my own system and with a business:

- **Start with the business.** If a process is broken, AI makes it break faster. Fix the bottleneck first, then decide where AI helps.
- **Cut before you add.** Most operations have tools, reports, and steps that nobody would miss. Retiring them is the cheapest improvement there is.
- **Every recurring job shows that it ran.** If nobody can tell whether it worked this morning, it's a liability.
- **Keep it readable.** The owner should be able to open a file and see what the system knows about the business.

That's what I mean by business first, then AI. If you want help figuring out where AI fits in your business, [here's how I work](HOW-I-WORK.md).

*Joshua Polasky, October 2026*
