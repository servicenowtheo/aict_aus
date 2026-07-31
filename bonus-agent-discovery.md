# Bonus: Agent Discovery

Back in Lab 2 we noted that AI Control Tower can discover AI automatically via Service Graph Connectors (SGC), rather than relying on someone to manually submit an intake form. In Lab 5 we saw the same idea again: when an agent is discovered from outside ServiceNow, its models, prompts, datasets, and tools get pulled into AI Control Tower right alongside it. This bonus exercise is where you finally see that in action.

**Scenario**

IT suspects several teams have connected directly to AI vendor APIs without ever going through the AI System Intake process you walked in Lab 2 — no request filed, no Impact Assessment, no review by Alene or Josh. You'll run a discovery scan to surface what's actually out there, investigate one of the discovered agents in enough depth to understand what it touches, bring it under governance, and confirm the platform now treats it as a fully managed, value-tracked asset — not just a row that appeared in a list.

Duration: 10 minutes

### Section 1: Discover Shadow AI

1. From the AI Control Tower homepage, navigate to **Lab Scripts > Run Agent Discovery** in the application navigator.
2. Click the **Run Agent Discovery** button.
3. Click through the confirmation dialog. Watch the scan cycle through the vendors it's checking — AWS, Azure, Databricks, OpenAI, Google, Salesforce, HuggingFace, Snowflake.
4. When the scan completes, you'll see **"✓ Discovered 8 AI agents."**
5. Click **Open AI Asset Inventory**. All 8 agents are unmanaged, and each belongs to a different department:

   | Agent | Vendor | Department |
   |---|---|---|
   | AWS Bedrock — Claims Processing | Amazon Web Services | Finance |
   | Azure AI Foundry GPT-4 Turbo — Customer Comms | Microsoft | Customer Support |
   | Databricks Mosaic AI — Internal Analytics Copilot | Databricks | IT |
   | OpenAI GPT-4 — Internal Knowledge Base Assistant | OpenAI | IT |
   | Google Vertex AI — Demand Forecasting | Google | Operations |
   | Salesforce Einstein — CRM Recommendations | Salesforce | Sales |
   | HuggingFace Inference — Sentiment Analysis | HuggingFace | Marketing |
   | Snowflake Cortex — Workforce Insights | Snowflake | HR |

   Note: this is the point of AI discovery — it's rarely one rogue tool. Here it's eight, spread across six departments, none of which ever went through intake.

### Section 2: Investigate a Discovered Agent

Open **Databricks Mosaic AI — Internal Analytics Copilot** — engineering built it so staff can query the company's lakehouse in plain English instead of writing SQL.

1. Read the asset's description on its record.
2. From the AI Control Tower workspace, go to the **Security & Privacy** tab, then click **access map** just above the _Access issues_ widget (the same Access Map you used in Lab 1).
3. In the **AI agents** panel on the left, find and select **Databricks Mosaic AI Agent**.
4. The graph fans out to the three tools this agent actually uses:
   - **Query Lakehouse Data**
   - **Generate Workforce Forecast**
   - **Export Analytics Dataset**

   Note: this is the difference between a name in a spreadsheet and a real governance picture — you can now see exactly what this agent touches, not just that it exists.

### Section 3: Bring It Under Governance

Discovery only tells you what's out there — nothing changes until someone acts on it.

1. Navigate to **AI Control Tower > Configurations > Automation rules**.
2. Find **Lab: Manage Discovered AI Agents**. It ships inactive, so nothing runs until you turn it on.
3. Click **Activate**.
4. Click **Run Now**.
5. You'll see: **"Lab: Manage Discovered AI Agents - Processed 8.0 assets to managed status."**
6. Return to the AI Asset Inventory and confirm all 8 agents now show **governed = true**.

   Note: this action only flips the governed flag — it does not run a risk assessment for you. A newly-governed agent that actually needs one still goes through Impact Assessment like any system in Lab 3.

### Section 4: See the Value Payoff

1. Navigate to the **Value** tab.
2. Each of the 8 newly-governed agents now has a value template attached, showing time saved and acceptance rate per use.
3. Look specifically at Databricks Mosaic AI — Internal Analytics Copilot: roughly 30 minutes saved per use, at a 70% acceptance rate among engineers who no longer hand-write SQL.

_**Congratulations, you've discovered, governed, and measured the value of shadow AI across your organization!**_
