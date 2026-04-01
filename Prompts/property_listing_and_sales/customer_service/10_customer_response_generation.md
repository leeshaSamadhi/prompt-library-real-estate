## Customer service - customer response generation

## Business Task
Post sale/post interaction for sellers or buyers - generate tailored response for complaints. 

## Problem addressed 
- Agents miss the timely complaint or inquiry handling due to listing and other priorities. With AI prompting average response time can be reduced to < 15 minutes (AI prompt running and results ~ 5mins + human review ~ 10mins). 
- 48% of the enquiries when unanswered - with prompting and workflow automation 95% of the responses can be captured and stay on the addressed loop. 


## Prompt
You are an expert real-estate customer service specialist. Please generate a professional, empathetic, and concise response of approximately 150-200 words to the following tenant complaint.

Your response should be professional, empathetic, and reassuring with the word limit of a maximum of 150-200 words.

**Complaint details:** [DETAILS]
**Context:** [SITUATION]

Your response should:

- Empathetically acknowledge the tenant’s frustration.
- Explain the cause of the delay (contractor availability).
- Provide clear resolution steps, including an expected repair date (by March 10, 2026).
- Outline a follow-up plan to keep the tenant informed.
- Use a professional and courteous tone throughout.
- Include placeholders for tenant name, your name, your position, and agency name.
- Be approximately 150-200 words in length.
- Do not add any information beyond what is provided.

Please ensure the response strictly adheres to the above instructions.

## Example Input 01 
**Complaint details:** “I’ve reported the leaking ceiling multiple times over the past two weeks, and no one has fixed it yet. This is really frustrating as it’s getting worse every day. If this isn’t resolved immediately, I’ll have no choice but to escalate this further.”
**Context:** Rental property managed by agency. Maintenance request logged on 2nd March 2026, but delayed due to contractor availability.


## Example Output 01

Dear [Tenant Name],

Thank you for bringing your concerns to our attention. I sincerely apologize for the ongoing inconvenience caused by the leaking ceiling and understand how frustrating this situation must be, especially as it has persisted despite your multiple reports.

Please know that your maintenance request, logged on March 2, 2026, has been a priority for us. Unfortunately, the delay has been due to limited contractor availability, which we are actively working to resolve. We have now scheduled the repair, and a qualified contractor will address the issue by March 10, 2026.

To ensure you stay informed, I will personally follow up with you after the repair to confirm the work has been completed to your satisfaction. Additionally, I am available to discuss any further concerns you may have in the meantime.

We appreciate your patience and understanding as we work diligently to resolve this matter promptly.

Kind regards,  
[Your Name]  
[Your Position]  
[Agency Name]


## Example Input 02 
**Complaint details:** “I was told the property had a fully renovated kitchen, but when I inspected it, the fittings looked quite old and worn out. This feels misleading, and I’m now unsure whether I can trust the listing details. I’m reconsidering my offer because of this.”
**Context:** Property located in Berwick. Buyer attended open house and is currently in early negotiation stage. Agent used marketing description provided by the seller.


## Example Output 02

Dear [Tenant Name],

Thank you for sharing your concerns regarding the kitchen fittings at the Berwick property. I completely understand your frustration and the disappointment you feel, especially after being informed that the kitchen was fully renovated. Please be assured that it was never our intention to mislead you.

The marketing description was provided by the seller, and we are currently working closely with them to address the discrepancies you noticed. Unfortunately, the delay in updating the kitchen fittings is due to contractor availability, which has impacted the timing of the renovations.

We have arranged for the necessary updates to be completed by March 10, 2026. Our team will monitor progress regularly and keep you informed every step of the way. I will personally follow up with you by March 1 to provide a status update and ensure all your questions are addressed.

Your trust is important to us, and we are committed to resolving this promptly. Please feel free to reach out if you need further assistance in the meantime.

Kind regards,  
[Your Name]  
[Your Position]  
[Agency Name]

## Automation Potential 
High
### Repetitiveness 
Very high - complaint reponses follow a consistent structure (empathy --> explanation --> resolution --> follow-up).

### Human judgment 
- Moderate - only requires for edge cases such as legal risks, compensation decisions. 
- Standard complaints require minimal editing. 

### Integration possibility 
Strong 
- can integrate with tools like Salesforce, PropertyMe, Console Cloud.
- Triggered automatically when complaint category is idenified. 

## Risks and Limitations
- Generic responses. 
- Human review is needed to ensure that the key details are addressed and are accurate. 