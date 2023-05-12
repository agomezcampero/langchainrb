## [Unreleased]
## [0.3.0] - 2023-05-12

- Agents
  - Introducing `Agent::ChainOfThoughtAgent`, a semi-autonomous bot that uses Tools to retrieve additional information in order to make best-effort informed replies to user's questions.
- Tools
  - Introducing `Tool::Calculator` tool that solves mathematical expressions.
  - Introducing `Tool::Search` tool that executes Google Searches.

## [0.2.0] - 2023-05-09

- Prompt Templating
  - Ability to create prompt templates and save them to JSON files
  - Default `Prompt::FewShotPromptTemplate`
  - New examples added to `examples/`

## [0.1.4] - 2023-05-02

- Backfilling missing specs

## [0.1.3] - 2023-05-01

- Initial release