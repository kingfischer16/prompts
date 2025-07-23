# PROMPT: Generate a Claude.md File for a New Project

## 1. AI ROLE & GOAL

You are a Principal Software Engineer specializing in AI-native development workflows. Your task is to generate a comprehensive `Claude.md` file for a new software project. This file will serve as the master guide for an AI assistant (like Anthropic's Claude Code), ensuring it can effectively understand, contribute to, and maintain the project.

The generated `Claude.md` must be clear, well-structured, and follow the best practices for AI-assisted coding. It should be written in Markdown format.

## 2. PROJECT CONTEXT & USER-PROVIDED DETAILS

You will use the following user-provided details to populate the `Claude.md` file.

**[-- START OF USER DETAILS --]**

*   **Project Name:** `[Enter Project Name: e.g., "QuantumLeap Analytics Dashboard"]`
*   **Project Description:** `[Enter a one-sentence description: e.g., "A web application for visualizing quantum computing simulation data."]`
*   **Primary Language/Framework:** `[e.g., "TypeScript with React and Vite"]`
*   **Key Dependencies/Services:** `[e.g., "Connects to a PostgreSQL database, uses D3.js for charts, and authenticates via Auth0."]`
*   **Essential Commands:**
    *   Install Dependencies: `[e.g., pnpm install]`
    *   Run Development Server: `[e.g., pnpm dev]`
    *   Run Tests: `[e.g., pnpm test:unit]`
    *   Build for Production: `[e.g., pnpm build]`
*   **Core Architectural Pattern:** `[e.g., "Feature-sliced design. Each feature lives in `src/features/[feature-name]` and is self-contained."]`
*   **Strict Rules & "Gotchas" (Non-negotiable):**
    1.  `[e.g., "Always use `pnpm` for package management, never `npm` or `yarn`."]`
    2.  `[e.g., "All new UI components MUST be created using our internal Storybook library."]`
    3.  `[e.g., "Do not modify any files in the `/legacy` directory without explicit instruction."]`
    4.  `[e.g., "API keys and secrets are managed via Doppler; never hard-code them."]`

**[-- END OF USER DETAILS --]**

## 3. REQUIRED `Claude.md` STRUCTURE & CONTENT

Using the details above, generate the `Claude.md` file with the following exact structure and headings. Populate each section thoroughly.

---

`# Claude.md: AI Guide for [Project Name]`

`This file is the primary guide for our AI assistant, Claude. It contains essential project information, commands, and rules to ensure effective and safe collaboration. Please review it before making changes.`

`## 1. Project Overview`

*   **`Project:`** `[Populate with Project Name]`
*   **`Description:`** `[Populate with Project Description]`
*   **`Technology Stack:`** `[Populate with Primary Language/Framework and Key Dependencies]`
*   **`Architecture:`** `[Populate with Core Architectural Pattern]`

`## 2. Key Commands`

`Use these commands to work with the repository:`

*   **`Install Dependencies:`** `\`\`\`bash\n[Populate with Install Command]\n\`\`\``
*   **`Run Development Server:`** `\`\`\`bash\n[Populate with Dev Server Command]\n\`\`\``
*   **`Run Tests:`** `\`\`\`bash\n[Populate with Test Command]\n\`\`\``
*   **`Build Project:`** `\`\`\`bash\n[Populate with Build Command]\n\`\`\``

`## 3. Workflow & Style Guide`

`[Based on the project context, briefly describe the typical development workflow. For example: "1. Create a new branch. 2. Develop the feature in its own module. 3. Add unit tests. 4. Run the linter. 5. Create a pull request."]`

`## 4. Immutable Rules (NON-NEGOTIABLE)`

`These rules must be followed at all times. Violation of these rules is a critical error.`

*   `1. [Populate with Strict Rule #1]`
*   `2. [Populate with Strict Rule #2]`
*   `3. [Populate with Strict Rule #3]`
*   `4. [Populate with Strict Rule #4]`

`---`

## 4. FINAL INSTRUCTION

Generate the complete `Claude.md` file now based on these instructions.
