# Automated tests

If the code's behaviour changes, a test better fail. 

## Context

Acceptance test: A test suite that describes, in full, the behaviour of the code in question

## Guides

* Feature tests to describe behaviour and avoid regressions
* Integration tests to defensively check connections with other systems before deploying
* Multiclass tests to test systems of a few classes that collaborate to accomplish a task (preferred over loads of unit tests). Developer hesitation to perform changes that would reduce maintenance load because of having to change the tests are a telltale sign that the tests employ a lower level of abstraction than they should.
* Only use unit tests when documenting and validating complicated logic contained within a single class or function

## Related

* [The Ultimate Guide to Multiclass A/B Testing (Part 1)](https://towardsdatascience.com/the-ultimate-guide-to-multiclass-a-b-testing-9fb0a73ff352)
* [The Ultimate Guide to Multiclass A/B Testing (Part 2)](https://towardsdatascience.com/the-ultimate-guide-to-multiclass-a-b-testing-3cca2c687bea)

## Resources

* [Risk-Oriented Testing](https://chelseatroy.com/2018/12/18/risk-oriented-testing-from-rubytapas-screencast/)
