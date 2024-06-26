# Unit Testing with Vitest

This repository utilizes Vitest to test TypeScript functions.

## Unit testing best practices
- **Test One Concept at a Time:** Each unit test should focus on testing a single concept or behavior. A unit is known as a function, class, or component.
- **Keep Tests Small and Fast:** Unit tests should be small and executed quickly. They should only test a small piece of functionality.
- **Use Descriptive and Readable Test Names:** A test name should clearly describe what is being tested.
- **Arrange, Act, and Assert (AAA) Pattern:** Unit tests should be structured using the AAA pattern. The "Arrange" phase sets up the necessary preconditions and inputs, the "Act" phase invokes the unit being tested, and the "Assert" phase verifies the expected behavior or outcome.
- **Test both Positive and Negative Scenarios:** Ensure that tests cover both the correct (valid inputs) and incorrect (invalid input, edge cases, error conditions) behavior. 
- **Use Mocks and Stubs:** Unit tests should focus on testing a specific unit of code in isolation.
- **Test Coverage:** Aim for high test coverage, which refers to the percentage of code that is covered by your tests.
- **Test Independance and Order:** Ensure that each test is independent and does not rely on the state or behavior of other tests.
- **Regularly Review and Update Tests:** Unit tests should be reviewed regularly to ensure they remain accurate, relevant, and aligned with the current codebase.
- **Integration Testing into Your Development Workflow:** Incorporate unit testing into your development process and run tests frequently. Automated testing tools and continuous integration (CI) systems can help execute tests automatically.

## Motivation for Vitest
- **Fast:** Uses esbuild to compile ts to js which is 20-30x faster than the standard ts compiler tsc.
- **Mutli-threading:** Uses multi-thread to run the test using service workers via tinypool which uses the node.js thread pool.
- **DX:** Out of the box support for es module, typescript, JSX.
- **Jest Compatability:** Compatible with Jest which was created by Meta.
- *Website:* https://vitest.dev/

## Motivation for Jest
- **Popular and Dependable:** A nice JS testing framework with a focus on simplicity.
- **Isolated:** Tests are parallelized by running them in their own processes to maximize performance
- **Zero config:** Jest aims to work out of the box, config-free on most JS projects.
- **Great API:** Jest has the entire toolkit built in one place. Well documented and well maintained.
- *Website:* https://jestjs.io/

## Code Coverage
- Code coverage is a software metric for measuring the percentage of code that is executed by test cases during software testing.
- Helps to identify untested areas in the code, potentially revealing bugs or logic errors.
- High code coverage is desirable, but it does not guarantee the absence of bugs; comprehensive test cases are essential for reliable software.
- 100% code coverage is a desirable goal, but not always practical.

