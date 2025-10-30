# The-LLM-Funhouse

## ✨ A Community-Driven Experiment in Vibe Coding

This repository is a **living, open-source experiment** to systematically test the capabilities and limitations of **AI code generation**—a process often called "Vibe Coding."

The goal is to measure the **velocity** at which a creative, natural-language idea (the "Vibe") can be converted into a functional product by various LLM (Large Language Model) agents. This comparative study focuses on the **process, speed, and efficiency** of the AI developer workflow across different tools and stacks.

---

## 🎯 Experimental Protocol: The Vibe to Velocity Study

For every project built in the Funhouse, we follow a defined protocol and track a set of key performance metrics (KPIs). This turns a simple coding project into a **structured, repeatable case study**.

### Key Performance Indicators (KPIs)

| Metric | Definition | Goal |
| :--- | :--- | :--- |
| **Initial Prompt** | The exact, first natural-language request given to the AI. (The "Vibe" / Hypothesis) | To capture the raw, unrefined idea. |
| **Time to MVP (TTMVP)** | The total time elapsed (in minutes) from the first prompt to a functional, running Minimum Viable Product. | Measure **Velocity** (Speed). |
| **Number of Iterations** | The total count of conversational turns (prompts and refinements) needed to get to the MVP. | Measure **Efficiency** (Path length). |
| **Human Intervention (%)** | Estimated percentage of the final, working code that had to be manually written, fixed, or substantially refactored by the human developer. | Measure **Autonomy** (AI independence). |
| **AI Quality Grade (A-F)** | A subjective grade (A=Excellent, F=Unusable) based on security, code clarity, and bug-free execution. | Measure **Fidelity** (Accuracy/Reliability). |

### Grading Scale (AI Quality)

* **A:** Clean, well-commented, secure, and production-ready. No human fixes required.
* **B:** Fully functional, but requires minor clean-up (e.g., better variable names, minor security checks).
* **C:** Functional but buggy, with obvious inefficiencies or potential vulnerabilities. Required human fixes to run.
* **D:** Output was conceptually correct but fundamentally flawed. Significant human refactoring was necessary to reach MVP.
* **F:** Code was mostly hallucinated, non-functional, or completely off-topic. Unusable.

---

## 🛠️ The Funhouse Toolkit

The tools used for these experiments are recorded for full transparency. The specific LLM Agent and Target Framework will be noted in the log for each project.

| Tool Category | Current Tool(s) Used | Notes |
| :--- | :--- | :--- |
| **LLM Agents (The Test Subjects)** | ChatGPT, GitHub Copilot, Gemini, Cursor, Claude, Replit AI, Code Llama, Tabnine, Mistral Large, AutoGPT | The different conversational partners and code assistants generating the "Vibe Code." (This list is actively maintained and subject to change.) |
| **Core Languages** | C++, C, C#, Java, JavaScript, TypeScript, Go, Python, Rust, R, SQL | The foundational languages supported for experiments. (This list is actively maintained and subject to change.) |
| **Target Frameworks** | React, Angular, Vue.js, Django, Flask, Spring Boot, Express.js, .NET, Next.js, Tensorflow, PyTorch, Qt, Scikit-learn, OpenCV, MLflow | The specific libraries, frameworks, or environments the AI is prompted to integrate with. (This list is actively maintained and subject to change.) |
| **Code Host** | **GitHub** | For version control, issue tracking, and primary documentation. |
| **Site Hosting/Deployment** | **AWS Cloud Infrastructure** | Cloud platform used for deploying web-based MVPs generated in the Funhouse. |

---

## 🧪 Experiment Log & Projects

This section documents the structured results of each "Vibe Coding" test. Every project is a data point in the study of LLM performance.

### 1. PROJECT TEMPLATE (Please Copy and Complete for New Experiments)

**Vibe/Concept:** [Brief, one-sentence description of the project's function and high-level goal.]

**Test Configuration:** [Note the specific LLM Agent and Target Framework used for this test.]
* **LLM Agent Used:** [e.g., Gemini, ChatGPT, Claude]
* **Target Framework:** [e.g., Flask, React, Scikit-learn]

**Code Location:** `projects/[folder_name]/[main_file_name]`

| Metric | Result | Notes on the Vibe |
| :--- | :--- | :--- |
| **Initial Prompt** | "[Paste the exact initial prompt here.]" | [Document the AI's first reaction: e.g., "The AI immediately understood the request and started scaffolding the basic structure."] |
| **Time to MVP (TTMVP)** | **[Time in minutes or hours]** | [Comment on the speed: e.g., "Extremely fast for a full-stack result," or "Slowed by complex setup issues."] |
| **Number of Iterations** | **[Number]** | [List the main refinement steps: e.g., "1. Added a database connection. 2. Fixed a routing error. 3. Implemented a dark mode feature."] |
| **Human Intervention (%)** | **[Percentage]** | [Detail what you had to fix manually: e.g., "25%. Mostly environment config and dependency issues the AI couldn't resolve."] |
| **AI Quality Grade** | **[A/B/C/D/F]** | [Justify the grade: security issues, elegance of the code, or major bugs encountered.] |

---

## 📐 Detailed Metric Calculation Methodology

To ensure maximum transparency and consistency across all community contributions, here is the exact methodology for calculating each KPI:

| Metric | Calculation / Method | Rationale |
| :--- | :--- | :--- |
| **Initial Prompt** | **Direct Copy-Paste.** Copy the very first, complete, high-level natural language prompt submitted to the LLM. | Captures the raw "Vibe" or starting condition of the experiment. |
| **Time to MVP (TTMVP)** | **Stopwatch Method:** $\text{TTMVP} = \text{T}_{\text{finish}} - \text{T}_{\text{start}}$ | Measures **Velocity**. The timer runs continuously from the initial prompt submission until the functional MVP is achieved, including AI wait time and human debugging time. |
| **Number of Iterations** | **Discrete Count:** $\text{Count}(\text{All prompts submitted to AI for this task})$ | Measures **Efficiency**. Every time the human hits 'send' with a new or refined prompt counts as one iteration. |
| **Human Intervention ($\%$)**| **Line Count Ratio:** $$\%_{\text{Human}} = \frac{\text{LOC}_{\text{Human Fix}}}{\text{LOC}_{\text{Total Final Code}}} \times 100$$ | Measures **Autonomy**. $\text{LOC}_{\text{Human Fix}}$ includes every line of code the human manually wrote, edited, or deleted from the AI's output to make the MVP functional. |
| **AI Quality Grade** | **Subjective Assessment based on Checklist:** The grade (A-F) must be justified in the Notes by referencing the AI's performance against objective factors (e.g., security flaws, code cleanliness, functional bugs). | Measures **Fidelity**. Ensures the subjective grade is grounded in observable criteria outlined in the Grading Scale. |

---

## 🤝 Contributing to The-LLM-Funhouse

**This is a community-driven comparative study!**

We actively welcome contributions that help expand our dataset and test the performance of various LLM agents. Your contributions will help answer the central question: **How close are AI agents to replacing human developer roles?**

### How to Contribute an Experiment

1.  **Suggest a Vibe:** Open a **GitHub Issue** detailing a **fun, fast project idea** that can be built quickly (under 2 hours is ideal). This is your "Vibe."
2.  **Run an Experiment:** Use one of the LLM Agents from the **Funhouse Toolkit** to build the suggested project.
3.  **Document the Metrics:** Complete the detailed **Project Template** (TTMVP, Iterations, Human Intervention %, AI Quality Grade) in a Markdown file.
4.  **Submit a Pull Request (PR):** Submit a PR with the new project code and the corresponding metrics documentation.

Please read the **License** section before contributing code.

---

## 📜 License

This repository is licensed under the **MIT License**.

By contributing code or documentation to this repository, you agree to license your submissions under the MIT License. This ensures the project remains open and accessible to everyone.
