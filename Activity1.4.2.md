## **Activity Title: Stakeholder Mapping and Contextual Scenario Building**
## partnered with Josh Hanning

### Scenario Card 1: E-Commerce Expansion

**Scenario**: Your e-commerce company is considering expanding its market to a new region. The region is known for its distinct cultural preferences, economic conditions, and digital usage patterns.

**Objective**: Analyze the potential of the new market, considering the unique characteristics of the region and the company’s capabilities.

**Data Available**: Market research data, current company analytics, regional economic reports.

----

### Scenario Card 2: Product Launch Failure

**Scenario**: A new product launched by your company did not perform as expected in the market. Sales are low, and initial customer feedback is mixed.

**Objective**: Understand the reasons behind the product’s underperformance and develop strategies to improve its market position.

**Data Available**: Sales data, customer feedback, competitor product performance data, marketing campaign data.

----

### Scenario Card 3: Supply Chain Disruption

**Scenario**: A critical component supplier for your manufacturing company has gone bankrupt due to global economic shifts, causing disruptions in your supply chain.

**Objective**: Develop a data-driven strategy to navigate through the supply chain disruption while minimizing impacts on production and customer satisfaction.

**Data Available**: Inventory data, alternative supplier data, production schedules, customer orders.

----

### Scenario Card 4: Employee Turnover Spike

**Scenario**: Your organization, known for its positive work culture, is suddenly experiencing a spike in employee turnover, especially among mid-level managers.

**Objective**: Investigate the potential causes behind the increased turnover and propose data-driven strategies to enhance employee retention.

**Data Available**: Employee satisfaction survey results, exit interview data, industry benchmark data, internal communication and policy changes logs.

----

### Scenario Card 5: Customer Service Crisis

**Scenario**: There’s a sudden surge in customer complaints regarding your company’s customer service, specifically related to response times and resolution satisfaction.

**Objective**: Analyze the root causes of the surge in complaints and develop strategies to improve customer service and regain customer trust.

**Data Available**: Customer complaint data, customer service operational data, recent changes in customer service protocols or personnel, social media and public feedback.

---

### Objective:

Enhance your ability to identify stakeholders and establish a relevant context for data analysis and storytelling through practical application in a given business scenario.

### Duration:

60 minutes

### Instructions:

### Scenario Card 3: Supply Chain Disruption

**Scenario**: A critical component supplier for your manufacturing company has gone bankrupt due to global economic shifts, causing disruptions in your supply chain.

**Objective**: Develop a data-driven strategy to navigate through the supply chain disruption while minimizing impacts on production and customer satisfaction.

**Data Available**: Inventory data, alternative supplier data, production schedules, customer orders.

**Step 1: Scenario Allocation**
**Assumption**
Who are WE??? -- Data Contractor
- Each group will receive a scenario card with a unique business situation.
- Take a few minutes to read and understand the scenario, ensuring all group members are clear on the situation and objective.

**Step 2: Stakeholder Mapping**
- Document the needs, challenges, and data requirements of each stakeholder on your worksheet.
- Identify and map the stakeholders relevant to your scenario, considering:
- **Primary Stakeholders**: Those directly impacted by the scenario.
-   **Supply Chain Manager - needs new suppiler and fast
-   Data Admin - need to be able to absorb new suppiler information and interpret with exisiting 
- **Secondary Stakeholders**: Those indirectly impacted or influencing the scenario. 
- Cheif Financial Operator - Needs the company to stop loosing money
- Data Engineer from Contracting team (Us) - Need data sources and data architecture mapping to execute data pipeline

**Step 3: Contextual Analysis**
**Assumption**
- The company is a needs materials to build their products upon in turn to ship out to end customers
Notes - Acceptance criteria & success critia 
- Establish the context for data analysis in your scenario by:
- **Identifying key business objectives and challenges.**

**Objectives**
- Locate available suppilers that provide our inventory needs and can meet our production schedules
- Stay within the product budgets and quality standards
- ensure suppilies can meet our shipping SLAs & targets

**Challenges**
- Alternative Supplier data that we store in our data tables could be outdated
- We have new inventory products that is not yet loaded into the inventory table - scalability of new partner to introduce new products in the future (havnt told the data team we now build cars with 20 in tires)
- Economy external factors (recessions / covid, hurricans, etc)
- Contractual restrictions - have to order x amount or sign x time contract

**Outlining relevant internal and external factors that might influence the data and its interpretation.**
-   **Assumtions**
- New suppiler does not have all supplies previous supplier has
- **Internal & External Factors**
- Product Codes between suppliers
- Aggregate data between suppliers (Product ranking / stars, Shipping success rates)
- refresh rate of data
- accuracy of records (data quailty)

**Data Available**: Inventory data, alternative supplier data, production schedules, customer orders.
- **Formulating key questions that the data analysis should answer.**
- Which suppiliers meet our criteria
- What items are still missing after working with new suppiler
- What days do we produce the most products
- What locations are the products coming and going from
- How many customers cancelled orders due to supply chain issues
- What is the retention of our customer during our economical shift & customer service loss

----
  
**Scenario**: A critical component supplier for your manufacturing company has gone bankrupt due to global economic shifts, causing disruptions in your supply chain.

**Objective**: Develop a data-driven strategy to navigate through the supply chain disruption while minimizing impacts on production and customer satisfaction.

**Data Available**: Inventory data, alternative supplier data, production schedules, customer orders.
  - ![alt text](https://github.com/AllieLamica/HCABDA/blob/c902d7f30480c70a3640b53be5072581fe96cf88/Week%201%20Assignments/1.4.2.PNG)



**Step 4: Crafting a Mini Data Story**

- Develop a brief data story outline based on your stakeholder mapping and contextual analysis.
- Ensure your outline includes:
- **Primary Stakeholders**: Those directly impacted by the scenario.
-   Supply Chain Manager - needs new suppiler and fast
-   Data Admin  - need to be able to absorb new suppiler information and interpret with exisiting
- **Secondary Stakeholders**: Those indirectly impacted or influencing the scenario. 
- Cheif Financial Operator - Needs the company to stop loosing money
- Data Engineer from Contracting team (Us) - Need data sources and data architecture mapping to execute data pipeline
- Production Manager - keep in the loop so they know how the product manufacturing line is impacted
-  ![alt text](https://github.com/AllieLamica/HCABDA/blob/e5b72c3508c1db1d52125aa89e51aff43a76b814/Week%201%20Assignments/1.4.21.png)

  **Beginning**: Introducing the scenario, stakeholders, and context.
  - Allie and Josh are contractors for the Data Analytics team.
  - The manufacturing company in question is Automobile manufacturer
  - The manufacturing company currently works with three suppliers and only have issues with one causing supply chain issues
  - The one supplier provides standard and custom tires & rims
  - Our company recieves inventory, manufactures cars and ships them out to dealerships
 
  **Middle**: Hypothetical data insights and how they relate to the context and stakeholders.
  - Through our analysis, we discovered:
  - The alternative supplier data was outdated and did not show all suppliers in our area that contain our products
  - the alternative supplier data did not categorize inventory by type, so it was difficult to find those that can replace just our tire & rim needs
  - The alternative supplier data did not show those that have retired / gone out of business,
  - Therefore we did some data quailty to get up to date
  - We perfomed a data profile to determine which suppliers had our necessary products and could ship to our location. We agreed to specific shipment dates based on the production scheduled data table
  - Due to the exisiting supply chain disruption, we identified the downstream impacts to the production line and used predictive analysis to determine new target dates for our cars
  - We performed data analysis to determine how many cancelled orders were recieved by date & cancellation reason
  - Additionally, We used # of orders in the past X months to forcast our customer retention rate

  **End**: Potential recommendations or strategies, considering the stakeholders and context
  
-----
**Step 5: Group Presentations**

- Present your stakeholder map, contextual analysis, and mini data story to the class.
- Be prepared to explain your thought process and rationale behind your analysis and story.

**Step 6: Peer Feedback and Discussion**

- Listen actively to peer presentations and be prepared to provide constructive feedback, alternative perspectives, and additional insights.
- Engage in discussions, considering the varied approaches and insights presented by different groups.

**Step 7: Debrief and Key Takeaways**

- Participate in a group discussion, sharing your learnings, challenges, and insights from the activity.
- Reflect on the importance of considering stakeholders and context in data storytelling.

### Note:

- Ensure to consider diverse perspectives and potential complexities in the scenarios.
- Engage actively in discussions, respecting all viewpoints and providing supportive feedback.
- Focus on the process of identifying stakeholders and establishing context rather than finding a solution to the scenario.

### Let’s Dive In!

Embark on this explorative activity, navigating through the complexities of stakeholders and context in data storytelling. Be curious, be critical, and most importantly, enjoy the collaborative learning process!
