# Amazon Q Developer – Prompt Library

This file collects example prompts that demonstrate Amazon Q’s capabilities across code comprehension, debugging, documentation, migration, and modernization.  
These are based on real workshop usage and adapted for everyday engineering.

---

## Code Comprehension

- `Explain to me what this project is about and how it's structured`
- `What are the key components and functionality of this pom.xml file?`
- `Please analyze the project structure and tell me where the core game logic is implemented.`

## Debugging & Testing

- `Run the application using Maven. Fix any errors.`
- `Create a unit test that tests getRandomWord in the WordList class.`
- `Create a unit test to verify getRandomWord is returning random responses.`
- `Run the Maven tests and fix any errors or failures.`

## Documentation

- `@Word.java Add JavaDoc comments to the selected method`
- `Create a GettingStarted.md file for the application with setup instructions.`

## Migration & Modernization

- `Migrate our game application from Java to Rust.`
- `Create a transformation.md file documenting the migration.`
- `Generate a transformation_plan.md file with steps, testing strategies, and timeline.`
- `Migrate the word selection functionality from Java to Rust.`
- `Generate unit tests for our migrated Rust code.`

## Architecture & Refactoring

- `Please define a plan for refactoring the WordList repository into a new microservice using Python + AWS Lambda + API Gateway.`
- `/dev Using the plan, refactor the WordList repository.`

## Fun & Creative

- `Roast this code in a funny way.`
- `Give me a humorous code review in the style of a stand-up comedian.`

---

## Notes

- Use `@workspace`, `@file`, or `@folder` to scope Q to parts of your project.
- Commands like `/review`, `/transform`, and `/clear` provide additional control.
