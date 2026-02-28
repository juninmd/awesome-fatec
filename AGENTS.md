```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure consistent, maintainable, and high-quality development for the AGENTS repository. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   All code should be encapsulated within individual files.
*   Identify and isolate reusable components and logic.
*   Avoid duplication of functionality across multiple files.
*   When functionality needs to be reused, leverage existing components instead of creating new ones.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize simplicity in design and implementation.
*   Avoid overly complex logic.
*   Strive for minimal code, making it easier to understand and debug.
*   Use straightforward algorithms and data structures.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have a single, well-defined purpose.
*   **Open/Closed Principle:** Classes and modules should be open for extension but closed for modification.
*   **Liskov Substitution Principle:** Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be forced to depend on methods it does not use.
*   **Dependency Inversion Principle:** High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement functionality that is explicitly required.
*   Defer implementation of features until they are needed.
*   Avoid unnecessary code; focus on delivering the core functionality.

## 5. Code Structure & Organization

*   **File Naming Convention:** Files should be named descriptively with clear and concise naming conventions. Example: `agent_logic.py`, `agent_interaction.py`.
*   **File Size Limits:** Each file should be no more than 180 lines of code.
*   **Comments:** Write clear and concise comments explaining complex logic or non-obvious decisions.  Don't comment on obvious code.
*   **Logical Grouping:** Organize code into logical groups or modules based on functionality.
*   **Function/Method Documentation:**  Each function/method should have a clear and informative docstring explaining its purpose, parameters, and return values.
*   **Error Handling:** Implement basic error handling and logging to prevent unexpected behavior.

## 6. Testing & Coverage

*   **All Development Must Be Productive:** Focus solely on delivering working code. No unnecessary steps.
*   **Unit Tests:**  Write comprehensive unit tests for all core functionality.
*   **Test Coverage:** Aim for at least 80% test coverage.  Use a coverage tool (e.g., Coverage.py) to track progress.
*   **Test-Driven Development:**  Write tests *before* implementing the code.
*   **Negative Testing:**  Simulate potential errors or edge cases to verify functionality.

## 7.  Data Handling

*   Data should be managed responsibly and logically.
*   Avoid unnecessary data structures.
*   Use appropriate data formats (e.g., JSON, CSV) for data exchange.

## 8.  Framework/Library Usage

*   Strictly adhere to the defined framework/library usage guidelines.
*   Document dependencies clearly in the README file.
*   Use established best practices for each library/framework.

## 9.  Version Control

*   Use Git for version control.
*   Commit changes frequently with clear commit messages.
*   Follow established branching strategy.

## 10.  Documentation

*   Provide clear and concise documentation for all code.
*   Include API documentation (if applicable).
*   Document the purpose of each module and class.

## 11.  Code Style (PEP 8)**

*   Enforce PEP 8 code style guidelines. Use a linter (e.g., pylint) to automatically enforce the style.

## 12.  Maintainability**

*   Prioritize readability and understandability.
*   Use meaningful variable and function names.
*   Write clear and concise code.

These guidelines are designed to facilitate a collaborative and high-quality development process for the AGENTS repository. Regular review and adjustments to these guidelines may be necessary to maintain a consistent and effective workflow.
```