# The system that became its own project

In early 2026 I built an AI chief of staff to run my own work. It kept my calendar, my commitments, and my rules for how I like to work, and it gave me a brief every morning. In the spring I published a starter version. People starred it and forked it, and I used mine every day.

Then I kept adding to it. Memory tiers. Hooks on every step of a session. Scheduled jobs that ran before I woke up. Dashboards. Logs. Every addition made sense when I added it. By July my private build was over five thousand files.

It broke quietly. Jobs failed and nothing told me. Once I found a scheduled job that had been dead for eleven days. I was starting my mornings by fixing the machine. It had become a second job.

In July 2026 I tore it down and rebuilt it, starting by cutting everything I wouldn't miss. Everything that matters now lives in plain files a person can open and read. If something breaks and nobody misses it, I archive it instead of adding monitoring. Every job I kept shows when it last ran, so I can see a failure. The public version, [chief-of-staff-2](https://github.com/jdpolasky/chief-of-staff-2), is about 35 files, and my own system runs leaner and more efficiently than the five-thousand-file version ever did.

## The same thing happens in a business

A business starting on AI can drift the same way. A tool gets added for email, another for scheduling, another for reports. Each one looks like a win when it's bought. A year later nobody knows what's connected to what, some things fail without anyone noticing, and someone on the team is busy keeping it all running.

So here's how I work now, with my own system and with a business. I start with the business, because AI makes a broken process break faster. I cut before I add: most operations have tools, reports, and steps nobody would miss, and retiring them makes the rest easier to run. I want every recurring job to show that it ran, because if nobody can tell whether a job worked this morning, nobody will know when it breaks. And the owner should be able to open a file and see what the system knows about the business.

If you want help figuring out where AI fits in your business, [here's how I work](HOW-I-WORK.md).

*Joshua Polasky, October 2026*
