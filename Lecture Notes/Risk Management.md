#Risk #RiskManagement #Agile
### Terminology
**Uncertainty:** 
	**General:** neither probability nor consequences known
	**Specific:** consequences known, probabilities unknown
**Risk:** Probabilities and consequences known, Definition (ISO 310000): effects of uncertainty on the degree of achievement of objectives
**Problem:** materialized risk
**Risk management:** systematic approach of thinking about corrective actions before problems arise

### Risk gathering

- Brainstorming
- Checklist
- Assumption analysis
- SWOT analysis
- Root cause analysis
- Interviews
- Delphi method
- Sensitivity analysis
- Probability analysis
- Utility theory
- Decision trees
- Simulation

**Goal: Assess risk exposure as probability * consequences*

## Software project risk management (Futrell)

![[ProjectRisk.png]]
### Agile risk management

1. **Identification:** All project members identify and report risk. The project manager owns the risk log containing the risk list. In regular meetings (Stand Up) impediments are highlighted. Collaborative estimation leads to higher likelihood of identifying risks.
2. **Analysis:** Assesses likelihood and impact of each risk on a scale from 1-5.
3. **Prioritization:** Significant risks are identified.
$$Risk_{Exposure}=Likelihood\cdot\operatorname{Im}pact$$


![[AgileRiskManagement.png]]

4. **Planning:** Collaborative, bring risky requirements forward in the schedule --> more time to asses risk and identify solution
![[AgileRisk.png]]
5. **Resolution:** Risk resolution means executing the risk management plan --> factor all work for the agile team into the Release Plan
6. **Monitoring:** Continually monitor the risk management plan. Also continue risk identification for the next risk management cycle.

#### Principles
**First Things First:** Deal with high risk items first. Deferring it is project suicide, do the difficult, risky tasks up front.
**Fail early:** Figure out as early as possible whether your project will succeed.
**Repeat:** Lightweight, quick processes. Continuous cycle of assessment and action to mitigate risks. At least every iteration planning, review Risk Register & look for new risks.
#### Effects of agile

| Common Risk                               | Agile's impact on common risk |
| ----------------------------------------- | ----------------------------- |
| Feature creep                             | -                             |
| Requirements or developer gold-plating    | -                             |
| shortchanged quality                      | -                             |
| Overly optimistic schedules               | -                             |
| Inadequate design                         | +(?)                          |
| Silver-bullet syndrome                    | +                             |
| Weak personnel                            | no impact                     |
| Control failure                           | no impact                     |
| Friction between developers and customers | -                             |

**Silver-bullet syndrome:** Believe, that a single solution, technology, process, or tool can solve all the complex problems in a given domain.
- Characteristics:
	- **Over-Reliance on One Solution
	- **Over-Promising Results**
- Consequences:
	- **Disappointment and Disillusionment**
	- **Wasted Resources**

**Requirements Gold-Plating:** Adding additional functionalities to the project  scope, that were not originally requested by the stakeholders.
**Developer Gold-Plating:** Developers adding additional features, enhancements or improvements to the software the were not part of the original requirements.


- https://michaellant.com/2010/06/04/five-simple-steps-to-agile-risk-management/