## SDLC Model
### Waterfall
![[waterfall.png]]
- **Arrow going down**: the results from one stage are input into the next stage
- **Arrow going up**: often more work is required at an earlier stage to complete the current stage.
- **Good for**: small project where requirement are understood
- **Not Good for**: complex and object oriented project, long and ongoing project
- Benefits
	- Simple to understand: Stages are clearly define 
	- Easy to manage: fixed stage with clear outcome
	- Stages complete one at a time
- Drawbacks
	- No working software until late during the cycle(integration done at the end), don't allow identification of potential technical or business issues early
	- can't accomodate changing of requirement
	- difficult to measure progress within stages
### Iterative
![[Iterative.png]]
- **Good for**: small requirement at the start, Iteratively review to identify further requirement and result in complete system
- Benefit
	- early design flaw can be found and taken corrective measure quickly
	- functionality developed early in the life cycle
	- result obtain early and periodically
	- parallel development can be plan
	- progress can be measure
	- less costly to change requirement
	- testing and debugging of smaller subset of program is easy
	- risk are identified and resolve during iteration
	- Easier to manage risk – high-risk part is done first.
	- With every increment, operational product is delivered.
	- Issues, challenges and risks identified from each increment can be utilised/applied to the next increment.
	- Better suited for large and mission-critical projects.
	- During the life cycle, software is produced early, which facilitates customer evaluation and feedback.
- DrawBack
	- Benefit only large project as its hard to break small software system into further small servicable system
	- more resource may be required
	- design issues might arise because not all requirement are gathered at the beginning of the entire life cycle
	- defining increment may require definition of the complete system
### RAD
![[RAD.png]]
- minimal planning, make prototype which is a working model of part of the solution, module develop in parallel as prototype and early integration is done, user inivolvement are required through the cycle
- Benefits
	- Change of requirement
	- Progress can be measure
	- Productivity increase with fewer people in short time -> reduce development time
	- increase reuseability of component
	- quick initial review occurs
	- encourage customer feedback
	- integration from the very beginning can solve a lot of integration issues
- Drawback 
	- Only system that can be modularise can be built
	- Required highly skill developer and designer
	- Suitable for projects requiring shorter development times.
	- Suitable for systems that are component based and scalable
## Design
### Structure Chart
- Its feature
	- hierarchy of modules
	- iteration
	- selection
- Example
	- ![[Structure Chart.png]]
### State Transition Diagram
- Computer is a FSM (finite state machine) which has a start state; some input cause the state to change
- Example
	- ![[State Table.png]]
	- ![[State Transition.png]]

## Testing
### Error
- Cause of error:
	- programmer mistake
	- requirement not made correctly
	- design error
	- poor ui -> user mistake
	- computer hardware experience failure
- Type of erorr:
	- Syntax error: grammatical error, not follow rule of high level langauge construct
	- 
- Reason for testing: reputation, early error fix