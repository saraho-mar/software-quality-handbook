#Testing strategy

##Testing Types
A clear testing strategy helps a startup team build software more reliably and reduce defects before release. 
Different types of testing are used for different purposes, and each one supports quality differently.

Unit testing:
Unit testing checks small individual parts of the code, such as methods or functions, to make sure they behave correctly. 
This helps developers catch logic errors early and makes it easier to change code safely later.

Integration Testing:
Integration testing checks whether different components of the system work correctly together. 
Even if individual parts pass unit tests, problems can still happen when data moves between components or when one part depends on another.

Validation or Acceptance testing:
Validation testing checks whether the software meets the requirements and behaves as expected from the user’s point of view. 
This helps confirm that the product solves the intended problem, not just that the code runs.

System Testing:
System testing checks the complete system as a whole. This can include performance, recovery, security, and behaviour under realistic conditions. 
It is useful for finding issues that only appear when the full system is running.

A strong testing strategy does not rely on only one kind of testing. Instead, it uses a combination of testing types so that defects can be found at different stages before they reach production.

##Checklist

Before releasing or merging important work, the team should ask:

- Have unit tests been added or updated where needed?
- Have important integration points been tested?
- Does the feature behave as expected from the user’s perspective?
- Have edge cases or invalid inputs been considered?
- Have any known bugs or risky areas been checked?
- Does the change affect existing functionality that should be regression tested?
- Are test results clear and recorded?
- Has the right type of testing been chosen for the change?

##Sources 
- What is Software Testing- IBM
  Link: https://www.ibm.com/think/topics/software-testing
- What is Integration Testing- IBM
  Link: https://www.ibm.com/think/topics/integration-testing
- The Practical Test Pyramid - Martin Fowler
  Link: https://martinfowler.com/articles/practical-test-pyramid.html
