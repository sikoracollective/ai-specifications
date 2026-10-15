# General Coding Specification

## Duplicate Code
- Duplicate, or copy and pasted, code should be avoided as much as possible.
- Always create reusable methods when it makes sense.

## Design Patterns
- Design patterns shall be used when it makes sense to avoid code rewrites if new functionality has to be added at a later date.

## Security Issues
- Security should always be kept in mind when generating new code. Correct any found issues during the development process, rather than just at the end of it.
- If a security review of the code is requested, list all issues and their severity.
- If any third party code is used, those libraries should be researched to see if they contain any known vulnerbilities. If vulnerabilities are found, the user should be made aware of those and their severity.
- The latest version of any third party code should always be preferred.

## Hardening
- If a hardening review of the code is requested, list all the issues and their severity.

## Logging
- Add logging into the code where it makes sense.
- Follow the best practices for the language when generating log statements.
- Use the standard logging tools for the language.
- No personally identifiable information should be logged.
- Log levels
    - Make sure the correct logging level is specified for log messages, if the logging tool allows for it.
    - If a logging tool does not have logging level functionality, prefix log messages with one of the following log levels, followed by a space: FATAL, ERROR, WARN, INFO, or DEBUG.
    - Log level words shall be capitalized.

## Documentation
- Comments should be added to the code while it is being generated.
- Comments should be formatted according to the best practices for the language.
