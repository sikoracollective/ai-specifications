# General Testing Specification

## Test Directory
- Place all testing-related functionality and documentation in a tests directory.
- Put the tests directory in the main directory of the application.

## Tests
- Generate automated tests for new functionality when possible.
- Cover new behavior, including important edge cases and failure paths, not only the happy path.
- Use the project's existing test framework and patterns.
- Keep tests isolated. Do not make tests depend on each other.
- Avoid depending on external systems unless required.
- Prefer deterministic tests. The same input should produce the same result.
- Clean up test data and fixtures after runs when tests create state.
- Never hardcode credentials, API keys, tokens, or other secrets in tests.
- Add or update tests in the same change when behavior changes.

## Test Setup
- State the exact steps to set up the test environment in a README.md file.
- Document the exact command(s) to run the tests in that same README.md file.
- Put that README.md file in the tests directory.
- Do not put setup or run instructions in the main README.md.
- Only list the steps for a macOS environment.

## Test Reports
- Store test reports in a logs directory under the tests directory.
- Gitignore the tests/logs directory. Do not commit generated test reports.
- Use only these verdicts: PASS, FAIL, and SKIP.
- Start each report line with the verdict in uppercase, then the test file, then the test name.
- Example: `PASS tests/exampleTest.js submits a valid form`
- State how many tests were run, how many passed, how many failed, and how many were skipped.
