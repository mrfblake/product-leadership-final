# Product Strategy One-Pager & OKRs: [Fable / Meridian / your initiative]

> Module 1 · Craft an Advanced Product Strategy, ★ Deliverable 1
>
> Your one spine: the **Playing to Win** cascade, one deliberate **hard no**, and an **OKR cascade** that flows directly from it.
> Draft the cascade + hard no in Sprint 1, then add the OKRs in Sprint 2. The goal: specific enough that a skeptical board member couldn't poke a hole in it.

## 0. Chosen scenario

**Path:** _Fable Growth (B2C · retention + engagement) · Meridian Foundations (B2B · adoption + expansion) · my own initiative_

I picked it because currently I'm working in a B2B company so I'm more confident within the Meridian Foundations scenario.

## 1. Playing to Win cascade

| Question | Your choice |
|---|---|
| **Winning aspiration**: winning in the customer's terms, not internal metrics | Winning means Meridian becomes the superintendent's ultimate 'CYA' and daily relief tool—giving them a frictionless way to prove work is done, instantly flag blockers, and get the home office off their back so they can go home on time.|
| **Where to play**: segment, geography, channel, use case (the no's matter too) | We will play exclusively on the smartphones of superintendents and foremen on our core $50M+ enterprise projects. By focusing strictly on replacing the native camera and group text chain with a frictionless mobile capture tool, we solve the field adoption crisis for the Top 100 GCs first, creating a natural wedge to win back the $5M–$50M mid-market. We will leave complex administrative workflows on the existing desktop platform. |
| **How to win**: your differentiator competitors can't easily replicate |We will win through Asymmetric Value. Instead of building a 'reporting tool' for the office, we will use our incumbent access to identify the field's biggest personal bottlenecks—like dispute resolution or delayed RFI answers. We will build a frictionless, mobile-first utility that solves those specific field problems, acting as a 'Trojan Horse' that automatically generates the compliance data the enterprise backend requires without the field having to think about it.|
| **Capabilities required**: what you must be world-class at (build / buy / partner) | The UX researchers need to be explicitly tasked with Behavioral & Incentive Discovery, not just interface usability. They aren't just looking at where to put the "Submit" button; they need to shadow the foreman to find out what makes him curse, what makes him stay until 6 PM, and what information he hides from the PM. |
| **Management systems**: the metrics and rituals that reinforce your choices | We will govern this initiative with field-specific management systems. Instead of traditional engagement metrics, we will optimize for 'Time-to-Capture' and offline sync reliability, aiming to get users in and out in seconds. We will prove ROI to the enterprise by tracking the reduction in manual desktop data entry, and we will keep our 10-person squad grounded through mandatory job-site visits and direct, informal feedback loops with foremen|

## 2. Your one hard no

We are explicitly choosing not to write a single line of bespoke mobile code or build one-off app features for individual enterprise clients, no matter how large the contract. (We are trading the illusion of "white-glove mobile development" for a strict "configure, don't code" boundary.)

## 3. OKR cascade

**Objective:** Establish Meridian as the frictionless, indispensable daily habit for field teams, seamlessly bridging the mud and the back-office.
KR1 (Speed & Habit): Decrease the average time required for a superintendent to capture and log a field issue from 3 minutes (current manual desktop/email workaround) to under 15 seconds.
KR2 (Measure the "CYA" value): Reduce the average time it takes a superintendent to resolve an on-site dispute or blocker with the PM office from 2 hours to 30 minutes.
KR3 (Enterprise Translation): Increase the percentage of daily site photos, logs, and initial RFIs that originate directly from the mobile app from 5% (current state) to 75%, proportionally reducing manual end-of-day desktop data entry.
KR4 (Measure Voluntary Habit): Achieve a 60% DAU/MAU ratio among superintendents without any corporate mandates requiring them to use the app.


## 4. AI pressure-test notes

_Run the devil's-advocate prompt (in the Sprint 2 guide). Capture the verdict._

| Prompt question | What the AI surfaced | Change or defend? |
|---|---|---|
| Biggest assumption that could be wrong | 1. The single biggest assumption you are making that could be wrong You are assuming the barrier to field adoption is purely UI/UX friction (speed and offline capability). The real barrier might be that superintendents and foremen hate the system of record entirely. They use WhatsApp and their camera roll because it is a closed, informal loop that the back-office can’t scrutinize in real-time. You are assuming that if you make it frictionless to report to the "corporate beast," they will gladly do it. If their true incentive is to avoid micro-management, a faster app just means they can incriminate themselves faster. | The strategy pivot shifted the core premise from a Usability Mindset (fixing UI friction so the field will report to the office) to a Behavioral Mindset (solving the field's personal bottlenecks so they use the app voluntarily, which secretly feeds the office). Here is the summary of how that pivot changed the cascade: 1. Winning Aspiration Before: Focused on "keeping the home office informed without feeling like paperwork." After: Focused entirely on "protecting the field." Winning now means Meridian is the ultimate "CYA" (Cover Your Ass) tool that helps foremen instantly prove work is done, resolve blockers, and get the home office off their back so they can go home on time. 2. How to Win Before: Relied on using 38 Top-100 GCs as an R&D moat for co-creation. After: Relied on Asymmetric Value (The Trojan Horse). We win by identifying a massive personal pain point for the field (e.g., waiting on RFI answers, dispute resolution) and building a utility exclusively to solve that. The app acts as a Trojan Horse—the field uses it for their own relief, and the app automatically translates those actions into the compliance data the enterprise needs. 3. Management Systems & OKRs Before: Measured technical outputs and speed (99.9% offline sync rate, time-to-capture). After: Measures behavioral outcomes and voluntary habit. New OKR metric: Reduce the time it takes a superintendent to resolve an on-site dispute. New OKR metric: Achieve high Daily Active Usage (DAU) without any corporate mandates forcing the field to use it. 4. Capabilities Required Before: UX Research focused on "muddy boots" usability (glare, large buttons, offline capability). After: UX Research is upgraded to Behavioral & Incentive Discovery. The team must shadow foremen to discover what makes them stay late, what they hide from project managers, and what their true selfish incentives are, rather than just testing interface buttons.|
| The board question I can't yet answer | You said your 'How to Win' relies on turning our 38 Top-100 GC clients into a 'captive innovation lab' for co-creation. But your 'Hard No' explicitly refuses to build the bespoke workflows these exact clients will demand. How exactly do you plan to look a $50M+ client in the eye, ask them to co-create a product with you, and then tell them you refuse to accommodate their proprietary workflows—without them churning or escalating to the CEO? | Change the hard no: We are explicitly choosing not to write a single line of bespoke mobile code or build one-off app features for individual enterprise clients, no matter how large the contract. (We are trading the illusion of "white-glove mobile development" for a strict "configure, don't code" boundary.) |
| KRs that are outputs in disguise | 3. Are your KRs actually outputs disguised as outcomes? Yes. KR2 (99.9% offline sync rate) is an output disguised as an outcome. It is a technical Service Level Agreement (SLA)—the baseline output of competent engineering. It does not measure customer value, it measures if the app is broken or not.Furthermore, as a CSO, I’ll note that all three KRs are product usage metrics, not business outcomes. Where is the KR proving this stops the churn to mid-market competitors, or that it expands our ACV (Annual Contract Value)? You are measuring how fast the app works, not if the business is winning. | Changed |
| The "no" I should reconsider | 4. The case for reconsidering your "Hard No" You said you will not build bespoke or custom-configured mobile workflows. I argue you must reconsider this, or at least how you achieve it mechanically. You are targeting $50M+ enterprise projects. At that scale, a GC’s proprietary workflow (their specific safety protocols, their unique RFI routing) is their competitive advantage. Forcing a Top 100 GC to adapt to Meridian’s "standardized" field workflow is arrogant and will fail. You shouldn't build custom code for them, but you absolutely must build a configurable rules engine that allows their PMs to customize the mobile inputs without your 10-person squad writing a single line of bespoke code. If you lock them into a rigid box, they will leave.| Changed |
| Strategy or wish list? Why? | 5. In one sentence: is this a strategy or a wish list? Why? This is a wish list dressed up as a strategy because your core mechanism for winning (partnering with massive enterprises) directly contradicts your operating constraints (refusing their custom demands with only a 10-person squad). Now be harsher: what would a competitor’s strategy team say? "Meridian is completely paralyzed by the classic innovator's dilemma. They are trying to build a consumer-grade app with enterprise-grade compliance, using a tiny side-team of 10 people, while refusing to give their biggest clients what they actually want. They are going to build a generic 'snitch tool' that foremen will still refuse to use because it feeds the home office, and they’ll alienate the PMs by refusing to customize it. Let them play in the mud holding focus groups; we'll keep eating their $5M-$50M market share from the bottom up with a product that doesn't drag 10 years of enterprise technical debt behind it."| · |

## 5. Self-diagnostic (6 questions)

- [X] **Clear**: a new PM could read it and know exactly what we will and won't do
- [X] **Names the real challenge**: the diagnosis is specific enough to be uncomfortable
- [X] **Makes a hard bet**: it says no to something valuable
- [X] **Cascadable**: teams can translate it into their own OKRs
- [X] **Coherent**: every choice reinforces the others
- [X] **Committed**: resources are actually moving toward it

## Link to full artifact

_[link to your Strategy Sprint Builder export in your repo]_
