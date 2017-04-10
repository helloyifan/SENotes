

Course Summary

Introduction:
* fault /error / failure
* static vs dynamic approaches

Explatory  Testsing
* most of tests you write should be automated
* however not all manual testing is useless, createive people with good knowledge of computer can find interesting results

Defining Test  Suites
* branch and statement coverage - cfgs
  * Good branch statement cvg doesnt mean good test suite
* round-trip coverage
  * FSMS

Grammar-based Appraoches
* fuzzng (good for security - try american fuzzing loop)
* generate inputs from grammar
* mutation testing
  * (improve test suit by killing mutants)


Results - how good can statement coverage get?
 * 96% Junit, 80% usual

Does mutation testing work? (yes)
Is coverage helpful (not very)


Engineering Test Suites

* motivated need for tests
* test design principles
  * self - checking
  * verify state or behaviour (mock objects)
  * use continuous intergation
  * done be flaky
* unit vs regression vs intergation tests
 * xUnit 
 * Selenium

Tools
* dynamic vs static
* coverity
* code review + bug reporting
* PMD, Find Bugs, jshint
* FB infer - memleaks, null derefs
* valgrind, address sanitizes
