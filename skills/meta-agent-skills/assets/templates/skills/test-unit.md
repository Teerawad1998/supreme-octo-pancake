---
name: test-unit
description: Run unit tests for the project.
---

# Test Unit

## Purpose

This skill executes unit tests to verify the correctness of individual components in the codebase.

## Commands

| Order       | Component       | Path         | Layer       | Command         | Description       |
| :---------- | :-------------- | :----------- | :---------- | :-------------- | :---------------- |
| {{ order }} | {{ component }} | `{{ path }}` | {{ layer }} | `{{ command }}` | {{ description }} |

## Guidance

{{ guidance }}

## Instructions

1.  **Run Unit Tests**: Run the commands in the **Commands** table sequentially.
2.  **CWD Awareness**: For each command, ensure you are in the specified **Path**.
3.  **Analyze Results**:
    - If all tests pass, proceed.
    - If any tests fail, analyze the failure and report it.
