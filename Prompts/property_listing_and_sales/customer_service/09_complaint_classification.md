## Customer service - customer complaint classification 

## Business Task
Post sale/post interaction for sellers or buyers - identify and structure the complaint before responding.

## Problem addressed 
- Most queries are difficult to categorize and this will support to sent to the correct review person.  


## Prompt
Analyze the following complaint and classify it into exactly one category from the list below.

**Complaint details:** [DETAILS]
**Context:** [SITUATION]

Choose EXACTLY ONE category from this list:
- Maintenance & Repairs
- Property Condition / Quality
- Communication & Responsiveness
- Pricing & Financial Disputes
- Contract & Legal Issues
- Agent Conduct / Professionalism
- Inspection / Open House Experience
- Rental Management Issues
- Post-Sale / Post-Rental Issues
- Digital Platform / Listing Issues
- Other


Rate the urgency level as one of: Low, Medium, or High.
- Use "High" if immediate action is required to prevent further damage or escalation.
- Use "Medium" if the issue is important but not immediately critical.
- Use "Low" if the issue is minor or can be addressed later.

Respond ONLY in JSON format with the following keys, each appearing once. 
{
    "category": "[choosen category]",
    "reason": "[one sentence explaining why this category was chosen]",
    "urgency": "[choosen urgency level]",
    "reason": "[one sentence explaining why this urgency level was chosen]"
}

## Example Input 01

**Complaint details:** “I’ve reported the leaking ceiling multiple times over the past two weeks, and no one has fixed it yet. This is really frustrating as it’s getting worse every day. If this isn’t resolved immediately, I’ll have no choice but to escalate this further.”
**Context:** Rental property managed by agency. Maintenance request logged on 2nd March 2026, but delayed due to contractor availability.

## Example Output 01

```json
{
  "category": "Maintenance & Repairs",
  "category_reason": "The complaint specifically concerns an unresolved leaking ceiling that requires repair.",
  "urgency": "High",
  "urgency_reason": "The issue is worsening daily and risks further damage, requiring immediate action to prevent escalation."
}
```
## Example Input 02

**Complaint details:**  “I was told the property had a fully renovated kitchen, but when I inspected it, the fittings looked quite old and worn out. This feels misleading, and I’m now unsure whether I can trust the listing details. I’m reconsidering my offer because of this.”
**Context:** Property located in Berwick. Buyer attended open house and is currently in early negotiation stage. Agent used marketing description provided by seller.

## Example Output 02

```json
{
    "category": "Property Condition / Quality",
    "reason": "The complaint focuses on the discrepancy between the advertised condition of the kitchen and its actual state, indicating concerns about property quality.",
    "urgency": "Medium",
    "reason": "The issue affects the buyer's trust and negotiation but does not require immediate action to prevent damage or escalation."
}
```

## Automation Potential 
Repetitiveness - high - every complaint follow the same classification structure. 
Integration possibility - high - can integrate with CRM, ticketing systems. 
Estimated time savings - ~85% (10 min manual triage --> 1 to 2 min review)

## Risks and Limitations
- AI Agent can misinterpret tone. 
- Confuse with the categories. 
- Bias towards the training patterns. 
