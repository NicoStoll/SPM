#Agile #SAFe #Scrum
### Agile Manifesto

- Individuals & Communication > Formal processes
- Customer Collaboration > Formal contracts
- Flexible change adjustment > following a plan
- Working software > documentation

### Agile Monitoring & Control Cycle

![[AgileControlCycle.png]]
- small control loops due to small iterations
- direct communication and feedback
- earlier dealing with risk
### Assumption

**Rather less but stable, accurate functionality than unusable solid fundament**

| Pro                                                                                    | Con                                                       |
| -------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| More current utility                                                                   | Loss of architecture overview                             |
| Future utility uncertain                                                               | Additional effort for code unused in later iterations     |
| More clarity for future iterations                                                     | Additional effort for intermediate changes (refactorings) |
| Less risk                                                                              | Organizational resistance to changes                      |
| Software as an immaterial good easily changeable at little cost with good tool support |                                                           |

### Scaling Agile
- **horizontal scaling:** additional iterations until project is finished --> consequences:
	- dealing with increasing uncertainty on finishing times for items
	- dealing with increasing HR issues: team development & fluctuation
- **vertical scaling:** employ multiple teams simultaneously --> consequences:
	- team/individual status communication between teams difficult
	- competition for scarce resources between teams
	- iterations (overlapping, simultaneous)
	- when does delivery take place?
#### Key practices:
- Cadence and synchronization
- Managing WIP (work in progress)
- Collaboration  in solving the biggest problems

#### Scrum of Scums
- low-scale (max. 5 teams)
- lightweight scaling
- emphasis on coordinative meetings
	- ambassador from each Scrum team
	- further team members as needed
	- not limited to 15 minute timebox
![[ScrumOfScrums.png]]
#### SAFe
- Agile Release Train (ART, team of multiple teams (50-125 people))
- delivers value in Program Increments (PI) of typically 8-12 weeks (4 development and 1 innovation & planning iteration)
- Enablers:
	- **Exploration enablers:** support research, prototyping, ...
	- **Architectural enablers:** build the architectural runway
	- **Infrastructure enablers:** build, enhance and automate the development, testing and deployment environments
	- **Compliance enablers:** Verification & Validation, documentations and signoffs, regulatory submissions and approvals

![[SAFe.png]]

### Success Factors and effects of Agile

#### Six Sigma:
- **Man**: 
	- key factor in agile
	- capable, responsible developers work in small groups on a broad range of tasks
	- Trust-based direct customer collaboration
- **Method**:
	- small hierarchies
	- Manager as enabler
	- Lightweight
- **Measures & Motivation**
	- self-chosen tasks in own responsibility
	- discernable product impact
	- early feedback by short iterations
- **Machine**
- **Materials/Information**
	- short iterations lead to very current information
	- direct customer communication provides accurate information
- **Milieu (Environment)**
	- lightweight processes and small groups lead to low environment complexity

#### Studies:
- **User Involvement**
	- directly from manifesto: Collaboration, Communication
	- short iterations --> feedback loops
- **Top Management Support**
	- IT-company: inherently due to small hierarchies
	- Customer: mandatory with continuous customer involvement
- **Process/Problem Analysis**
	- direct communication and small problem sizes facilitate proper analysis
- **Planning and Organization**
	- small groups and iteration sizes reduce complexity
	- manager as enabler removes organizational aspects from developers
- **Realistic Expectations**
	- ensured by short product  increments and direct communication


### Questions

#### What are the four core values of the Agile Manifesto?

<details> <summary>Click to show answer</summary> <p>Individuals and interactions over processes and tools, working software over comprehensive documentation, customer collaboration over contract negotiation, and responding to change over following a plan.</p> </details>

#### What are the main differences between horizontal and vertical scaling in Agile methodologies, and what are some challenges associated with each?

<details> <summary>Click to show answer</summary> <p>Horizontal scaling involves additional iterations until the project is finished, leading to uncertainties in finishing times and HR issues. Vertical scaling employs multiple teams simultaneously, leading to challenges in inter-team communication, competition for resources, and coordination of delivery timelines.</p> </details>

#### Discuss how the principles of Agile align with the Six Sigma framework, particularly focusing on the 'Man,' 'Method,' and 'Materials/Information' categories. How can integrating Agile and Six Sigma improve project outcomes in terms of quality and efficiency?

<details> <summary>Click to show answer</summary> <p>Agile emphasizes capable, responsible developers working in small groups with direct customer collaboration ('Man'), small hierarchies and managers as enablers ('Method'), and short iterations with direct customer communication providing accurate information ('Materials/Information'). Six Sigma focuses on improving quality and reducing defects through a structured approach. Integrating Agile and Six Sigma can improve project outcomes by combining Agile's flexibility and quick feedback loops with Six Sigma's rigorous quality control, leading to both high efficiency and high-quality deliverables.</p> </details>