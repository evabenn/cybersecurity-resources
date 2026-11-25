# My 2027 Cybersecurity Roadmap (Free Career Guide)

> You commented **START**. Here's the exact roadmap I'd follow if I wanted to get into cybersecurity from scratch in 2027. And yes, everything on this page is free.

Hi, I'm Eva. I've been in cybersecurity for over 13 years. I worked my way from zero to leadership security roles and I've been a security hiring manager in big tech. This is the order I'd do things in if I had to start again today.

There are four steps. Do them in order. You don't need every link on this page. Pick one resource per step, finish it, then move on.

**How "free" works here:**
- Every resource has a free version that is enough to learn from
- Most ask you to create a free account
- Some sell paid upgrades. You don't need them to follow this roadmap
- Certification exams cost money. The study material below does not

*Links checked November 2026.*

---

## One. Learn the basics. Don't skip this step!

The basics are how computers and operating systems work, how to get around a Linux command line, and the core security ideas every role uses.

| Resource | How to Use (Free) | Why It Matters |
|----------|-------------------|----------------|
| [Cisco Networking Academy: Introduction to Cybersecurity](https://www.netacad.com/courses/introduction-to-cybersecurity) | Free self-paced course, about 6 hours, free account | The big picture: common threats, how attacks work, how companies defend |
| [Professor Messer: CompTIA A+ Core 1](https://www.professormesser.com/free-a-plus-training/220-1201/220-1201-video/220-1201-training-course/) and [Core 2](https://www.professormesser.com/free-a-plus-training/220-1202/220-1202-video/220-1202-training-course/) | Free videos, no account. Core 1 is 63 videos, about 10 hours | Hardware, operating systems, troubleshooting. This is the IT base security sits on |
| [Linux Journey](https://labex.io/linuxjourney) | Free, no sign-up. Start with the Grasshopper lessons: command line, permissions, processes | Most security tools and servers run on Linux |
| [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) | A game you play in the terminal, built for absolute beginners | You practice Linux commands by solving levels instead of reading about them |
| [Professor Messer: Security+ (SY0-701)](https://www.professormesser.com/security-plus/sy0-701/sy0-701-video/sy0-701-comptia-security-plus-course/) | Free videos, no account. 121 videos, about 15 hours | The core security vocabulary you'll hear in every interview |
| [CS50's Introduction to Cybersecurity (Harvard)](https://cs50.harvard.edu/cybersecurity) | Five weeks of lectures and assignments, free through Harvard's OpenCourseWare | Built for technical and non-technical people. Covers accounts, data, systems, software, privacy |
| [TryHackMe: free beginner roadmap](https://tryhackme.com/resources/blog/free_path) | TryHackMe's own list of free rooms in order. Free accounts get one hour a day on the in-browser hacking machine | Guided, hands-on practice from day one |

**Short on time?** Do Introduction to Cybersecurity, then Linux Journey, then Bandit.

**A note on certs.** Certs open doors. Skills keep you in the room. Use the free videos above to learn, and decide on an exam later. Two things to know for 2027:
- Security+ is changing. The new exam (SY0-801) came out in November 2026 and the current one (SY0-701) retires June 11, 2027. Professor Messer is releasing his [free SY0-801 videos](https://www.professormesser.com/sy0-801-certification-course/sy0-801-security-plus-course/) now. If you plan to test after June 2027, follow that course instead.
- Older lists still say the ISC2 Certified in Cybersecurity exam is free. That program has closed to new sign-ups.

---

## Two. Learn basic networking. Then learn how the pieces fit together.

The pieces are your device, the network, apps, databases, and the cloud. You covered your device in step one. Here is the rest.

| Piece | Resource | How to Use (Free) | Why It Matters |
|-------|----------|-------------------|----------------|
| The network | [Cisco Networking Academy: Networking Basics](https://www.netacad.com/courses/networking-basics) | Free self-paced course, about 22 hours, free account | How devices talk to each other: IP addresses, routers, switches, protocols |
| The network | [Professor Messer: Network+ (N10-009)](https://www.professormesser.com/network-plus/n10-009/n10-009-video/n10-009-training-course/) | Free videos, no account. 87 videos, about 13 hours | Goes deeper once the basics click |
| The network | [Practical Networking: free first module](https://www.youtube.com/playlist?list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi) | YouTube playlist | Shows how data moves through the Internet, step by step |
| The network | [Wireshark](https://www.wireshark.org/) with [Malware Traffic Analysis exercises](https://www.malware-traffic-analysis.net/training-exercises.html) | Wireshark is free and open source. Download an exercise and open it. Start with the newest ones | You see real network traffic, including real attacks |
| Apps | [MDN: How the web works](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Web_standards/How_the_web_works) | One article. Read it twice | Clients, servers, DNS, HTTP. Every web attack builds on this |
| Apps | [PortSwigger Web Security Academy](https://portswigger.net/web-security) | 100% free lessons and labs. Start with the Apprentice labs | You learn how web apps work by seeing how they break |
| Databases | [SQLBolt](https://sqlbolt.com/) | 18 short lessons you do in the browser | Almost every app stores its data in a database. SQL is how you ask it questions |
| The cloud | [Microsoft Learn: Describe cloud concepts](https://learn.microsoft.com/en-us/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/) or [AWS Cloud Practitioner Essentials](https://skillbuilder.aws/learn/94T2BEN85A/aws-cloud-practitioner-essentials/8D79F3AVR7) | Pick one. Microsoft Learn needs no account to read. AWS needs a free Skill Builder account | What the cloud is and who secures what (the shared responsibility model) |

**Test yourself before you move on.** Explain out loud what happens when you type a website address and press Enter. Your device, DNS, the network, the web server, the database behind it, the cloud it all runs on. If you can explain it to a friend, you're ready for step three.

---

## Three. Pick a path and go ham on it.

I don't want you trying to learn everything. Cybersecurity is a huge field and you will waste your time if you try. Pick a focus and go deep.

### Want to do Blue Team? Go to KC7.

| Resource | How to Use (Free) | Why It Matters |
|----------|-------------------|----------------|
| [KC7](https://kc7cyber.com/) | Free for players, always. Start with [A Rap Beef](https://kc7cyber.com/go/beef), then [KQL 101](https://kc7cyber.com/go/take10). You need a free KC7 account and a free Microsoft account | You play a security analyst and investigate an intrusion in real-looking logs. No experience needed |
| [SOC Core Skills with John Strand](https://www.youtube.com/playlist?list=PL-4fuTjKox5daG-Fdii8sIdj7nOdX70aW) | Watch the full class on YouTube. The [live class](https://www.antisyphontraining.com/beginners-guide-to-entry-level-cybersecurity/) is pay-what-you-can, and that includes $0 | 16 hours on the core skills a SOC analyst uses on the job |
| [Blue Team Labs Online](https://blueteamlabs.online/) | Free account. All Challenges are free. Investigations are the paid part | Log analysis, phishing, forensics practice you can download and work through |
| [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/) | Free account. Do the labs that are not tagged Premium | Investigations built on network captures, disk images, and logs |

### Want to learn AI hacking? Try a free weekly challenge at GoHack.ai.

| Resource | How to Use (Free) | Why It Matters |
|----------|-------------------|----------------|
| [GoHack.ai](https://gohack.ai/) | Free account. A new free challenge every week | Hands-on keyboard practice hacking AI systems. Don't sleep on it |
| [OnlyLANs](https://onlylans.ai/) | Free, no account. Three levels | A prompt injection wargame I built with Andrew Bellini for Just Hacking Training. Trick the AI assistant into leaking its secrets |
| [Gandalf by Lakera](https://gandalf.lakera.ai/) | Free, plays in the browser | The best-known prompt injection game. Each level adds a new defense |
| [PortSwigger: Web LLM attacks](https://portswigger.net/web-security/learning-paths/llm-attacks) | Free learning path with 7 labs | Prompt injection, excessive agency, and indirect prompt injection against real web apps |
| [OWASP GenAI LLM Top 10 2026](https://genai.owasp.org/resource/owasp-genai-llm-top-10-2026/) and [OWASP Top 10 for Agentic Applications 2026](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/) | Free downloads | The shared language for AI security risks. Read these before an interview |
| [Microsoft: AI Red Teaming 101](https://learn.microsoft.com/en-us/security/ai-red-team/training) | 10 free episodes. The matching labs need your own paid AI API key, so watch first | How a real AI red team works, from fundamentals to automation |
| [GitHub Secure Code Game](https://securitylab.github.com/secure-code-game/) | Free and open source. Runs in your browser through GitHub Codespaces. Season 3 covers LLM security, Season 4 covers AI agents | You attack a vulnerable AI assistant, then learn how to fix it |
| [MITRE ATLAS](https://atlas.mitre.org/) | Free to browse | A knowledge base of real attacks on AI systems and how to defend against them |

### Want a different path?

Red Team, Cloud Security, GRC, Digital Forensics, Threat Intelligence. They are all in my [Career Paths Table](https://github.com/evabenn/cybersecurity-resources/blob/main/cybersecurity-career-paths.md), with who each role fits and where to practice for free.

---

## Four. Build proof.

Put one project on GitHub. Show the problem you worked on, the evidence you found, and what you'd do next. Now you have something concrete to walk through in an interview.

| Resource | How to Use (Free) | Why It Matters |
|----------|-------------------|----------------|
| [GitHub Skills: Introduction to GitHub](https://github.com/skills/introduction-to-github) | Free, takes less than an hour | Repositories, commits, and pull requests. Enough to publish your first project |
| [GitHub Docs: Managing your profile README](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme) | Follow the steps | A short intro at the top of your GitHub profile, so a hiring manager knows who you are in ten seconds |
| [The DFIR Report](https://thedfirreport.com/) | Read one or two of the public reports | Real intrusions written up with evidence. This is what good looks like |

### Project ideas

- **Blue Team:** Work one KC7 case or one Malware Traffic Analysis exercise from start to finish, then write up what happened and how you know.
- **AI hacking:** Write up a GoHack.ai weekly challenge or OnlyLANs. What you tried, what worked, why it worked, and how you'd defend against it.

Two rules. Don't publish answers to a challenge that is still live, and check each platform's write-up rules first. Never put real company data, passwords, or keys in a public repo.

### Copy this write-up template

```markdown
# [Project title]

## The problem
What was I trying to figure out? One or two sentences.

## What I used
The platform, the tools, and the data. Link to the lab or challenge.

## The evidence
What I found, step by step. Add screenshots, queries, or commands, and say what each one showed.

## What it means
The story in plain English. What happened, and how do I know?

## What I'd do next
How I'd contain it, fix it, or keep investigating.

## What I learned
Two or three things I can do now that I couldn't do before.
```

---

## Keep going

Everyone feels behind. The field changes fast. Start before you feel ready, because nobody feels ready.

- **[Security Mondays](https://www.youtube.com/@evabennofficial):** My weekly show with security leaders. New episode every Monday.
- **[SANS Internet Storm Center Stormcast](https://isc.sans.edu/podcast.html):** About five minutes of security news every weekday.
- **[Career Paths Table](https://github.com/evabenn/cybersecurity-resources/blob/main/cybersecurity-career-paths.md):** What each role does and who it fits.
- **[10 + Bonus 20 Free Resources](https://github.com/evabenn/cybersecurity-resources/blob/main/bonus-20.md):** More free labs and tools when you want them.

---

## Connect with me:

**Eva Benn**: [LinkedIn](https://www.linkedin.com/in/evabenn/)

**YouTube**: [@evabennofficial](https://www.youtube.com/@evabennofficial)

**Instagram**: [@evabennofficial](https://www.instagram.com/evabennofficial)

**TikTok**: [@evabennofficial](https://www.tiktok.com/@evabennofficial)
