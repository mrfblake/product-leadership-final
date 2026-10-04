# Outcome Roadmap & Trade-off Memo: Meridian 

> Module 2 · Prioritization & Roadmapping for Product Leaders, ★ Deliverable 2
>
> Translate your strategy into a multi-team, outcome-driven roadmap, and a memo defending the hard prioritization calls behind it.

## 1. Outcome roadmap

_A multi-team roadmap organized by **outcomes**, not feature lists. Show how near-term revenue pressure is balanced against long-term platform bets._

| Horizon | Outcome / bet | Owning team(s) | Success signal |
|---|---|---|---|
| Now (0 to 3 mo) | Bet 1: We bet launching a standalone mobile app completely isolated from the PM's web platform will establish the initial daily capture habit and drive mobile origination (KR3) for superintendents and foremen. | Core Mobile Engineering | We see a sustained spike to 25% mobile origination for site photos and initial RFIs within the first 30 days of beta launch, proving they prefer the standalone app over their native camera roll.|
| Now (0 to 3 mo) | Bet 2: We bet stripping the daily log workflow from 14 required fields down to 4 will drive the interaction time under our 15-second threshold (KR1) for field teams doing data entry in the mud. | UX Research & Engineering | Production telemetry confirms 80%+ of mobile daily logs are completed in under 15 seconds, and PMs accept the logs without triggering rework or support tickets.|
| Now (0 to 3 mo) | Bet 3: We bet delivering real-time schedule and blocker push notifications will create immediate, selfish "CYA" value that drives unmandated daily app usage (KR2 & KR4) for superintendents managing active job sites. | Product & Engineering | We achieve a 60% DAU/MAU ratio specifically driven by users opening the app via push notification, and beta foremen report their dispute resolution time dropping below the 30-minute target.|
| Next (3 to 6 mo) | We bet deploying an unshakeable, offline-first background sync architecture will ensure zero data loss in dead zones and cement complete trust in the app for field teams working in concrete basements or remote sites. | Core Mobile Engineering.| We hit a 99.9% error-free background sync rate and receive zero support tickets from the field regarding "lost" photos or logs.|
| Next (3 to 6 mo) | We bet building an automated "Trojan Horse" backend translation layer will silently generate the 14-field compliance reports the home office demands without adding friction for superintendents. | Engineering | Enterprise PMs accept 100% of the mobile-generated data as contractually compliant, while the field's input time remains strictly under 15 seconds.|
| Next (3 to 6 mo) | We bet integrating native voice-to-text for issue capture will eliminate the friction of typing with hard hats and dirty gloves for foremen actively walking the job site. | Mobile Engineering & UX Research. | 50%+ of all text-based logs and RFIs originate via voice-to-text, further reducing our Time-to-Capture metric.|
| Later (6 to 12 mo) | We bet automatically pinning GPS, weather, and floorplan metadata to mobile photos will eliminate the need for manual contextual explanations and accelerate RFI answers for both field teams and home office PMs. | Mobile Engineering & Product. | The average time it takes a PM to understand and answer a field RFI drops by 50% because the metadata replaces back-and-forth text messages.|
| Later (6 to 12 mo) | We bet auto-generating indisputable timeline reports using timestamped mobile logs will instantly resolve subcontractor disputes and protect the GC's margin for Superintendents. | Backend Data/Analytics & UX. | Superintendents report their "CYA" dispute resolution time dropping from hours of arguing to minutes of simply exporting a Meridian timeline.|
| Later (6 to 12 mo) | We bet packaging this frictionless mobile app as a standalone, lightweight entry product will stop the bleeding and win back market share from simpler competitors for $5M–$50M mid-market contractors. | Product Lead & Go-To-Market / Sales. | A complete reversal of churn in the mid-market segment and a 20% increase in new logos in the $5M-$50M tier within two quarters of launch. |

_[screenshot or shareable link to your roadmap visual]_

## 2. Trade-off memo

_What did you sequence first, what did you push out, and what did you cut entirely, and why? Use WSJF / cost of delay reasoning where it helps._

I chose to sequence the standalone mobile app, the simplified 4-field log, and CYA push notifications first because they offer the highest risk reduction with the lowest job size. Our biggest strategic risk is behavioral will foremen actually use it? so we must validate that we can establish the 15-second capture habit before investing our limited engineering capacity in anything else.

I pushed out the unshakeable offline sync, the API translation layer, and the desktop rules engine because they carry a massive job size and strict sequential dependency. Building heavy infrastructure or PM configuration tools before proving the field will actually adopt the frontend UI risks wasting months of our 10-person squad's time on a bridge to nowhere.

I cut mobile project management dashboards and bespoke enterprise workflows entirely because they actively destroy our strategy. Dashboards introduce negative user value by bloating the UI and killing our 15-second speed metric, while custom coding for individual Top-100 GCs has an infinite job size that would instantly paralyze our lean team.

## Link to full artifact

_[link to this deliverable in your repo]_
