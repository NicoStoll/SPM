#Agile #Lean #TechnicalDebt #Documentation
### Agile Project Management
[[Agile]]

Traditional Project Management:
- **Sequential Approach:** Projects follow a structured, linear progression through defined phases
- **Emphasis on Planning**
- **Hierarchical Structure:** Clear roles within a hierarchical organizational framework
- **Predictive Nature:** Relies on predicting and planning for the entire project lifecycle

Agile Project Management:
- **Iterative and Incremental Approach**
- **Customer Collaboration:** feedback throughout the development process
- **Cross-Functional Teams:** self-organizing teams comprising members with diverse skills and expertise
- **Collaborative environment**
- **Sprints/Iterations**
- **Planning, Execution, Review:** Each iteration includes planning, execution, review and adaptation phases
- **Backlog Management:** Prioritization and management of a product  backlog containing user stories or features
- **Daily Stand-ups**

Agile Methods
1. **Kanban:** Use an Kanban board to represent the different stages of the process. Limit the Work in Progress (WIP) by setting limits in each stage. 
2. **SCRUM:** Iterative Development by dividing the work into fixed-length iterations called sprints (2-4 weeks). Defined roles (Scrum Master, Product Owner, and Development Team)
3. **SCRUMBAN:** Hybrid approach. Emphasizes continuous delivery over fixed-length iterations, enabling continuous delivery and continuous improvement
4. **Extreme Programming:** emphasizes TTD, continuous integration and refactoring. 
5. **Feature Driven Development:** Iterative and Incremental, focuses on delivering features or functionalities in short iterations


### Lean Project Management
**Lean Thinking:** focusing on creating value for the customer by optimizing the flow of products and services through value streams while minimizing waste.
**Principles:**
1. **Define Value:** Identify what matters to the customer
2. **Eliminate Waste:** Cut unnecessary steps
3. **Smooth Flow**
4. **Pull System:** Respond to customer demand
5. **Continuous Improvement**

**Differences to Agile:**
- Focus on eliminating waste <-> Agile emphasizes adapting to changing environments and delivering value in short iterations
- Lean allows for greater Scope flexibility

### Agile Project Management Approaches in other Branches
Agile is applicable in other branches as well, e.g. Automotive, Education, ...
Automotive:
- Faster Innovation: Streamlined product development
- Improved Quality Control: Continuous Testing
- Enhanced Customer Focus
- **Challenges:** Long development cycle, supplier integration, regulatory compliance

### Scaling Agile Frameworks for Large Software Projects

| Framework                        | Best for                                    | Description                                                                                                                                                                                                                                                                                                                                                                                                                               |
| -------------------------------- | ------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Disciplined Agile Delivery (DAD) | Adaptable and flexible approach             | DAD provides a process decision framework that is highly adaptable and promotes flexibility by integrating strategies from various agile and lean approaches. It emphasizes a goal-driven delivery lifecycle that accommodates multiple lifecycles (e.g., Scrum, Kanban) based on project needs.                                                                                                                                          |
| LeSS                             | Extending Scrum with minimal complexity     | Large-Scale Scrum (LeSS) is designed for organizations looking to scale Scrum principles and practices across multiple teams while minimizing additional complexity. It simplifies organizational structures and processes to maintain the core principles of Scrum at scale.                                                                                                                                                             |
| Nexus                            | Medium-sized businesses or large projects   |                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| SAFe                             | Large organizations aligning multiple teams | Scaled Agile Framework (SAFe) is suitable for large enterprises aiming to coordinate and align multiple agile teams across complex projects. It provides a structured approach to scaling agile practices, integrating principles from lean, systems thinking, and DevOps to achieve enterprise-wide agility. SAFe includes roles, ceremonies, and artifacts to facilitate alignment, collaboration, and continuous improvement at scale. |

### Agile/Hybrid Project Portfolio Management

- **Alignment**: Ensure all projects and programs within the portfolio are aligned with the strategic objectives. Short config cycles lead to fast adaptation to strategic changes, Projects harming the progress of the portfolio need to be terminated immediately.
- **Agility:** Authorize only projects which are going to start in the next portfolio cycle. Project durations should be short. A Portfolio Bugger protects the portfolio against the organizational or natural hindrances.
- **Efficiency:** Key resources must focus on portfolio projects. To avoid multitasking, tasks should be performed in a sequential manner

### Managing DevOps Projects

Five dimensions of DevOps:
1. **Collaboration** - Empowerment of team members
2. **Automation** - Streamlines processes, reduced manual errors
3. **Culture** - enhanced empathy and support
4. **Monitoring** - proactive issue detection, continuous feedback loop
5. **Measurement** - use of common business-focused metrics, informed decision-making
![[Assets/DevOps.png]]

### AI in Project Management
1. **Automation of Routine Tasks:** Scheduling, resource allocation, progress tracking. Frees up PMs time for strategic planning and problem-solving
2. **Data-Driven Insights:** Analyze large datasets to identify pattern/trends. Provides insights into risk management, forecasting and performance optimization
3. **Enhanced Decision-Making:** predictive analysis and  decision support systems. Aids informed decisions using real-time data

### Vendor Management in Outsourced Software
Vendor Selection via **Analytic Hierarchy Process (AHP)**
- **Pre-REP Activities:** Preparation and Planning conducted by company personnel before issuing the request for Proposal (REP)
- **Post-REP Activities:** Evaluation of decision-making processes carried out by company personnel after receiving proposals from potential vendors

### Managing Technical Debt in Software Projects
**Technical Debt:** extra costs that accumulate from taking shortcuts during the software project lifecycle, caused by e.g. delivery pressure, lack of prioritization, insufficient resources
**Forms:**
- Design Debt
- Testing Debt
- Documentation Debt
**Costs of Technical Debt:**
- Increased maintenance cost
- Decreased productivity
- Reduced system performance
**Measurement:**
- Estimation Techniques 
- Systems Perspective (debt spans architecture and design)
- Practical Metrics (quantify with code complexity, modularity)
- Impact on Projects (long-term implications on project flexibility and cost)
**Best Practices:**
- Proactive identification and monitoring
- Documentation and Knowledge sharing
- Continuous improvement
- Collaborative Decision-making

### Software Project Documentation and Knowledge Management
- Documentation must be an integral part of the development process
**Documentation Lead:** Dedicated Team member, responsible for consistency of documentation
**Process Documentation:**
- Project Plans
- Coding Guidelines
- Development Practices
**Product Documentation:**
- System Documentation
- Configuration Guides
- API Documentation
- Common issues
### Managing MLOps Projects

MLOps, short for Machine Learning Operations, is a set of practices that aims to deploy and maintain machine learning models in production reliably and efficiently. It combines the principles of DevOps (Development and Operations) with machine learning to automate and streamline the entire machine learning lifecycle, from data preparation and model training to deployment and monitoring. MLOps focuses on collaboration between data scientists, ML engineers, and operations teams to ensure models are continuously delivered, monitored, and updated in a scalable and reproducible manner.