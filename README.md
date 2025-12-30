# Soc-analyst-roadmap
Those who want to start their career in cybersecurity (SOC Analyst) role this the perfect roadmap.
Introduction
So you want to break into cybersecurity as a SOC analyst. Maybe you're completely new to the field, or maybe you've been studying but aren't sure what to focus on. Either way, you're in the right place.



------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Here's the truth: landing your first SOC analyst role doesn't require a computer science degree, expensive bootcamps, or years of experience. What it requires is focused practice on the right skills and proof that you can do the job.

This roadmap will show you exactly what to learn, in what order, and how to prove your skills to hiring managers. I've broken it down into a realistic 90-day plan that you can follow whether you're studying full-time or fitting it around your current job.

Why 90 Days?
This isn't arbitrary. Based on working with hundreds of students and analyzing what actually gets people hired, 90 days is the sweet spot:

- Long enough to build real skills and create a portfolio

- Short enough to maintain momentum and motivation

- Realistic for both full-time learners and those studying part-time

> ⚠️ Reality Check: This roadmap requires commitment. Expect to dedicate 2-4 hours per day. If you can only do 1 hour, that's fine—just extend the timeline to 120-180 days.

What You'll Learn
By the end of 90 days, you'll be able to:

- Analyze security logs to identify threats

- Build detection rules for common attack techniques

- Investigate security alerts using industry frameworks

- Use SIEM tools like Splunk to hunt for threats

- Map attacks to MITRE ATT&CK framework

- Communicate findings to technical and non-technical audiences

- Pass the Security+ certification (optional but recommended)

More importantly, you'll have a portfolio of projects to show employers that you can actually do the work.

The Roadmap Overview
Here's how the 90 days break down:

- Days 1-30: Foundations & Security+ Prep

- Days 31-60: Detection Engineering & Hands-On Labs

- Days 61-90: Advanced Skills & Portfolio Building

Let's dive in.

---

Days 1-30: Foundations & Security+ Prep
Week 1: Security Fundamentals (Days 1-7)
Goal
Understand the core concepts that everything else builds on.

What to Learn
Network Fundamentals:

- TCP/IP basics (how data moves across networks)

- Common protocols: HTTP/HTTPS, DNS, SMTP, SSH, RDP

- Ports and services (know the common ones: 80, 443, 22, 3389, etc.)

- How firewalls work

Security Concepts:

- CIA Triad (Confidentiality, Integrity, Availability)

- Authentication vs Authorization

- Encryption basics (symmetric vs asymmetric)

- Common attack vectors (phishing, malware, social engineering)

Resources
Free:

- Professor Messer's Security+ videos (Sections 1.1-1.5) - [YouTube]

- Cybrary's Network+ basics (free tier)

- TryHackMe's "Pre-Security" path (free)

Study Plan:

- 2 hours/day watching videos and taking notes

- 30 min/day reviewing flashcards (use Anki or Quizlet)

- 30 min/day on TryHackMe practicing concepts

> 💡 Pro Tip: Don't just passively watch videos. Take notes by hand—research shows you'll retain 65% more information.

Week 1 Checkpoint
By day 7, you should be able to:

- [ ] Explain what happens when you visit a website (DNS → TCP → HTTP)

- [ ] List 10 common network ports and their services

- [ ] Describe the CIA triad with examples

- [ ] Identify phishing emails and explain red flags

---

Week 2: Operating Systems & Logs (Days 8-14)
Goal
Learn where security data comes from and how to read it.

What to Learn
Windows Security:

- Windows Event Logs (Security, System, Application)

- Key Event IDs for security:

- 4624: Successful logon

- 4625: Failed logon

- 4688: Process creation

- 4672: Admin logon

- PowerShell basics for investigation

Linux Security:

- Linux file permissions and users

- Common log locations (/var/log/)

- Auth logs, syslog basics

- Basic commands: grep, cat, tail, awk

Resources
Free:

- Microsoft's Windows Event Log documentation

- OverTheWire's "Bandit" (Linux practice)

- EpicDetect's Linux Fundamentals track

Hands-On Practice:

- Set up a free Windows VM (using VirtualBox)

- Generate Event Logs by logging in/out

- Practice filtering logs with Event Viewer

- Set up a Linux VM and explore /var/log/

Study Plan
- 1.5 hours/day learning Windows/Linux concepts

- 1.5 hours/day hands-on practice in VMs

- 1 hour/day watching Professor Messer (continue Security+)

Week 2 Checkpoint
By day 14, you should be able to:

- [ ] Navigate Windows Event Viewer and filter events

- [ ] Identify suspicious logon patterns in Event Logs

- [ ] Use grep to search Linux log files

- [ ] Explain what each field in a log entry means

---

Week 3: SIEM Basics & Splunk (Days 15-21)
Goal
Learn the core tool that SOC analysts use daily: the SIEM.

What to Learn
SIEM Concepts:

- What is a SIEM and why do we need it?

- Log collection and aggregation

- Correlation rules and alerts

- Use cases (compliance, threat detection, investigation)

Splunk Fundamentals:

- SPL (Search Processing Language) basics

- Searching logs with index, sourcetype, search commands

- Basic transforming commands: stats, table, sort

- Time ranges and filtering

Resources
Free:

- Splunk Fundamentals 1 (free training on Splunk's site)

- Boss of the SOC (BOTS) dataset (practice data)

- EpicDetect's SPL Fundamentals challenges (free tier)

Hands-On Practice:

- Install Splunk Free (local instance)

- Import sample security logs

- Practice writing SPL queries

- Complete 10-15 basic search challenges

Study Plan
- 2 hours/day Splunk training

- 1 hour/day practicing SPL queries

- 1 hour/day continue Security+ study

Week 3 Checkpoint
By day 21, you should be able to:

- [ ] Write a basic SPL query to search logs

- [ ] Use stats to count events by field

- [ ] Filter logs by time range

- [ ] Create a simple alert for failed logins

> 🎯 Milestone: You're now 1/3 done and have the foundations to build on!

---

Week 4: Security+ Final Prep (Days 22-30)
Goal
Lock in Security+ knowledge and schedule your exam.

What to Focus On
Security+ Domains:

- Domain 1: General Security Concepts (24%)

- Domain 2: Threats, Vulnerabilities & Mitigations (22%)

- Domain 3: Security Architecture (18%)

- Domain 4: Security Operations (28%)

- Domain 5: Security Program Management (8%)

Focus 80% of your time on Domains 2 and 4—these are most relevant to SOC work.

Resources
Free:

- Professor Messer's complete Security+ course

- Practice exams from ExamCompass (free)

- Dion Training practice tests (affordable on Udemy)

Premium (Worth It):

- EpicDetect's Security+ Prep Track - hands-on challenges mapped to exam objectives

- Official CompTIA practice tests

Study Plan
- 2 hours/day reviewing weak areas

- 1 hour/day practice exams

- 1 hour/day hands-on labs (reinforce concepts)

Week 4 Checkpoint
By day 30, you should:

- [ ] Score 80%+ on practice exams consistently

- [ ] Have Security+ exam scheduled (or ready to schedule)

- [ ] Understand all 5 domains at a conceptual level

- [ ] Be able to explain MITRE ATT&CK framework basics

> 🔥 Action Item: Schedule your Security+ exam for day 35-40. Having a date creates urgency.

---

Days 31-60: Detection Engineering & Hands-On Labs
Week 5: MITRE ATT&CK Framework (Days 31-37)
Goal
Learn the industry-standard framework for understanding and detecting threats.

What to Learn
ATT&CK Fundamentals:

- What is MITRE ATT&CK and why it matters

- Tactics vs Techniques vs Procedures

- The 14 Enterprise tactics

- How to read ATT&CK technique pages

- Using ATT&CK for detection

Focus Tactics (learn deeply):

- TA0001: Initial Access (how attackers get in)

- TA0006: Credential Access (stealing passwords)

- TA0008: Lateral Movement (spreading through network)

- TA0010: Exfiltration (stealing data)

Resources
Free:

- MITRE ATT&CK website and Navigator tool

- ATT&CK technique pages (read 20+ in detail)

- EpicDetect's MITRE ATT&CK for Defenders (free lessons)

Hands-On Practice:

- Use ATT&CK Navigator to create coverage matrices

- Map sample attacks to ATT&CK tactics

- Practice identifying techniques in log data

Study Plan
- 2 hours/day learning ATT&CK framework

- 1.5 hours/day mapping real-world attacks

- 30 min/day practicing on EpicDetect

Week 5 Checkpoint
By day 37, you should be able to:

- [ ] Navigate the ATT&CK Matrix confidently

- [ ] Identify tactics and techniques in incident scenarios

- [ ] Explain 10+ specific techniques in detail

- [ ] Map a real breach (like SolarWinds) to ATT&CK

---

Week 6: Building Detections (Days 38-44)
Goal
Learn to create detection rules for real attack techniques.

What to Learn
Detection Engineering Basics:

- What makes a good detection?

- Data sources for detection (logs you need)

- Alert tuning and reducing false positives

- Detection-as-Code concepts

Build Detections For:

- Phishing (T1566): Email analysis, suspicious links

- Credential Dumping (T1003): LSASS access, mimikatz

- Lateral Movement (T1021): Unusual RDP/SMB connections

- C2 Communication (T1071): Beaconing patterns

Resources
Free:

- Sigma rule repository (examples)

- EpicDetect detection challenges (free tier)

- ATT&CK technique pages (detection sections)

Hands-On Practice:

- Write 10 detection rules in SPL

- Write 5 Sigma rules

- Test detections against sample data

Study Plan
- 2 hours/day learning detection concepts

- 2 hours/day writing and testing rules

Week 6 Checkpoint
By day 44, you should be able to:

- [ ] Write a detection rule for a specific ATT&CK technique

- [ ] Explain data sources needed for detection

- [ ] Identify false positive causes

- [ ] Create alerts in Splunk for suspicious activity

---

Week 7: Threat Hunting (Days 45-51)
Goal
Learn to proactively search for threats (not just react to alerts).

What to Learn
Threat Hunting Fundamentals:

- Hunting vs detection (differences)

- Hypothesis-driven hunting

- Using ATT&CK for hunt ideas

- Analyzing hunt results

Hunt For:

- Persistence mechanisms: Registry, scheduled tasks, services

- Credential access: Unusual authentication patterns

- Discovery activity: Network scanning, account enumeration

- Collection activity: Suspicious file access

Resources
Free:

- SANS Hunt Evil poster (free PDF)

- ThreatHunter Playbook (GitHub)

- EpicDetect threat hunting challenges

Hands-On Practice:

- Conduct 5 hunts in your Splunk instance

- Document your process and findings

- Build hunt queries for common techniques

Study Plan
- 1.5 hours/day learning hunting methodology

- 2 hours/day conducting hunts

- 30 min/day documenting findings

Week 7 Checkpoint
By day 51, you should be able to:

- [ ] Develop a hunt hypothesis based on ATT&CK

- [ ] Write hunt queries in SPL

- [ ] Analyze hunt results and identify anomalies

- [ ] Document findings professionally

---

Week 8: Incident Response (Days 52-60)
Goal
Learn to investigate and respond to security incidents.

What to Learn
IR Fundamentals:

- NIST IR lifecycle (Preparation → Detection → Analysis → Containment → Eradication → Recovery)

- Alert triage process

- Evidence collection

- Timeline creation

- Reporting findings

Practice Scenarios:

- Phishing incident investigation

- Malware infection response

- Insider threat investigation

- Ransomware attack

Resources
Free:

- SANS Incident Handler's Handbook (free)

- NIST SP 800-61 Computer Security Incident Handling Guide

- EpicDetect investigation scenarios

Hands-On Practice:

- Investigate 5 mock incidents

- Create incident timelines with ATT&CK mapping

- Write incident reports

Study Plan
- 2 hours/day learning IR process

- 1.5 hours/day practicing investigations

- 30 min/day writing reports

Week 8 Checkpoint
By day 60, you should be able to:

- [ ] Triage security alerts systematically

- [ ] Build attack timelines with ATT&CK

- [ ] Collect and preserve evidence

- [ ] Write clear incident reports

> 🎯 Milestone: You're now 2/3 done and have real detection/hunting skills!

---

Days 61-90: Advanced Skills & Portfolio Building
Week 9: Cloud Security (Days 61-67)
Goal
Add cloud detection skills to your repertoire.

What to Learn
Cloud Security Basics:

- AWS/Azure/GCP security fundamentals

- IAM (Identity and Access Management)

- Cloud-specific attack techniques

- Cloud logging (CloudTrail, Azure Activity Logs)

Cloud Detections:

- Unusual API calls

- IAM privilege escalation

- Data exfiltration to external buckets

- Compromised credentials

Resources
Free:

- AWS CloudTrail documentation

- EpicDetect Cloud Security track

- Free tier AWS account (practice environment)

Hands-On Practice:

- Set up free AWS account

- Enable CloudTrail logging

- Practice analyzing CloudTrail logs in Splunk

- Build 5 cloud-specific detections

Study Plan
- 2 hours/day learning cloud security

- 1.5 hours/day hands-on AWS practice

- 30 min/day building detections

Week 9 Checkpoint
By day 67, you should be able to:

- [ ] Explain shared responsibility model

- [ ] Analyze CloudTrail logs for threats

- [ ] Detect common cloud attacks

- [ ] Build cloud security detections

---

Week 10: Portfolio Projects (Days 68-74)
Goal
Create 3-5 projects to showcase your skills.

Project Ideas
Project 1: Detection Rule Repository

- 20+ detection rules you've written

- Organized by ATT&CK tactic

- Include: SPL queries, Sigma rules, use cases

- Host on GitHub

Project 2: Threat Hunt Report

- Full threat hunt documentation

- Hypothesis, data sources, queries, findings

- ATT&CK mapping

- Recommendations

- Professional formatting

Project 3: Security Monitoring Dashboard

- Splunk dashboard for security monitoring

- Track: Failed logins, new accounts, privilege changes

- Visualizations and alerts

- Screenshots and explanation

Project 4: Incident Response Case Study

- Investigate a mock incident (use CTF or EpicDetect scenarios)

- Complete timeline with evidence

- ATT&CK mapping

- Remediation recommendations

- Lessons learned

Project 5: ATT&CK Coverage Matrix

- Map your detection coverage to ATT&CK

- Use Navigator to visualize

- Document gaps and improvement plan

- Show before/after as you add detections

Portfolio Platform
Create a portfolio site using:

- GitHub Pages (free)

- Medium blog (free)

- Personal website (cheap hosting)

What to Include:

- About you & your goals

- 3-5 detailed projects

- Skills section (tools, frameworks, techniques)

- Certifications (Security+)

- Link to GitHub, LinkedIn

Week 10 Checkpoint
By day 74, you should have:

- [ ] 3 completed projects documented

- [ ] GitHub repo with detection rules

- [ ] Portfolio website (or blog) live

- [ ] Professional README files for all projects

---

Week 11: Job Applications (Days 75-81)
Goal
Start applying strategically while continuing to learn.

Resume & LinkedIn
Resume Optimization:

- Lead with Security+ certification

- Add "Projects" section with your portfolio items

- Use metrics where possible ("Built 20+ detection rules", "Analyzed 10,000+ security events")

- Include skills: Splunk, SIEM, MITRE ATT&CK, Windows/Linux, Detection Engineering

- Add keywords from job descriptions

LinkedIn Optimization:

- Professional headshot

- Headline: "Aspiring SOC Analyst | Security+ | Detection Engineering"

- Detailed About section with your story

- Add projects to Featured section

- Connect with security professionals (engage, don't spam)

Application Strategy
Where to Apply:

- LinkedIn (most responsive)

- Indeed (high volume)

- Company websites directly

- MSSP/consulting firms (high hiring volume)

- Cybersecurity-specific job boards

How Many:

- Apply to 5-10 jobs per day

- Quality over quantity (tailor your resume)

- Focus on "Junior SOC Analyst", "Security Analyst I", "SOC Tier 1"

Application Tips:

- Customize resume for each role (use their keywords)

- Write a brief cover letter mentioning your portfolio

- Link to your portfolio/GitHub

- Follow up after 1 week

Week 11 Checkpoint
By day 81, you should have:

- [ ] Polished resume with portfolio projects

- [ ] Optimized LinkedIn profile

- [ ] Applied to 30-50 positions

- [ ] Started getting interview requests

---

Week 12: Interview Prep (Days 82-90)
Goal
Nail the interviews and get an offer.

Common Interview Questions
Technical Questions:

- "What happens when you type a URL into a browser?"

- "What is the CIA triad? Give examples."

- "Explain the difference between IDS and IPS."

- "Walk me through investigating a phishing alert."

- "What is MITRE ATT&CK and how would you use it?"

- "How would you detect lateral movement in logs?"

- "What's the difference between correlation and detection?"

Behavioral Questions:

- "Why do you want to work in cybersecurity?"

- "Tell me about a time you had to learn something quickly."

- "How do you stay current with security threats?"

- "Describe a challenging problem you solved."

Scenario Questions:

- "You receive an alert for 100 failed logins. What do you do?"

- "A user reports a suspicious email. Walk me through your process."

- "How would you determine if a server is compromised?"

Interview Prep Resources
Practice:

- Mock interviews with friends/mentors

- Record yourself answering questions

- EpicDetect interview prep scenarios

- Pramp or Interviewing.io (free mock interviews)

Research:

- Study the company (what do they protect?)

- Know their tech stack (SIEM, EDR, etc.)

- Prepare 3-5 questions to ask them

- Review job description for talking points

The STAR Method
For behavioral questions, use STAR:

- Situation: Set the context

- Task: Explain the challenge

- Action: Describe what you did

- Result: Share the outcome

Example:

"Tell me about a time you learned something quickly."

S: "I needed to learn Splunk SPL for a detection project"

T: "I had to build 10 detection rules in 2 weeks"

A: "I completed Splunk training, practiced 2 hours daily, and built rules incrementally"

R: "I delivered all 10 rules on time and they reduced false positives by 30%"

Week 12 Checkpoint
By day 90, you should have:

- [ ] Completed 5+ interviews

- [ ] Received at least 1 job offer

- [ ] Negotiated salary effectively

- [ ] Accepted a SOC analyst position!

---

What If You Don't Get An Offer in 90 Days?
First: Don't panic. The 90-day timeline is ambitious. Here's what to do:

Extend & Refine (Days 91-120)
More Practice:

- Complete advanced challenges on EpicDetect (upgrade to Premium for full access)

- Participate in CTFs (Capture The Flag competitions)

- Contribute to open-source security projects

- Write more blog posts about what you're learning

Networking:

- Attend local security meetups (BSides, OWASP chapters)

- Join Discord communities (SOC Analyst Discord, EpicDetect community)

- Connect with recruiters on LinkedIn

- Ask for informational interviews

Get Feedback:

- Ask recruiters why you were rejected

- Have someone review your resume

- Record mock interviews and analyze them

- Join resume review threads on r/cybersecurity

Consider Stepping Stones:

- IT Help Desk → pivot to security

- Security Operations Intern

- Junior roles at smaller companies

- Contract/temp positions (get experience)

> 💡 Truth Bomb: Most people take 4-6 months to land their first role. That's normal. The 90-day plan gives you a huge head start.

---

Premium vs Free: How EpicDetect Helps
Throughout this roadmap, I've referenced EpicDetect challenges and tracks. Here's what you get:

Free Tier
- 50+ detection challenges

- MITRE ATT&CK tactic pages

- Basic SPL lessons

- Community forums

- Enough to get started and build skills

Premium Tier ($19/month or $149/year)
What you get with Premium:

- 600+ challenges across all MITRE tactics

- Complete learning tracks:

- Detection Engineering Fundamentals

- MITRE ATT&CK for Defenders

- Splunk for Security Operations

- Cloud Security Fundamentals

- Incident Response Practitioner

- And more...

- Hands-on labs with real security data

- Certification prep (Security+, CySA+)

- Progress tracking and completion certificates

- Interview prep scenarios

- Portfolio project templates

Is Premium worth it?

Compare:

- Bootcamps: $10,000-20,000

- University courses: $1,000-5,000 per course

- Other platforms: $30-50/month

- EpicDetect Premium: $149/year ($12.42/month)

Premium gives you structured learning + hands-on practice for less than the cost of one security book per month.

> 🎁 Limited Offer: Use code SOCANALYST90 for 20% off annual Premium (first 100 users)

Upgrade to Premium →

---

The Skills Employers Actually Want
Based on analyzing 100+ SOC analyst job postings, here are the top required skills:

Technical Skills (Must Have)
1. SIEM Experience (90% of jobs)

- Splunk is #1 (learn this first)

- Sentinel, Elastic, QRadar also common

- Focus: Writing queries, building alerts, dashboards

2. Log Analysis (85% of jobs)

- Windows Event Logs, Sysmon

- Linux logs (auth, syslog)

- Network logs (firewall, proxy, DNS)

- Cloud logs (CloudTrail, Azure)

3. Incident Response (75% of jobs)

- Alert triage and investigation

- Evidence collection

- Timeline creation

- Reporting

4. Security Tools (70% of jobs)

- EDR platforms

- Network monitoring tools

- Vulnerability scanners

- SOAR platforms (bonus)

5. MITRE ATT&CK (60% of jobs)

- Framework knowledge

- Mapping attacks to tactics/techniques

- Used in interviews frequently

Soft Skills (Equally Important)
1. Communication (95% of jobs)

- Write clear incident reports

- Explain technical findings to non-technical people

- Document processes

2. Critical Thinking (90% of jobs)

- Analyze patterns in data

- Distinguish signal from noise

- Prioritize alerts

3. Continuous Learning (85% of jobs)

- Stay updated on threats

- Learn new tools quickly

- Adapt to changing environment

4. Teamwork (80% of jobs)

- SOCs are collaborative

- Share knowledge

- Help teammates

Certifications
Entry Level (Pick One):

- Security+ (most popular, vendor-neutral)

- CySA+ (more SOC-focused)

- GIAC GSEC (expensive but prestigious)

Nice to Have:

- CEH (ethical hacking, shows offensive knowledge)

- OSCP (advanced, helps stand out)

- Cloud certs (AWS Security Specialty, Azure Security)

The Truth About Certs:

- Security+ gets you past HR filters

- Experience/portfolio gets you past technical interviews

- Both together is optimal

---

Sample Study Schedule
Here's what a realistic week looks like:

Full-Time Study (40 hours/week)
Monday-Friday:

- 9:00-11:00 AM: Video courses / reading

- 11:00-12:00 PM: Review notes, flashcards

- 12:00-1:00 PM: Lunch break

- 1:00-3:00 PM: Hands-on labs / challenges

- 3:00-4:00 PM: Projects / portfolio work

- 4:00-5:00 PM: Practice exams or review

Weekend:

- Saturday: 4 hours review + practice

- Sunday: Light study or rest day

Part-Time Study (15-20 hours/week)
Weekdays (2 hours/day):

- 1 hour: Learning (videos/reading)

- 1 hour: Hands-on practice

Weekend (5-6 hours/day):

- Saturday: Deep learning + practice

- Sunday: Projects + review

Keys to Success:

- Consistency over intensity

- Track your progress

- Take breaks (Pomodoro technique)

- Join study groups for accountability

---

Free Resources Compilation
Here's everything free that I've mentioned:

Learning Platforms
- TryHackMe: Pre-Security path (free)

- HackTheBox: Academy free tier

- Cybrary: Free courses

- EpicDetect: 50+ free challenges

- YouTube: Professor Messer, Network Chuck, John Hammond

Tools & Software
- Splunk: Free version for personal use

- VirtualBox: Free virtualization

- Kali Linux: Free security distro

- Wireshark: Free packet analysis

- Sysmon: Free Windows monitoring

Documentation & Guides
- MITRE ATT&CK: Free framework and navigator

- NIST: Free security guides and frameworks

- SANS: Free posters and reading room

- ATT&CK Technique Pages: Free detailed info

Practice Data
- Boss of the SOC (BOTS): Free Splunk datasets

- Security Onion: Free sample captures

- GitHub: Thousands of sample logs and rules

Community
- Reddit: r/cybersecurity, r/AskNetsec, r/SecurityCareerAdvice

- Discord: SOC Analyst Community, EpicDetect Discord

- LinkedIn: Follow security professionals

- Twitter/X: #InfoSec community

---

Success Stories
Here are real examples from students who followed this roadmap:

Sarah - Career Switcher (Former Teacher)
Background: No IT experience, elementary school teacher

Timeline: 120 days (extended plan)

What She Did:

- Completed Security+ in 6 weeks

- Built detection rule portfolio (30+ rules)

- Contributed to open-source Sigma rules

- Documented everything on Medium blog

Outcome: Junior SOC Analyst at MSSP ($55k starting salary)

Her Advice: "The portfolio was key. In interviews, I showed my GitHub and they saw I could actually do the work."

Marcus - IT Help Desk → SOC
Background: 2 years help desk, no security experience

Timeline: 75 days

What He Did:

- Leveraged IT knowledge for log analysis

- Focused heavily on SIEM (Splunk)

- Completed 200+ EpicDetect challenges (Premium)

- Created home lab with Splunk + Security Onion

Outcome: SOC Analyst Tier 1 at Fortune 500 ($65k)

His Advice: "The hands-on practice was everything. I could answer technical interview questions with real examples."

Jessica - Recent College Grad
Background: Criminal justice degree, zero tech background

Timeline: 90 days exactly

What She Did:

- Studied 4 hours daily (treated like a job)

- Passed Security+ in 5 weeks

- Built impressive portfolio site

- Networked heavily on LinkedIn

Outcome: Multiple offers, accepted SOC role at financial services ($60k)

Her Advice: "Apply even if you don't meet 100% of requirements. My portfolio proved I could learn."

---

Common Mistakes to Avoid
Learn from others' mistakes:

1. Tutorial Hell
Mistake: Watching endless videos without practicing

Fix: 60% practice, 40% theory. Build things immediately.

2. Perfectionism
Mistake: Waiting until you "know enough" to apply

Fix: Apply when you're 70% qualified. You'll learn on the job.

3. Ignoring Soft Skills
Mistake: Only focusing on technical skills

Fix: Practice communication. Write reports. Explain concepts to non-technical friends.

4. Not Networking
Mistake: Applying cold to hundreds of jobs

Fix: Message recruiters, attend meetups, engage on LinkedIn. Most jobs are filled through connections.

5. Giving Up Too Early
Mistake: Getting discouraged after 20-30 rejections

Fix: 50-100 applications is normal. Each rejection teaches you something.

6. Skipping the Portfolio
Mistake: Just listing "skills" on resume with no proof

Fix: Build projects. Document them. Show don't tell.

7. Wrong Certifications
Mistake: Getting CISSP before entry-level experience

Fix: Security+ first. Advanced certs come after you have a job.

---

Final Thoughts
Landing your first SOC analyst role is 100% achievable in 90 days if you:

1. Follow a structured plan (like this roadmap)

2. Practice hands-on (not just theory)

3. Build a portfolio (prove your skills)

4. Apply strategically (quality over quantity)

5. Stay consistent (2-4 hours daily)

The cybersecurity industry is desperate for talent. There are currently 700,000+ unfilled security roles in the US alone. Companies are willing to hire motivated beginners who can demonstrate skills.

You don't need a perfect resume. You need to prove you can do the work.

Your Next Steps (Today)
1. Bookmark this roadmap and commit to the 90-day plan

2. Create a free EpicDetect account and complete your first challenge

3. Download Anki and start your first flashcard deck

4. Schedule Security+ exam for 35 days from now (creates urgency)

5. Join the EpicDetect community Discord for accountability

Want Structured Guidance?
If you want the fastest path with structured learning:

- Upgrade to EpicDetect Premium for complete learning tracks, 600+ challenges, and certification prep

- Use code SOCANALYST90 for 20% off annual plan

- Get everything you need in one platform

Questions?
Drop questions in the comments or join our Discord community. We have hundreds of students on the same journey.

You've got this. Start today. 🚀

---

Related Reading
- Security+ Study Guide: The Detection Engineering Approach

- What SOC Hiring Managers Actually Look For

- 10 SPL Queries Every SOC Analyst Must Know

- Building a Security Portfolio That Gets You Hired
