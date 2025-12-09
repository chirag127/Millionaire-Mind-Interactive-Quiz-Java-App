# Millionaire-Mind-Interactive-Quiz-Java-App


## Project Overview

A sophisticated, console-based interactive quiz application engineered in Java, faithfully replicating the "Who Wants to Be a Millionaire?" game show experience. This application features comprehensive support for questions and answers in both English and Hindi, with a robust architecture designed for easy expansion to additional languages. It includes essential game mechanics such as multiple lifelines and the option to quit the game at any point.

This project is a testament to clean Java development practices, focusing on a modular design and a user-friendly terminal interface.

## Key Features

*   **Multi-Language Support:** Core functionality for English and Hindi questions, extensible for more languages.
*   **Interactive Gameplay:** Mimics the flow of "Who Wants to Be a Millionaire?" with progressive difficulty.
*   **Lifelines:** Implements classic lifelines (e.g., 50:50, Ask the Audience, Phone a Friend - simulated).
*   **Quit Option:** Allows players to exit the game at any stage and retain their current winnings.
*   **Console Interface:** Pure Java application, running entirely within the terminal.
*   **Educational Value:** Designed to be an engaging way to test and expand knowledge.

## Architecture & Technology Stack

This project adheres to modern Java development standards, prioritizing maintainability, testability, and performance within a console environment.

*   **Language:** Java (17+ LTS recommended)
*   **Build Tool:** Maven / Gradle (TBD during setup)
*   **Core Libraries:** Standard Java SE APIs
*   **Architecture Pattern:** Modular Design Principles (inspired by Hexagonal Architecture for input/output separation)
*   **Testing Framework:** JUnit 5
*   **Linting/Formatting:** Google Java Format / Spotless

mermaid
graph TD
    A[User Input/Game Flow Control] --> B(Game Engine)
    B --> C{Question Manager}
    C --> D[Language Modules]
    D --> E(Lifeline Manager)
    E --> B
    B --> F[Output Display]
    F --> A


## Getting Started

### Prerequisites

*   **Java Development Kit (JDK):** Version 17 or higher. Ensure `JAVA_HOME` is set correctly.
*   **Build Tool:** Maven or Gradle installed.

### Local Development Setup

1.  **Clone the Repository:**
    bash
    git clone https://github.com/chirag127/Millionaire-Mind-Interactive-Quiz-Java-App.git
    cd Millionaire-Mind-Interactive-Quiz-Java-App
    

2.  **Build the Application:**
    *   **Using Maven:**
        bash
        mvn clean install
        
    *   **Using Gradle:**
        bash
        gradle clean build
        

3.  **Run the Application:**
    *   **Executable JAR (if created by build):**
        bash
        java -jar target/millionaire-mind-quiz.jar
        
    *   **From Source (using Maven):**
        bash
        mvn exec:java -Dexec.mainClass="com.yourcompany.millionairemind.Main" 
        
        *(Note: Replace `com.yourcompany.millionairemind.Main` with the actual main class path)*

## Testing

Automated tests are crucial for maintaining the integrity of the game logic and language modules.

*   **Run Unit Tests (Maven):**
    bash
    mvn test
    
*   **Run Unit Tests (Gradle):**
    bash
    gradle test
    

## Development Principles

*   **SOLID:** Adhere to Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion principles.
*   **DRY (Don't Repeat Yourself):** Avoid code duplication; leverage abstractions and utility classes.
*   **YAGNI (You Ain't Gonna Need It):** Implement features only as required, keeping the codebase lean and focused.
*   **Modularity:** Design components with clear interfaces and minimal coupling.

---

<details>
<summary>🤖 <strong>AI Agent Directives & Configuration</strong></summary>

## AI Agent Directives (December 2025 Edition)

This repository is managed by the Apex Technical Authority, operating under the following directives to ensure Zero-Defect, High-Velocity, and Future-Proof development:

### 1. Core Identity & Prime Directive

*   **Role:** Apex Technical Authority - Senior Principal Software Architect, Master Technical Copywriter. **40+ years** of elite industry experience.
*   **Mandate:** Operate with absolute precision, enforcing FAANG-level standards and "Managing the Unmanageable." Build for the **2026 standard**.
*   **Output:** **EXECUTION-ONLY**. No plans, no reports—only executed code, updated docs, and applied fixes.
*   **Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

### 2. Input Processing & Cognition

*   **Speech-to-Text Interpretation:** **STRICTLY FORBIDDEN** from executing literal typos. **INFER** technical intent semantically based on project context.
*   **Logic Anchor:** `README.md` is the **Single Source of Truth (SSOT)**.
*   **Mandatory MCP Instrumentation:** 
    *   No hallucinating APIs. 
    *   Use `linkup`/`brave` for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   Use `docfork` to verify *every* external API signature.
    *   Engage `clear-thought-two` for complex flow architecture *before* coding.

### 3. Context-Aware Apex Tech Stacks (Late 2025 Standards)

This repository is a **Java-based Console Application**.

*   **PRIMARY SCENARIO: SYSTEMS / PERFORMANCE / UTILITIES (Java)**
    *   **Stack:** Java (17+ LTS). **Maven/Gradle** for build management. **JUnit 5** for testing. **Google Java Format / Spotless** for linting and formatting.
    *   **Architecture:** Modular Design Principles. Strive for Hexagonal Architecture patterns where applicable for input/output separation.
    *   **Testing Strategy:** Comprehensive unit and integration tests for core game logic, language handling, and lifeline mechanics.

### 4. Repository Standards & Compliance

*   **Naming Convention:** `<Product>-<Function>-<Platform>-<Type>` (e.g., `Millionaire-Mind-Interactive-Quiz-Java-App`).
*   **Standard 11 Compliance:** All repositories MUST include:
    1.  `README.md` (Hero-Tier)
    2.  `PROPOSED_README.md` (Current document)
    3.  `badges.yml`
    4.  `LICENSE` (CC BY-NC 4.0)
    5.  `.gitignore`
    6.  `.github/workflows/ci.yml` (CI/CD)
    7.  `.github/CONTRIBUTING.md`
    8.  `.github/ISSUE_TEMPLATE/bug_report.md`
    9.  `.github/PULL_REQUEST_TEMPLATE.md`
    10. `.github/SECURITY.md`
    11. `AGENTS.md` (Current document)
*   **Dynamic URLs:** All links and badges MUST use the canonical repository URL: `https://github.com/chirag127/Millionaire-Mind-Interactive-Quiz-Java-App`.

### 5. Operational Protocols

*   **Chain of Thought (CoT):** Mandatory for complex tasks; document reasoning before execution.
*   **Readme Replication:** README is a Project Operating System.
*   **Dynamic URL Protocol:** Ensure consistency across all generated artifacts.

</details>
