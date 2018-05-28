## Gherkin\* and Cucumber\*: A new test case path composition approach to testing Ruby on Rails web applications

### Abstract

Software testing is one of the most important phases of software development processes. Its main goals are: finding bugs, meeting the needs of stakeholders and proving that each part of software works as expected.
Great tests can be written by testers with experience, intuition and also a lot of creativity. One way to measure the adequacy of tests is called code coverage. It represents the percentage of lines of code covered by executed tests. One goal of testers is reaching the 100% of code coverage or arrive close to it. However, having the maximum percentage of coverage on a project gives a false sense of confidence. In other words, if part of the software is tested with 100% of coverage, nothing can be guaranteed about its robustness. In fact, test cases usually cover only the logical workflow of the entire software workflow. This problem limits considerably what we can infer with software testing.
This thesis presents a novel approach to testing Ruby on Rails web applications. This method automatically generates new test cases based on the composition of the single ones.

### Contents

* Chapter 1: Introduction
  * 1.1 Motivations
  * 1.2 Goals
  * 1.3 Results
  * 1.4 Outline
* Chapter 2: State of the art
  * 2.1 Introduction
  * 2.2 Ruby and its approach to testing
  * 2.3 RSpec and Capybara
  * 2.4 Gherkin
  * 2.5 Cucumber
  * 2.6 SimpleCov
  * 2.7 Gems overview
* Chapter 3: The limits of the Cucumber gem
  * 3.1 A real example
  * 3.2 Related work
* Chapter 4: The proposed solution
  * 4.1 Gherkin*
  * 4.2 Cucumber*
  * 4.2.1 Graph generation
  * 4.2.2 Test case paths detection
  * 4.2.3 Scenario generation
  * 4.3 Results
* Chapter 5: Conclusion

### Entry

```
@mastersthesis{zen-bs-thesis,
  author = {Zen, Roberto},
  school = {University of Trento},
  title = {Gherkin* and Cucumber*: a new test case path composition approach to testing Ruby on Rails web applications},
  year = {2014}
}
```
