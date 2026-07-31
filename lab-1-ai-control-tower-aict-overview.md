---
description: This first lab will be an overview of the AI Control Tower workspace.
---

# Lab 1 - AI Control Tower (AICT) Overview

#### Scenario

Alene, who is our AI Steward / Coordinator, will be able to see a comprehensive overview of the AI status, AI asset inventory, and other AI-related metrics.  These metrics include top items to review, new cases or inquiries, AI systems added, assets pending review, tasks past their deadlines, and several tabs of material AI asset information.  Alene will navigate these tabs to see the data within the various widgets on the tabs which will allow her to gain critical insight into the AI assets at her organization

Duration: 25 minutes

### Section 1 - The AICT Workspace

1. You should be logged in as the administrator.  If not, please use the steps provided by your instructor to secure an instance and get the username and password.
2.  Impersonate Alene Rabeck, the AI Steward, by clicking on the silhouette at the top-right of the screen, clicking **Impersonate User**, and then picking Alene.\
    <br>

    <figure><img src=".gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>

    <figure><img src=".gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>
3.  You may get a pop-up dialog about working your way and maximizing your workpace.  If so, click **Next** five times and then click **Got it!**. You should then be at the AI Control Tower workspace.  At the top-left you will see three icons.  The _Home_ icon is where you are currently and this shows the AICT dashboard and multiple tabs of information.  The next icon down is the _Lists_ for AI Assets.  The last icon is for _Configurations_.  We will not click into those icons right now. \
    \
    You will also see information about the _Top items to Review_. This pane gives the AI steward/coordinator a snapshot of tasks that need to get done or are overdue and new cases and inventory added. If you notice the blue text, those indicate hyperlinks to take you to the systems or tasks.\
    <br>

    <figure><img src=".gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

### Section 2 - Overview Tab

1.  Continuing on the home page, scroll down and review the tiles and charts in the _Overview_ tab.<br>

    <figure><img src=".gitbook/assets/image (117).png" alt=""><figcaption></figcaption></figure>
2. These panes and report widgets provide a quick glance overview of:
   1. All AI Systems and hyperlinks to the records in the lifecycle phases.
   2. AI Systems by type and provider to check over and/or drill into those systems.
   3. AI Systems that have gone through a risk assessment and the results of the assessments.
   4. Trending information for AI Systems that have been added or deployed in the quarter. Since we have not added or deployed any systems recently, this lab may show an empty chart.
   5.  Compliance to Authority documents and Policies. This section shows the compliance effectiveness percentage of different statuses of active controls applied on Authority documents and Policies. You can drill down respective sectors of the bar graph to access and view the list of active controls. To change to Policies, click on the **Compliance by** drop-down list and select **Policies**.<br>

       <figure><img src=".gitbook/assets/image (116).png" alt=""><figcaption></figcaption></figure>
   6. AI cases by priority show active AI cases such as bias, hallucinations, data breaches, etc.
   7. &#x20;Productivity, Usage, and Value.  This is gives the AI committee or AI Center of Excellence a scan of the AI. We will drill into these in more depth when we get to the Value tab.<br>

### Section 3 - AI Strategy Tab

1.  AI control Tower can be used to manage an organization's AI strategy, define goals and define targets, as well as manage the AI work that is being executed in the organization. AICT has some basic strategy and goals available, but there is an integration with ServiceNow's Strategic Portfolio Management solution (SPM).  Customers that have SPM installed will get additional capabilities such as managing AI strategy and execution.\
    Click on the **AI strategy** tab.<br>

    <figure><img src=".gitbook/assets/image (118).png" alt=""><figcaption></figcaption></figure>
2.  After the strategy view is loaded, you should see widgets like the following:<br>

    <figure><img src=".gitbook/assets/image (119).png" alt=""><figcaption></figcaption></figure>
3. The _AI_ &#x73;_&#x74;rategy_ tab enables the user to see the high level view into the AI strategy and how the well goals and targets are being met.  The highest piece is the strategic plan or the mission of the company. Under the mission of the company, you have the different strategic priorities that align to the mission. Under the strategic priorities, you can define the goals which tie into these particular strategic priorities. The goals can be defined as those which are AI and those which are not AI as well by using the category field. After you have defined your goals, you would need to define if I achieve this goal. At the top of this tab, you may also select filters to see the strategy specific to _Department_ and/or _Strategic priority_.
4.  Continuing down that page, you see additional charts like the Planned vs. Budget vs. Actual and AI work prioritization for ongoing and upcoming projects.  At the bottom, is the AI RIDAC which shows the risks, issues, decisions, actions, and changes in an impact vs. probability matrix.  Note: These are specific to the projects coming from SPM, not the risks being evaluated at the AI system or agent or model level.<br>

    <figure><img src=".gitbook/assets/image (84).png" alt=""><figcaption></figcaption></figure>



### Section 4 - AI Asset Inventory

The AI asset inventory tab contains all the AI-related assets used by an organization, including AI models, AI systems, prompts, and  datasets.  In future releases, mcp server assets will be included.

1.  Click on the **AI asset inventory tab**.<br>

    <figure><img src=".gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure>
2. This tab shows several different charts on the inventory of the AI assets.  The top-left shows the asset count and the counts by asset.  The two donut-style charts show the AI systems by provider and by type.  Note: You may filter by provider in the drop-down at the top-right of the _AI systems by type_ widget.
3. The center pane shows a chart with the AI systems and their current lifecycle phases. Lastly, the out-of-the-box assets include a Department field which can be added to any of the AI assets and then this stacked bar chart would show the AI assets by type and by department.
4. Lab 3 will drill further into details on AI inventory records and the lifecycle.



### Section 5 - Value

The _Value_ tab measures the productivity value of any AI system within the AI control tower inventory.  The solution provides productivity for any skill and agent or a use case that is registered in the CMDB as an AI system. These productivity and value calculations are measure based on the time the AI system is giving back to the human in the loop.  It is not necessarily measuring the productivity of the LLM or the system itself, such has how long did the reasoning model take and/or how many tokens were consumed. \
\
Today, we have a value framework (we will cover in more detail later) which measures three dimensions: (1) usage, (2) a productivity time value, and (3) an acceptance rate (a reflection of the quality measure of the AI system). AICT applies that value template to every AI system which has been selected.  AI stewards and AI centers of excellence are able to use the control tower to see what is the impact of their AI system.

1.  Click on the **Value** tab.<br>

    <figure><img src=".gitbook/assets/image (87).png" alt=""><figcaption></figcaption></figure>
2.  The _Value_ dashboard page helps gain insights into the value realized from multiple types of AI systems, view data about user engagement and feedback, and adoption of every type of AI system in your organization.The Value dashboard page contains visualizations that help you assess the value of your AI systems. The first widget is shows the estimated productivity gains (in hours) in the selected period as a result of using various AI systems, including third-party AI systems. Going across, you see the _Average AI users_ and _Top 5 AI systems by value (in hrs)_ charts. These data points show the average unique users for ServiceNow AI systems and the AI systems showing the most value to users across ServiceNow and third-party AI systems. To go a little deeper on the value calculation, click on **Default Experience for Now Assist**.<br>

    <figure><img src=".gitbook/assets/image (88).png" alt=""><figcaption></figcaption></figure>


3.  Clicking on that AI system will take you to the asset record (we will go deeper into the asset record in Lab 3) and the _Value template_ tab on that record. You will see the productivity chart and a section on the value templates. Here you can modify date ranges, agent personas, and the ability to add a new value template.  Click on the **View details** button.<br>

    <figure><img src=".gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>


4.  You should now see the _Default Skill Template_. This tab shows the current productivity of this template over time and then shows the calculation and template details.  We will now look at the details of the calculation.  Click on the **Edit template.**<br>

    <figure><img src=".gitbook/assets/image (90).png" alt=""><figcaption></figcaption></figure>


5.  The _Calculation builder and Template details_ sections are now displayed.  In the _Calculation builder_ secion we can see selections for the system/agent Persona, Usage, Time value type, Time indicator, Acceptance rate type, and Acceptance rate constant.<br>

    <figure><img src=".gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure>

    In this example, we are using a ServiceNow AI system and have access to execution data to get the usage numbers (_AIValue - Daily Skill Executions_). The Time value type field shows _Indicator_ which is pulling data from a ServiceNow indicator, and in this template, this indicator pulls the daily average assist.  The Time value type field may also be populated by a constant rather than an indicator.  For example, the constant might be running this agent will save five minutes each time it is used, so the constant would be set to 5.  The last factor for the calculation is the acceptance rate.  In this record, the acceptance rate type is a constant and we put in a rate of 50 (or 50%).  During implementation, customers can determine this rate and make modifications as needed. The acceptance rate is a reflection of the quality measure of the AI system. \
    \
    The net calculation is then Usage \* Time \* Acceptance.\
    \
    For third-party systems, the usage data would be populated from usage connections from AICT to the external system. The time value data would be a constant and the acceptance rate would be a constant.
6.  Let's now go back _Home_ and continue the AICT Workspace review.  At the top of the screen under the ServiceNow banner, **Click** the three **X** icons on the three tabs that were created when drilling into the asset and value records. This will close those three tabs and take us back to the home screen.\
    <br>

    <figure><img src=".gitbook/assets/image (120).png" alt=""><figcaption></figcaption></figure>


7.  If you are no longer on the _Value_ tab, click on the **Value** tab.  Now scroll down to the section with the four tabs of _Productivity, Engagement, Quality, & Creator Skills_. If you see an aqua-blue ServiceNow icon, this means the charts are specific to only ServiceNow AI.&#x20;

    <figure><img src=".gitbook/assets/image (122).png" alt=""><figcaption></figcaption></figure>

    In _Productivity_, we can show task closure efficiencies, to 10 AI Systems consuming assists, and AI systems with no usage.  We can also change the date range filter as needed.  Now, click on the  **Engagement** tab.<br>

    <figure><img src=".gitbook/assets/image (123).png" alt=""><figcaption></figcaption></figure>

    In the Engagement tab, we see several reporting widgets containing usage, actions, and adoption. Browse through these widgets to see some of the metrics being displayed.<br>

    <figure><img src=".gitbook/assets/image (124).png" alt=""><figcaption></figcaption></figure>


8.  Click on the **Quality** tab. This gives insight from ServiceNow AI specific assets and actions for feedback (thumbs up / thumbs down), task closures with an associated ServiceNow AI system execution plan, and success rate (percentage of successful AI executions.<br>

    <figure><img src=".gitbook/assets/image (125).png" alt=""><figcaption></figcaption></figure>


9.  Click on the **Creator skills** tab.  In our demo instance, we do not have custom built skills so these charts will not show data. &#x20;

    <figure><img src=".gitbook/assets/image (126).png" alt=""><figcaption></figcaption></figure>

    You can see we can track instance usage, highest skill usage, calls, etc.



### Section 6 - Evaluation

The Evaluation tab enables organizations to conduct structured assessments of AI assets using built-in templates or custom scoring criteria, measuring dimensions such as fairness, accuracy, business impact, and model drift. This tab provides a consistent, repeatable framework for AI stewards and governance teams to validate that AI models meet organizational expectations before and after deployment.

1.  Click on the **Evaluation** tab.<br>

    <figure><img src=".gitbook/assets/image (128).png" alt=""><figcaption></figcaption></figure>

    In this lab/workshop environment, we have not added data for the evaluations.  In addition, the evaluations will be changing in the ServiceNow Australia release and this lab is expected to be updated at that time with more comprehensive data.
2. Today, AI Control Tower includes a framework for evaluating performance and value with data like we saw in Section 5 on AI system usage and adoption which leverage value templates and measurement.  In the upcoming releases, AICT will include:&#x20;
   1. Monitoring for Custom Agents
      1. SDK to collect enterprise agent traces
      2. Run-time evaluations and configurable metric attribution
   2. Enteprise Monitoring Connectors
      1. Expanding support to include trace data from Hyper-scalers (Logs)
   3. Integrated Monitoring & Triaging
      1. Enterprise security evaluations
      2. Alerts, thresholds, & insights
      3. Evaluate-driven workflow actions<br>
3. In the screenshot below (Note: this will not be in your lab instance.), you can see key capabilities on the new _Evaluations_ tab.
   1. Quickly see the health of your AI systems using two out-of-the-box AICT pillars of _Quality_ and _Safety._ These scores are averages of both your ServiceNow agents and external agents.
   2. View the lowest scoring systems for teams to investigate.
   3.  See frequency of evaluations conducted to date, with heatmaps for each metric evaluated.\
       <br>

       <figure><img src=".gitbook/assets/image (209).png" alt=""><figcaption></figcaption></figure>







### Section 7 - Risk & Compliance

The Risk and compliance tab on the AI Control Tower displays the risk classification of an AI asset inventory and the compliance posture for the selected authority documents and policies.

AI assets refer to the various components and resources that are essential for the development, deployment, and operation of artificial intelligence systems. These assets can include AI systems, AI models, and Datasets.\
\
Understanding and managing these AI assets is crucial for ensuring that AI systems are effective, reliable, and compliant with regulatory and ethical standards as defined by your organization.

1.  Click on the **Risk & compliance** tab.<br>

    <figure><img src=".gitbook/assets/image (131).png" alt=""><figcaption></figcaption></figure>


2.  Review the first section around _Regulatory risk classification_.&#x20;

    <figure><img src=".gitbook/assets/image (133).png" alt=""><figcaption></figcaption></figure>

    Here you can see the risk assessment results across the AI assets.  If you recall when going through the _Overview_ tab, there was one chart on just AI systems.  This tab covers three asset types: AI systems, AI models, and Datasets.
3.  Scrolling down to the _Compliance by authority documents and policies_ section, we can see how well controls have passed their tests/attestations and we can see any issues or cases related to the particular framework or policy.<br>

    <figure><img src=".gitbook/assets/image (134).png" alt=""><figcaption></figcaption></figure>

    Now click on the **Policies** button to see the differences in the control compliance results tied to policies vs. tied to the authoritative sources.<br>

    <figure><img src=".gitbook/assets/image (135).png" alt=""><figcaption></figcaption></figure>


4.  Scroll down to the _Risk Overview_ section.<br>

    <figure><img src=".gitbook/assets/image (136).png" alt=""><figcaption></figcaption></figure>

    \
    This section monitors and tracks the risk posture of the AI assets in your organization. Using the AI asset filter, you can filter risk posture insights by the type of AI asset inventory. The AI systems by aggregated risk score section displays the classifications of AI systems by aggregated risk score using a donut chart. The risk scores are qualitatively classified as High, Medium,  and Low. The Risk heat map widget displays the visualization of all identified risks within the AI assets. The heat map is segmented, and the segmentation changes based on the filter. The activities fall under the respective combination of risk and control effectiveness, or impact and likelihood. The combination is based on the selected risk classification filter. You can filter the risk heat map by the Risk Assessment Methodology (RAM), if you have multiple RAMs published.

### Section 8 - Security & Privacy

The _Security & Privacy_ tab of AI Control Tower offers a dashboard-based overview of your ServiceNow specific AI security metrics. The dashboard contains several visualizations detailing AI security metrics. In addition to tracking metrics the _Security & privacy_ tab contains the access map, a tool that gives a node-graph visualization of the relationships between your ServiceNow agents, agentic workflows, and tools. You can use the map to investigate the relationships between your AI agents and workflows further.

1.  Click on the **Security & privacy** tab.<br>

    <figure><img src=".gitbook/assets/image (137).png" alt=""><figcaption></figcaption></figure>


2.  You should now see the _Security & privacy_ dashboards.<br>

    <figure><img src=".gitbook/assets/image (138).png" alt=""><figcaption></figcaption></figure>

    \
    These four reports show:

    1. Potential access issues showing the proportion of AI agents experiencing access-related issues and lists the top systems with issues (e.g. an agent is unable to update a record).
    2. Autonomous vs. supervised agentic workflows display the proportion of autonomous (self-driven) to supervised (human-guided) agentic tools in use. Hover over a portion of the chart to see the exact proportion and count of agents.
    3. Privileged AI Agents show AI agents with elevated permissions, such as an agent with admin or security admin permissions, that may be able to perform critical actions.
    4. Dormant AI systems shows AI agents that have not been active for over 90 days. This allows the AI steward or AI team to review agent permissions to reduce security risk(s).
3.  Click on **access map** just above the _Access issues_ widget.<br>

    <figure><img src=".gitbook/assets/image (139).png" alt=""><figcaption></figcaption></figure>

    The access map will open a new tab within AICT showing the access map.  The Access map displays a node map detailing the relationships of your ServiceNow agents, agentic workflows, and tools. You can use the map to review these relationships, configure agent details, and resolve access issues. The map includes filters for both agents and agentic workflows.
4.  Click on the **AI agents** greater than sign (**>)** in the left column and then scroll down the list and click on **Problems investigation AI agent**.<br>

    <figure><img src=".gitbook/assets/image (142).png" alt=""><figcaption></figcaption></figure>

    <figure><img src=".gitbook/assets/image (143).png" alt=""><figcaption></figcaption></figure>

    \
    You should now see the map of the this agentic workflow. Our demo system does not show any, but a warning icon would show on ay agent having access issues. You can also see the path of the workflow to the agent to the tools.<br>

    <figure><img src=".gitbook/assets/image (144).png" alt=""><figcaption></figcaption></figure>
5.  Select the **Problems investigation AI agent**. Here you can see the flow to the other assets (agents, skills, tools, etc.) and you can see a pop-up on the right side with details of the agent and the tables it accesses.<br>

    <figure><img src=".gitbook/assets/image (145).png" alt=""><figcaption></figcaption></figure>


6.  Feel free to click around on the tools or other agents listed to view their details and/or select the additional AI agents or Agentic workflows from the _Access Map_ column. The _Optimize GRC issue resolution_ has multiple agents as seen in the picture below.  When finished, **click** the **X** on the Access Map tab at the top of the screen.  This will take you back to the AICT home page (and will likely bring you to the _Overview_ tab).\
    <br>

    <figure><img src=".gitbook/assets/image (147).png" alt=""><figcaption></figcaption></figure>



### Section 9 - AI Cases

Track, monitor, and analyze your AI case workflows, identify your workflow bottlenecks, and check your accountability of your AI-related risks by using AI Case tab in AICT.  As an AI steward, you can also use the dashboard to track the status and trends of your AI-related inquiries. Cases would be related to things like hallucinations, bias, and vulnerabilities, whereas inquiries would be a user wanting to know what models are available or how to reuse an agent.

1.  Select the **AI cases** tab.<br>

    <figure><img src=".gitbook/assets/image (148).png" alt=""><figcaption></figcaption></figure>


2.  You should now see the AI case with the ability to toggle between _AI cases_ and _Inquiries_ at the top-left of the tab and the ability (assuming permissions are granted) to _Create AI case_ or _Issue_ at the top-right.<br>

    <figure><img src=".gitbook/assets/image (149).png" alt=""><figcaption></figcaption></figure>

    \
    The reporting widgets below show the cases (or inquiries) by state and by priority and then options for viewing the list of cases.  The blue colored fields are hyperlinks, e.g. the name or sub-type.
3.  Scrolling down further, you see the Trending and Tracking information about the AI cases (or inquiries).<br>

    <figure><img src=".gitbook/assets/image (150).png" alt=""><figcaption></figcaption></figure>

    \
    The trends show visual patterns and historical data associated with the cases (or inquiries).  You can track items like total cases and closures, average time to close, peak case volume, the fastest month for resolutions, closure efficiency has improved or regressed, and year over year changes to resolution time.\
    \
    Tracking shows us the progress at the task and issues levels.

### Section 10 - Lab 1 Summary

The AI Control Tower (AICT) workspace provides AI stewards with a centralized hub for governing, monitoring, and managing all enterprise AI assets. The **Overview tab** offers a high-level dashboard of AI systems across lifecycle phases, risk assessment results, compliance posture, and productivity metrics. The **AI Strategy tab** connects AI initiatives to organizational goals and strategic priorities, with enhanced capabilities available for customers with ServiceNow's Strategic Portfolio Management (SPM). The **AI Asset Inventory tab** visualizes the full catalog of AI systems, models, prompts, and datasets by provider, type, and lifecycle phase. The **Value tab** measures AI productivity in three dimensions — usage, time value, and acceptance rate — across both ServiceNow-native and third-party AI systems, with drill-down capabilities into engagement, quality, and creator skills. The **Evaluation tab** supports structured assessments of AI assets using built-in or custom scoring templates to validate fairness, accuracy, business impact, and model drift. The **Risk & Compliance tab** displays risk classifications across all AI asset types and tracks control compliance against authority documents, policies, and regulatory frameworks. The **Security & Privacy tab** monitors AI security metrics including access issues, privileged agents, autonomous vs. supervised workflows, and dormant AI systems, with an Access Map for visualizing agent relationships. Finally, the **AI Cases tab** allows stewards to track, monitor, and analyze AI-related cases and inquiries — such as hallucinations, bias, and vulnerabilities — including trending and resolution tracking data.
