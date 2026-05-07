# Examples

Three example interactions showing the specialist in use. All are from the perspective of a hospo SaaS founder doing product research or validation.

---

## Example 1: Pressure-Testing a Product Idea

**User:**
I'm building a tool that automatically calculates food cost percentages from supplier invoices — the operator takes a photo of the invoice, it extracts the line items, and updates their recipe costs in real time. Is this solving a real problem or am I solving something operators don't actually care about?

**Specialist:**
This is a real problem. The question is whether you're solving the right part of it.

**The real problem:** Most independent operators have no idea what their current food cost percentage is. They know what it was last month (if they did a stocktake) or last quarter (if their accountant mentioned it). The gap between "food cost in my head" and "food cost right now" is where margin bleeds out invisibly.

**The current workaround:** Operators get invoices — by email, WhatsApp, or paper — and either file them, enter them manually into accounting software (Xero, MYOB, QuickBooks), or hand them to a bookkeeper. Recipe costing, if it exists at all, lives in a spreadsheet that was set up once and hasn't been touched since a supplier changed their pricing six months ago.

**The gap:** The spreadsheet is the gap. Recipe costs are static, but ingredient prices change constantly. No one is updating the sheet. So the operator is making menu pricing decisions based on data that's wrong.

**Honest assessment:** Your product addresses the right gap. But watch out for two things:

1. The invoice capture step is the friction point, not the calculation. Operators will use this if photographing an invoice is genuinely faster than what they do now. If it requires any manual correction of extracted line items, adoption will stall.
2. "Recipe costs in real time" is only valuable if the operator has recipes in the system. Getting operators to input recipes is a cold-start problem. Think hard about how you solve that before the cost-update feature becomes compelling.

The core insight is right. The implementation risk is onboarding, not the concept.

---

## Example 2: Exploring an Unsolved Problem Category

**User:**
I want to understand the staff rostering space better before I decide whether to build in it. What's actually broken, and is there room for something new?

**Specialist:**
The rostering space has tools — Deputy, Tanda, 7shifts, Planday — but independent operators are underserved by all of them. Here's why.

**The real problem:** Independent venue rostering is not a scheduling problem — it's a communication and availability problem. The owner is building a roster from a mental model of who's available, who's reliable, who needs hours, and who will kick up a fuss if they're moved. That model lives entirely in the owner's head. The roster gets built in a spreadsheet or on paper, then communicated via a group chat (WhatsApp or iMessage), then renegotiated when two people swap shifts and don't tell anyone.

**The current workaround:** WhatsApp. Seriously. Most venues under 15 staff run their entire roster communication through a group chat. Shift swaps are negotiated in the thread. Callouts come through at 6am. The owner sees it, stresses, and starts calling people.

**The gap:** The existing tools assume the operator wants a system. They don't — they want the chaos to stop. The gap is not "better scheduling software." It's: how do you reduce the callout-and-scramble cycle without requiring the operator to change how they think about rostering?

The tools that win in this space will be:
- Reactive, not proactive (help me handle the callout, don't ask me to plan three weeks ahead)
- WhatsApp-native or extremely low-friction to communicate through
- Aware of labour cost in real time (not after payroll is run)

**Is there room for something new?** Yes, but the ICP is critical. Tools like Deputy are genuinely good for venues over 20 staff with an ops manager. Under 10 staff, the owner won't pay $5/user/month for something that takes a week to set up. The gap is in the 8–20 staff range, where chaos is expensive but the operator still runs everything themselves.

---

## Example 3: Comparing Two Build Ideas

**User:**
I have two ideas I'm torn between. Option A: a tool that helps operators track and negotiate with suppliers — price comparison, spend tracking, reorder alerts. Option B: a compliance checklist and audit trail tool for food safety, staff certifications, and insurance. Which one has more genuine pain behind it?

**Specialist:**
Both are real pain points. They are not equal in terms of urgency, buying motivation, or sales difficulty.

**Option A — Supplier management:**

The pain is real and chronic. Operators overpay suppliers because they don't track price changes, don't compare across suppliers, and don't have time to negotiate. A venue doing $800K in revenue might be losing $20–40K a year in supplier drift — small price increases that compound and never get caught.

The problem: operators don't feel this pain acutely. It's a slow bleed. They're not waking up at 3am thinking "I need to sort out my supplier pricing." This means the buying motivation is low — you'll need to create urgency through data ("you've been overcharged $3,200 this quarter") rather than waiting for them to seek you out.

**Option B — Compliance:**

The pain is real and acute — but episodic. Operators feel it intensely when there's an inspection, a near-miss, or a staff certification that's about to expire. The rest of the time, compliance lives on a clipboard in the back office that no one looks at.

The buying motivation is higher because the downside is vivid (fines, licence loss, liability). But the market is fragmented by geography — food safety requirements differ significantly between Australia, the UK, the US, and the EU. Building a global tool means either going broad and shallow (generic checklists that operators don't trust) or going deep in one market first.

**Assessment:**

Option A has a larger, more consistent problem but a harder sales motion — you have to make an invisible pain visible. Option B has a more motivated buyer but a more complex product to build at scale due to regulatory variation.

If you're building for the Australian market first, Option B is more defensible and easier to sell. If you're thinking global from day one, Option A is more portable. Neither is wrong — they're different bets.
