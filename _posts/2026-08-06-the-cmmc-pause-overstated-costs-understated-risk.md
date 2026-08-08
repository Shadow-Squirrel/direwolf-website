---
title: "The CMMC Pause: Overstated Costs, Understated Risk"
description: "The Pentagon has paused CMMC Phase 2 third-party assessments. A practitioner's case for why the cost argument is weaker than advertised — and the security bill for the delay is bigger than anyone admits."
---

On July 13, 2026, the Pentagon suspended Phase 2 of the Cybersecurity Maturity Model Certification program, the stage that would have required contractors handling controlled unclassified information to pass an independent third-party assessment before taking applicable awards this November. A reform task force is now reviewing the program; Phase 1 self-assessments and the underlying NIST SP 800-171 requirements remain in force. The department framed the decision as arithmetic: more than 100,000 companies needing assessments, only around a hundred organizations authorized to perform them, and per-company costs the Small Business Administration put near $594,000. Having worked the practitioner side of this problem, I believe the cost case is weaker than advertised, the burden far less novel than the headlines suggest, and the security bill for the delay larger than anyone is admitting.

Start with the number. Market quotes for the Level 2 assessment itself have generally run $30,000 to $60,000 for a small, single-site business, and the Pentagon's own rulemaking analysis priced the full certification cycle, preparation included, at roughly $105,000 to $118,000. The SBA reaches $594,000 by folding in the cost of implementing NIST 800-171 itself, and a maturing market of enclave architectures and managed compliance providers has been pulling even those costs steadily downward, with first-year totals now starting around $70,000. Real money for a small shop, certainly. Not a $600,000 wall.

The deeper problem with the cost argument is that none of this is new. Basic federal safeguarding rules date to 2016. Full implementation of NIST 800-171 became a binding contract condition under DFARS 252.204-7012 at the end of 2017. Since late 2020, contractors have been required to score themselves against those controls and post the result in the government's Supplier Performance Risk System. CMMC Level 2 adds no new security controls at all; it verifies the same 110 requirements contractors have been attesting to for nearly a decade. Treating that verification as a surprise expense confuses the audit with the debt. And the record shows the debt is real. A 2024 study by Merrill Research for CyberSheath put the average self-assessed score across the industry at minus 12, on a scale where compliance is 110. Where assessors have checked the paperwork, it gets worse: one Navy contractor posted a perfect 110 and was later scored at minus 170 by the department's own assessment center; another self-reported a 104 and audited at minus 142; Raytheon paid $8.4 million over compliance representations spanning roughly thirty contracts; and when the DoD inspector general examined attesting contractors in 2022, all ten fell short of standards they had certified to. Every one of those falsely attested networks held CUI. That, not assessment fees, is what has made the defense industrial base vulnerable, and CMMC exists precisely to close it.

The suspension leaves that gap open at a genuinely bad moment. An NSA official has said publicly that China deliberately targets the smallest companies in the defense industrial base, with hacking resources outnumbering those of the United States and its allies combined. Google's threat-intelligence teams have tracked sustained spearphishing of aerospace and defense employees through 2025, and the same week the pause was announced, security agencies from more than a dozen countries jointly warned of state-sponsored targeting of defense supply chains. Our adversaries watch American policy signals closely, and a multi-year extension of the honor system is a signal. They do not pause their programs to run 60-day reviews.

None of this changes what contractors owe today. DFARS 7012 is still contract law, the Justice Department is turning inflated self-assessments into False Claims Act settlements at a record pace, and verification will almost certainly return in some form. Companies that keep implementing, or get assessed by choice, lose nothing however the review lands. But we have suspended the one mechanism proven to separate real compliance from claimed compliance, on the strength of cost figures that don't survive contact with the market, while the adversary works hardest against the companies least equipped to notice. That is a window, and windows get used.

---

## Sources

**The suspension & program status**

- [DefenseScoop — DOD halts CMMC cybersecurity requirements Phase 2](https://defensescoop.com/2026/07/13/dod-halts-cmmc-cybersecurity-requirements-phase-2/)
- [Federal News Network — Pentagon suspends CMMC Phase 2 requirements, launches review of program](https://federalnewsnetwork.com/cybersecurity/2026/07/pentagon-suspends-cmmc-phase-two-requirements-launches-review-of-program/)
- [DoD Office of Small Business Programs — Department of War suspends CMMC Phase II requirements](https://business.defense.gov/Engage/News/Article/4542563/forging-the-arsenal-of-freedom-department-of-war-suspends-cmmc-phase-ii-require/)
- [SBA — SBA commends suspension of CMMC Phase II for small defense contractors](https://www.sba.gov/article/2026/07/13/sba-commends-us-department-wars-suspension-cmmc-phase-ii-small-defense-contractors)
- [National Defense — Pentagon suspends Phase 2 of CMMC program](https://www.nationaldefensemagazine.org/articles/2026/7/13/breaking-pentagon-suspends-phase-2-of-cmmc-program)
- [National Defense — Pentagon's CMMC pause draws praise, criticism from industry](https://www.nationaldefensemagazine.org/articles/2026/7/14/just-in-pentagons-cmmc-pause-draws-praise-criticism-from-industry)
- [CSIS — What the CMMC pause means for the defense industrial base](https://www.csis.org/analysis/what-cmmc-pause-means-defense-industrial-base)

**Assessment costs (market rates vs. the $594K figure)**

- [PreVeil — CMMC certification costs](https://www.preveil.com/blog/cmmc-certification-costs/)
- [Huntress — CMMC certification cost](https://www.huntress.com/cmmc-compliance-guide/cmmc-certification-cost)
- [Total Assure — CMMC Level 2 assessment costs](https://www.totalassure.com/blog/cmmc-lvl-2-assessment-costs)
- [Cabrillo Club — CMMC certification cost guide](https://cabrilloclub.com/insights/cmmc-certification-cost-guide)

**Compliance gap & False Claims (the −12 average, 110 vs. −170, settlements)**

- [CyberSheath — Defense on the Brink: the perilous state of cybersecurity across the DIB](https://cybersheath.com/resources/downloads/defense-on-the-brink-the-perilous-state-of-cybersecurity-across-the-dib/)
- [CyberSheath — Study shows only 4% of defense contractors ready for Pentagon's cybersecurity mandate](https://cybersheath.com/company/news/study-shows-only-4-of-defense-contractors-ready-for-pentagons-new-cybersecurity-mandate/)
- [Cybersecurity Ventures — Reality check: the defense industry's implementation of NIST SP 800-171](https://cybersecurityventures.com/reality-check-defense-industrys-implementation-of-nist-sp-800-171/)
- [U.S. Department of Justice — Alabama defense contractor pays $507,144 to resolve False Claims Act liability](https://www.justice.gov/opa/pr/alabama-defense-contractor-agrees-pay-507144-resolve-false-claims-act-liability-relating)
- [FedContractPros — DOJ's LogZone settlement: cybersecurity scores as False Claims Act evidence](https://www.fedcontractpros.com/blog/dojs-logzone-settlement-shows-why-cybersecurity-scores-can-become-false-claims-act-evidence)
- [Quarles — DOJ's Civil Cyber-Fraud Initiative settles NIST SP 800-171 allegations against Raytheon](https://www.quarles.com/newsroom/publications/dojs-civil-cyber-fraud-initiative-utilizes-false-claims-act-to-settle-allegations-of-knowing-non-compliance-with-nist-sp-800-171-against-raytheon-and-its-successor)
- [National Law Review — Cybersecurity noncompliance triggers another False Claims Act settlement](https://natlawreview.com/article/cybersecurity-noncompliance-just-triggered-another-false-claims-act-settlement)
- [PreVeil — The False Claims Act and defense contractors](https://www.preveil.com/blog/false-claims-act-defense-contractors/)
- [Mayer Brown — False Claims Act enforcement: record-breaking year signals continued attention to cybersecurity](https://www.mayerbrown.com/en/insights/publications/2026/03/false-claims-act-enforcement-record-breaking-year-signals-continued-attention-to-cybersecurity)
- [Mondaq — The CMMC pause, supply chain chokepoints, and the escalating False Claims Act trap](https://www.mondaq.com/unitedstates/government-contracts-procurement-ppp/1823508/the-cmmc-pause-supply-chain-chokepoints-and-the-escalating-false-claims-act-trap)

**Adversary threat (NSA on China, Google threat intel, joint advisory)**

- [Cybersecurity Dive — NSA on cybersecurity help for defense contractors (Black Hat)](https://www.cybersecuritydive.com/news/nsa-defense-contractors-cybersecurity-help-black-hat/757169/)
- [Industrial Cyber — Google flags sustained cyber pressure on the defense industrial base from Russia- and China-linked actors](https://industrialcyber.co/reports/google-flags-sustained-cyber-pressure-on-defense-industrial-base-from-russia-china-linked-actors/)
- [Google Threat Intelligence — Threats to the defense industrial base](https://cloud.google.com/blog/topics/threat-intelligence/threats-to-defense-industrial-base)
- [Virtru — CMMC Compass](https://www.virtru.com/blog/compliance/mcglobaltech-cmmc-compass)

**What comes next**

- [Breaking Defense — CMMC may be paused, but cybersecurity audits likely to return: industry experts](https://breakingdefense.com/2026/07/cmmc-may-be-paused-but-cybersecurity-audits-likely-to-return-industry-experts/)
- [SecurityWeek — Industry reactions to Pentagon suspending CMMC Phase 2](https://www.securityweek.com/industry-reactions-to-pentagon-suspending-cmmc-phase-2-feedback-friday/)
