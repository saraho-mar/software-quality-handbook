# Testing Strategy

## Why testing strategy matters 

Since this is a fast moving small company a strong testing strategy will help them move fast without breaking production a lot, as it reduces the chnaces of defects, 
allows developers to easily change code and makes the releases more predictable. 
The correct method of testing should be used to improve quality.

## Sarah 

Source 1:
Title: Software Testing in Continuous Delivery
Link: https://www.atlassian.com/continuous-delivery/software-testing?utm_source=chatgpt.com

Key points:
 - Software testing improves quality because it checks if the code is correct, the performance, and any expected behaviour before the release.
 - Good testing strategies combines different testing levels such as integration, unit and end to end testing.
 - Unit tests give a fast foundation while integration and end to end tests give more confidence.
 - Testing reduces long term costs because it catches defects early and lowers the maintanence efforts.
 - In continuous delivery automated tests act as quality support before any code is merged or deployed.

Why its useful:
This is useful because it explains how testing is part of a practical delivery procress rather than just an activity on its own. 
Its even more helpful becuase it shows how different kinds of tests worktogether to improve quality and allow for safer releases.

Source 2:
Title: Architecture strategies for testing
Link: https://learn.microsoft.com/en-us/azure/well-architected/operational-excellence/testing

Key points:

 - Testing strategies need to be formalised ans aligned with business objectives rather than just having the same generic approach to all workloads.
 - Teams should start testing early and be continuous instead of leaving it to the end.
 - Layered approach is recommendedby using unit tests, integration tests and end to ed testing in a balanced way.
 - Tests in fast feedback layers should be integrated into pipelines so faulty code is stopped early.
 - Different types of testing should be used based on risk, workload type, and business impact rather than using every test type equally.
 - Tests should be treated with the same care as production code, including code review, versions, maintenance, and reliability checks.
 - Flaky tests should be fixed or removed.
 - Teams should maintain and evolve their tests over time so that the coverage stays useful as the system changes.

Why it is useful:
This is useful to the startup as it will help them in treating tests as stategic engineering activities rather than just a random set of test types.
It is even more helpful because it shows teams how to align testing with business risks, delivery pipelines and maintaining long term.

Source 3:
- What is Software Testing- IBM
  Link: https://www.ibm.com/think/topics/software-testing
Source 4:
- What is Integration Testing- IBM
  Link: https://www.ibm.com/think/topics/integration-testing
Source 5:
- The Practical Test Pyramid - Martin Fowler
  Link: https://martinfowler.com/articles/practical-test-pyramid.html    

## Best practices

- Prioritise fast and reliable automated tests
- Use a balanced mix of unit, integration, and end-to-end tests
- Add tests alongside new features and bug fixes instead of leaving them until later
- Keep tests clear, maintainable, and easy to trust
- Run tests regularly during development and before merging code
- Fix flaky tests quickly so the team can rely on the results
- Review test code the same way as production code
- Treat testing as a tool for confidence and defect prevention

## Bad practices 

- Relying only on manual testing before release
- Not writing enough automated tests for important features
- Depending heavily on slow or flaky end to end tests
- Leaving testing until the end of development
- Keeping broken or unreliable tests in the pipeline
- Measuring quality only by the number of tests written
- Writing tests that are difficult to understand or maintain
- Treating test code as less important than production code
- Merging code even when important tests are failing

## Team rules for this company

- Every new feature has to include automated test coverage
- Every bug fix should include a regression test where practical
- Pull requests should not be merged if critical automated tests are failing
- Unit and integration tests should form the foundation of the testing approach
- End to end tests should be used selectively
- Flaky tests must be fixed or removed quickly
- Test code must meet the same quality expectations as production code
- Testing must happen throughout development not only before release

## Testing Types

A clear testing strategy helps a startup team build software more reliably and reduce defects before release. Different types of testing are used for different purposes, and each one supports quality differently.

Unit Testing:
Unit testing checks small individual parts of the code, such as methods or functions, to make sure they behave correctly. This helps developers catch logic errors early and makes it easier to change code safely later.

Integration Testing:
Integration testing checks whether different components of the system work correctly together. Even if individual parts pass unit tests, problems can still happen when data moves between components or when one part depends on another.

Validation or Acceptance Testing:
Validation testing checks whether the software meets the requirements and behaves as expected from the user’s point of view. This helps confirm that the product solves the intended problem, not just that the code runs.

System Testing:
System testing checks the complete system as a whole. This can include performance, recovery, security, and behaviour under realistic conditions. It is useful for finding issues that only appear when the full system is running.

A strong testing strategy does not rely on only one kind of testing. Instead, it uses a combination of testing types so that defects can be found at different stages before they reach production.

## Checklist

Before releasing or merging important work, the team should ask:

- Have unit tests been added or updated where needed?
- Have important integration points been tested?
- Does the feature behave as expected from the user’s perspective?
- Have edge cases or invalid inputs been considered?
- Have any known bugs or risky areas been checked?
- Does the change affect existing functionality that should be regression tested?
- Are test results clear and recorded?
- Has the right type of testing been chosen for the change?
