# Exercise_3
unit testing : tests small, isolated units of code
Tests for a single function, class, or module are called Unit Tests. Unit Tests prove that a single piece of code fulfills its basic requirements. Unit Tests may perform very detailed checks and include a fair amount of nitpicking. When writing Unit Tests, we usually want to cover many border cases , such as empty input, long input, weird input, and so on
Unit Tests should be

Fast—execute in a few seconds or less

Isolated—test only one piece of code at a time

Repeatable—can be rerun with the same outcome

Self-verifying—the Test Suite does not need additional information to evaluate the test

Timely—tests are written before the code (more on this in section “The Test-First Approach”)

Other common Best Practices found in Unit Tests are using only one assert per test (although this is rather a rule of thumb) and using mock objects to replace complex components by simpler placeholders, so that the test depends only on the code unit being tested.
