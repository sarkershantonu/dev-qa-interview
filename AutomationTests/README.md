# Automation Testing
- How to decide automation tools/framework to work with
- What to automate?
- How to automate?
- Why automate? 
- Business values
- Deliverables
- Decision making help & noise in team
- How to decide most effective tests
- is 100 % tests are automatable , if yes, how? if no why not? 

# A classical conversation : 
https://www.youtube.com/watch?v=pNeDFJp_xwU

# Best Practices
- Break down test by V diagram of testing
- Make test as independent as possible
- evaluate tests by refactoring and review
- find most effective test
- isolate environment variable as much as possible
- Make report more redable to decision makers and more detail for developer/support team
- Integrate with CI/CD deployment
- Provide peoridic run report available
- Avoid flakey tests. 
- Avoid UI test. 
- Seperate test based on component for most effective outcomes
- End to End test should have UAT scenarios 
- Run tests as suite and organize suites based on scrum/kanban goal 
- Decide UAT suite 
- Decide Regression suite and after every release, increase this based criticality 
- Include Basic performance & security checks insde regression as non functional tests. 
- Review test after each run. 

# Avoiding flakey test

# Avoiding fake testers

# Designing framework bottom up

# Reporting principle 
- Less manual overhead
- Auto test reports using build tools/commands
- Each type of audience should have different view of a report. Like stake holders, business analyst, developer/qa, prod-support etc. 
- Fail alert should be included 
- Log support shold be there
- Analysis can be included (custom perserts, log analyzers like splunk, logstash, amazon cloudwatch)
- Screenshot should be included for selenium


# How to decide tools
- Why it is best for team
- Why not ?
- How is the skill of the team
- Existing technology stack
- Developer skills
- Tester skills
- How quick to apply tests
- How quick we can show results to teams
- How we can make it effective
- How is the delivery time line & cost
- Will management invest in this
- How much training needed
- What is learning curve for this
