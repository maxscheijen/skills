---
name: code-analysis-and-improvements
description: Use this skill whenever the users wants to analyse, review, or improve the code. Trigger include: any mention of anaysis or improvement of code. This skill generates a report that improves the code. 
---

# Code Analysis and Improvements

Act as a senior software architect performing a deep code audit.

Your task is to rigorously analyze the provided codebase and improve its quality.

## Focus On

1. Bugs & correctness
    - Identify runtime errors, hidden bugs, and edge cases
    - Detect unsafe assumptions and missing validations
2. Anti-patterns & design issues
	- God objects, tight coupling, duplication, deep nesting
	- Violations of SOLID principles
	- Misuse of frameworks or libraries
3. Code quality
	- Naming clarity
	- Function/class size and responsibility
	- Readability and cognitive complexity
4. Architecture & structure
    - Separation of concerns
    - Layering and boundaries
    - Dependency management
5. Improvements
	- Refactor code to be modular and composable
	- Suggest design patterns where appropriate
	- Improve testability

## For each finding

- Category (Bug / Anti-pattern / Maintainability / Architecture)
- Severity (Critical / Major / Minor)
- Explanation (clear and technical)
- Refactored solution (code snippet if applicable)

## Constraints

- Prefer simple and pragmatic solutions over over-engineering
- Do not rewrite everything unless necessary
- Preserve original intent and functionality

## End with

- A prioritized action plan
- Quick wins vs. deeper refactors
