# HTB CPTS Review and Experience


<img width="1128" height="791" alt="image" src="https://github.com/user-attachments/assets/f7084bf9-07ec-4e77-8ed2-5e389503aa8d" />


## Introduction

The HTB Certified Penetration Testing Specialist (CPTS) was easily one of the most difficult, exhausting, and rewarding things I have done in cybersecurity so far.

Before starting CPTS, I already had experience with blue team training, SIEM work, threat hunting concepts, and defensive labs through certifications like BTL1 and CDSA. At the same time, I had also spent several years consistently working through Hack The Box machines, CTFs, Active Directory labs, and offensive security environments on my own.

Because of that, I went into CPTS with a decent foundation in both defensive and offensive concepts. Even then, CPTS still pushed me much deeper into enterprise-style attack path analysis, Active Directory abuse, and long-form offensive methodology than anything I had previously done.

What immediately stood out to me was how heavily the course focused on methodology rather than shortcuts or memorization. There were very few situations where simply knowing a tool or exploit instantly solved the problem.

Almost everything came down to:
- disciplined enumeration
- understanding relationships between systems
- paying attention to small details
- chaining information together
- staying organized for long periods of time

A lot of the course forced me to slow down and think critically instead of rushing toward exploitation.

That ended up being one of the most valuable parts of the experience.


---

# The Course Material

The CPTS path covers a massive amount of content and goes far deeper than many entry-level offensive security courses.

Some of the major areas included:
- Active Directory exploitation
- Windows and Linux privilege escalation
- Web application attacks
- Password attacks
- Pivoting and tunneling
- Internal network enumeration
- Credential abuse
- Lateral movement
- Reporting and documentation

The Active Directory sections were probably the most valuable training I have personally completed so far.

What I liked most was that the course constantly reinforced *why* something worked rather than simply giving commands to copy and paste.

A huge portion of the training focused on understanding:
- user relationships
- group permissions
- delegated rights
- trust relationships
- attack paths
- privilege inheritance

Instead of relying entirely on automated tools, CPTS forced me to actually analyze environments carefully and think critically about how systems interacted with each other.

There were countless moments where a piece of information that seemed completely unimportant at first became critical much later in the attack chain.

That was honestly one of the biggest lessons from the course:

> Small details matter.

The material also constantly reinforced the importance of re-enumeration. There were many situations where revisiting systems, credentials, shares, permissions, or notes eventually revealed something important that I originally overlooked.

That felt much closer to real-world environments than many beginner-focused labs where attack paths are usually obvious and linear.


---

# The Lab Experience

The labs themselves were extremely time consuming in a good way.

A lot of the environments required:
- chaining multiple findings together
- pivoting across internal networks
- reusing credentials intelligently
- analyzing ACLs and permissions
- thinking about attack paths
- maintaining detailed notes throughout the process

One thing CPTS really teaches you is that organization becomes critical very quickly.

If you do not keep good notes, track credentials properly, document findings carefully, or organize screenshots consistently, things can spiral into chaos later on.

I learned very quickly that penetration testing is not just about exploitation.

It is also heavily about:
- organization
- patience
- documentation
- consistency
- avoiding tunnel vision
- maintaining a clear methodology

There were multiple times where I spent hours going down the wrong path because I became too focused on one idea.

Then later I would step back, re-enumerate carefully, and suddenly notice something small that completely changed the direction of the attack path.

That cycle happened constantly throughout CPTS.

It was frustrating at times, but honestly made the learning experience much more valuable because progress felt earned instead of scripted.

The labs also felt significantly more realistic than many beginner-level penetration testing environments I had used previously.

A lot of platforms teach exploitation in isolated scenarios where the intended path becomes obvious very quickly. CPTS felt much more like working through an enterprise environment where progress often happens slowly and methodically.

Sometimes the smallest detail would become the key to progressing hours later.

That aspect alone improved my methodology more than simply learning additional exploitation techniques.

One thing that also stood out to me throughout CPTS was how much practical pivoting and tunneling mattered once the environments became larger and more segmented.

Before CPTS, I had used tunneling tools in smaller labs and CTF-style situations, but the certification forced me to become much more comfortable using Ligolo-ng in realistic internal network scenarios.

There were multiple situations where progress completely depended on successfully:
- establishing pivots
- routing traffic internally
- accessing segmented systems
- scanning internal networks carefully
- maintaining stable tunnels while continuing enumeration

At first, pivoting felt overwhelming because once multiple networks, hosts, and credentials start stacking together, it becomes very easy to lose track of what traffic is actually going where.

Over time though, working through those situations made me much more comfortable thinking about internal network movement realistically instead of treating pivoting as just another tool step.

By the end of CPTS, I felt significantly more confident using Ligolo-ng and managing multi-host internal enumeration paths than I did beforehand.

That was another area where the certification felt much closer to real-world enterprise environments than isolated CTF-style boxes.


---

# The Exam Experience

The CPTS exam itself was one of the most mentally draining cybersecurity experiences I have ever had.

Not necessarily because every step was technically impossible, but because of the level of persistence, focus, organization, and endurance required over such a long period of time.

The exam felt much closer to a real engagement than a traditional certification exam.

You are not simply solving machines.

You are:
- documenting findings
- collecting evidence
- writing a professional report
- managing screenshots
- maintaining organization
- tracking credentials
- analyzing relationships between systems
- troubleshooting mistakes
- avoiding tunnel vision while exhausted

The reporting portion especially added a level of realism that I genuinely appreciated.

Writing professional findings while still actively progressing through the environment completely changed the pacing of the exam.

You constantly have to think:

> “Did I screenshot this?”  
> “Did I save the command output?”  
> “Can I reproduce this later if needed?”  
> “Will this still make sense when I am exhausted later?”  
> “Did I explain this clearly enough?”  

That pressure becomes very real over time.

The final stretch of the exam was honestly brutal.

By the end, I had spent well over 100 hours working on the report itself between:
- organizing findings
- cleaning screenshots
- restructuring sections
- rewriting explanations
- reducing repetition
- fixing formatting
- converting screenshots into code blocks
- compressing images
- troubleshooting PDF issues
- trying to reduce overall report size

At one point near the end, I stayed awake for roughly 26 straight hours trying to finish everything before submission.

I remember hitting a point where I was simultaneously:
- troubleshooting findings
- compressing screenshots
- reorganizing sections
- converting terminal screenshots into text blocks
- trying to reduce PDF size limits
- checking formatting repeatedly
- making sure screenshots were still readable after compression
- trying to reduce the total report length without losing important technical detail

That part alone honestly felt like a separate challenge entirely.

I think a lot of people underestimate how mentally exhausting the reporting process becomes after already spending so much time inside the environment itself.

By the very end, it genuinely felt less like “taking a certification” and more like completing an actual consulting engagement under pressure.


---

# What Stood Out Most

The biggest takeaway from CPTS was how heavily it emphasized methodology over shortcuts.

The certification constantly reinforced that:
- enumeration quality matters
- documentation matters
- persistence matters
- attack paths matter
- organization matters
- small details matter

A lot of progress did not come from one major exploit.

Instead, it came from slowly connecting smaller pieces of information together over time.

That made the experience frustrating at times, but also incredibly rewarding once everything finally started making sense.

CPTS also changed how I approach environments in general.

I became much more methodical about:
- re-enumeration
- documentation
- privilege analysis
- attack path thinking
- credential tracking
- note organization

It taught me that good methodology often matters more than simply knowing dozens of exploits.


---

# Final Thoughts

Overall, CPTS felt significantly closer to real-world offensive security work than most certification experiences I have seen.

It pushed me far beyond simply learning tools or memorizing commands.

The certification strengthened my understanding of:
- Active Directory attack paths
- privilege escalation methodology
- lateral movement
- internal enumeration
- pivoting and tunneling
- reporting discipline
- enterprise-style attack chain analysis

More than anything, CPTS reinforced the importance of patience, organization, persistence, and analytical thinking during offensive operations.

It was exhausting, frustrating, overwhelming at times, and incredibly rewarding by the end.

Passing CPTS felt less like completing a normal certification and more like proving to myself that I could stay persistent and methodical through a very long and difficult engagement.

One thing I also think is worth mentioning is that even the process of *taking* the CPTS exam teaches you a huge amount.

There were multiple situations during the exam where I learned something new simply from getting stuck, troubleshooting mistakes, re-enumerating systems, or forcing myself to slow down and rethink an attack path.

A lot of the growth honestly came from the pressure itself.

You begin to realize very quickly where your weaknesses are:
- note organization
- time management
- tunnel vision
- enumeration discipline
- documentation habits
- troubleshooting under stress

The exam constantly forces you to adapt.

Even after years of doing labs, CTFs, and boxes, there were still moments during CPTS where I completely changed how I approached certain problems because the environment forced me to think more realistically and methodically.

I think that is one of the reasons the certification stands out so much to me personally.

Even if the exam is exhausting, frustrating, and mentally draining at times, the process itself ends up becoming an enormous learning experience.

By the end, I felt like I improved not only technically, but also in the way I organize my thoughts, document findings, manage time, and approach enterprise-style environments overall.

For anyone genuinely interested in practical penetration testing methodology and realistic enterprise attack path analysis, I think CPTS is an extremely valuable experience.
