0x03. Unittests and Integration Tests UnitTests Back-end Integration tests By: Emmanuel Turlay, Staff Software Engineer at Cruise Weight: 1 Ongoing second chance project - started Aug 24, 2023 6:00 AM, must end by Sep 2, 2023 6:00 AM An auto review will be launched at the deadline In a nutshell… Auto QA review: 0.0/26 mandatory & 0.0/4 optional Altogether: 0.0% Mandatory: 0.0% Optional: 0.0% Calculation: 0.0% + (0.0% * 0.0%) == 0.0%

Unit testing is the process of testing that a particular function returns expected results for different set of inputs. A unit test is supposed to test standard inputs and corner cases. A unit test should only test the logic defined inside the tested function. Most calls to additional functions should be mocked, especially if they make network or database calls.

The goal of a unit test is to answer the question: if everything defined outside this function works as expected, does this function work as expected?

Integration tests aim to test a code path end-to-end. In general, only low level functions that make external calls such as HTTP requests, file I/O, database I/O, etc. are mocked.

Integration tests will test interactions between every part of your code.

Execute your tests withResources
Read or watch:

unittest — Unit testing framework
unittest.mock — mock object library
How to mock a readonly property with mock?
parameterized
Memoization
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

The difference between unit and integration tests.
Common testing patterns such as mocking, parametrizations and fixtures
