![[ProjectPlanning.png]]
- derive activities from the [[Work Breakdown Structure (WBS)]]
	- Additionally take into account:
		- dependencies among tasks
		- efforts
		- assign resources
		- using milestones and deliverables
- calculate start and finish time for ...
	- complete project
	- individual tasks
### Agile Planning

Plan only the next iteration
1. Assign story points to the work
2. estimate team velocity (story points per iteration)
3. derive duration
4. lay out a release plan
5. calibrate plan by doing the planned work
6. adjust the plan with feedback from measured velocity
7. regularly revise the plan as you learn more


### Dependencies

**mandatory** (based on dependencies between activities) vs **random** 
**internal** (within the project) vs. **external** 

| relationship                      | explanation                                                                                                              |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| end-begin relationship            | most common case, predecessor has to be completed before successor starts (e.g. design - implementation)                 |
| end-end-relationship              | predecessor completed before successor completed (e.g. test - QA)                                                        |
| beginning- beginning relationship | predecessor starts before successor starts (e.g. implementation has already started before writing documentation starts) |
| beginning-end-relationship        | definition of maximal distance between activities                                                                        |

### Estimation
[[Estimation]]

### Critical Path Method
[[Critical Path Method]]

### Staff assignment
based on...
- staffing qualifications
- common sense
- productive times (15+-2 days chargeable per month, other: vacation, training, non-project activities, emails, ...)

**putting more people on a late project makes it even later** --> overhead for coordination and introduction, increased effort for communication
### Resource Leveling
- resources evenly distributed
- try to avoid any considerable fluctuations
	- substantial effort for orientation for any staff member, when starting a new task
- try to flatten the histogram ( workload < 100%)

### Common Pitfalls:
- too much in too little time
- unrealistic deadlines
- management insists on unrealistic dates
- plans not discussed with ALL stakeholders
- insufficient data base for sound planning
- staffing not appropriate
- too optimistic planning
- future tasks cannot be estimated yet