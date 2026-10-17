# Appendix A: Decision Framework Templates

This appendix collects the main decision frameworks from across the book in a single reference. Each template is designed to be used directly - in a meeting, a governance review or a planning session. They are starting points, not fixed formats. Adapt them to your organization's terminology and context.

Some frameworks are described in their chapters rather than templated here, such as the build vs buy factors in Chapter 8 and the change conversation in Chapter 9.

## A-1: The augmentation audit

Use this to map tasks in a role or workflow before deciding what to delegate to AI.

For each significant task, score it High / Medium / Low on two dimensions, then record your recommendation.

**Task:** _______________________________________________

**AI suitability** (High / Medium / Low): _______

*High if the task involves drafting, summarizing, transforming, formatting or applying a consistent approach at volume. Low if it requires current information, verified facts, organizational context or judgment calls.*

**Human value-add** (High / Medium / Low): _______

*High if the task depends on experience, relationships, accountability, tacit organizational knowledge or consequential judgment. Low if it is primarily mechanical or templated.*

**Recommendation:**
- High AI suitability + Low human value-add -> delegate to the intern, with the supervision level set using A-3
- High on both -> hybrid: AI handles volume and first pass, people handle judgment
- Low AI suitability + High human value-add -> keep with people
- Low on both -> question whether the task needs to be done at all
- Medium or mixed scores -> start with the hybrid approach and a higher supervision level, then adjust as evidence builds

*Copy this block for each task in the role or workflow.*

## A-2: The four-part brief template

Use this when briefing your Digital Intern on any task where output quality matters.

**Role**
Who is the intern for this task? What perspective or expertise should they bring?

> Example: *You are a communications advisor helping a senior manager prepare for a difficult team meeting.*

**Task**
What specifically do you need? Be precise about format, length and purpose.

> Example: *Write a one-page briefing note summarizing the three main concerns likely to be raised and suggesting a response to each.*

**Context**
What does the intern not already know that is essential for this task?

> Example: *The meeting follows a restructure announcement last week. The team has concerns about role changes and reporting lines. The manager wants to acknowledge concerns without making commitments that have not yet been approved.*

**Constraints**
What should the output not include? What limits apply?

> Example: *Do not reference specific salary changes. Keep the tone calm and factual. No longer than one page.*

## A-3: The supervision level decision

Use this to assign and record supervision levels for AI-assisted tasks.

**Task description:** _______________________________________________

**Step 0: Non-negotiable check.** Does this task fall into any of these categories?
- [ ] Decisions that affect individuals in consequential ways (hiring, performance, credit, access to services)
- [ ] Outputs with legal or regulatory exposure
- [ ] Novel or ambiguous situations where the right answer is genuinely uncertain

*If any box is ticked, human review is required regardless of the levels below.*

**Reversibility** - can errors be corrected after the fact?
- [ ] High - errors are easily corrected after the fact
- [ ] Medium - errors can be corrected, with effort or cost
- [ ] Low - errors are hard to undo once the output has been acted upon

**Verifiability** - can a human quickly check whether the output is correct?
- [ ] High - easily checked against a source
- [ ] Medium - requires some effort to verify
- [ ] Low - difficult or time-consuming to verify

**Stakes** - what is the consequence if the output is wrong?
- [ ] High - significant harm to individuals, organization or reputation
- [ ] Medium - correctable but costly
- [ ] Low - minor and easily fixed

**Familiarity** - how well do we know how the intern performs on this task type?
- [ ] High - strong track record on this specific task type
- [ ] Medium - some experience, some uncertainty
- [ ] Low - new task type, no track record

**Recommended supervision level:**
- [ ] Level 1 - review everything (any non-negotiable category, or any High stakes, Low familiarity, Low reversibility or Low verifiability)
- [ ] Level 2 - spot check (Medium stakes, Medium familiarity, and at least Medium reversibility and verifiability)
- [ ] Level 3 - exception-based (Low stakes, High familiarity, and clear escalation criteria set from outside, such as output type, thresholds, sensitive topics or automated checks - not the intern's own confidence)
- [ ] Level 4 - autonomous (Low stakes, a well-defined and repeatable task, High familiarity, High reversibility and High verifiability only)

**Named owner:** _______________________________________________

**Review date:** _______________________________________________

*Record the result in the task register (A-8).*

## A-4: The risk register

Use this to document and manage the seven risks of AI adoption in your organization. Complete one block per risk. Review quarterly.

**Risk 1 - Confident wrong answers**
- Likelihood in our context (High / Medium / Low): _______
- Potential impact (High / Medium / Low): _______
- Mitigations in place: _______________________________________________
- Owner: _______________________________________________

**Risk 2 - Data leakage**
- Likelihood: _______
- Impact: _______
- Mitigations: _______________________________________________
- Owner: _______________________________________________

**Risk 3 - Regulatory and legal exposure**
- Likelihood: _______
- Impact: _______
- Mitigations: _______________________________________________
- Owner: _______________________________________________

**Risk 4 - Bias in decisions**
- Likelihood: _______
- Impact: _______
- Mitigations: _______________________________________________
- Owner: _______________________________________________

**Risk 5 - Reputational harm**
- Likelihood: _______
- Impact: _______
- Mitigations: _______________________________________________
- Owner: _______________________________________________

**Risk 6 - Skill atrophy**
- Likelihood: _______
- Impact: _______
- Mitigations: _______________________________________________
- Owner: _______________________________________________

**Risk 7 - Cost overrun**
- Likelihood: _______
- Impact: _______
- Mitigations: _______________________________________________
- Owner: _______________________________________________

**Last reviewed:** _______________________________________________

## A-5: The business case checklist

Use this before presenting a business case for an AI initiative.

**Problem statement**
- [ ] The problem is stated in terms of what the organization currently spends time or money on - not in terms of what AI can do
- [ ] The problem is specific and measurable

**Costs**
- [ ] Tool fees and subscriptions included
- [ ] Infrastructure costs included
- [ ] Oversight and checking time estimated and costed
- [ ] Process change and training costs estimated
- [ ] Error correction costs estimated
- [ ] Total cost model reviewed by someone independent of the initiative

**Benefits**
- [ ] Time saved per task specified
- [ ] Volume of tasks specified
- [ ] What the recovered time will be used for specified
- [ ] Value of recovered time specified and justified
- [ ] Assumptions listed explicitly and available for challenge

**Scalable-win test**
- [ ] It applies to a large enough volume of work to produce meaningful aggregate savings
- [ ] It improves in value with use
- [ ] It frees time that was genuinely constrained, rather than just speeding up an existing task

**Success metrics**
- [ ] Specific metrics defined
- [ ] Baseline measurement taken or planned
- [ ] Review date specified
- [ ] Named person responsible for reporting

## A-6: The stage-gate questions

Use these at each stage transition to decide whether to proceed, refine or stop. The stages are described in Chapter 8.

**Gate into Prove** (experiment complete when...)
- [ ] Output quality meets the defined bar
- [ ] The organization can use it effectively without special support
- [ ] The economics work at the volume projected
- [ ] A decision document has been written and reviewed independently

**Gate into Scale** (prove complete when...)
- [ ] Consistent results over typically at least three months of production use
- [ ] Error tracking in place and reviewed
- [ ] Supervision levels explicit and maintained
- [ ] A scaling plan documented before scaling begins

**Gate into Embed** (scale complete when...)
- [ ] Volume, user and task scope all assessed separately
- [ ] New users trained and supervised as new starters
- [ ] Task scaling treated as a new experiment with its own gate
- [ ] Governance owner named and active

**Ongoing gate** (embed healthy when...)
- [ ] Governance absorbed into standard operating procedure
- [ ] Quality reviewed at least quarterly
- [ ] Named owner for each application still in role and engaged
- [ ] Regulatory context reviewed for changes since last review

*All gates should be assessed by someone independent of the team that ran the current stage.*

## A-7: The ten board questions - prepared answers template

Use this to prepare for a board-level conversation about AI. Complete before the meeting.

**On risk**

1. What risks does our use of AI create and how are we managing them?

   *Your answer:* _______________________________________________

2. What data are we putting into AI systems and what happens to it?

   *Your answer:* _______________________________________________

3. What would happen if an AI output caused harm to a customer, employee or third party?

   *Your answer:* _______________________________________________

**On governance**

4. Who is responsible for AI decisions in this organization?

   *Your answer:* _______________________________________________

5. How do we know when AI output has been checked before it's acted upon?

   *Your answer:* _______________________________________________

6. What would we do if something went wrong?

   *Your answer:* _______________________________________________

**On value**

7. What is AI actually delivering for us and how do we know?

   *Your answer:* _______________________________________________

8. What is it costing us, including the costs we don't see directly?

   *Your answer:* _______________________________________________

**On strategy**

9. Are we ahead of, behind or in line with our peers on AI adoption?

   *Your answer:* _______________________________________________

10. What decisions do we need to make at board level about AI in the next twelve months?

    *Your answer:* _______________________________________________

## A-8: The task register

Use this to record the tasks your organization uses AI for and the supervision level assigned to each (Chapter 3). Complete one block per task or task category. Review quarterly and whenever a review trigger occurs.

**Task or task category:** _______________________________________________

**Supervision level (1-4), set using A-3:** _______

**Rationale for that level:** _______________________________________________

**Named owner:** _______________________________________________

**Review triggers** (conditions that cause the level to be reconsidered, such as a new audience, a regulatory change or a cluster of errors): _______________________________________________

**Last reviewed:** _______________________________________________

## A-9: The audit trail record

Use this for any AI-assisted decision that could later be questioned (Chapter 5). For high-volume, low-stakes work a lightweight log can capture the same four elements.

**1. AI use**
- System: _______________________________________________
- Purpose: _______________________________________________
- Date: _______________________________________________

**2. Output** (what it was, or at least what it was used for): _______________________________________________

**3. Human review applied before the output was acted upon:** _______________________________________________

**4. Final decision made by:** _______________________________________________

*These records may themselves contain sensitive information. Apply your data policy to them (Chapter 4).*

## A-10: The sign-off protocol

Use this to define what authorization is required before AI output is acted upon, published or sent (Chapter 5).

**Categories of output that require sign-off before use** (for example customer communications, regulatory submissions, decisions affecting individuals, public statements):

_______________________________________________

**Seniority required to sign off, by category:**

_______________________________________________

**What sign-off means in practice** (what the reviewer must check, not just that a review occurred):

_______________________________________________

*Example of a meaningful standard: "Reviewed for factual accuracy against primary sources by someone with appropriate expertise."*

**Protocol owner:** _______________________________________________

**Review date:** _______________________________________________

## A-11: The maturity assessment

Use this to assess honestly where your organization sits on the maturity model in Chapter 10. Tick the level whose description best matches reality today, not where you want to be, and note the evidence.

- [ ] **Level 1 - Experimental.** Individuals and teams use AI independently, with no coordination, policy or systematic evaluation.
- [ ] **Level 2 - Coordinated.** Approved tools, emerging data policy and some cross-team learning, but fragmented governance.
- [ ] **Level 3 - Governed.** Clear policies, supervision frameworks and accountability structures, with documented use and active risk management.
- [ ] **Level 4 - Optimized.** Skilled briefing, calibrated oversight, systematic learning and governance embedded in the workflow.
- [ ] **Level 5 - Adaptive.** Able to evaluate and absorb new AI developments quickly and wisely.

**Evidence we can point to for the level ticked:** _______________________________________________

**The main risk at this level (see Chapter 10):** _______________________________________________

**Leadership focus for the next level:** _______________________________________________

## A-12: The ten executive questions - prepared answers template

Use this to test whether your AI program has governance or only activity (Chapter 10). Complete before a leadership review.

1. What is our organization's AI risk appetite and who approved it?

   *Your answer:* _______________________________________________

2. Which AI applications in our organization carry the most significant risk and what is being done to manage each?

   *Your answer:* _______________________________________________

3. Who is accountable for AI governance overall and what does that accountability include in practice?

   *Your answer:* _______________________________________________

4. How do we know when AI is being used in ways that fall outside our policies?

   *Your answer:* _______________________________________________

5. What is the total cost of our AI program, including oversight, process change and error correction?

   *Your answer:* _______________________________________________

6. What value has our AI program delivered and how do we know?

   *Your answer:* _______________________________________________

7. How do our AI capabilities compare to our most capable competitors?

   *Your answer:* _______________________________________________

8. What regulatory changes in the next twelve months are most likely to affect our AI program?

   *Your answer:* _______________________________________________

9. What organizational capabilities - skills, processes, culture - are we building for the long term and which are we outsourcing to vendor tools?

   *Your answer:* _______________________________________________

10. If our primary AI vendor disappeared tomorrow, what would be the impact and how quickly could we recover?

    *Your answer:* _______________________________________________
