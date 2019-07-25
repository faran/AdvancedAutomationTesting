# AdvancedAutomationTesting

EDX
Automated Software Testing

* Topic  1
Error, Fault and Failure
Validation vs Verification
Exploratory Testing

* Topic 2
Functional Testing
Partitions and equivalence partitioning
boundary testing

* Topic 3
Structural testing and code coverage
intellij code coverage
Branch coverage
condition coverage
path coverage and mc/dc

Testability & Mock Objects
Unit and System testing
- unit is seperately testable.
- fast but less real
- system is from user point of view hence called system
- slow 

Integration Testing
Integration test when it is integrated like db and web service

Testing Pyramid
on top is 
manual testing
then 
system tests
then
integration tests
and at the bottom is
unit tests

Mock Objects / Mockito

Controllability and Observalbility
how much system behaviour you can control

how much testing can you done by invoking the behaviour of the system under test (sut)
observability is how easy for us to observe the sut in order to verify the system behaved as expected

Testability
Design for testability 
- If xmas is hard coded and no way to change the date 
Dependency Injection
Dependency Injection vs Dependency Inversion Principle

Topic 5 : 
Code Smells
- AAA
- Arrange Act Assert
- Duplication
- Limited number of assertions
- Resource optimism (assuming resource is there like data/content)
- slow tests
- Always run tests on CI/CD
- Test Run war (work on developer)
- General fixture (pre cond )
- indirect tests (testing other things than that particular test or class)
- sensitive equality (specfic assertions)
- -Lonely tests (passes when run on their own )
- test data builder

FIRST properties of good tests
Fast
Isolated
repetable
Self validating
timely

Smells

Test data builder

Flakiness

Advanced Automation Testing
Topic 1
Decision Table
FIFA 

Same points	                F	            T	          T	          T
Same goal Diff	            dc            F	          T	          T
Same nr of goal scored	dc	F             dc	        F	          T
Action Winner	              nr of points	goal diff	  nr of goal	lots
