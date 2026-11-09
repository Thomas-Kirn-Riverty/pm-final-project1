# Strategic Discovery Map (Module 1)

## Responses
- **Write one feature from the map that, if an engineer asked “why is this a priority for our 12-week roadmap?”, you honestly could not give a strategic answer for.:** Danke für die Unterlagen. Ich habe das Datenpaket gelesen. Es sind fiktive Übungsdaten für den Case “A Fair Way Forward” (digitaler Ratenzahlungs-Journey im deutschen Portal), aufgeteilt nach Modulen 2 bis 6. Hier eine kurze Orientierung, was mir beim ersten Durchgang auffällt:

Die Kernstory in den Zahlen

Der Trichter verliert die meisten Leute früh: Nur 22 % der Portal-Besucher starten einen Ratenplan. Danach sind die Abbruchquoten pro Schritt mit je ca. 17 bis 22 % recht gleichmäßig verteilt.
Von 3.846 Vereinbarungen fallen 19 % innerhalb von 60 Tagen mit einer Zahlung aus.
Ab Monat 4 wurde der 6-Monats-Plan zuerst angezeigt. Die Abschlussquote stieg von 44,2 auf 45,6 %, aber die Ausfallquote sprang von 15,6 auf 18,4 % und stieg weiter auf 19 %. Das ist der klassische Zielkonflikt zwischen Abschluss und Nachhaltigkeit, und Backlog-Item B7 (“kürzesten Plan zuerst”) würde ihn verschärfen.

Segmente mit auffälligen Unterschieden

Mehrere offene Forderungen: Die Abschlussquote sinkt von 52,1 % (1 Forderung) auf 27,6 % (3+), der Agentenkontakt steigt von 25,6 auf 43,0 %. Das passt zu T-202 und zur Kontaktursache “Können Forderungen kombiniert werden?”.
Variables Einkommen oder Schichtarbeit: niedrigere Abschlussquote (41,6 %) und die höchste Ausfallquote (22,5 %). N-01 und N-02 erklären das qualitativ.
Mobile gegenüber Desktop: 43,8 % gegenüber 54,0 % Abschlussquote, passend zu T-201 (Upload-Timeouts).
Chat-Nutzer: höhere Abschlussquote (53,3 %), aber auch höhere Ausfallquote (21,6 %). Das passt zu T-208 und N-05. Hier ist Vorsicht bei der Kausalität geboten (Selbstselektion).

Agentenkontakte
Die drei Top-Gründe (Was passiert bei verpasster Zahlung, Forderungen kombinieren, Warum wird Einkommen abgefragt) machen zusammen etwa 52 % aus. Alle drei sind prinzipiell durch bessere Information im Produkt adressierbar.

Was lässt sich damit machen?
Ich kann zum Beispiel:

Eine Problemanalyse bzw. Insight-Synthese für Modul 2 und 3 erstellen (Hypothesen mit Belegen aus Interviews, Tickets und Daten).
Das Backlog (B1 bis B8) mit Value- und Effort-Scores versehen und begründen, inklusive Priorisierung.
Metriken und Guardrails für Modul 5 ableiten (z. B. Abschlussquote gegen Ausfallquote und Beschwerden).
Pilotsegment und Annahmen für Modul 6 vorschlagen und die Zielgruppengrößen rechnen.
Daten prüfen oder Fragen dazu beantworten.

Eine Anmerkung: Die zwei CSV-Dateien (journeys_sample_month.csv und agent_contacts.csv) sind im Paket nur referenziert, nicht enthalten. Für Auswertungen auf Zeilenebene bräuchte ich diese separat. Für alles andere reichen die Tabellen im Dokument.

Woran arbeitest du gerade, und in welchem Modul stehst du? Dann steige ich dort direkt ein.

The primary user is a shift worker with two open claims. This is the “Ana” persona from N-01 and N-03, and the segment with the weakest numbers: 41.6% agreement and 22.5% missed payments.

Features ranked by effort vs. impact

Rank	Idea	Effort	Impact	Evidence
1	Why-we-ask explainer (B2)	Low	Medium-high	“Why is income asked?” is 16.2% of agent contacts (419); T-206
2	Save progress, fix the back button	Low	Medium	T-204; N-01 left meaning to come back
3	Income bands, with “typical month” or “this month”	Medium	High	N-01, N-06; variable-income plans miss payments most
4	One plan for several claims (B1)	High	High	Agreement is 37.7% with 2 claims and 27.6% with 3+; 17.3% of contacts

The effort and impact ratings are my estimates, not from the data pack. Item 4 is a separate feature from the check. I’d treat it as a bigger bet and a dependency to scope early.

Monetization paths and tradeoffs

The data pack has no pricing or revenue data, so these are hypotheses to test with the client account manager.

Fee per kept plan (no missed payment after 60 days) aligns revenue with fair outcomes. The tradeoff is slower, harder-to-measure revenue and a contract change.
Fee per agreement is simple to measure, but it rewards volume. It can push providers toward higher rates and shorter plans, which is the same trap as the 6-month-first change.
Reporting add-on for clients covers broken plans and complaints, which clients already watch (N-10). The data must be aggregated, so privacy review is needed.
Lower cost-to-collect is not revenue, but it is a real business case. The 419 income-question contacts take about 82 agent hours a month, an upper bound on what the check could save.

Retention risks and mitigations

Plan broken (19%): match the rate to the consumer’s income pattern, offer a pay-day date, and fix T-207, where the reminder arrives after the due date.
Silent drop-off: save progress and send a gentle resume link. N-01 meant to come back, and the funnel loses 17-22% per step.
Complaints reaching the client: track complaints as a guardrail next to agreement rate.
Fast chat confirming plans without consequences (N-05, T-208): show what happens after a missed payment before the person confirms.

Strategic tensions to debate

Data ask vs. trust: more detailed answers give better plans, but N-06 fears the data will be used against them. Ranges and a skip option reduce accuracy.
Extra step vs. drop-off: the check may lower the 46% agreement rate while lowering the 19% failure rate. The team needs to agree up front which matters more.
Fee per agreement vs. fee per kept plan: the pricing model decides whether the business wants sustainable plans or just more agreements.
Fast chat vs. advice: chat users agree more (53.3%) but miss more payments (21.6%). Speed may be hurting the people the product is meant to protect.

In the dark theme, the four coral tension labels may be hard to read. I can re-render the map with that fixed.

For the sprint, I’d start with tension 2, because the A/B test design depends on it. I can turn it into a test plan with hypothesis, metrics and guardrails.

Strategic crisis, based on the brief, if the company does nothing for 12 months, what happens to its market position?

I can’t answer the market-position part directly. The pack has no market share, competitor, client-contract or regulatory data, and I only have the data pack, not the brief text. Below I extrapolate the internal trends and then reason about what they could mean for position. The first part is data; the second is hypothesis.

What the numbers say about “doing nothing”

The headline metric is hiding a stall. Agreement rate rose from 43.1% to 46.0% over six months, which looks like progress. But agreements that survive 60 days without a missed payment (my calculation: agreements × (1 − missed-payment rate)) have been flat since Month 2.

Month	Agreements	Missed payment within 60 days	Kept agreements
1	3,495	15.2%	about 2,960
2	3,735	15.9%	about 3,140
3	3,658	15.6%	about 3,090
4	3,850	18.4%	about 3,140
5	3,793	18.8%	about 3,080
6	3,846	19.0%	about 3,115

The extra agreements since the 6-month-first change in Month 4 are being cancelled out by extra broken plans.

Two scenarios for Month 18 (my assumptions, not forecasts):

Plateau: missed payments stay near 19%. Kept agreements stay around 3,100 a month, so there is no growth and no collapse.
Creep: missed payments keep rising at the Month 4-6 pace of about 0.3 points a month, reaching roughly 22-23%. At flat agreements that is about 140 more broken plans a month (about 3,850 × 3.6 points), and kept agreements fall to around 3,000.

What stays unsolved either way:

The 22% who start the journey is unchanged, so 78% of portal visitors still don’t begin.
About 35% of starters (2,968) have two or more open claims, and they agree at 37.7% or 27.6% versus 52.1% for one claim.
Variable-income users (2,862 starters) keep missing 22.5% of payments.
Mobile users (6,563 starters) convert at 43.8% versus 54.0% on desktop. Closing that gap would mean roughly 670 more agreements a month (my arithmetic, an upper bound).
Agent contact has improved slowly, from 33.4% to 31.0%. I wouldn’t extrapolate that trend. Roughly 2,600 contacts a month still arrive for the same reasons.
What this could mean for market position (reasoning, not evidence)

The risk is a slow erosion, not a sudden crisis, and the growing agreement rate could delay anyone noticing.

Client trust. N-10 says clients care about complaints as much as recovery, and broken plans show in their reporting. A rising missed-payment rate could weaken the case at contract renewal even while agreements look healthy.
Regulatory and fairness exposure. The trend shows a plan default that raised agreements and broken plans together. N-12 says every recommendation must be explainable to consumers and agents. If that is ever challenged, “we saw the effect and did nothing” is a weak position. This is my inference, and the pack contains no regulatory facts.
Competitive leapfrogging. If others offer one plan for several claims, affordability-aware options and mobile-first uploads, Riverty’s baseline would look weak by comparison. The pack has no competitor data, so this is an assumption to test.
Cost to serve. With no change, the same contact reasons keep consuming agent time. At about 12 minutes each, the three top reasons (what if I miss a payment, combine claims, why income is asked) are roughly 1,350 contacts a month, about 270 agent hours.

Doing nothing is a decision to keep optimising for agreements while sustainable outcomes stall.

What I’d watch

If missed payments cross about 20% for two months, or complaints start rising, the “slow burn” becomes a client conversation. I’d define those thresholds before the next review so the trigger isn’t set after the fact.

I can turn this into a one-page “cost of inaction” brief with the two scenarios charted, or draft the questions to ask the client account manager to fill the market-position gap.
- **Write one feature that looks “correct” for the app but has zero strategic weight, you have no idea if it helps the company make money or whether a single user actually asked for it.:** _(not filled in)_
- **Compare V3 to your Step 1 baseline. What changed, and is the output objectively better, did the AI get smarter, or did your added PM knowledge (JTBD, effort/impact, retention) force it to be useful?:** _(not filled in)_
- **Key takeaway: how does this prove the PM’s role is to think while the AI’s role is to execute?:** _(not filled in)_
