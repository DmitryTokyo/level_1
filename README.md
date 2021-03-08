# Testing sandbox level 1

Welcome to the testing sandbox: practice-driven testing instrument.
It can help you to get more comfortable and skilful at writing different
types of tests.

## The plan

The sandbox has five different levels. Here is an approximate plan:

1. Basics unit testing (you are here).
2. Production-ready unit testing for simple functions.
3. Confident unit testing: advanced features, complicated mocking, tests organisation.
4. End-to-end tests mastery.
5. TDD and PBT.

Some levels can have sub-levels, and every level can have its process of completion.

Level 1 is about the basics of unit testing.
It's not enough to be confident at writing tests in production,
but it's a solid start of getting to unit testing.

## How to complete this level

1. Read/watch everything in a reading list.
2. You have some code in `code.py`. Write tests for this code with 100% branch coverage. Push it to your fork of the repo (no need in the pull request).
3. Ask your colleague to make a review of your code. Fix all errors.
4. Ask me (@melevir) to review your code. Fix all errors.
5. Hooray!

## Materials

Read this before writing the first line of code:

- [Branch coverage measurement](https://coverage.readthedocs.io/en/coverage-5.5/branch.html)
- [Specifying tests](https://docs.pytest.org/en/stable/usage.html#specifying-tests-selecting-tests) (so you don't have to run all the tests each time)
- [So, what's a good unit test look like?](https://medium.com/chris-nielsen/so-whats-a-good-unit-test-look-like-71f750333ac0)

Read/watch this during or after writing tests:

- [Pragmatic unit testing (video)](https://www.youtube.com/watch?v=5iJWOPaNZDA)
- [UnitTest by Martin Flower](https://martinfowler.com/bliki/UnitTest.html)

## Review how to

- Review considered to be done when reviewr left 3+ comments.
- Use [conventional comments](https://conventionalcomments.org/).
- If you think, that some somment is not required to fix, use `non-blocking` decorator.
- Every comment without `non-blocking` decorator has to be fixed by the author of code.
