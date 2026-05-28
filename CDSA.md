# HTB CDSA Review and Experience

<img width="1116" height="791" alt="image" src="https://github.com/user-attachments/assets/8f9e266f-f637-4dcf-82b6-18d443758c50" />


## Introduction

The HTB Certified Defensive Security Analyst (CDSA) was probably the certification that made me enjoy blue team work the most.

Before taking CDSA, I had already spent a few years doing offensive security labs, Hack The Box machines, Active Directory environments, and CTFs while also completing BTL1 beforehand. Because of that, I already understood a lot of attacker techniques from the offensive side.

What CDSA helped me understand better was what those same attacks actually *look like* once defenders have visibility into an environment.

That was the part I found most interesting.

A lot of the certification felt less like:
> “Find the malicious thing.”

and more like:
> “Figure out what happened.”

That difference made the investigations feel much more realistic.


---

# The Course Material

The CDSA path focused heavily on:
- Splunk
- Sysmon
- Windows event logs
- SIEM investigations
- threat hunting
- attacker behavior analysis
- incident response workflows
- MITRE ATT&CK mapping

One thing I liked immediately was that the material stayed very hands-on.

Instead of spending huge amounts of time on theory, most of the learning came directly from actually investigating activity and working through telemetry.

The course also did a good job showing how noisy enterprise environments can become.

Not every suspicious-looking event actually matters, and not every attacker action is immediately obvious.

A lot of the challenge came from learning how to:
- narrow down investigations
- filter out noise
- identify behavioral patterns
- recognize what deserves deeper analysis

That part honestly reminded me a lot of detective work.

There were times where I would spend a long time digging through logs trying to understand whether something was:
- legitimate activity
- administrator behavior
- misconfiguration
- or actual attacker behavior

I enjoyed that side of the certification much more than I expected.


---

# The Lab Experience

The labs were probably my favorite part of CDSA overall.

A lot of defensive labs online feel overly simplified where you immediately know:
> “Okay, this is the malicious event.”

CDSA was not really like that.

Many investigations required slowing down and carefully building a timeline from multiple sources of information.

Sometimes I would think I found the answer quickly, then realize later I completely misunderstood what was actually happening.

Other times, one random-looking event would suddenly explain the entire investigation once I connected it to something else later on.

The Splunk sections especially helped me become much more comfortable searching through large amounts of telemetry.

At first, it honestly felt overwhelming seeing so much information at once.

But after enough investigations, I started getting better at recognizing:
- suspicious process behavior
- unusual authentication activity
- strange PowerShell usage
- attacker movement patterns
- abnormal parent-child relationships

One thing I appreciated was that CDSA constantly forced me to justify *why* something was suspicious instead of just labeling everything malicious automatically.

That helped develop a much better investigative mindset overall.


---

# The Exam Experience

The CDSA exam felt very different from offensive security exams I had taken before.

With offensive certifications, the adrenaline usually comes from exploitation and trying to gain access.

CDSA felt slower, more analytical, and much more investigation-focused.

The difficulty came from maintaining concentration and understanding the bigger picture across multiple systems and logs.

There were multiple points during the exam where I found myself going back through timestamps, process trees, and authentication events trying to reconstruct exactly what happened step-by-step.

That part actually felt very realistic.

One thing I noticed quickly was how easy it is to jump to conclusions during investigations.

There were several moments where I thought:
> “Okay, this must be the attack.”

only to later realize I was looking at completely normal behavior while the actual malicious activity was somewhere else entirely.

That experience alone taught me a lot about slowing down and thinking carefully before making assumptions.

The exam also made me realize how important organization becomes during investigations.

I constantly had notes open tracking:
- timestamps
- usernames
- PowerShell commands
- process execution
- event IDs
- suspicious hosts
- attacker timelines

Without organized notes, it would have been extremely easy to lose track of the investigation flow.

# Report Writing and Documentation

One thing I ended up appreciating much more throughout CDSA was the importance of investigation documentation and report writing.

It is one thing to find suspicious activity.

It is another thing entirely to clearly explain:
- what happened
- why it mattered
- how the attacker moved through the environment
- what evidence supports the conclusion
- and how all of the activity connects together logically

The certification constantly reinforced that screenshots, notes, timelines, and evidence collection are extremely important during investigations.

There were multiple situations where I realized:
> if I did not document something properly while investigating, it became much harder later to explain the full attack chain clearly.

That made organization a huge part of the process.

I found myself constantly:
- taking screenshots
- saving important log results
- tracking timestamps
- documenting process execution
- organizing Splunk searches
- keeping investigation notes updated

The reporting side also forced me to think much more carefully about clarity.

It was not enough to simply say:
> “This activity was malicious.”

I had to explain:
- how the attacker behavior unfolded
- how the telemetry supported the conclusion
- what sequence of events occurred
- and why the investigation logically pointed toward malicious activity

That process honestly helped improve my analytical thinking a lot because it forced me to piece investigations together into a complete and understandable story rather than just collecting isolated evidence.

By the end of CDSA, I had a much bigger appreciation for how important clear documentation and communication are during real investigations.

Finding malicious activity is only part of the job.

Being able to explain it clearly and logically is just as important.


---

# What Stood Out Most

The biggest thing CDSA changed for me was how I look at offensive activity from the defensive side.

Coming from years of red team labs and Hack The Box environments, I was already familiar with many common attack techniques.

What CDSA showed me was how visible many of those techniques become once:
- proper telemetry exists
- Sysmon is configured well
- logging is centralized
- investigations are done carefully

It was honestly interesting recognizing offensive techniques I had personally used in labs appearing through:
- PowerShell logs
- authentication telemetry
- process creation events
- Splunk searches
- endpoint activity

That perspective made both my offensive and defensive understanding stronger together.

I also gained a much bigger appreciation for how important visibility is in enterprise environments.

A lot of attacks become much harder to hide once defenders have strong telemetry and analysts who know how to interpret it correctly.


---

# Final Thoughts

Overall, CDSA felt like one of the most realistic and practical defensive security certifications I have completed so far.

The certification improved my understanding of:
- threat hunting
- Splunk investigations
- Windows telemetry
- attacker behavior analysis
- SIEM workflows
- incident response investigations
- enterprise defensive visibility

More than anything though, CDSA improved the way I approach investigations mentally.

It taught me to:
- slow down
- avoid assumptions
- focus on evidence
- build timelines carefully
- think behaviorally instead of emotionally during investigations

I also think CDSA paired extremely well with my offensive security background because it connected both sides together in a very practical way.

By the end of the certification, I felt much more confident understanding not only how attacks happen, but also how defenders actually detect, investigate, and piece those attacks together inside enterprise environments.

For anyone interested in realistic threat hunting and enterprise-style investigation workflows, I think CDSA is an extremely valuable certification.
