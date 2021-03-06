# Contributing to resync

Issues and pull requests are appreciated. I apologize if it takes me some time to respond to issues.

## Submitting issues

In the case of bugs please describe in detail, preferably with a recipe to repeat and demonstrate the problem. Although you should include test data as necessary, please be careful not to include secrets or passwords!

If you suggest a new feature, please give an example of expected behavior and use. For changes to modules and methods a tests case would be idea.

## Coding style

If submitting a pull request:

   * Please discuss in a issue before submitting a pull request for significant changes.
   * Please submit pull requests against the `develop` branch (changes are collected there before making a release).
   * Please follow [PEP8](https://www.python.org/dev/peps/pep-0008/) and [PEP257](https://www.python.org/dev/peps/pep-0257/) style rules.
   * Please don't repeat code.
   * Please cover the code with tests.

## Local conventions

   * Tests: Use `from tests.testcase_with_tmpdir import TestCase` in place of `unittest.TestCase` to get a test object with `self.tmpdir` as temporary location to write to.
