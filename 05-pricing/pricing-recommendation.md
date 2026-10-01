# Pricing & Packaging Recommendation — Roamly Groups

> Module 5 · Increase Revenue Through Smarter Pricing and Packaging — ★ Deliverable 5
>
> Propose a pricing model and packaging structure for a product with no existing price. Work in order: value first, packaging second, research last — then compile a one-page recommendation for stakeholders.

## 1. Pricing goal

- **Goal:** **Enter a new market: prove that group booking on Roamly is a real, repeatable behavior and seed the invite loop.** Not maximize revenue from a known audience, and not defend a position.
- **Why this is the right commercial goal now:** The bet (Deliverable 2) depends on a product-led loop: organizers bring in invitees, and invitees create new accounts. Any friction in price works against that loop, especially on the invitee side, where trust in a platform they don't know is the riskiest assumption. Groups is a new behavior for Roamly, so adoption has to come before margin optimization. Revenue still arrives: recovered group sessions that used to drop off, larger baskets (several tickets per booking), and existing host commission (A1).

## 2. Pricing model

- **Model:** **Transaction-based hybrid.** Free to organize; value is event-driven (each group booking), so a per-booking structure fits better than a subscription. A subscription would charge the organizer for a behavior that happens a few times a year and would put a price barrier in front of the loop.
- **Who pays — and for what?**
  - The **organizer** gets the most value (relief from fronting and chasing) but is the person we least want to charge, because they are our loop starter. They pay nothing to organize.
  - **Invitees** pay for their own share of the experience, and they are the party most sensitive to anything that looks like an extra fee.
  - The **default hypothesis:** if there is a service fee on the middle tier, it is folded into the per-person price shown up front ("all-in"), the way Viator and GetYourGuide present prices with no separate checkout fee *[S2]*, rather than added as a surcharge at checkout. **Who bears the fee is the single biggest open question** (see section 4).
- **Cost floor (so the price covers its own costs):** Using the 2.9% + $0.30 benchmark *[S5]* as a stand-in for Roamly's actual rates (A1), one $480 booking split across eight $60 payments costs about $2.10 more to process than one payment (3.40% vs 2.96% of the basket, a gap of about 0.4%). Splitting is cheap to support but not free, because the fixed fee repeats per payer.

**Market reference points *[S5]*:** SquadTrip charges a 6% fee paid by the traveler; WeTravel's free plan charges 2.5% per transaction; Stripe-level processing is about 2.9% + $0.30. Viator keeps roughly 20% of gross bookings from suppliers, and GetYourGuide takes a supplier-specific commission *[S2]*. Those sources set the range, not the answer.

## 3. Packaging approach

- **Structure:** **Combination: by accounts (group size) and by features, in a Good-Better-Best ladder.** Group size is the natural dimension (a 4-person trip and a 15-person trip are different jobs), and features such as payment reminders and polls reflect how much of the organizer's work Roamly takes over.
- **Audiences & fit:** Two audiences from Deliverable 4. The **organizer** chooses the tier. The **invitee** doesn't choose a tier, so the structure must never confuse them: the invitee sees one thing, their exact share. One ladder serves both because the choice sits with the organizer.

| Tier | Who it's for | Price | What's included |
|---|---|---|---|
| **Group Basics** | Small groups trying Groups for the first time (up to about 6 people) | **Free to the organizer; no group service fee** | Group booking via invite link · each person pays their own share · shared itinerary |
| **Group Plus** ★ | Most friend-group and celebration organizers (up to about 15 people) | **Per-person service fee, hypothesis range 0–5% of each share** (test cells: 0%, 3%, 5%); final value from research | Everything in Basics + payment deadlines and automatic reminders · availability polls and preference voting *(subject to V1 scope, A4)* · spots held until the payment deadline *(subject to host and Finance rules, A5)* · multi-experience itineraries |
| **Group Concierge** | Large or complex groups (16+), including early corporate and wedding-party demand | **Waitlist / custom quote at launch; no new product built** | Everything in Plus + host coordination for private-group requests · invoicing *(to be scoped only if demand is proven)* |

★ **Goldilocks middle: Group Plus.** It's the tier we route most organizers toward, because it takes over the work organizers hate most (chasing). Basics gets people in the door and seeds the loop; Concierge exists to **measure** demand for bigger and corporate groups without breaking the "no enterprise features at launch" commitment from the bet.

**Rollout rules (Module 5: a pricing change is a launch):**
- *Localization is not currency conversion.* Roamly operates in 40 cities *[Brief]*; fee levels and the per-person price sensitivity need local research before the fee goes live outside the first markets.
- *Grandfathering:* none needed for a brand-new feature. The policy is set up front so early-beta organizers are not penalized later; anyone in the beta keeps Plus pricing for a defined period.
- *Monitoring:* an agreed dashboard and rollback threshold before any fee is turned on (see tripwires in Deliverable 6).

## 4. Research to validate

*A PM doesn't run these studies; the job is to name what to commission and the assumption it tests.*

- **Method:** **Van Westendorp** to set the acceptable per-person fee range, plus **Max-Diff** to rank which Plus features organizers value most (reminders, polls, spot hold, multi-experience itineraries). Conjoint is a later step if the ladder grows.
- **Respondents:** recruited against the ICP: organizers who have planned a group experience in the last 12 months (existing Roamly users and non-users), plus a separate invitee sample, with age and group size captured so results can be sliced.
- **Assumption to validate:** Organizers and invitees accept a small, all-in per-person fee on Plus (0–5%) in exchange for removing fronting and chasing, **without lowering the share of invitees who pay**.
- **The one thing that would change everything if we got it wrong:** **Who bears the fee.** If invitees punish any visible group fee, the whole loop slows, and the right answer is to absorb the fee in host commission (or charge nothing) and monetize through volume instead. This is tested in the closed beta, with fee cells compared on the invitee payment rate.

## 5. The one-page recommendation

> We recommend a **transaction-based hybrid with three Good-Better-Best group tiers** (free Basics, a Plus tier with a small all-in per-person fee, and a Concierge waitlist) for Roamly Groups, to **prove group booking is a repeatable behavior and seed the invite loop**, because **the organizer's burden is the unsolved problem, and the one thing that could break the loop is friction on the invitee side**.

For each stakeholder, what they most need to hear:

- **Finance** (margin & revenue model): Splitting a payment costs only about 0.4% of the basket more to process at benchmark rates (A1), so the economics hold. Revenue comes from recovered drop-off and bigger baskets, with the Plus fee as upside rather than the base case. The fee level is a tested range, and Finance owns the rollback threshold.
- **Sales Leadership** (it closes deals): This lands first with hosts and partners, since the people closing deals here are the Host Partnerships team. Hosts get larger confirmed parties, payments secured before the day, and fewer no-shows (to be verified with hosts, A7). The Concierge waitlist gives them a place to log bigger and corporate requests without a new product.
- **Product Marketing** (the story that lands): "One link, everyone pays their own share" is the story, so the price must never contradict it. An all-in per-person price keeps the invitee's number simple. Free Basics is the proof point for "no fronting".

**Validate first:** The invitee payment rate under three fee cells (0%, 3%, 5%) in the closed beta, before any fee is turned on at launch. Pair it with the Van Westendorp study for the range and the Max-Diff for tier contents.

## Link to full artifact

Pricing Builder Output: `05-pricing/roamly-pricing.md`.

## Sources

- **[S2]** [Best Tour Booking Sites 2026: GetYourGuide vs Viator & More](https://www.findingtheuniverse.com/best-tour-booking-sites/)
- **[S5]** [7 Best Group Travel Payment Platforms Compared (2026)](https://www.squadtrip.com/guides/best-group-travel-payment-platforms-compared/) — published by SquadTrip, a vendor; fees are indicative.
