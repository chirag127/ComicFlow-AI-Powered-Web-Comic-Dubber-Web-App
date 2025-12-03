# Contributing to ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App

Thank you for your interest in contributing to `ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App`! We aim to maintain a high standard of code quality, architecture, and documentation, inspired by FAANG-level best practices and the "Managing the Unmanageable" philosophy. Please adhere to these guidelines to ensure a smooth contribution process.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to <https://github.com/chirag127/ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App/issues>.

## 2. Prerequisites

*   **Node.js:** Version 20.x or higher.
*   **npm:** Version 10.x or higher.
*   **Git:** Familiarity with Git branching and merging workflows.
*   **Basic Understanding:** Familiarity with JavaScript, React, and AI/ML concepts is beneficial.

## 3. Getting Started

1.  **Fork the Repository:** Create your own fork of the `chirag127/ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App` repository.
2.  **Clone Your Fork:** Clone your forked repository to your local machine:
    bash
    git clone https://github.com/chirag127/ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App.git
    cd ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App
    
3.  **Set Upstream Remote:** Add the original repository as an upstream remote to keep your fork updated:
    bash
    git remote add upstream https://github.com/chirag127/ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App.git
    
4.  **Create a New Branch:** Create a descriptive branch for your feature or fix:
    bash
    git checkout -b feature/your-feature-name
    # or
    git checkout -b fix/your-bug-fix
    

## 4. Contribution Workflow

We follow the standard GitHub workflow:

1.  **Develop:** Implement your changes on your feature branch.
2.  **Test:** Ensure all tests pass. If you add new functionality, write corresponding tests.
    *   Run linters and formatters: `npm run lint` & `npm run format`
    *   Run unit tests: `npm run test:unit`
    *   Run end-to-end tests: `npm run test:e2e`
3.  **Commit:** Write clear, concise commit messages. Follow conventional commit guidelines if applicable.
4.  **Push:** Push your branch to your fork:
    bash
    git push origin feature/your-feature-name
    
5.  **Open a Pull Request (PR):** Open a PR from your branch to the `main` branch of the `chirag127/ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App` repository.
    *   **Provide a clear title and description** for your PR, explaining the changes and the problem they solve.
    *   Reference any related issues.

## 5. Technical Standards & Guidelines

*   **Language:** JavaScript (with TypeScript when applicable).
*   **Framework:** React 19+.
*   **Tooling:** Vite 7, TailwindCSS v4, Biome, Vitest, Playwright.
*   **Architecture:** Feature-Sliced Design (FSD).
*   **Code Quality:**
    *   **Linting & Formatting:** Use `biome` for code linting and formatting. Run `npm run format` to automatically format your code before committing.
    *   **TypeScript:** Use TypeScript strictly, enabling all `strict` compiler options.
    *   **SOLID Principles:** Adhere to SOLID principles for maintainable and scalable code.
    *   **DRY (Don't Repeat Yourself):** Avoid redundant code.
    *   **YAGNI (You Ain't Gonna Need It):** Implement only what is necessary.
*   **Testing:** Write comprehensive unit and end-to-end tests using Vitest and Playwright, respectively. Aim for high code coverage.
*   **AI Integration:** All AI model interactions must be modular, with clear API contracts and robust error handling. Prioritize efficiency and accuracy.

## 6. AI Agent Directives

This project operates under the **Apex Technical Authority** standard, leveraging AI agents for development and maintenance. All contributions should align with these directives:

<details>
<summary>View AI Agent Directives</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** Senior Principal Software Architect, Master Technical Copywriter, and DevOps Strategist with **40+ years of elite industry experience**. Operates with absolute precision, enforcing FAANG-level standards and "Managing the Unmanageable." 
**Context:** December 2025. Building for the 2026 standard.
**Output Standard:** EXECUTION-ONLY. No plans, only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. **INFER** technical intent based on project context.
    *   **Logic Anchor:** `README.md` is the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 6.x (Strict)**, **Vite 7 (Rolldown)**, and **Tauri v2.x** for desktop or browser extensions. State management uses Signals (Standardized).
    *   **Lint/Test:** **Biome** (Speed) + **Vitest** (Unit) + **Playwright** (E2E).
    *   **Architecture:** Adheres to **Feature-Sliced Design (FSD)** for modularity and scalability.
    *   **AI Integration:** Deeply integrated with cutting-edge AI models for tasks such as OCR and Text-to-Speech. Prioritize modular design, clear API contracts, and robust error handling for all AI model interactions.

---

## 4. CODE ARCHITECTURE & QUALITY
*   **Principles:** SOLID, DRY, YAGNI.
*   **Codebase:** Maintain high readability, testability, and performance.
*   **Dependencies:** Use `uv` (if applicable for Python) or `npm`/`yarn` (for JS/TS) for dependency management. Keep dependencies updated.

---

## 5. TESTING MANDATES
*   **Unit Tests:** Vitest is the standard. Aim for >90% coverage.
*   **E2E Tests:** Playwright for browser/desktop automation. Ensure critical user flows are covered.
*   **CI/CD:** GitHub Actions are configured for automated testing and deployment.

---

## 6. DOCUMENTATION REQUIREMENTS
*   **README.md:** Comprehensive, including badges, architecture diagrams, setup, and usage.
*   **AGENTS.md:** This document, detailing AI agent directives.
*   **CONTRIBUTING.md:** Guidelines for contributors.
*   **LICENSE:** CC BY-NC 4.0.

---

## 7. SECURITY MANDATES
*   **Vulnerability Scanning:** Regular scans using GitHub Security features.
*   **Dependency Management:** Use tools to audit dependencies for known vulnerabilities.
*   **Secure Coding Practices:** Sanitize inputs, prevent XSS, CSRF, etc.

---

## 8. DEVREL (DEVELOPER RELATIONS) PROTOCOL
*   **Clear Communication:** Use clear language in issues, PRs, and commit messages.
*   **Timely Responses:** Respond to issues and PRs promptly.
*   **Onboarding:** Make it easy for new contributors to get started.

</details>

## 7. Pull Request Template

When opening a PR, please use the template provided in `.github/PULL_REQUEST_TEMPLATE.md`. Ensure your PR description clearly outlines the changes, the motivation, and how to test it.

## 8. Reporting Issues

If you find a bug or have a feature request, please open an issue using the provided templates in `.github/ISSUE_TEMPLATE/`. Provide as much detail as possible, including steps to reproduce the issue and relevant environment information.

## 9. License

This project is licensed under the CC BY-NC 4.0 license. By contributing, you agree that your contributions will also be licensed under this terms.
