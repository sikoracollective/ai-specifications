# General README Specification

## Files
- If an application or plugin requires a specific type of readme file, that file is the source of truth.
- A README.md file is a secondary file that should follow the main readme file.
- README.md files are used for GitHub documentation.
- If the primary readme and README.md conflict, the primary readme wins.
- Keep README.md aligned with the primary readme by summarizing or linking to it. Do not maintain a conflicting fork of the same content.

## Contents
- README files should contain general information such as purpose, how to use or install at a high level, and license.
- Include high-level prerequisites when they are needed to use or install the project, such as runtime or OS requirements.
- Do not list deep specifics about individual files.
- A short project structure overview is allowed when it helps orient readers.
- Keep readme language short and clear.
- Prefer a focused readme. Link out instead of duplicating long documentation.
- Use best practices for the language or specific app when writing readme files.
- Only document real behavior. Do not invent features or outdated steps.
- Never include credentials, API keys, tokens, or other secrets in readme files.

## License
- Use the MIT license unless the platform or application type requires a different license.
- WordPress plugins and themes should use GPL v2 or later.
- Add a LICENSE.md file, or the license file required by the platform, when the project is licensed.
- The README should state the license and link to the license file when one exists.

## Updating
- Update readme files in the same change when behavior that users need to know about changes.
