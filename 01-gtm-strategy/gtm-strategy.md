# GTM Strategy — Roamly Groups

> Module 1 · Build Your V1 GTM Strategy — ★ Deliverable 1
>
> **Reading guide.** Facts from the project brief are tagged *[Brief]*. External facts carry a source tag (*[S1]*…) listed at the bottom. Anything else is an **assumption** (*A1*…), listed in the register at the end, and is meant to be validated, not trusted.

## 1. The Discover Framework

| Lens | Your answer |
|---|---|
| **D**emand — who has the problem & how strong is the pull? | Roamly users are already trying to book for parties the product wasn't built for: coordinating across separate accounts, splitting payments by hand, syncing availability. Drop-off on these sessions is high and support feedback is consistent: people want to do this on Roamly *[Brief]*. Outside the product, group travel is mainstream: 54% of U.S. adults took a group trip in the last five years *[S1]*. |
| **I**deal customer profile (ICP) | **The organizer**: an existing Roamly user who plans experiences for a party of roughly 5–12 (friends' trips, birthdays, bachelor/bachelorette weekends, celebrations) and personally fronts the money and chases replies. Acute pain, authority to book, and already in Roamly's base. Group money friction is highest among Gen Z (72%) and Millennials (54%) *[S1]*, so expect the ICP to skew there (A6). |
| **S**egment & positioning angle | **Friend-group and celebration organizers.** Angle: relief for the organizer. Roamly Groups removes the unpaid-travel-agent job, so the person who plans the trip gets to enjoy it. (Why this segment over four others: see section 2.) |
| **C**hannels that reach them | Owned first. In-app prompts triggered by group behavior (an organizer starts a multi-person booking), email to users with abandoned group sessions, and the invite link itself, which is the growth channel. Earned: word of mouth in the travel communities and review platforms where Roamly built its reputation *[Brief]*. Paid: none at launch. |
| **O**ffer / value proposition | One link books the whole party. Everyone picks their share and pays it, and the group sees one shared itinerary. The organizer never fronts the total or chases anyone. |
| **V**alidation signal (what proves demand?) | Today: support flags, high group-session drop-off, and repeat booking at 3x the industry average *[Brief]*, plus market evidence that 45% of group travelers have experienced financial conflict or discomfort *[S1]*. After beta: share of invited participants who pay within 72 hours and the number of new accounts each group brings in (see section 5). |
| **E**conomics (rough CAC vs. value) | Organizers are existing users, so their acquisition cost is near zero. Invitees arrive through the loop at the cost of the invite flow, not an ad budget. Value comes from recovered group sessions and larger baskets (several tickets per booking). Cost: payment processing. At a 2.9% + $0.30 benchmark rate *[S5]*, paying one $480 order as eight $60 payments costs about $2.10 more than one payment (3.40% vs 2.96%), a gap of roughly 0.4% of the basket. Roamly's actual CAC, LTV and commission rates were not provided (A1). |
| **R**isks & unknowns | (1) Invitees won't sign up or pay quickly, which breaks the loop. (2) Groups cannibalize or confuse the individual booking flow that already works. (3) What happens when one person doesn't pay by the deadline is an unresolved product and policy question (A5). (4) Larger parties change host economics and capacity (A7). (5) Chargebacks and refund complexity grow with split payments. |

## 2. The problem & the audience

- **Problem worth solving:** Booking a group trip makes one person the unpaid travel agent. They collect replies in a group chat, front the money, keep the spreadsheet, and carry the social cost when someone drops out or pays late. The pain is more about the *burden on one person* than about booking logistics. Money is a large part of it: 45% of group travelers have experienced financial conflict or discomfort, and 82% say they would pay more than their fair share to avoid money arguments *[S1]*.
- **Primary ICP:** The organizer of a 5–12 person friend-group or celebration trip, already a Roamly user.
- **What they do today (the alternative):** A DIY stack of a group chat, a payments or expense app (Venmo, Splitwise) and a shared spreadsheet or doc. Venmo launched Groups in 2023 to track and settle shared expenses *[S6]*, and Splitwise only splits costs *[S4]*, so neither books anything. This stack is Roamly's primary competitor (see Deliverable 2).

**Segments considered (top five), and why friend-groups won:**

| Segment | Verdict |
|---|---|
| **Friend-group & celebration organizers** | **Chosen.** Already visible in Roamly's data, product is ready (split payments, shared itinerary, group booking), product-led motion fits, and the invitees create a growth loop. |
| Corporate team offsites | Higher contract value, but a sales-led motion, and V1 likely lacks invoicing, approvals and admin controls. Deferred. |
| Family reunions / multi-generational | Large and valuable but infrequent, with a slower repeat cycle. Second wave. |
| Destination wedding parties | High stakes and very custom. Better served after V1 proves the basics. |
| Clubs, communities and student groups | Plausible community-led channel later. Price-sensitive and harder to size now. |

**Working team (who must shape this, not just execute it):** Product and Engineering, Payments/Finance (margin, fraud, refunds), Analytics (baseline and instrumentation), Customer Support and Customer Success (the group-session signal), Host Partnerships (supply side), Product Marketing, and Legal/Trust & Safety (payments terms).

## 3. GTM motion

**Chosen motion:** **Product-led (PLG)**, with a light community-led layer (organizer word of mouth). Sales-led is deliberately deferred.

Five-input diagnostic:

| Input | Roamly Groups (organizers) | Points to |
|---|---|---|
| Time to value | Minutes: start a group, share a link, first payment lands | PLG |
| Buyer & user relationship | Organizer decides and books (buyer = user); invitees pay but didn't choose | PLG |
| Annual contract value | Low to mid: tens to hundreds of dollars per booking | PLG |
| Sales cycle | Self-serve | PLG |
| Scales via | Product virality: each group invites roughly 4–11 people | PLG |

Four of five inputs point the same way, and the fifth (scale) is the reason this segment is attractive. The corporate segment would flip several of them to sales-led, which is why it's a separate, later decision.

- **Goal:** **Expand** (existing users) first. Organizers are already experienced Roamly users. **Acquire** arrives through invitees, who are new to the product.
- **Acquisition:** Organizers come through in-app triggers and email aimed at users who start or abandon group-sized bookings. Invitees come through the organizer's link, so the product is the channel.
- **Activation:** An organizer is activated when they invite at least one person and the first participant pays. A group is activated when every participant has paid by the deadline. The invitee's first-run must be short: see the plan, see their exact share, pay.
- **Monetization:** Free to organize at launch. Revenue comes from recovered group bookings, larger baskets, existing host commission (A1), and an optional service fee on the middle tier (see Deliverable 5).
- **Launch tier:** **Tier 2, a focused GTM plan.** Reach is a subset of users plus their invitees, impact is high (new revenue and a growth loop), and risk is moderate (staying silent leaves the workaround in place, and a messy launch could hurt individual booking). A closed beta comes first.

## 4. V1 one-pager

> **For** trip organizers who end up chasing friends for replies and money, **Roamly Groups** is a **group-booking feature for curated local experiences** that lets one person book, split and plan for a whole party from a single link. **Unlike** a group chat, a payments app and a spreadsheet stitched together, **we** collect each person's share up front and keep everyone on one itinerary, so the organizer never fronts the cost.

**Three key messages:**
1. One link gets everyone in and paid up. *(Organizer relief.)*
2. You never front the money or chase anyone. *(Removes the social cost.)*
3. Everyone sees the plan and their own share before they pay. *(Builds invitee trust.)*

**Channel approach:** Owned first (in-app, email, invite link), earned through organizer and invitee sharing, paid held back until the loop proves out.

## 5. Success metrics

*Targets are **proposed starting points**. Roamly's baselines were not provided (A2), so each gets re-set in week 0 from analytics data.*

| Metric | Target | Why it matters |
|---|---|---|
| **North-star:** fully paid group bookings per month | Baseline in week 0; target set after the closed beta | Measures the whole job: everyone in, everyone paid |
| Leading: share of invited participants who pay within 72 hours | ≥ 70% (proposed) | The riskiest link in the loop; a low number means invitee friction |
| Leading: new-to-Roamly accounts created per group | ≥ 2 on average (proposed) | Shows the virality that justifies a product-led motion |
| Leading: group-session completion rate | Close at least half the gap to individual-session completion (proposed) | Shows the original problem, high drop-off, is being fixed |
| Guardrail: individual-booking conversion | Within ±2% of a holdout (proposed) | Protects what already works |

## 6. The assumption I'm most worried about

**Invitees will join from a link and pay their share quickly, with little friction (A3).**

If invitees stall, the organizer ends up chasing people again, only now inside Roamly, and the product-led loop never starts. **How to test it:** in the closed beta, measure invite-to-payment conversion within 72 hours, and A/B two invitee flows: pay first and create an account afterward, versus account first. Decide the launch flow from the result. Also decide the unpaid-share policy (A5) before beta, because it shapes what the organizer fears most.

## Assumption register

| ID | Assumption | How to validate |
|---|---|---|
| A1 | Roamly already earns commission from hosts and margins can absorb payment processing; processor rates resemble the 2.9% + $0.30 benchmark *[S5]*. | Finance confirms actual rates and commission. |
| A2 | Group-session drop-off is measurable and a baseline can be set in week 0. | Analytics pulls the baseline. |
| A3 | Invitees can join with minimal information (account creation after payment is possible) in V1. | Engineering confirms scope; test in beta. |
| A4 | V1 includes the invite link and group booking, payment of each person's share by a deadline, and a shared itinerary. Lightweight availability or preference alignment may also be in scope. | Product confirms V1 scope. |
| A5 | A policy exists for unpaid shares (for example, the organizer chooses to cover the spot or release it). | Decide with Product, Finance and Host Partnerships before beta. |
| A6 | The typical party is 5–12 and skews Gen Z and Millennial. | Check session data. |
| A7 | Hosts can accommodate parties of roughly 12 (the brief says the network can support the product *[Brief]*). | Host Partnerships confirms capacity limits per experience type. |
| A8 | Booking and planning activity peaks in early January, which supports a post-holiday launch window. | Check Roamly's own seasonality. |

## Link to full artifact

Final deck: `06-launch/final-presentation.html` (HTML) and `06-launch/final-presentation.pptx` (PowerPoint).

## Sources

- **[S1]** CIT Bank / Harris Poll survey (n = 2,067 U.S. adults, May 2026): [82% of Group Travelers Will Pay a 'Peace Tax'…](https://www.prnewswire.com/news-releases/82-of-group-travelers-will-pay-a-peace-tax-to-avoid-money-arguments-cit-bank-survey-finds-302807226.html)
- **[S4]** [Best Group Trip Planner Apps Compared (2026): Wanderlog, TripIt & More](https://www.weplanify.com/en/alternatives/best-group-trip-planner-apps)
- **[S5]** [7 Best Group Travel Payment Platforms Compared (2026)](https://www.squadtrip.com/guides/best-group-travel-payment-platforms-compared/) — published by SquadTrip, a vendor; treat the fee figures as indicative.
- **[S6]** [Venmo gets a new way to split expenses among groups (TechCrunch, Nov 2023)](https://techcrunch.com/2023/11/14/venmo-gets-a-new-way-to-split-expenses-among-groups-like-clubs-teams-trip-buddies-and-more)
