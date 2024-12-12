# Complagent

Create an LLM based agentic, persistive, cyclic application. The agent should assist the user:

- Assess the compliance related research topic or question and suggest an agenda or workflow
- Get Human Feedback and seal the agenda, create a to do list
- Assist the user to search and compile necessary information
- draft a report.

Now for specific examples:

## Ideas

### Counterparty Risk Assessment

- Use Case: Assessing counterparty compliance with sanctions or credit risk.
- Support: The agent can:
  - Cross-check counterparties against sanctions lists (e.g., OFAC, EU Sanctions).
  - For cargo ships, analyze ship movements and ownership through sources like https://aisstream.io. 
  - News, legal databases, ratings the internet for information on counterparties.
  - Analyze transaction patterns with a specific counterparty.
    Example: "Are there any transactions with counterparties flagged in the latest sanctions update?"


Agent workflow example:

- Understand the question and a break the task down, ie. research sanction breaches, credit events, legal proceedings etc.
- Get Human Feedback and seal the agenda, create a to do list
- Assist the user to search and compile information,
- draft a comprehensive report about the counterparty including historical actions, breaches if any etc.


### Regulatory Updates and Alerts

- Use Case: Staying updated on evolving regulations.
- Support: The agent can monitor regulatory websites and news for changes in laws or reporting requirements and summarize updates.
    - Example: "What are the latest updates from the CFTC regarding emissions trading?"

Agent workflow example:
 
- Understand to compare and analyze changing regulatory external implications with internal compliance policies, understand that failings or overreaches need to be worked out, suggest an agenda or workflow
- Get Human Feedback and seal the agenda, create a to do list
- Assist the user to compare internal vs. external policies and regulations. Work out potential new internal directives
- draft adjustments to internal compliance policies.


### Cross check any sanctions or news on existing CPs

Sanctions and News Monitoring

- Use Case: Ensuring counterparties or regions involved in trades are not under regulatory scrutiny.
- Support: The agent can scan news sources, regulatory announcements, and sanctions databases for relevant updates.
    - Example: "Check if there are any news reports or sanctions updates about counterparties in the past 24 hours."

Agent workflow example:
 
- Based on the internal counterparty database, provide the user with a suggested workflow to research changing circumstances, suggest an agenda or workflow
- Get Human Feedback and seal the agenda, create a to do list
- Assist the user to work out new developments that are potentially relevent to internal compliance policies affecting dealings with counterparties, for negatively affected counterparties, draft a report on the potential risks, and actions that can be taken considering the current trade position with the company.
- draft reports for the user to take action on.


ship location finder:

https://aisstream.io