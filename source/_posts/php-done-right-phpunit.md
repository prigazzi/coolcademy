title: Unit Testing
date: 2014-10-15 11:17:57
categories:
    - codecademy
---
## Why Unit Test?

* **Correctness**.
  With Unit testing, you can be certain, in a matter of seconds, that the code you wrote doesn't have bugs and behaves as expected.

* **Stability**.
  You can be sure that changes introduced in the future, by whatever developer, in whatever component of the entire system, aren't breaking existing functionality. You can advert a crisis by just having a failing test telling you something's wrong.

* **Design**.
  A Unit Test is a perfect proof of concept of how a specific component should behave, and how your code is supposed to be used. It shows how clear an API is, or how simple is to accomplish a certain task. It's the best documentation possible for any component.

## What am I testing exactly?

The general idea into Unit Testing, it's to configure a system, let it do it's work, and the check that the output is consistent with what we expected. This could be the desired output, or even an expected error if the input was incorrect. 

This viewing of the system to test as a black box that has an input and produces an output, could be extended from testing a single method, to an entire simulated request, depending on the level of integration you want. 