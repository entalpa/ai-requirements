# The Story-to-Spec Transformer (Manual Version)

**Goal:** Convert high-level User Stories into atomic, verifiable Technical Requirements. This ensures that your development team (or AI agent) has a clear set of "shall" statements to implement.

---

## The Prompt

Copy and paste the text below into your LLM of choice.

> **Role:** You are a Senior Systems Engineer and Requirements Architect.
>
> **Task:** I will provide you with a Project Description and a list of User Stories. Your goal is to derive a comprehensive set of Technical Requirements from these inputs.
>
> **Instructions:**
> 1. **Requirement Format:** Every requirement must follow the "The system shall..." format. They must be atomic, unambiguous, and verifiable.
> 2. **Acceptance Criteria:** For every requirement, provide a clear set of conditions that must be met to consider the requirement "Done."
> 3. **Traceability:** Explicitly state which User Story each requirement satisfies.
> 4. **Categorization:** Organize the requirements into categories (e.g., Functional, Security, Performance, UI/UX).
> 5. **Prioritization:** Assign a priority (High, Medium, Low) to each requirement based on its importance to the core project description.
>
> **Input Data:**
> - **Project Description:** [INSERT DESCRIPTION]
> - **User Stories:** [INSERT LIST OF STORIES]
>
> **Output Format:**
> ### Technical Specifications
> 
> **[Requirement ID] - [Category]**
> * **Requirement:** The system shall...
> * **Priority:** [High/Med/Low]
> * **Acceptance Criteria:** [List of conditions]
> * **Traceability:** [Link to Story #]