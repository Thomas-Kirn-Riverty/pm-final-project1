# Instalment, Simplified PRD (Riverty BU Collection, A Fair Way Forward)

**Scenario:** Riverty BU Collection, A Fair Way Forward

**Author:** Me · **Status:** Draft · **Target:** High-Fidelity Prototype · **Persona:** Ana is a composite character. She draws mainly on N-01 (shift work, two open claims) and adds evidence from N-02 and N-05. All quotes are verbatim from the interview notes in data-pack.md.  Role  A shift worker with variable monthly income and two open claims, using the portal on her phone between shifts.  Goal  She wants to set up an instalment plan she can keep, so the letters stop and she isn’t caught out by a missed payment.  Friction (moment of misery)  The income question, where she stalls. N-01: “I opened it on my break. It asked for my income and I did not know if they meant this month or a normal month. I closed it and meant to come back.” The ticket behind it is T-206: no help text explains why income is asked or how long it is kept.  Choosing a plan by feel, where the harm lands. N-02: “I picked the plan with the lowest number of months because it looked like the right answer. The amount was too high and I missed the second payment.”  I treat the plan choice as her core friction because the interviews and the numbers both confirm it. Variable-income users miss 22.5% of payments, against 17.4% for fixed salaries and 19.0% overall (2,862 starters).  Supporting evidence N-05 (chat, one claim): “I was not sure what would happen if I paid late.” This matches T-208, where the chat confirms a plan without showing what happens after a missed payment. N-06 (three claims, tight finances): “I was scared to type the wrong number. What if they use it against me?” Her workaround today  She closes the tab, works out a figure elsewhere (inferred), picks a plan by a rule of thumb and may phone an agent. Only the closed tab and the rule of thumb are stated by participants.  How she maps to the initiative Problem: Shift workers pick plans they can’t keep because the portal gives them no way to judge affordability. Primary metric: Continuation from the affordability questions to the income document step for variable-income starters. The all-starter baseline is 80.7%. Guardrail: Agreement rate, 41.6% in her segment, with a floor of about 40.6%. Limits Composite: N-01 stalled and never chose a plan. N-02 chose a plan but has one claim and no stated shift work. No single interviewee lived both moments. Overlap: The pack has no cross-tabulation, so I can’t say how many people are both variable-income and two-claim. Multiple claims: Her question about handling several claims (N-03, T-202) isn’t solved by this initiative. Data status: All data is illustrative sample data.

## 1. The Big Picture
- **Vision:** Ana weiß an der Einkommensfrage, warum sie gefragt wird und wie lange die Angabe gespeichert bleibt, und macht weiter, statt den Tab zu schließen.
- **Press release:** BU Collection now explains why it asks about income, right at the question
New plain-language note tells people why their income is requested, how it is used and how long it is kept.
[City], [launch date] — BU Collection today introduced a short, plain-language explanation next to the income question in its digital instalment journey. People setting up a payment plan can now see why the question is asked before they answer it.
The problem: a personal question with no reason attached
People who are behind on a payment are asked to share their income at a stressful moment. Until now, the portal did not say why the question was asked, what the answer would be used for or how long it would be kept. People with varying pay also had to guess what the question meant. Some closed the page to work it out, and some worried the answer could be used against them.
What is new: the reason appears next to the question
A short note now sits directly beside the income question. It says why income is asked, what it is used for and how long it is kept, in everyday words with no legal jargon. The text is visible on a phone without leaving the page or tapping through to another screen. It was reviewed by BU Collection’s privacy and compliance teams [to be confirmed before release]. The question itself and the rest of the journey are unchanged.
Quote
“People who are behind on a payment are often asked for personal information at the hardest moment. If we ask for it, we should say why, and say it where they are looking. [Add a second sentence on trust and fairness.]”
— [Name], [Title], BU Collection [Placeholder quote: the named person must approve the wording before release.]
How it works: three steps, no extra screen
1. A person opens the instalment journey and reaches the income question.
2. Beside the question, a short note explains why income is asked, what it is used for and how long it is kept.
3. The person answers with that information in front of them, or leaves and returns knowing what the question is for.
Availability and what comes next
The explanation is available from [launch date] in the [German] portal, on mobile and desktop. BU Collection plans to continue improving the instalment journey, including making the income question itself clearer for people whose pay varies from month to month. [Confirm wording and timing with the product team before release.]
About BU Collection and press contact
About BU Collection: [Boilerplate to be supplied by communications.]
Press contact: [Name], [email], [phone]
Internal notes: remove before release
This release claims no results, because the pack has no outcome data for the feature. Three things must be settled first.
• Retention period: The pack does not state how long income data is kept. Privacy must supply it before the note can say so.
• Wording of reassurance: Any promise such as “not used against you” needs legal and compliance sign-off (N-12 requires decisions to be explainable).
• Placeholders: City, launch date, portal market, quote and named speaker, boilerplate and press contact are all unfilled.
Evidence behind the release: T-206 (no help text on the income question), N-01 (stalled at the income question), N-06 (fear of data use) and 419 monthly contacts asking why income is asked (16.2% of contacts). The feature does not define “this month or a normal month”, so the release only says the question is unchanged.
Data status: All figures and notes come from illustrative sample data, not Riverty research.
- **Success metric:** Continuation rate from the affordability questions to the income document step, measured for variable-income and shift-work starters.  Baseline (all starters): 80.7%, which is 5,943 of 7,364 people. 1,421 people (19.3%) are lost at this step (data-pack.md, Funnel). Segment baseline: Not in the pack. It needs journeys_sample_month.csv, which is missing, so it has to be measured first. Why this metric for the explainer It matches the stall: N-01 closed the portal at the income question and “meant to come back”. T-206 shows the question has no explanation. The explainer targets exactly that moment. It is fast: A pilot shows a signal within days, while the missed-payment gap takes at least 60 days. It targets Ana’s group: Variable-income starters (2,862) have the worst failure rate, 22.5% against 17.4% for fixed salaries. What it confirms and what it doesn’t Confirms: Less stalling at the income question. Doesn’t confirm: That the plans chosen afterwards are better. Higher continuation could also mean people click through without understanding. Lagging check: Missed payments within 60 days in the segment, currently 22.5%. Read alongside the guardrail  Agreement rate: 46.0% overall and 41.6% in her segment, with a suggested floor of about 40.6% in the segment (my assumption).  Limits Step granularity: The funnel step covers all affordability questions, not only income, so the pilot needs to log the income question separately. Cause not proven: A rise in continuation shows less stalling, not that the explainer caused it. Data status: All data is illustrative sample data.
- **Guardrail:** Agreement rate: the share of journey starters who end in an agreement.  Baseline: 46.0% overall, which is 3,846 of 8,360 starters. Pilot segment baseline: 41.6% for variable-income and shift-work starters (2,862). Source: data-pack.md, Baseline rates and User split. Why this metric It protects the existing base. The explainer adds text to a journey that already converts 46.0% of starters. If it pushes people out, this is where it shows first. It balances the primary metric. Continuation at the income step could rise because people click through, and the agreement rate catches it if they abandon later. It is fast. It is visible within the session, unlike the 60-day missed-payment rate. Suggested floor (my assumption) Pilot segment: About 40.6%, one point below its baseline. Everyone else: 46.0%. Rule: Stop or review if either is breached for two consecutive weeks.  The one-point tolerance and the two-week rule are my assumptions, not figures from the pack.  Companion checks Kept agreements per month: About 3,115. It is the final test but lags by 60 days. Fixed-salary agreement rate: 48.1%, which the pilot shouldn’t touch. Contacts asking why income is asked: 419 a month (16.2%). A fall supports the explainer, if the number of starters stays stable. Complaints reaching the client: Not in the pack. Limits Normal variation: The agreement rate moved between 43.1% and 46.3% over six months, so small dips can be normal swings. Segment baseline: The 41.6% comes from the user split, not row-level data, which isn’t in the pack. Data status: All data is illustrative sample data.

## 2. The Details
### User stories
- As a shift worker with variable income who is setting up an instalment plan on my phone,
- I want to see why the portal asks for my income, what it is used for and how long it is kept, right next to the question,
- so that I know what I’m agreeing to and keep going instead of closing the page.
- Acceptance criteria (my draft)
- Visible at the question: The note appears beside the income question without a tap or a new screen, on mobile and desktop.
- Three answers: It states why income is asked, what the answer is used for and how long it is kept.
- Plain language: It uses everyday words, with no legal terms.
- Approved wording: Privacy and compliance have signed off the text, including the retention period.
- Question unchanged: The question and the rest of the journey stay as they are.
- Measurable: The income question is logged as its own step, so continuation can be read for variable-income starters.
- Evidence behind it
- T-206: No help text explains why income is asked or how long it is kept.
- N-01 (two claims, shift work): Stalled at the income question and closed the portal.
- N-06 (three claims): “I was scared to type the wrong number. What if they use it against me?”
- Contacts: 419 a month (16.2%) ask why income is asked.
- How success is read
- Primary metric: Continuation from the affordability questions to the income document step, 80.7% for all starters.
- Guardrail: Agreement rate, 46.0% overall and 41.6% in her segment.
- Out of scope
- “This month or a normal month”: N-01’s confusion needs the question reworded, which belongs to the affordability check.
- Consequences of a missed payment: That gap sits at plan choice (T-208, N-05).
- Several open claims: N-03 and T-202 are a separate feature.
- Limits
- Open question: The retention period isn’t in the pack and must come from privacy.
- Unproven effect: Nothing shows that an explainer alone stops people leaving at this question.
- Data status: All data is illustrative sample data.
### Screens to build
- Screens to Build: Plain explainer for why income is asked
- The data pack lists no screens, so this is my reading of the feature. It changes one existing screen, not a new flow. 7,364 starters (88.1%) already reach the affordability questions, so the income question exists today.
- Screens and states
- #	Screen or state	New or changed	What it needs	Priority
- 1	Income question, mobile	Changed	The explainer note beside the question, visible without a tap. It says why income is asked, what it is used for and how long it is kept.	Must-have
- 2	Income question, desktop	Changed	The same note in the wider layout.	Must-have
- 3	Income question, small or narrow phone	Changed	A check that the note doesn’t push the field or the button off the screen.	Must-have
- 4	Income question with expanded details	New state	A short note always visible, with the longer text opening on a tap.	Should-have
- 5	Period hint beside the field	Changed element	A one-line hint on which period is meant. It is a stopgap until the question itself is reworded.	Should-have
- Not new screens
- Plan options and review: Unchanged (T-204 and T-208 are separate).
- Document upload: Unchanged (T-201 is separate).
- Chat and agent screen: Unchanged, although the same wording should reach both (should-have).
- Skip option: A could-have, and a separate decision.
- What to build in order
- Screen 1, then 2 and 3 once the wording is approved by privacy and compliance.
- Screens 4 and 5 if capacity remains.
- The measurement point for the income question, which isn’t a screen but is needed to read the primary metric.
- Open questions
- Layout today: The pack doesn’t say whether income is its own screen or one of several questions on a page. That decides how much space the note gets.
- Retention period: It isn’t in the pack, so the note can’t be finished until privacy supplies it.
- Language: The pack doesn’t say whether the portal needs wording in more than one language.
- Limits
- My interpretation: The screen list is derived from the feature name, T-206 and the evidence behind it, not from a specification.
- Data status: All data is illustrative sample data.
### Functional requirements
- Functional Requirements: Plain explainer for why income is asked
- These seven rules come from the three must-haves: the reason is explained, it appears at the question, and compliance confirms it. The pack contains no requirements, so every threshold below is my assumption and needs team confirmation.
- ID	Requirement	How to measure	Must-have it covers
- FR-1	The note appears on the same screen as the income question, with no tap or navigation needed.	Pass or fail on a 360 px-wide phone and on desktop, in each supported browser.	At the question
- FR-2	The note states 3 things: why income is asked, what the answer is used for and how long it is kept.	Content checklist, 3 of 3 present.	Why and how long
- FR-3	The retention period is stated as a concrete duration (for example, a number of months), not “as long as necessary”.	Pass or fail against the privacy-approved figure.	How long
- FR-4	The note is at most 60 words.	Word count.	At the question, readable on a phone
- FR-5	At least 4 of 5 test participants, including at least 1 shift worker, can say in their own words why income is asked and how long it is kept.	Short comprehension test before release.	Plain language
- FR-6	Privacy and compliance approve the final wording in writing before release.	Release is blocked without the approval record.	Confirmed wording
- FR-7	The income question stays unchanged: same label, field and number of steps in the affordability questions.	Step count and field list identical before and after.	Scope
- Two further rules I’d add for the pilot
- These support the primary metric and aren’t part of the must-haves.
- ID	Requirement	How to measure
- FR-8	The income question is logged as its own funnel event, firing in at least 99% of sessions that reach it, so continuation can be read by income pattern.	Compare event count with session count in test traffic.
- FR-9	The note meets a text contrast of 4.5:1 and causes no horizontal scrolling at 200% zoom.	Accessibility check.
- Where each rule comes from
- T-206: No help text explains why income is asked or how long it is kept (FR-1 to FR-4).
- N-06: “What if they use it against me?” (FR-2, FR-3, FR-5).
- N-12: Decisions must be explainable, so approval is documented (FR-6).
- Primary metric: Continuation from the affordability questions to the income document step (80.7% for all starters), which FR-8 makes readable for the segment.
- Limits
- Assumed thresholds: The 60 words, 4 of 5 participants, 99% and 4.5:1 are my choices. The 4.5:1 follows common accessibility guidance.
- Missing input: The retention period isn’t in the pack, so FR-3 can’t be checked until privacy supplies it.
- Unknown layout: The pack doesn’t say whether income is its own screen, which affects FR-1 and FR-4.
- Data status: All data is illustrative sample data.
### Smart behaviors (Situation → Outcome)
- Smart Behaviors: Plain explainer for why income is asked
- These are my draft rules for how the screen should respond in each situation. The data pack contains none, so I’ve marked which come from the must-haves and which are should-haves.
- Must-have
- If a person reaches the income question on any device → the note appears beside it with no tap or new screen.
- If the phone screen is narrow (360 px) → the note fits with the field and the button visible, and nothing scrolls sideways.
- If the person returns to the income question after going back or leaving → the note shows again, in the same place.
- If the retention period isn’t approved by privacy → the feature stays off, and no placeholder text is shown.
- If privacy changes the retention period → the note shows the new figure from one source, with no copy to update by hand.
- If the text size is raised to 200% → the note reflows and no words are cut off.
- If the income question is shown → a separate funnel event is logged with the income pattern, so continuation can be read for variable-income starters.
- Should-have
- If the person taps “more details” → the full explanation opens and the short note stays visible.
- If the person asks in chat or an agent is asked why income is requested → the same wording is used.
- Pilot only (my assumption)
- If a starter is in the control group → no note is shown, and the same events are logged for comparison.
- Left out on purpose
- “If income varies month to month → show a specific hint”: This needs the question reworded, which belongs to the affordability check.
- “If the person skips the question”: A skip option is a could-have and a separate decision.
- Limits
- My draft: The behaviours come from the must-haves, T-206 and N-06, not from a specification.
- Missing input: The retention period isn’t in the pack, so rules 4 and 5 can’t be tested until privacy supplies it.
- Data status: All data is illustrative sample data.
### Technical constraints
- Technical Constraints: What Not to Build
- The data pack gives no technical constraints, so this list is my proposal. It keeps the feature a small, text-level change to one existing screen. Each item is something I’d rule out for the explainer, with the reason.
- Production feature
- Don’t build	Why
- A new API or backend service	The note is static text. Nothing needs to be fetched or computed.
- A new database table or stored data	Nothing new is collected. The explainer shows information and doesn’t capture any.
- A new screen or step	The income question already exists (7,364 starters reach the affordability questions). A new step could cut agreement, the guardrail.
- Changes to the income question	The wording of “this month or a normal month” belongs to the affordability check, so FR-7 keeps the question unchanged.
- Personalised or dynamic text	No rules by income pattern, claim count or segment. That would add logic and review effort for an unproven gain.
- A content management system or admin tool	One text constant, or config value, for the note and the retention period is enough (the retention period must have a single source).
- New third-party scripts or tracking	Log one funnel event for the income question (FR-8) in the existing analytics. Never log the income value itself.
- Chat or agent-screen changes	The same wording for chat and agents is a should-have and a separate piece of work (T-208, T-205).
- A skip option or income ranges	Both change the question and the data it produces. They are could-haves for another decision.
- Its own experiment platform	Use the existing release mechanism for the control group in the pilot.
- If you build a prototype
- If you mean a clickable mockup to test the wording (FR-5), I’d use the same limits:
- One HTML file you can open in any browser, with inline CSS and JavaScript.
- No backend, no API calls and no stored data.
- No external libraries or fonts that need an internet connection.
- Dummy text and fictional data only, and no real consumer information.
- Why these limits
- Scope: The feature answers T-206 with text. Anything beyond the three must-haves (why, how long, at the question) belongs elsewhere.
- Risk: Less code means less review, and privacy and compliance sign-off (N-12) stays focused on the wording.
- Guardrail: No new step or field protects the 46.0% agreement rate.
- Limits
- My proposal: None of these constraints come from the pack or from a team decision. They need confirmation with engineering.
- Unknown stack: The pack doesn’t say how the portal is built, so I can’t say what a text change costs. My effort score of 1 is an assumption.
- Data status: All data is illustrative sample data.

## 3. The Logistics
### Features out
- Out of the explainer feature
- Out	Why
- New API or backend service	The note is static text.
- New database or stored data	The explainer shows information and doesn’t collect any.
- New screen or step	It could cut agreement, the guardrail.
- Rewording the income question	This belongs to the affordability check (FR-7).
- Personalised or dynamic text	It adds logic and review effort for an unproven gain.
- CMS or admin tool	One text value with a single source for the retention period is enough.
- New third-party scripts or tracking	Use one funnel event in the existing analytics.
- Chat and agent-screen changes	Same wording there is a should-have and separate work (T-208, T-205).
- Skip option and income ranges	They change the question and its data. I rated both as could-haves, and I’m moving them out of this release because they belong to another decision.
- Its own experiment platform	Use the existing release mechanism.
- Out of the initiative (roadmap cut list)
- Your roadmap cuts these four, using your IDs:
- B4: Pick a payment date that matches pay day.
- B5: Handoff summary for the agent.
- B6: One plan for several open claims.
- B7: Chat assistant on every portal page.
- B8 (“show the shortest plan first”) sits in LATER on your roadmap. I scored it as a reject, because it extends the Month 4 change, when missed payments rose from 15.6% to 18.4%. You may want to move it to the cut list.
- Limits
- My proposal: The pack contains no Won’t-Have list, so none of this comes from a team decision.
- Unknown stack: The pack doesn’t say how the portal is built, so engineering should confirm the technical items.
- Data status: All data is illustrative sample data.
### Edge cases & safety guard
- Edge Cases and Safeguards: Plain explainer for why income is asked
- The data pack lists none, so this is my draft from the feature’s risks. Each row follows the same If/Then logic as the smart behaviours.
- Edge cases
- Situation	Safeguard
- The retention period is missing or unapproved	The feature stays off. No placeholder or guessed figure is shown.
- Privacy changes the retention period	The note reads the figure from a single source, so no copy is left stale.
- A reassurance such as “not used against you” is not legally confirmed	It is left out of the text until legal and compliance approve it (N-12).
- Narrow phone (360 px) or text zoomed to 200%	The note reflows, and the field and button stay visible with no sideways scrolling.
- The person uses a screen reader	The note is read together with the question, in the same order as on screen.
- The note is longer than 60 words after a copy edit	The release check fails, and the text is shortened before launch.
- The person goes back or leaves and returns	The note shows again at the question. T-204 clears the affordability answers, and the note doesn’t depend on them.
- Chat or an agent answers with different wording	Same wording for both is a should-have until then. Agents and chat should not contradict the note.
- The portal needs more than one language	Each language version needs its own approved wording. The pack doesn’t say whether this applies.
- A person with varying pay still can’t tell what “income” means	The explainer doesn’t fix this, because “this month or a normal month” needs the question reworded. Track it as a known gap.
- The note causes more people to leave	See the guardrail below.
- The control group sees no note	The same events are logged so the groups can be compared.
- Safeguards
- Never log the income value. Only the funnel event (income question shown and passed) is logged, with the income pattern segment.
- No new data is collected. The explainer only displays text, so it adds no new privacy risk.
- Approval gate: Release is blocked without written privacy and compliance sign-off (FR-6).
- Kill switch: The note can be switched off without a new release, using the existing release mechanism.
- Rollback trigger (my assumption): If the agreement rate in the pilot segment falls below about 40.6%, or below 46.0% for everyone else, for two consecutive weeks, stop or review.
- Watch contacts: The 419 monthly contacts asking why income is asked should fall, as long as the number of starters stays stable. If they don’t, the note may not be seen or understood.
- Comprehension check before release: At least 4 of 5 test participants, including a shift worker, can explain why income is asked and how long it is kept (FR-5).
- Limits
- My draft: The edge cases and thresholds are my proposal, not from the pack or a team decision.
- Unknown stack: The pack doesn’t say whether a switch-off without a release is possible, so engineering should confirm.
- Missing input: The retention period isn’t in the pack and must come from privacy.
- Data status: All data is illustrative sample data.
### Decision log
- ID
- Decision
- Why
- D1
- Ana, a shift worker with variable income and two open claims, is the lead persona.
- Her segment has the worst failure rate, and her stall at the income question is documented.
- D2
- Optimise for kept agreements (no missed payment in 60 days), not agreement rate alone.
- Month 4 raised agreements and broken plans together, and kept agreements stayed flat at about 3,100.
- D3
- Primary metric: continuation from the affordability questions to the income document step for variable-income starters.
- It is fast, matches Ana’s stall and sits in the existing funnel.
- D4
- Guardrail: agreement rate.
- It shows first if the new text pushes people out, and it balances the primary metric.
- D5
- Guardrail floor of about 40.6% in the pilot segment and 46.0% elsewhere, reviewed after two consecutive weeks below.
- A one-point drop is roughly break-even on kept agreements if half the failure gap closes.
- D6
- Planning assumption: a team of 7 (2 backend, 2 frontend, 1 QA, 1 designer, 1 PM) and a 12-week window.
- The pack gives no team size or time window.
- D7
- NOW: the plain explainer for why income is asked (Value 4, Effort 1, Quick Win).
- It answers the missing help text and the 419 monthly contacts asking why income is asked.
- D8
- NEXT: the affordability check before the plan options, built on the existing affordability answers.
- It targets the plan chosen by feel and the unclear income question.
- D9
- LATER: a mobile upload that works, or no document under a set amount.
- It fixes real failures but acts after the step the primary metric measures.
- D10
- CUT: pay-day payment date, agent handoff summary, one plan for several claims, chat on every page.
- None moves the primary metric in 12 weeks, and each has a stated reason.
- D11
- The explainer is one text note on the existing income screen, with no new API, database, screen or change to the question.
- It keeps the feature small and protects the agreement guardrail.
- D12
- Rewording “this month or a normal month” belongs to the affordability check, not the explainer.
- The explainer cannot resolve that confusion on its own.
- D13
- Open: where does the retention period come from, and what is it?
- The note must state a concrete duration, and the pack gives none.
- D14
- Open: is a reassurance such as “not used against you” legally allowed?
- Legal and compliance must approve any promise before release.
- D15
- Open: should “show the shortest plan first” move from LATER to the cut list?
- It extends the Month 4 change, when missed payments rose from 15.6% to 18.4%.
### Evals
- #	Eval	Method	Pass rule	Covers
- E1	Placement	Check a 360 px phone and desktop in each supported browser	Note is on the same screen as the income question, and the label, field and step count are unchanged	FR-1, FR-7
- E2	Content	Checklist on the final text	All 3 elements present (why, what for, how long), a concrete retention duration, at most 60 words	FR-2, FR-3, FR-4
- E3	Approval	Check the sign-off record	Written privacy and compliance approval exists, and release is blocked without it	FR-6
- E4	Comprehension	Short test with 5 people, including at least 1 shift worker	At least 4 of 5 can say why income is asked and how long it is kept	FR-5
- E5	Accessibility	Contrast check, 200% zoom, screen reader	Contrast of 4.5:1, no sideways scrolling, note read together with the question	FR-9
- E6	Logging	Compare event count with session count in test traffic	Income-question event fires in at least 99% of sessions, and the income value is never logged	FR-8
- E7	Safe default	Remove the approved retention period in a test build	The feature stays off and no placeholder text appears	Smart behaviour 4
- During the pilot
- #	Eval	Method	Pass rule
- E8	Primary metric	Compare continuation from the affordability questions to the document step for variable-income starters, note vs no note	Higher than the control group. The baseline for all starters is 80.7%, the segment baseline is missing, and no target lift is set.
- E9	Guardrail	Track agreement rate weekly	At least about 40.6% in the pilot segment and 46.0% elsewhere. Two consecutive weeks below triggers a review.
- E10	Contacts	Compare contacts asking why income is asked per 100 starters	Lower than the baseline of about 5.0 per 100 (419 of 8,360, my calculation)
- What the evals can’t tell you
- Cause: E8 only shows the note helps if the control group is run at the same time. A before-and-after comparison would also pick up changes like the Month 4 plan order.
- Understanding: Higher continuation could mean people click through without reading, which is why E4 is separate.
- Plan quality: None of these evals checks whether the plans people choose afterwards are better. That needs the 60-day missed-payment rate, which is slower.
- Open points
- Target lift and sample size: The pack has none. Set them before the pilot starts, so a result isn’t judged after the fact.
- Segment baseline: journeys_sample_month.csv isn’t in the pack, so E8 has no starting figure for Ana’s group yet.
- Shift workers in E4: Only N-01 is explicitly a shift worker, so you’d need to recruit more.
- Data status: All figures come from illustrative sample data.

## MoSCoW scope
- **Must:** Das Must-have ist eine kurze, verständliche Erklärung direkt an der Einkommensfrage, die beide Fragen aus T-206 beantwortet: warum das Einkommen abgefragt wird und wie lange die Angabe gespeichert bleibt. Ohne diese beiden Aussagen löst das Feature das Ticket nicht.; Die Datenlage gibt nur diese Mindestanforderung her. Alles darüber hinaus ist meine Einschätzung.; Die drei Kernbestandteile; Warum: Ein Satz zum Zweck, zum Beispiel dass die Angabe hilft, einen passenden Plan vorzuschlagen. Das adressiert Anas Stopp bei der Einkommensfrage (N-01).; Wie lange und wofür: Die Speicherdauer und was mit der Angabe geschieht. Das adressiert die Angst vor Datenmissbrauch (N-06: “What if they use it against me?”).; Am richtigen Ort: Der Text steht an der Frage selbst, ohne dass Ana danach suchen muss, und ist auf dem Handy lesbar. Ein Hilfetext, den sie nicht sieht, ändert ihr Verhalten nicht.; Was zusätzlich zwingend ist; Die Aussagen müssen stimmen. Ein Versprechen wie “wird nicht gegen Sie verwendet” darf nur stehen, wenn Datenschutz und Compliance es bestätigen. N-12 verlangt, dass Empfehlungen erklärbar sind. Die Speicherdauer fehlt im Datenpaket und muss geklärt werden.; Einfache Sprache. Der Text soll ohne Fachbegriffe auskommen, weil Anas Problem Verständnis ist, nicht fehlende Information an sich.; Was kein Must-have ist; Definition von “diesen Monat” oder “normaler Monat”: Das löst N-01s Verwirrung wirklich, gehört aber zur Umformulierung der Frage und damit zum Affordability-Check (dein B2).; Folgen eines verpassten Zahlungseingangs: Diese Lücke liegt bei der Planwahl (T-208, N-05).; Überspringen-Option: Sie verringert die Angst, ist aber eine eigene Entscheidung.; Wie man das Must-have prüft; Primärmetrik: Die Fortsetzung von den Affordability-Fragen zum Dokumentschritt (80,7 % über alle Starter) sollte steigen. Die Einkommensfrage muss dafür separat gemessen werden.; Kontakte: Die 419 Kontakte zur Frage “Warum wird Einkommen abgefragt” (16,2 %) sollten sinken, sofern die Zahl der Starter stabil bleibt.; Grenzen; Wirkung unbewiesen: Nichts im Datenpaket belegt, dass eine Erklärung allein den Abbruch an der Frage verhindert.; Interpretation: Das Datenpaket nennt das Feature nur mit einer Zeile, die Bestandteile sind meine Ableitung aus T-206, N-01 und N-06.; Datenstatus: Alle Daten sind illustrative Beispieldaten.
- **Should:** Die Should-haves; Ein kurzer Hinweis, welcher Zeitraum gemeint ist. Ein Satz neben dem Feld wie “Gemeint ist ein typischer Monat” überbrückt N-01s Verwirrung (“this month or a normal month”), bis der Affordability-Check die Frage umformuliert. Das ist kein Ersatz für die neue Frage.; Kurztext sichtbar, Details auf Tipp. Auf dem Handy bleibt der Hauptsatz immer sichtbar, und die ausführliche Erklärung klappt auf. So bleibt der Bildschirm kurz, ohne dass Ana nach Informationen suchen muss.; Gleiche Formulierung in Portal, Chat und beim Agenten. N-04 bevorzugt das Telefon und N-05 den Chat, und beide sollten dieselbe Antwort bekommen. So bleibt die Erklärung konsistent, und die 419 Kontakte zu dieser Frage lassen sich mit demselben Wortlaut beantworten.; Getrennte Messung der Einkommensfrage. Der Funnelschritt deckt alle Affordability-Fragen ab. Ein eigener Messpunkt für die Einkommensfrage und für das Aufklappen der Details zeigt, ob die Erklärung wirkt. Ohne ihn lässt sich die Primärmetrik für diesen Schritt nicht sauber lesen, deshalb würde ich sie für den Pilot fast wie ein Must-have behandeln.; Textprüfung mit Schichtarbeitenden. Nur N-01 ist ausdrücklich Schichtarbeiter. Ein kurzer Test mit weiteren Betroffenen zeigt, ob der Text verständlich ist.; Warum das Should-haves sind; Verbessern das Ergebnis, ohne die Kernaufgabe zu ändern (warum und wie lange).; Kosten wenig, da es sich um Text, Gestaltung und Messung handelt (meine Einschätzung).; Abgrenzung; Must-have: Warum, wofür und wie lange, an der Frage selbst, bestätigt von Compliance.; Nice-to-have (Wunsch, nicht nötig): Überspringen-Option und Einkommensbereiche. Beides ist eine eigene Entscheidung und gehört eher zum Affordability-Check.; Grenzen; Wirkung unbewiesen: Das Datenpaket belegt nicht, dass eine Erklärung den Abbruch verhindert.; Segmentbasis fehlt: journeys_sample_month.csv liegt nicht vor, sodass es für Anas Gruppe keinen Ausgangswert gibt.; Datenstatus: Alle Daten sind illustrative Beispieldaten.
- **Could:** Could-have: Plain explainer für die Einkommensfrage; Ein Could-have ist ein Zusatz, den man nur macht, wenn Zeit bleibt. Er ist weder nötig, um T-206 zu lösen, noch verbessert er das Feature spürbar genug für ein Should-have. Das Datenpaket nennt das Feature nur mit einer Zeile, die Einordnung ist deshalb meine Einschätzung.; Die Could-haves; Ein Beispiel für schwankendes Einkommen. Ein kurzer Satz wie “Verdienen Sie je nach Schicht unterschiedlich, nennen Sie einen mittleren Monat” hilft Schichtarbeitenden wie Ana. Es ist nur ein Beispieltext, nicht die neue Frage selbst. Grundlage ist N-01, der Wortlaut müsste getestet werden.; Eine “Lieber nicht angeben”-Option. Sie könnte die Angst aus N-06 verringern (“What if they use it against me?”). Sie senkt aber die Datenqualität für die Planempfehlung und ist eine eigene Produktentscheidung. Deine strategische Karte nennt diese Spannung (“Data ask vs. trust”) bereits.; Einkommensbereiche statt einer genauen Zahl. Sie nehmen die Sorge, die falsche Zahl einzutippen (N-06). Sie ändern aber die Frage selbst und gehören damit zum Affordability-Check, nicht zum Erklärtext.; Derselbe Erklärtext vor dem Portal. In E-Mail, SMS oder Brief könnte ein Satz erklären, warum später nach dem Einkommen gefragt wird. Der Einstieg über den Brief-QR-Code hat mit 20,3 % die höchste Ausfallquote (E-Mail 18,1 %, SMS 19,3 %), aber das Datenpaket zeigt nicht, dass der Kanal etwas mit der Einkommensfrage zu tun hat. Das ist eine schwache Hypothese.; Verlinkung zu unabhängiger Beratung. Ein Hinweis auf eine Schuldnerberatung würde den Ansatz “Transparenz und Vertrauen” stützen. Dass Betroffene dort Rat suchen, ist abgeleitet und kommt in keinem Interview vor. Außerdem müssen Compliance und Kunde zustimmen.; Textvarianten testen. Zwei Formulierungen gegeneinander laufen zu lassen, zeigt, welche besser wirkt. Das lohnt sich erst, wenn Fallzahlen und Messung der Einkommensfrage stehen.; Warum das Could-haves sind; Dünne Belege: Keiner dieser Punkte wird durch ein Ticket oder mehrere Interviews gestützt.; Abhängigkeit von anderen Entscheidungen: Mehrere gehören eigentlich zum Affordability-Check oder zu Compliance und Kunde.; Geringes Risiko, geringer Effekt: Ohne sie bleibt das Feature voll nutzbar.; Übersicht; Stufe	Inhalt; Must-have	Warum und wie lange, an der Frage selbst, von Compliance bestätigt; Should-have	Zeitraum-Hinweis, Kurztext mit Details auf Tipp, gleicher Wortlaut in Chat und beim Agenten, getrennte Messung, Test mit Schichtarbeitenden; Could-have	Beispiel für schwankendes Einkommen, Überspringen-Option, Einkommensbereiche, Text vor dem Portal, Beratungslink, Textvarianten; Grenzen; Interpretation: Die Einordnung folgt meiner Einschätzung, nicht dem Datenpaket.; Kanalzahlen: Die Unterschiede zwischen den Eintrittskanälen sind Korrelationen, keine Belege für eine Ursache.; Datenstatus: Alle Daten sind illustrative Beispieldaten.
- **Won't (now):** ·

