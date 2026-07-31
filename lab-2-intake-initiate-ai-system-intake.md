# Lab 2: Intake - Initiate AI System Intake

#### Scenario

Mary Cruse, a product owner on the Cybersecurity Operations team, is tasked with registering the details of the department's use of an AI system for autonomous threat identification. The intake form for AI System registration is hosted on the ServiceNow Employee Center, which serves as a centralized portal for users across Cloud Dimensions to submit requests, access IT catalogs, complete assessments, and more.&#x20;

Through the Employee Center, Mary will document and submit for review all information related to his team’s AI use case, including relevant system(s), model(s), and dataset(s). Let's explore this intake process.&#x20;

Note: This lab will go through the manual process of an AI system intake.  AI Control Tower also has the ability to do enterprise AI discovery.  Discovery is a fundamental feature of the AI Control Tower offering a unified and comprehensive view of all AI assets—including AI systems, agents, models, prompts, and tools— across various hyperscalers, AI apps, and Agentic AI frameworks via Service Graph Connectors (SGC). AI discovery helps organizations reduce AI deployment risks by automatically finding AI assets and simplifying compliance. This feature improves governance by showing AI deployments across different environments, helping executives make informed decisions with full transparency. It also tracks AI usage and adoption, allowing organizations to measure productivity gains.

Duration: 8 minutes

### Section 1: Log in as Mary Cruse (AI Product Owner)

1.  Click on the **profile picture** at the top right corner and select **Impersonate user**.\
    \
    Search for **Mary**. Click the user profile and allow the page to reload. You will be logged into ServiceNow impersonating this user, with all associated permissions and levels of access. Click through the popup dialog, if necessary.<br>

    <figure><img src=".gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

    <figure><img src=".gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>


2. In the Filter Navigator (**All** menu on the top left-hand side), **search for** and select **Employee Center**.

![](<.gitbook/assets/2 (1).png>)

3. A new browser window will open presenting the Employee Center homepage. \
   Note: The Employee Center portal serves as a generic intranet in ServiceNow and provides value across many GRC workflows – for example, the Employee Center is where users can complete risk assessments, request third party due diligence, submit control evidence, and more. We will revisit the Employee Center throughout this lab to handle various end-user tasks.
4.  In the new _Employee Center_ window, navigate to the **Technology services | AI assets** page on the menu located at the top left of the screen and click on the **AI assets** link.<br>



    <figure><img src=".gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

    Note: On these _Technology services_ and _Risk and compliance_ areas, there are many requests we can submit relating to various GRC processes – such as Policy Exceptions, Privacy Cases, and Risk Events. These are functions outside of the AI Control Tower solution, but they are integrated seamlessly as a part of the centralized Employee Center experience.<br>
5.  Select **Request an AI Use Case** from the available options.<br>

    <figure><img src=".gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

    _Note: The resulting screen is a **general intake form** to collect information around any AI use case in the organization. Notice the data we can submit as a part of this documentation process._
6. Mary will be documenting all the details around an AI system called SkyTrack, which is an autonomous AI defense system. It uses the ThreatSense v1.0 model to predict and detect digital threats in real-time, automatically managing cybersecurity protocols for a U.S. military contract. The system is trained on two key datasets: CyberGrid Logs (historical network data) and the User Activity Matrix (employee login patterns). **Fill out the form as follows:**
   1. Name: **SkyTrack**
   2. Version: **1.0**
   3. State: **Draft**
      1. Note: our request will begin here and progress through a standard workflow for evaluating new AI Systems in the organization.
   4. Model Category: **Generative AI**
   5. Description: **A networked autonomous AI Defense System built for a US military contract.**
   6. Documentation: (leave blank)
   7. Provider: **Cloud Dimensions**
   8. Managed by should be pre-populated.  If not, Managed by: **Mary Cruse**\
      _&#x4E;ote: This will assign Mary as the Business Owner of the SkyTrack AI System in the AI Control Tower view. Later in the lab, you will see how this allows for the automatic routing of relevant tasks to Mary – such as control attestations for this particular system._
   9. AI Models: **Cloud Dimensions ThreatSense v1.0**\
      _&#x4E;ote: In this field, we are selecting from a pre-defined list of options. These types of data definitions can be configured in the AI Control Tower workspace._
   10. Datasets: **Cloud Dimensions CyberGrid Logs,** AND **Cloud Dimensions User Activity Matrix**\
       _&#x4E;ote: In this field, we are selecting from a pre-defined list of options. These types of data definitions can be configured in the AI Control Tower workspace._
7. Click the **Submit** button on the right-hand side.\
   ![](<.gitbook/assets/image (156).png>)

Mary has **successfully** submitted the **AI use case** to the **AI Control Tower** at Cloud Dimensions. Mary can add additional notes or attachments and review the new submission. In the following lab, Alene Rabeck, the AI Steward, has been notified of the new submission. She will review the AI use case and initiate the assessment workflow.<br>

<figure><img src=".gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>

### Section 2: Log in as Alene Rabeck (AI Steward) to access AI Control Tower

#### **Scenario**

Cloud Dimensions is focused on improving the documentation process for its AI use cases. The company has formed an AI Center of Excellence (CoE) and appointed **Alene Rabeck** as the **AI Steward**. Alene works within the **AI Control Tower Workspace** to monitor various metrics across the entire AI asset ecosystem, including usage by department, risk exposure, and compliance posture. She will also action on the request submitted by Mary. Let's explore this workspace view.

1.  When Mary selected the _Employee Center_, a new tab was launched.  Close this tab by clicking on the **X** on the **Employee Center Homepage** tab at the top of the browser.

    <figure><img src=".gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>


2.  You should be in the _Home_ screen for Mary.  Click on the **profile icon** at the top-right corner and select **Impersonate another user**.\
    .

    <figure><img src=".gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>
3.  Search for and select **Alene Rabeck**. Then, click the **Impersonate User** button.\
    <br>

    <figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>


4. Allow the page to load the _AI Control Tower workspace_. Alene’s day-to-day view includes the **Top Items to Review** section at the top of the page, which calls attention to activities such as new AI System requests, overdue tasks, and updates to the AI asset inventory. It also includes multiple dashboard views represented by tabs at the top of the page which we went over in Lab 1. Later in the lab documentation, we will explore risk and compliance metrics in more detail in the _AI Risk and Compliance Workspace_**.**
5.  In the _All AI Systems_ section, click into the **New** category by clicking the hyperlinked number.\
    <br>

    <figure><img src=".gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>


6.  If your list of AI systems is not sorted by _Display name_, **Click** on the **Display name** header twice to sort the records.  Scroll down and click on the record named **Cloud Dimesions SkyTrack 1.0**. This is the record submitted from Mary's perspective. Notice it is in a **Draft** state and shows Mary Cruse in the Managed By field.<br>

    <figure><img src=".gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>
7.  In the record view, notice the information provided by Mary through the intake process. Also note, there are four tabs in this AI asset record: _Details, Related assets, KPIs & metrics,_ and _Value template_. Click the **Start Review** button at the top-right.<br>

    <figure><img src=".gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>


8. You should now see two new tabs: _Lifcycle_ and _Risk & compliance_. After waiting 30 seconds or so and those two tabs do not show, **Click** the **Related assets** tab next to the _Details_ tab.  This should force the refresh of the other tabs. Notice the generated AI Asset Lifecycle view. Notice the various tasks and activities that have been auto-assigned to Mary, our system owner. Feel free to click through the _Related assets_ and _Details_ tabs to view the AI assets related to this system (recall we added one model and two datasets in the previous lab) and to view the metadata associated with the system.

The **Intake phase** of our organization’s AI use case process is now complete. Mary completed the form to create a new AI asset.  Alene reviewed the asset and started the review process which will kick off the lifecycle. In the next lab, you will take action on the required activities from Mary’s perspective in the AI Control Tower workspace.

_**Congrats, you’ve finished Lab 2! The AI System use case has been submitted for review and initiated the governance process starting with Assess. Please proceed to Lab 3 where we complete the Impact assessment as Mary Cruse the AI Product owner.**_
