
### Methods & Techniques

1. Controlling Budget: keep track of the efforts spent
	- very likely: relevant information too late in order to take any corrective action
	- keeping track of efforts not good enough
	- **gather remaining effort estimations: estimate every time unit**
1. Controlling Scope: determine the degree of completion
	- difficult, if work items are too large
	- [[Earned Value Analysis (EVA)]] & Earned Value Management (EVM)
2. Controlling Time: [[Milestone Trend Analysis (MTA)]]
3. Agile Controlling: Burndown Chart


### Burndown Chart

![[BurndownChart.png]]
- shows remaining effort over time
- single/multiple iterations
- additional effort below 0
- provides diagnosis of end date

### Corrective Action

![[CorrectiveActionControlling.png]]

- if you change one of these dimensions, the others will be affected as well

#### Examples:

**less time**
1. reduced functionality: customer is unlikely to appreciate this
2. fewer tests, reviews: reduced quality, increases bugs
3. more people: makes it even later (see [[Project Planning]])

**increased costs:**
1. fixed price customer project: price can often not be renegotiated
2. development: focus on core functionality

**reduced quality:**
1. get rid of it (no alternative)
2. prevention by using established software engineering methods ([[SWEBOK (Software Engineering Book of Knowledge)]])

- corrective actions may come from outside of the project --> steering committee, upper management. **Escalation is the last resort as a PM. It shows limited authority and capabilities BUT escalating to late is the worst case**


### Questions

#### What is the primary purpose of a burndown chart in Agile controlling, and what key information does it provide?

<details> <summary>Click to show answer</summary> <p>The primary purpose of a burndown chart is to track the remaining effort over time in an Agile project. It provides information on the progress of work, showing whether the team is on track to complete the project by the end date, and highlights any additional effort required.</p> </details>

### Explain the concept of Earned Value Analysis (EVA) and its importance in controlling project scope.

<details> <summary>Click to show answer</summary> <p>Earned Value Analysis (EVA) is a method used to measure project performance and progress in an objective manner. It integrates project scope, cost, and schedule measures to help determine the degree of completion. EVA is important because it provides early warning signals about project performance and helps in making informed decisions about corrective actions.</p> </details>

### Describe a scenario where Milestone Trend Analysis (MTA) would be beneficial for controlling project time.

<details> <summary>Click to show answer</summary> <p>Milestone Trend Analysis (MTA) would be beneficial in a scenario where a project has multiple critical deadlines or milestones that need to be met. For example, in a large software development project with set release dates for different features, MTA helps track the progress of milestones over time, identifying any delays early and allowing for timely corrective actions to keep the project on schedule.</p> </details>

### **Scenario:** You are managing a software project with a fixed budget and a fixed deadline, but the customer has requested additional features halfway through the project. How would you approach this situation using the methods and techniques discussed?

<details> <summary>Click to show answer</summary> <p>I would use the Earned Value Analysis (EVA) to assess the current progress and determine the impact of the additional features on the project's scope, cost, and schedule. I would then update the burndown chart to reflect the new requirements and discuss with the customer the potential trade-offs, such as extending the deadline, increasing the budget, or reducing other functionalities. If the customer insists on the additional features without changing the budget or deadline, I would escalate the issue to the steering committee or upper management for a decision.</p> </details>

### Discuss the potential risks and benefits of involving more people in a project as a corrective action to meet a tighter deadline. Provide examples from project management principles.

<details> <summary>Click to show answer</summary> <p>Involving more people in a project to meet a tighter deadline can have both risks and benefits. The potential benefit is increased manpower, which could theoretically speed up the completion of tasks. However, according to Brooks' Law from project management principles, adding more people to a late project can make it even later due to increased communication overhead and the time required to onboard new team members. Additionally, it can lead to coordination issues and reduced productivity. For example, in a software development project, adding new developers may initially slow down progress as they familiarize themselves with the codebase and project requirements. The key is to balance the additional resources with the potential disruption they may cause.</p> </details>





