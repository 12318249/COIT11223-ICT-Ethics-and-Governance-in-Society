# E-Portfolio 5: Automated Decision-Making (ADM) in Government Systems

**COIT11223 – ICT Ethics and Governance in Society | Assessment 3 Part B**

**Student Name:** _[Your name]_ | **Student ID:** _[Your ID]_ | **Term:** T2 2026

---

## Table of Contents

1. [Introduction: What is ADM?](#1-introduction-what-is-adm)
2. [Why ADM Matters to Me as an ICT Professional](#2-why-adm-matters-to-me-as-an-ict-professional)
3. [My Perspective Before This Unit](#3-my-perspective-before-this-unit)
4. [Analytical Framework Used in This Portfolio](#4-analytical-framework-used-in-this-portfolio)
5. [Artefact 1 – Australian Government ADM Consultation Paper (2024)](#artefact-1--australian-government-adm-consultation-paper-2024)
6. [Artefact 2 – Allars (2024): Robodebt and Administrative Review](#artefact-2--allars-2024-robodebt-and-administrative-review)
7. [Artefact 3 – Ombudsman Report on the Targeted Compliance Framework (2025)](#artefact-3--ombudsman-report-on-the-targeted-compliance-framework-2025)
8. [Artefact 4 – DTA Policy for the Responsible Use of AI in Government v2.0 (2025)](#artefact-4--dta-policy-for-the-responsible-use-of-ai-in-government-v20-2025)
9. [Artefact 5 – Sweden's Welfare Fraud Algorithm (Amnesty International, 2024)](#artefact-5--swedens-welfare-fraud-algorithm-amnesty-international-2024)
10. [Artefact 6 – Bias in the UK DWP Universal Credit Fraud Model (2024)](#artefact-6--bias-in-the-uk-dwp-universal-credit-fraud-model-2024)
11. [Comparative Analysis: Australia vs Other Countries](#comparative-analysis-australia-vs-other-countries)
12. [Conclusion: How My Understanding Has Changed](#conclusion-how-my-understanding-has-changed)
13. [References](#references)

---

## 1. Introduction: What is ADM?

Automated decision-making (ADM) is the use of technology, usually described in Commonwealth legislation as a "computer program", to automate all or part of a decision-making process that affects people's rights or entitlements (Attorney-General's Department 2024, p. 7). Allars (2024, p. 1147) describes ADM as a model in which rule-based formulae are run by computer programs to determine whether an individual meets legal criteria.

ADM sits on a spectrum:

| Level of automation | Example | Human role |
|---|---|---|
| Data extraction only | System pulls records for an officer to review | Human decides |
| Decision support | System recommends an outcome or flags risk | Human signs off (often with little analysis) |
| Partial decision | System determines factual elements, e.g. income | Human decides the rest |
| Full decision | System issues the decision, e.g. payment cancellation | None at the time of decision |

_Source: adapted from Attorney-General's Department (2024, p. 15)._

ADM and AI are related but distinct. Most Commonwealth ADM is **rules-based** ("if this, then that"), while newer systems use **machine learning** that infers outcomes from historical data and may not be explainable even to its developers (Attorney-General's Department 2024, pp. 12–13). Both types appear in this portfolio: Robodebt and the Targeted Compliance Framework (rules-based) in Australia, and machine-learning fraud models in Sweden and the United Kingdom.

---

## 2. Why ADM Matters to Me as an ICT Professional

ICT professionals are the people who translate legislation and policy into code. When the code is wrong, the error is not made once; it is repeated across hundreds of thousands of people before anyone notices. ADM is attractive to governments because it is faster, cheaper and more consistent than human processing (Attorney-General's Department 2024, p. 9). However, the same report lists risks that sit squarely within my professional responsibility: algorithmic bias, coding errors that misrepresent the law, inflexible application of rules where discretion is required, and the de-skilling of human officers (Attorney-General's Department 2024, p. 10).

The ACS Code of Professional Conduct requires me to put the **public interest** ahead of personal, employer or business interests, to protect **quality of life** for those affected by my work, and to maintain **competence** (Australian Computer Society 2014). The six artefacts below show what happens when those duties are not met in government systems, where the people affected are often the most vulnerable members of society and cannot simply choose another provider.

---

## 3. My Perspective Before This Unit

<!-- PERSONALISE THIS SECTION with your own experience, e.g. a government portal, visa system, myGov, Centrelink, or a system from your home country. Markers reward genuine personal reflection. -->

Before starting COIT11223, I viewed ADM mostly as a technical efficiency problem. I assumed that if a system was well tested, automation would be fairer than human decision-making because computers do not have bad days or personal prejudices. I had heard of Robodebt, but I understood it as "a buggy algorithm" rather than as an ethical and legal failure. I also assumed that keeping a "human in the loop" was a sufficient safeguard.

Over the term, the ethical theories from Week 4 and the ACS Code gave me tools to question those assumptions. As the artefacts below show, I now see ADM as a **socio-technical** system in which policy choices, legal interpretation, data quality, organisational culture and code all interact.

---

## 4. Analytical Framework Used in This Portfolio

Each artefact is analysed using the same framework so that my reflections are consistent and comparable.

**Ethical theories (Quinn 2020, Week 4 lecture):**

| Theory | Core question applied to ADM |
|---|---|
| Kantianism | Does the system treat people as ends in themselves, or merely as a means to savings or efficiency? Could the rule be universalised? |
| Act Utilitarianism | Do the total benefits of this specific deployment outweigh the total harms? |
| Rule Utilitarianism | What would happen if every agency adopted this rule for using ADM? |
| Social Contract Theory | Would rational citizens agree to this system? Does it protect the least advantaged (Rawls)? |
| Virtue Ethics | What would an honest, fair and practically wise ICT professional do? |

**ACS Code of Professional Conduct values (Australian Computer Society 2014):** 1.2.1 Primacy of the Public Interest; 1.2.2 Enhancement of Quality of Life; 1.2.3 Honesty; 1.2.4 Competence; 1.2.5 Professional Development; 1.2.6 Professionalism.

**ADM lifecycle safeguards (Attorney-General's Department 2024, pp. 17–31):** pre-implementation (risk assessment); system-level (audit, legal compliance, updating); decision-level (human referral, substitution, notification, reasons); post-decision (merits review).

---

## Artefact 1 – Australian Government ADM Consultation Paper (2024)

**Artefact:** Attorney-General's Department, *Use of automated decision-making by government: Consultation paper* (November 2024)
**Type:** Government policy document
**Link:** https://consultations.ag.gov.au/integrity/adm/user_uploads/consultation-paper-use-of-automated-decision-making-by-government.pdf

<!-- Optional: insert a screenshot of the cover page, e.g. ![AGD consultation paper](images/artefact1.png) -->

### Justification

**Summary:** This consultation paper responds to Robodebt Royal Commission Recommendations 17.1 and 17.2 by proposing a consistent legal framework for government ADM (Attorney-General's Department 2024, pp. 5–6). It defines ADM as the use of a "computer program" to automate decision-making, and it distinguishes rules-based systems from machine-learning AI (Attorney-General's Department 2024, p. 7). It found that 46 Commonwealth Acts already authorise ADM in inconsistent ways (p. 5). It also names four key risks: algorithmic bias, coding errors, inflexible application of discretion, and de-skilling of officers (p. 10).

**Why I chose it:** This artefact answers the first framing question, "What is ADM?", using the Australian Government's own definition. It also gave me a lifecycle model of safeguards (pre-implementation, system-level, decision-level and post-decision), which I use to evaluate every other artefact in this portfolio.

### Reflection

**What I learned about ADM:** I learned that ADM is not new. Section 6A of the *Social Security (Administration) Act 1999* has allowed computer programs to make decisions since 2001 (Attorney-General's Department 2024, p. 5). The problem is not automation itself but the piecemeal way it was authorised, without consistent safeguards. I was also surprised by the paper's admission that, as Robodebt showed, considerable harm can occur before complaint-based processes such as merits review stop unlawful action (Attorney-General's Department 2024, p. 16). Waiting for victims to complain is therefore not an adequate safeguard.

**How the artefact demonstrates this learning:** The paper's list of decision types (p. 15) helped me recognise that a "human sign-off" can be meaningless if the officer conducts no real analysis of the computer's recommendation. This changed my earlier assumption that a human in the loop is always protective.

**Links to unit material:** From a **Kantian** perspective, the Royal Commission's call for plain-language explanations and published business rules (p. 5) respects people as rational agents who are entitled to understand and challenge decisions about them. From a **Social Contract** perspective, citizens accept welfare conditions only on the understanding that rules are lawful and reviewable. The paper's proposed audit body and review rights try to restore that contract. Under the ACS Code, the proposed pre-implementation risk assessments (pp. 20–21) put **1.2.1 Primacy of the Public Interest** and **1.2.4 Competence** into practice.

**Why it is meaningful evidence:** This artefact is the "baseline" for my portfolio. It shows I can define ADM accurately, distinguish ADM from AI, and use a structured safeguard framework rather than relying on general opinions.

---

## Artefact 2 – Allars (2024): Robodebt and Administrative Review

**Artefact:** Allars, M. (2024) 'Automated decision-making and review of administrative decisions', *Georgia Law Review*, 58(3)
**Type:** Peer-reviewed journal article
**Link:** https://digitalcommons.law.uga.edu/glr/vol58/iss3/8

### Justification

**Summary:** Allars, a Sydney Law School academic, surveys Australian federal ADM schemes and analyses Robodebt in depth. Robodebt's "online compliance intervention" averaged each person's annual tax-office income into twenty-six equal fortnightly amounts and compared them with reported earnings (Allars 2024, p. 1168). This averaging rule was unlawful, and the letters demanding proof of income reversed the statutory onus of proof onto welfare recipients (Allars 2024, p. 1169). The Commonwealth raised about $1.763 billion in debts against roughly 433,000 people (Allars 2024, p. 1171).

**Why I chose it:** This scholarly, 2024 source challenged my belief that "the algorithm" caused Robodebt. Allars (2024, p. 1173) argues the unlawfulness was a product of human agency, and that ADM simply let the wrongdoing be carried out more efficiently (Allars 2024, p. 1182).

### Reflection

**What I learned about ADM:** The most important lesson was that ADM **amplifies** whatever policy is coded into it, including an unlawful one. Allars (2024, pp. 1172–1173) notes that the government persisted with income averaging despite early legal advice that it was unlawful. Automation turned one bad policy decision into hundreds of thousands of individual debts. I also learned that ADM affects vulnerable people unevenly. Casual workers with fluctuating incomes and poor fortnightly records were the people the averaging method was most likely to get wrong (Allars 2024, p. 1169).

**How the artefact demonstrates this learning:** The article traces the full chain from legal interpretation, to encoded business rule, to automated letter, to debt recovery. This let me see exactly where an ICT professional could have intervened. Allars (2024, p. 1148) also explains that ADM may apply rules inflexibly and shut out whole classes of eligible people without considering exceptional cases.

**Links to unit material:**
- **Kantianism:** Reversing the onus of proof treated recipients as a means to budget recovery, not as ends in themselves. The maxim "presume a debt unless the person can disprove it" could not be universalised without destroying trust in government.
- **Act Utilitarianism:** This theory exposes a weakness. A department focused on dollars recovered could calculate a "positive" outcome, while severe personal distress and later restitution costs went uncounted.
- **Rule Utilitarianism:** The theory gives a clearer verdict: a rule allowing agencies to automate debt-raising without confirming its legality would produce enormous harm if universally adopted.
- **ACS Code:** **1.2.3 Honesty** was breached when known legal concerns were not acted on. **1.2.1 Primacy of the Public Interest** requires professionals to raise concerns even when an employer wants a system delivered.

**Why it is meaningful evidence:** It is peer-reviewed, Australian and directly about government ADM. It shows I can engage critically with academic analysis and change my own position based on evidence.

---

## Artefact 3 – Ombudsman Report on the Targeted Compliance Framework (2025)

**Artefact:** Commonwealth Ombudsman, *Automation in the Targeted Compliance Framework: when the law is changed but the system isn't* (August 2025), with follow-up AAP reporting (June 2026)
**Type:** Government investigation report and news article
**Links:**
- Report summary: https://www.austaxpolicy.com/news/commonwealth-ombudsman-finds-cancellation-of-income-support-payments-under-target-compliance-framework-unlawful/
- Follow-up news: https://aapnews.aap.com.au/news/system-that-cancelled-welfare-payments-taken-offline

### Justification

**Summary:** The Ombudsman found that the Department of Employment and Workplace Relations and Services Australia unlawfully cancelled income support under the Targeted Compliance Framework (Commonwealth Ombudsman 2025). Post-Robodebt laws required officers to consider each jobseeker's circumstances before cancelling payments, but the automated system was never updated. As a result, 964 people lost payments between April 2022 and July 2024 (Garbutt-Young 2026). The department had also not created the Digital Protections Framework required by statute (Commonwealth Ombudsman 2025). In 2026 the system was taken offline for an extended rebuild (Garbutt-Young 2026).

**Why I chose it:** This is a current Australian case that happened after the Robodebt Royal Commission. It shows that lessons were not learned and makes system maintenance an ethical issue.

### Reflection

**What I learned about ADM:** I learned that ADM systems can **become** unlawful without anyone writing new code. When Parliament changes the law but nobody updates the system, the system keeps applying the old rules automatically. The Attorney-General's Department (2024, p. 23) had already identified "requirement to update the system throughout its lifecycle" as a necessary safeguard. The Targeted Compliance Framework shows what happens when that safeguard is missing. The Ombudsman also found that quality assurance failed to detect the problem and that there was significant delay between identifying the unlawful cancellations and pausing them (Commonwealth Ombudsman 2025).

**How the artefact demonstrates this learning:** The report title, "when the law is changed but the system isn't", captures a gap between policy teams and technical teams. The Ombudsman found insufficient consultation between policy and operational areas within the department, and with Services Australia (Commonwealth Ombudsman 2025). This is exactly where ICT professionals sit.

**Links to unit material:**
- **Virtue Ethics:** The question is not only "what rule was broken" but "what kind of professional allows a known risk to persist?" Practical wisdom and diligence would mean actively checking that systems reflect current law.
- **Social Contract Theory:** Parliament changed the rules to protect jobseekers, but the automated system broke that agreement. This undermines public trust in the whole compliance system.
- **ACS Code:** **1.2.4 Competence** includes keeping work consistent with legal requirements. **1.2.5 Professional Development** requires staying current with changes that affect my work. **1.2.2 Enhancement of Quality of Life** was clearly not served when vulnerable jobseekers lost income support.

**Why it is meaningful evidence:** It connects the unit to what is happening in Australian society during my studies, and it proves that Robodebt was not a one-off. It also shows that I can identify a specific professional duty (system maintenance and change management) rather than only general ethical principles.

---

## Artefact 4 – DTA Policy for the Responsible Use of AI in Government v2.0 (2025)

**Artefact:** Digital Transformation Agency, *Policy for the responsible use of AI in government*, version 2.0 (effective 15 December 2025)
**Type:** Whole-of-government policy
**Link:** https://www.digital.gov.au/ai/ai-in-government-policy

### Justification

**Summary:** This policy sets mandatory requirements for how non-corporate Commonwealth agencies adopt and govern AI (Digital Transformation Agency 2025). It replaces the first version, which took effect in September 2024. Agencies must:
- publish an AI transparency statement;
- designate accountable officials;
- appoint an accountable owner for each in-scope AI use case;
- keep an internal register of use cases;
- complete impact assessments and report high-risk uses to the DTA.

**Why I chose it:** After studying failures, I wanted to examine Australia's governance response. This artefact shows what responsible practice now formally requires of government ICT teams. It also lets me critically assess whether policy alone is strong enough, given that the Targeted Compliance Framework failed despite existing legal duties.

### Reflection

**What I learned about ADM:** I learned that Australia regulates government AI mainly through **policy and guidance**, not a single ADM statute. The Attorney-General's Department (2024, p. 11) explains that the ADM legal reform is meant to complement, not duplicate, these AI policies. This creates a layered but fragmented system, which Allars (2024, p. 1181) criticises as multiple complex guides, mostly expressed at a high level, with fractured lines of responsibility for compliance.

**How the artefact demonstrates this learning:** The policy's accountability roles respond directly to the problems in Artefacts 2 and 3, where nobody clearly owned the legality of the system. Its transparency statements also partly implement the Royal Commission's recommendation that agencies explain their use of automation publicly (Attorney-General's Department 2024, p. 18). However, I noticed a limitation: the use case registers are shared with the DTA, not necessarily with the public, so affected citizens may still not know how a decision about them was made.

**Links to unit material:**
- **Rule Utilitarianism:** The policy is rule-based ethics in practice. It creates general rules whose consistent application across agencies is expected to produce better outcomes than case-by-case judgement.
- **Kantianism:** The transparency requirements respect people's right to understand decisions about them.
- **ACS Code:** The accountable official role reflects **1.2.6 Professionalism** and **1.2.1 Primacy of the Public Interest**. Mandatory staff training supports **1.2.5 Professional Development**.

**Why it is meaningful evidence:** It shows I can move beyond criticising failures to evaluating solutions, which is what an ICT professional would need to do in a government role. It also demonstrates awareness that a governance document is only as good as its implementation.

---

## Artefact 5 – Sweden's Welfare Fraud Algorithm (Amnesty International, 2024)

**Artefact:** Amnesty International, 'Sweden: Authorities must discontinue discriminatory AI systems used by welfare agency' (27 November 2024)
**Type:** Human rights organisation statement based on investigative journalism
**Link:** https://www.amnesty.org/en/latest/news/2024/11/sweden-authorities-must-discontinue-discriminatory-ai-systems-used-by-welfare-agency/

### Justification

**Summary:** Amnesty International (2024) called on Försäkringskassan, Sweden's Social Insurance Agency, to stop using an opaque machine-learning system that flagged people for benefit-fraud investigations. An investigation by Lighthouse Reports and Svenska Dagbladet found the system disproportionately selected marginalised groups (Amnesty International 2024). Reporting identified women, people with foreign backgrounds, low-income earners and people without university degrees as over-flagged (Computer Weekly 2024). The agency refused to explain how the system worked. Sweden's privacy authority later announced the tool was no longer in use (Amnesty International n.d.).

**Why I chose it:** This is my international comparison. Unlike Australia's rules-based failures, it shows a machine-learning system producing biased outcomes, examined against the European Union's binding AI Act.

### Reflection

**What I learned about ADM:** I learned that machine-learning ADM can discriminate even when it never explicitly uses a protected attribute, because other data can act as proxies. The Attorney-General's Department (2024, p. 13) warns that AI systems may inherit human biases from their training data and cause systemic impacts on protected groups. This case is a real example. I also learned that opacity makes bias almost impossible to challenge. Amnesty (2024) noted that the agency's lack of disclosure made it hard even to determine where the system fell under the AI Act's risk categories.

**How the artefact demonstrates this learning:** The Swedish case shows the difference between a system being **accurate on average** and being **fair to individuals**. An investigation is itself a burden. People wrongly flagged experienced delays and legal hurdles in getting benefits they were entitled to (Amnesty International 2024).

**Links to unit material:**
- **Social Contract Theory (Rawls):** Rawls' difference principle asks whether a system benefits the least advantaged. Here, the burden of suspicion fell on low-income and marginalised groups, so the system fails this test.
- **Act Utilitarianism:** It may justify the system if fraud savings are large. However, this approach treats the cost borne by wrongly flagged individuals as a small number in a total, which is the theory's well-known weakness with minority rights.
- **ACS Code:** **1.2.2 Enhancement of Quality of Life** asks professionals to consider the needs of disadvantaged groups. **1.2.3 Honesty** is undermined when an agency will not explain how its system reaches outcomes.

**Why it is meaningful evidence:** It satisfies the requirement to examine a government system in another country. It also broadens my understanding from coding errors to algorithmic bias and shows how a stronger legal environment (the EU AI Act, in force from August 2024) can create pressure that Australia's current policy-based approach may lack.

---

## Artefact 6 – Bias in the UK DWP Universal Credit Fraud Model (2024)

**Artefact:** *Computing*, 'AI bias uncovered in UK welfare system' (December 2024), reporting on documents first obtained by *The Guardian* under Freedom of Information
**Type:** Technology news article
**Link:** https://computing.co.uk/news/2024/ai/ai-bias-uncovered-in-uk-welfare-system

### Justification

**Summary:** The UK Department for Work and Pensions (DWP) uses a machine-learning model to risk-assess universal credit advance claims. According to *Computing* (2024), an internal fairness analysis released under Freedom of Information found statistically significant outcome disparities based on age, disability, marital status and nationality. The DWP redacted key details, arguing that disclosure could help fraudsters game the system, and defended the tool because humans make the final decision. The article notes at least 55 automated tools in use across UK public authorities (*Computing* 2024).

**Why I chose it:** This artefact directly tests the "human in the loop" safeguard. That was the safeguard I trusted most before this unit, and it is the one the Robodebt Royal Commission called among the most effective (Attorney-General's Department 2024, p. 25).

### Reflection

**What I learned about ADM:** The key lesson is that a human making the final decision does not remove bias if the human only reviews cases that a biased model has already selected. The unfairness happens at the **selection** stage. This links to the Attorney-General's Department (2024, p. 10) warning that ADM can de-skill officers and increase reliance on, and default to, the system's output. A human officer who sees only flagged cases may treat the flag as evidence. I also learned about a real tension in transparency: publishing full business rules could help fraudsters, but secrecy prevents affected people from challenging bias (Attorney-General's Department 2024, p. 19).

**How the artefact demonstrates this learning:** The DWP's position (humans decide, so bias is acceptable) is exactly the argument I would have made before this unit. Seeing it criticised made me realise that safeguards must be judged by their **effect**, not their existence.

**Links to unit material:**
- **Virtue Ethics:** An honest and fair professional would publish enough of the fairness findings for independent scrutiny, rather than relying on redaction.
- **Kantianism:** Kant would object to treating individuals as statistical risk profiles based on characteristics they cannot control.
- **Rule Utilitarianism:** It suggests a rule that every government ML model must have published fairness testing before deployment, because the long-term benefit of public trust outweighs the short-term cost of some fraudsters adapting.
- **ACS Code:** **1.2.3 Honesty** requires not misrepresenting a system's reliability. Earlier assurances of "no immediate concerns" sit uneasily with later evidence of disparities. **1.2.1** requires putting the public interest above an agency's preference for secrecy.

**Why it is meaningful evidence:** Together with Artefact 5, it shows a pattern across countries: governments are using machine learning to target welfare fraud, and the same groups are repeatedly disadvantaged. It also demonstrates that I can critically evaluate a safeguard I previously took for granted.

---

## Comparative Analysis: Australia vs Other Countries

| Dimension | Australia: Robodebt | Australia: Targeted Compliance Framework | Sweden: Försäkringskassan | United Kingdom: DWP |
|---|---|---|---|---|
| **Technology** | Rules-based data matching | Rules-based compliance automation | Machine-learning risk scoring | Machine-learning risk scoring |
| **Main failure** | Unlawful policy encoded into the system | System not updated after a law change | Biased flagging and opacity | Biased selection and redaction |
| **Who was harmed** | ~433,000 welfare recipients | 964 jobseekers | Women, migrants, low-income groups | Groups by age, disability, marital status, nationality |
| **Safeguard that failed** | Legal review and merits review | Lifecycle updating and quality assurance | Transparency | Human-in-the-loop |
| **Response** | Royal Commission; AGD framework | Paused, then taken offline for rebuild | Tool discontinued after privacy authority involvement | Defended; continued scrutiny |
| **Regulatory setting** | Policy and guidance; ADM law proposed | Policy and guidance; ADM law proposed | Binding EU AI Act | UK guidance-based approach |

**Key finding:** Rules-based and machine-learning ADM fail in different ways. Rules-based systems mostly fail through **legal error**: wrong or outdated rules applied at scale. Machine-learning systems mostly fail through **bias and opacity**. In every case, the people harmed were those with the least power to challenge government decisions. This is why I believe ADM in welfare deserves the highest level of scrutiny.

---

## Conclusion: How My Understanding Has Changed

At the start of this unit, I saw ADM as a neutral efficiency tool and believed that testing plus human oversight would make it safe. My portfolio shows how that view changed:

1. **ADM is a policy amplifier, not a neutral tool.** Robodebt was a human legal error executed efficiently by a computer (Allars 2024, p. 1182).
2. **Lawful systems can become unlawful.** The Targeted Compliance Framework shows that maintenance and change management are ethical duties, not just technical tasks.
3. **"Human in the loop" is not automatically a safeguard.** The UK and Swedish cases show bias entering at the selection stage.
4. **Transparency is necessary but contested.** Every case involved some form of secrecy, and secrecy repeatedly hid harm.
5. **Governance is improving but fragmented.** Australia's DTA policy and proposed ADM framework are positive steps, but they rely heavily on agencies' good faith.

Of the theories studied, I found **Social Contract Theory**, particularly Rawls' focus on the least advantaged, the most useful for ADM in government. It explains why harm to vulnerable welfare recipients is especially serious even when a system looks efficient overall. The **ACS Code** turns that principle into concrete professional duties I can act on.

As a future ICT professional, I will apply these lessons in practice:
- Ask who is affected before building any system.
- Insist that legal requirements are verified before they are coded.
- Check that systems are updated when laws change.
- Push for fairness testing and meaningful transparency.
- Raise concerns early, even when it is uncomfortable.

---

## References

Allars, M 2024, 'Automated decision-making and review of administrative decisions', *Georgia Law Review*, vol. 58, no. 3, viewed 14 October 2026, <https://digitalcommons.law.uga.edu/glr/vol58/iss3/8>.

Amnesty International 2024, *Sweden: authorities must discontinue discriminatory AI systems used by welfare agency*, Amnesty International, 27 November, viewed 14 October 2026, <https://www.amnesty.org/en/latest/news/2024/11/sweden-authorities-must-discontinue-discriminatory-ai-systems-used-by-welfare-agency/>.

Amnesty International n.d., *Sweden 2025*, Amnesty International, viewed 14 October 2026, <https://www.amnesty.org/en/location/europe-and-central-asia/western-central-and-south-eastern-europe/sweden/report-sweden/>.

Attorney-General's Department 2024, *Use of automated decision-making by government: consultation paper*, Commonwealth of Australia, Canberra, viewed 14 October 2026, <https://consultations.ag.gov.au/integrity/adm/user_uploads/consultation-paper-use-of-automated-decision-making-by-government.pdf>.

Australian Computer Society 2014, *ACS code of professional conduct*, version 2.1, Australian Computer Society, Sydney, viewed 14 October 2026, <https://www.acs.org.au/content/dam/acs/rules-and-regulations/Code-of-Professional-Conduct_v2.1.pdf>.

Commonwealth Ombudsman 2025, *Automation in the Targeted Compliance Framework: when the law is changed but the system isn't*, Commonwealth Ombudsman, Canberra, viewed 14 October 2026, <https://www.austaxpolicy.com/news/commonwealth-ombudsman-finds-cancellation-of-income-support-payments-under-target-compliance-framework-unlawful/>.

*Computer Weekly* 2024, 'Swedish authorities urged to discontinue AI welfare system', *Computer Weekly*, viewed 14 October 2026, <https://www.computerweekly.com/news/366616576/Swedish-authorities-urged-to-discontinue-AI-welfare-system>.

*Computing* 2024, 'AI bias uncovered in UK welfare system', *Computing*, December, viewed 14 October 2026, <https://computing.co.uk/news/2024/ai/ai-bias-uncovered-in-uk-welfare-system>.

Digital Transformation Agency 2025, *Policy for the responsible use of AI in government*, version 2.0, Digital Transformation Agency, Canberra, viewed 14 October 2026, <https://www.digital.gov.au/ai/ai-in-government-policy>.

Garbutt-Young, L 2026, 'System that cancelled welfare payments taken offline', *AAP News*, 2 June, viewed 14 October 2026, <https://aapnews.aap.com.au/news/system-that-cancelled-welfare-payments-taken-offline>.

Quinn, MJ 2020, *Ethics for the information age*, 8th edn, Pearson, United States.
