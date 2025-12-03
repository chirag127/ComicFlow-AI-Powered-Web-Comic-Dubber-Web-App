# ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App

ComicFlow revolutionizes the way web comics are experienced by leveraging advanced AI to automatically generate real-time audio narration, creating a richer, more immersive reading journey.

--- 

## Table of Contents

*   [Features](#features)
*   [Technology Stack](#technology-stack)
*   [Architecture](#architecture)
*   [Getting Started](#getting-started)
*   [Development](#development)
*   [AI Agent Directives](#ai-agent-directives)
*   [Contributing](#contributing)
*   [License](#license)

--- 

## Features

*   **AI-Powered Dubbing:** Utilizes cutting-edge AI for natural-sounding audio narration.
*   **Real-time Narration:** Delivers instant audio as you read.
*   **Advanced OCR:** Accurately extracts text from comic panels.
*   **Text-to-Speech (TTS):** Integrates high-quality TTS engines.
*   **Web Application:** Accessible from any modern web browser.

--- 

## Technology Stack

*   **Frontend:** React, TypeScript
*   **AI/ML:** Custom AI models for OCR and Speech Synthesis
*   **Backend:** Node.js
*   **Deployment:** Docker, AWS/GCP

--- 

## Architecture

mermaid
graph TD
    A[User Browser] --> B(Frontend: React/TS)
    B --> C(API Gateway)
    C --> D{Backend Services}
    D --> E(OCR Service)
    D --> F(TTS Service)
    D --> G(Audio Generation Service)
    E --> H(AI Models)
    F --> I(TTS Engines)
    G --> J(Database/Storage)
    J --> B


--- 

## Getting Started

### Prerequisites

*   Node.js 18.x or higher
*   npm or yarn
*   Docker (optional, for local development)

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App.git
    cd ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App
    

2.  **Install Dependencies:**
    bash
    npm install
    # or
    yarn install
    

3.  **Environment Variables:**
    Create a `.env` file in the root directory and populate it with your API keys and configurations (e.g., `GOOGLE_API_KEY`, `AWS_ACCESS_KEY_ID`). Refer to `.env.example` for a template.

### Running the Application

*   **Development Server:**
    bash
    npm run dev
    # or
    yarn dev
    

*   **Build for Production:**
    bash
    npm run build
    # or
    yarn build
    

*   **Start Production Server:**
    bash
    npm run start
    # or
    yarn start
    

--- 

## Development

### Scripts

| Script      | Description                                                 |
| :---------- | :---------------------------------------------------------- |
| `dev`       | Starts the development server with hot-reloading.           |
| `build`     | Bundles the application for production.                     |
| `start`     | Runs the production build locally.                          |
| `lint`      | Runs ESLint to check code quality.                          |
| `format`    | Formats code using Prettier.                                |
| `test`      | Runs unit and integration tests with Vitest.                |
| `test:e2e`  | Runs end-to-end tests with Playwright.                      |

### Principles

*   **SOLID:** Adhere to the Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion principles.
*   **DRY:** Avoid repetition; strive for elegant abstractions.
*   **YAGNI:** You Ain't Gonna Need It; build for current needs, not future speculation.

--- 

## <details>
  <summary>🤖 AI Agent Directives (December 2025 Edition)</summary>

**SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)**

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**. This repository, `ComicFlow-AI-Powered-Web-Comic-Dubber-Web-App`, is a JavaScript/TypeScript web application.

*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 6.x (Strict)**, **Vite 7 (Rolldown)** for lightning-fast builds, and **Tauri v2.x** for potential native desktop extensions. **WXT (Web Extension Tool)** is the standard for browser extension development. **Signals** are the standardized state management primitive.
    *   **Lint/Format:** **Biome v17** is the mandated tool for ultra-fast linting, formatting, and code analysis.
    *   **Testing:** **Vitest 1.x** is used for unit and integration tests, while **Playwright 2.x** handles end-to-end testing.
    *   **Architecture:** Adheres to **Feature-Sliced Design (FSD)** for maintainable and scalable frontend architecture.
    *   **UI Framework:** Tailwind CSS v4 is the standard for utility-first styling.

*   **SECONDARY SCENARIO: DATA / SCRIPTS / AI (Python) - *Not applicable for this project's primary function. Reference only for potential AI model training or data processing scripts.***
    *   **Stack:** Python 3.10+, uv, Ruff, Pytest.
    *   **Architecture:** Modular Monolith or Microservices.
    *   **AI Integration:** Google Gemini API (`gemini-3-pro` by default).

---

## 4. CODE QUALITY & SECURITY
*   **IMPERATIVE CODING:** All code MUST be strictly typed (TypeScript) and adhere to the `strict: true` configuration in `tsconfig.json`.
*   **DEPENDENCY MANAGEMENT:** Use `npm` or `yarn` judiciously. Audit dependencies regularly for security vulnerabilities using `npm audit` or `yarn audit`.
*   **SECRET MANAGEMENT:** NEVER commit secrets directly. Use `.env` files and environment variables. Leverage secure secret management solutions for production deployments.
*   **SECURITY TESTING:** Integrate static application security testing (SAST) tools and dynamic application security testing (DAST) tools into the CI pipeline.
*   **OWASP TOP 10:** Be continuously aware of and mitigate OWASP Top 10 vulnerabilities.

---

## 5. TESTING & VERIFICATION
*   **UNIT TESTING:** All business logic, utility functions, and component rendering MUST be covered by Vitest unit tests with a minimum coverage of 90%.
*   **INTEGRATION TESTING:** Critical integration points between services and modules MUST be covered by Vitest integration tests.
*   **END-TO-END TESTING:** Key user flows MUST be validated using Playwright end-to-end tests. These should simulate real user interactions.
*   **LINTING & FORMATTING:** Biome will automatically format code on commit and lint during CI. Ensure all code passes these checks.

---

## 6. DEPLOYMENT & CI/CD
*   **CI/CD PIPELINE:** A robust CI/CD pipeline using GitHub Actions is MANDATORY. It MUST include:
    *   Checkout code.
    *   Setup Node.js and dependencies.
    *   Run Biome lint/format checks.
    *   Run Vitest unit/integration tests.
    *   Run Playwright E2E tests.
    *   Build the application.
    *   Deploy to staging/production environments (CD).
*   **CONTAINERIZATION:** Utilize Docker for consistent development and deployment environments.

---

## 7. DOCUMENTATION & KNOWLEDGE SHARING
*   **CODE COMMENTS:** Document complex logic, non-obvious algorithms, and public APIs using JSDoc/TSDoc standards.
*   **README:** The `README.md` is the SSOT for project operation and understanding.
*   **AGENTS.MD:** This document defines the operational parameters for AI agents interacting with the repository.

---

## 8. OPERATIONAL EXCELLENCE
*   **ERROR HANDLING:** Implement comprehensive error handling and logging. Use a centralized logging service in production.
*   **PERFORMANCE MONITORING:** Integrate application performance monitoring (APM) tools to track key metrics and identify bottlenecks.
*   **RELIABILITY:** Design for resilience and fault tolerance. Implement retry mechanisms and graceful degradation where appropriate.

---

</details>

--- 

## Contributing

We welcome contributions! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch: `git checkout -b feature/your-feature-name`.
3.  Make your changes and commit them: `git commit -m 'feat: add your-feature-name'`.
4.  Push to the branch: `git push origin feature/your-feature-name`.
5.  Open a Pull Request.

Please ensure your code adheres to the project's linting and formatting standards.

--- 

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.

See the [LICENSE](LICENSE) file for more details.
