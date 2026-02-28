```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the consistent, maintainable, and high-quality development of the AGENTS repository. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   All code should be encapsulated within reusable functions and modules.
*   Avoid duplication of logic and data.
*   Refactor code to eliminate redundant elements.
*   Use abstraction to hide implementation details.

## 2. KISS (Keep It Simple, Stupid)

*   Strive for minimal code complexity.
*   Avoid unnecessary lines of code.
*   Prioritize readability and understandability.
*   Focus on the core functionality; don’t over-engineer.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one, and only one, reason to change.
*   **Open/Closed Principle:**  The system should be open for extension but closed for modification.  New features should be added without altering existing code.
*   **Liskov Substitution Principle:**  Subclasses must be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to depend on implementation details.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement features that are explicitly required.
*   Avoid adding functionality without a clear, justified need.
*   Focus on the current task; don't prematurely add complexity.
*   Refactor code based on evolving requirements, not on assumptions of future needs.

## 5. Code Structure & Organization

*   **File Size Limit:** Each file should not exceed 180 lines of code.
*   **File Naming Convention:**  Use consistent file naming conventions.  (e.g., `agent_module_1.py`)
*   **Modularization:** Break down large components into smaller, manageable modules.
*   **Clear Comments:**  Provide concise and informative comments where necessary, explaining complex logic or design choices.  Avoid over-commenting.
*   **Documentation:**  For each module/function, include a brief description of its purpose and inputs/outputs in the docstring.
*   **Error Handling:** Implement appropriate error handling with informative error messages.  Avoid exceptions where possible.

## 6. Testing & Coverage

*   **Unit Tests Only:**  All development must be driven by unit tests.
*   **Test Driven Development (TDD):**  Write tests *before* writing code.
*   **Comprehensive Test Suite:**  Aim for at least 80% test coverage.  Utilize a testing framework like pytest or unittest.
*   **Mocking Strategy:**  Utilize mocks and stubs *only* for unit tests.  Don't use mocks for integration or end-to-end testing.
*   **Test Data Management:**  Ensure test data is managed effectively and doesn't introduce external dependencies.

## 7. Code Style & Conventions

*   **Indentation:** Use 2 spaces for indentation.
*   **Naming Conventions:** Follow established naming conventions (e.g., camelCase for variables/functions).
*   **Code Formatting:**  Use a code formatter (e.g., black) to enforce consistent code style.
*   **Whitespace:** Use whitespace consistently to improve readability.

## 8.  Version Control

*   Use Git for version control.
*   Commit frequently with clear, concise commit messages.
*   Follow a consistent branching strategy.

## 9.  Documentation & Collaboration

*   **README:**  Provide a README with a clear explanation of the project, instructions for setup, and usage examples.
*   **Code Review:**  Conduct thorough code reviews to ensure quality and adherence to guidelines.
*   **Collaboration:**  Collaborate effectively with team members, focusing on clear communication and shared understanding.


These guidelines are subject to change as the project evolves. Any deviations from these principles will require discussion and agreement with the team.
```