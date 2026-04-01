## Prompt version log

### Prompt file 

`Prompts\property_listing_and_sales\property-listing-creation\01_property_listing.md`

| Version | Change Made                    | Reason                                            | Result                      |
|---------|--------------------------------|---------------------------------------------------|-----------------------------|
| v1.0    | Initial listing prompt created | Required the basic start for the listing creation | Better output on the prompt |
| v1.1    | Added constraints on the prompt text| To get a more structured response            | More clear and on point response|
| v1.2    | Corrected typos and structured the text| To obtain on point details            | increased the overall score to 90 |


`Prompts\rental_yield_and_investment_analysis\02_property_investment_analysis`
| Version | Change Made                    | Reason                                            | Result                      |
|---------|--------------------------------|---------------------------------------------------|-----------------------------|
| v1.0    | Initial listing prompt created | To create a detailed financial analysis to the given property | Output based on given parameters but lacks relevancy |
| v1.1    | Correct minor language errors, added constraints | To get a more accurate response | Agent understood the prompt but still gave generic response|
| v1.2   | Corrected the [LOCATION] parameter mentioned in the commands | Agent got confused with the unknown parameter | The reponse was better than the previous|
| v1.3    | Specified the requirement section more clearly with added commands | To obtain more specific response| adhered to the word limit and gave a meaningful clean response |


`Prompts\marketing-plan\03_marketing_plan.md`

| Version | Change Made                    | Reason                                            | Result                      |
|---------|--------------------------------|---------------------------------------------------|-----------------------------|
| v1.0    | Initial marketing plan prompt created | Required the marketing campaign plan for the listing | Detailed output but content overloaded |
| v1.1    | Adjusted the content to be more precise and command to create template such as ads and emails | To obtain more specific content | increased accuracy and generated templates with less information overload|


`Prompts\buyer-persona-creation\04_buyer_persona.md`

| Version | Change Made                    | Reason                                            | Result                      |
|---------|--------------------------------|---------------------------------------------------|-----------------------------|
| v1.0    | Initial prompt created | Required the basic start to create a buyer persona | Too much words and detail |
| v1.1    | Added a word limit and specified the parameters well | More clear and on point response|
| v1.2    | Added a prompt to recommend locations according to the buyer persona| To obtain on point details            | Better results with stats and recommendations |

`Prompts\listing-advertisement\05_listing_ads.md`

| Version | Change Made                    | Reason                                            | Result                      |
|---------|--------------------------------|---------------------------------------------------|-----------------------------|
| v1.0    | Initial listing created | To create an advertising content and KPI strategy | over-assumed results |
| v1.1    | Added a word limit and specific commands | To get a structured output| Better structure with KPI indicators|


`Prompts\open-house-planning\06_open_house.md`
| Version | Change Made                    | Reason                                            | Result                      |
|---------|--------------------------------|---------------------------------------------------|-----------------------------|
| v1.0    | Initial prompt created | To create an open house guiding reference | detailed plan but bit more generic |
| v1.1    | Changed the commands and ensured compliance with open house standards | To get more compelling plan | Clean and clean plan|


`Prompts\lead-follow-up\07_lead-follow-up`
| Version | Change Made                    | Reason                                            | Result                      |
|---------|--------------------------------|---------------------------------------------------|-----------------------------|
| v1.0    | Initial follow up prompt created | To create a guided checklist | structured output but too vague |
| v1.1    | Changed the commands and added constraints | To make more connected and impressing | More understandable guide|



`Prompts\sales_negotiation\08_negotiation_and_deal_closing`
| Version | Change Made                    | Reason                                            | Result                      |
|---------|--------------------------------|---------------------------------------------------|-----------------------------|
| v1.0    | Initial negogiation script created | To align stakeholder expectation and buyer intention and critically align | detailed plan of negogiation but lacked examples |
| v1.1    | Assisted agent to avoid false claims explictly and be consice with given details with examples | To reduce the vague reponse | Structured example and a reasonable negotiation guide to the entered details|


`Prompts\customer_service\09_complaint_classification`
| Version | Change Made                    | Reason                                            | Result                      |
|---------|--------------------------------|---------------------------------------------------|-----------------------------|
| v1.0    | Initial classification prompt created | classify the complaint according to the category and urgency level | The prompt responce correctly classified but with low accuracy around 83% |
| v1.1    | corrected typos, provided more detailed criteria for urgency levels| To increase more clarity | Accurate classification with increased overall score of 90%|


`Prompts\customer_service\10_customer_response_generation`
| Version | Change Made                    | Reason                                            | Result                      |
|---------|--------------------------------|---------------------------------------------------|-----------------------------|
| v1.0    | Initial response generation script created | To generate the email response once the classification is done | prompt response didn't address the email properly |
| v1.1    | Added more criteria and instructions | To get a structured response | email response with more clarity |