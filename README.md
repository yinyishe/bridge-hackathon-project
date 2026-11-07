# BRIDGE

**Turn information into actionable insights.**

A decision in one department changes the work of the others. A new technical concept in engineering means new prices in sales, new orders in procurement and new plans in construction. The decision gets documented, but what it means for everyone else usually doesn't.

BRIDGE answers three questions for every decision:

1. **What changed?** A simple before/after visual.
2. **What does it mean for me?** Tasks for your role, each marked *confirmed* or *to be checked*.
3. **Why was it decided?** The reason in two sentences, with more detail one click away.

## Demo

The prototype uses **Stuttgart 21** as an example project.

- **Dashboard:** KPIs for decisions and impacts (confirmed / still to check), plus a "new message" tile for the latest decision.
- **ImpactView:** For example, *New fire-fighting water supply approved*, which switches from a partially filled pipe with a circulation system to a dry pipe with feed-in points for the fire brigade.
- **Role views:** Use the user menu to switch between Mara Schulz (Sales), Jonas Keller (Procurement) and Lea Brandt (Construction planning). It's the same decision, with different tasks for each role.
- **Sources:** Official documents are kept apart from internal assumptions, so it's clear what is fact and what is interpretation.
- **Knowledge Graph:** Shows how decisions connect, e.g. jet fans replacing the central ventilation shaft, emergency exits every 500 m, and halogen-free cables.
- **Handoffs:** Long documents passed between teams become a short summary with key points and open questions, linked to the related decision. The reader marks a handoff as *Understood* so the sender knows it arrived.

## Run it

There's no build step and no dependencies. Open `index.html` in a browser.

## Status

This is a hackathon prototype. All data is hard-coded in `index.html`. The role-specific impacts, names and statuses are fictional assumptions made for the demo and are not part of any official decision.
