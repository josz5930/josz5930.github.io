# Joseph Zeng — Application & AI Security

> Application and AI security, Singapore.

Personal site: **[josz5930.github.io](https://josz5930.github.io/)**

Sixteen years across offensive security, application security and security programme ownership. I lead the Singapore application security function at **ByteDance**, where I own the design-review and penetration-testing gates for TikTok, Lemon8 and other product lines.

I also build. I have specified, shipped and measured LLM and agent-based security systems that run in production, and I test the AI features other teams ship for prompt injection and tool abuse. Before that: national bug bounty triage in the public sector, regional offensive security delivery, and two published CVEs.

## Elsewhere

- [Security writing](https://github.com/josz5930/secarticles)
- [Mastodon](https://infosec.exchange/@josephzeng)
- [GitHub](https://github.com/josz5930)
- [LinkedIn](https://www.linkedin.com/in/josephzeng/)

## Now

- Leading a team of seven engineers plus interns in Singapore, working with counterparts in China, Australia, the UK and the US.
- Reading and testing agentic systems: prompt injection, tool abuse, and access control for model-driven workflows.
- Studying part-time MSc in Design and Artificial Intelligence for Enterprise at SUTD since September 2026.
- Open to senior roles in AI security, application security and technology management.

## Selected AI and agentic security work

**An LLM effort-prediction system, from idea to org-wide deployment**
Conceived, specified and shipped a system that reads product requirement documents and entity-relationship diagrams, then predicts the person-days a penetration test will need. Ran a one-month trial with structured feedback capture, tuned it against actual outcomes, and deployed it across the whole project-management estate. It survived deprecation of the platform underneath it and the loss of the linked engineering headcount, and was later released to the global security organisation as a reusable asset.

**An agentic security-review pipeline, and the case for not shipping it everywhere**
Built and evaluated an LLM agent that performs enhanced automated security review on live engineering tickets. Measured its time cost in a controlled trial on one product line before committing to an expansion pace, and held a documented position with engineering stakeholders that deterministic questionnaire logic keeps precedence over model judgement until the evidence supports handover.

**Adversarial evaluation of shipping AI features**
Hands-on prompt-injection and agent-abuse testing of live AI features, using Promptfoo as a standing part of security review. Built internal evaluation endpoints for cross-language prompt fidelity and prompt optimisation on the company model platform.

**A two-tier assistant for developer security questions**
Wrote the requirements and configured the knowledge base for an assistant that answers developer questions on secure-SDLC process and remediation. A fast non-reasoning model handles intent and sentiment routing; a reasoning model handles substantive answers. Extended it to intervene automatically on stalled remediation tickets and to serve an on-demand support channel.

**Risk that had not arrived yet**
Warned a product team about an account-takeover pattern in an AI support flow that could change account state without verifying identity, after a comparable incident elsewhere. Surfaced a supply-chain detection capability to the platform security team in response to a model-library poisoning incident class.

## Published vulnerability research

- **[CVE-2015-2210](https://nvd.nist.gov/vuln/detail/CVE-2015-2210)** — Command injection in the help system of a retail point-of-sale product. A local user could inject JavaScript into the window source to spawn a command shell, escaping the locked-down till environment. Rated 7.8 high. Disclosed 2015.
- **[CVE-2014-2729](https://nvd.nist.gov/vuln/detail/CVE-2014-2729)** — Stored cross-site scripting in a commercial web content management system, reached through an unhandled parameter and executed on page load. Fixed by the vendor. Disclosed 2014.

## Experience

### Application Security Manager
**ByteDance**, Singapore · Nov 2024 – present

- Own the application security assurance gates, security design review and penetration testing, for product lines in the rest-of-world scope.
- Proposed and led architecture planning for a platform-level replacement of the design-review stage after the incumbent platform lost engineering support, de-risking rollout by piloting where no pipeline depended on the gate.
- Found and closed process-gate bypasses where features shipped without review, separating platform defects from human circumvention and driving systemic fixes with the product organisation instead of one-off remediation.
- Designed the response to an IDOR exploitation incident: full automated scanning coverage plus structured training for the entire affected engineering organisation, rather than the minimum remediation.
- Built and launched a bilingual Mandarin and English secure-SDLC course end to end, then scaled it across eight engineering organisations by securing department-head consent one at a time. 636 engineers completed it at an 82% completion rate in one half-year, measured against a baseline corrected for departed staff rather than a flattering one.
- Grew the team from five to seven, screening 200+ resumes across 20+ interviews, and rebuilt the interview process with questions resistant to LLM assistance. Sponsored two promotion packets and held delivery together through heavy attrition on adjacent platform teams.

### Head of Offensive Security Services
**Bitdefender APAC** (f.k.a. Horangi), Singapore · Apr 2021 – Nov 2024

- Delivered 100+ engagements across banking, financial services, fintech, energy and government: web, mobile, network, cloud, thick-client and protocol testing, architecture review, source-code review and compliance work.
- Managed a team of ten and built higher-value service lines, including red team attack path mapping and smart contract review, taking the team through certification and guided delivery to reach capability.
- Rewrote most of the SOC 2 control procedures and enforced least privilege across two AWS accounts, replacing administrator access for eight engineers with scoped roles.
- Designed and facilitated table-top exercises for business continuity, malware and intrusion scenarios, on site and remote, through to after-action review. Ran CREST membership renewal with legal, finance, compliance and vendors.

### Senior Cybersecurity Specialist
**GovTech Singapore** · Jun 2019 – Apr 2021

- Ran triage for the national Government Bug Bounty Programme and Vulnerability Disclosure Programme: 400+ reports reviewed, 40+ assessed in detail, consistently inside a two-day reproduction metric.
- Managed a cross-organisational team of 14 for one programme iteration, covering triage testers, staff seconded from other agencies, interns, and a monitoring and intake team.
- Presented quarterly to the Assistant Chief Executive and to government CISOs on vulnerability trends, researcher demographics and manpower projections. Wrote the programme-level final report that went to Permanent Secretary level.

### Senior Manager
**Lazada**, Singapore · Jul 2017 – Jun 2019

- Ran periodic and pre-launch penetration testing for web and mobile across the group and its subsidiaries, and owned the testing process, procedure documentation and rostering.
- Created the assessment approach for independent service vendors integrating with platform APIs, deciding what to test and how across thick clients, web and mobile.
- Findings included server-side request forgery, backdoor OTP values, absent password validation, and a duplicate-identifier condition that caused denial of service.
- Built developer security e-training, delivered a two-day secure coding course, and spoke on physical-security threat modelling at Div0 in January 2019.

### Lead Consultant
**NCS**, Singapore · Mar 2015 – Jun 2017

- Project manager and lead implementer on a three-year government monitoring programme worth $4m+, covering 71+ organisations through sinkhole sampling, delivered with a team of six.
- Built NCS capability in mobile application penetration testing, wireless assessment and source code review, and led a three-year assurance programme spanning architecture review, vulnerability assessment, penetration testing and host configuration review.
- Led development of services built on threat intelligence partnerships, from sinkhole and spam-trap security ratings to human-intelligence adversary tracking. Ran presales scoping, effort estimation and proposals.

### Senior Associate
**KPMG**, Singapore · Nov 2012 – Mar 2015

- Assessed clients across financial services, pharmaceutical, oil and gas, education, public administration and transport, using web application testing, source code review, desktop and mobile testing, and configuration assessment.
- Published two vulnerabilities, listed above, both assigned CVE identifiers.
- Led creation of Java and .NET secure coding guidelines and wrote Objective-C guidelines for a regional bank. Led a year-long effort producing operating system hardening baselines with a junior associate and two interns.
- Performed three-phase post-incident assurance for breached clients: asset and port discovery, vulnerability scan, penetration test.

### Software Engineer
**ST Engineering** (Info-Software Systems), Singapore · May 2010 – Nov 2012

- Subsystem lead and deputy test manager on an $11m distributed systems programme with twelve full-time developers. Ran functional, load and stress testing, plus static and dynamic analysis against the OWASP Top Ten.

## Certifications

**AI and cloud**
Certified AI Security Professional (CAISP) · Certified Cloud Security Professional (CCSP) · GIAC Cloud Penetration Tester (GCPN)

**Offensive security**
OffSec Certified Professional (OSCP) · OffSec Web Expert (OSWE) · HTB Certified Web Exploitation Specialist (CWES) · GIAC Penetration Tester (GPEN) · GIAC Mobile Device Security Analyst (GMOB) · GIAC Open Source Intelligence (GOSI)

**Defensive and governance**
Certified Information Systems Security Professional (CISSP) · GIAC Certified Web Application Defender (GWEB) · Certified Threat Modeling Professional (CTMP)

## Education and languages

- MSc, Design and Artificial Intelligence for Enterprise — Singapore University of Technology and Design. Part-time, from September 2026.
- Bachelor of Computing (Honours), Electronic Commerce — National University of Singapore, 2010.
- English, native. Mandarin Chinese, HSK Level 5.

---

*Views here are my own and are not those of any employer. For anything industry-related, reach me through Mastodon or LinkedIn rather than this page.*
