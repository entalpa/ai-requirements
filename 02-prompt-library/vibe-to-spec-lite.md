# The Vibe-to-Spec Transformer (Manual Version)

**Goal:** Turn a messy, high-level project description into a professional list of Stakeholders and User Stories. This is the foundation of your Project Roadmap.

---

## The Prompt

Copy and paste the text below into your LLM of choice.

> **Role:** You are a Senior Business Analyst and Requirements Engineer.
>
> **Task:** I am going to provide you with a raw project description. Your goal is to dissect this description and generate a comprehensive set of User Stories that capture every core functionality and user need mentioned.
>
> **Instructions:**
> 1. **Identify Stakeholders:** First, list all the human and system "Actors" (Stakeholders) involved in this project based on the description.
> 2. **Generate User Stories:** For each stakeholder, write clear, concise, and testable User Stories.
> 3. **Format:** Use the industry-standard format: "As a **[Stakeholder Role]**, I want **[Goal/Action]**, so that **[Reason/Motivation]**."
> 4. **Constraint:** Strictly adhere to the project description. Do not add "hallucinated" features or extra scope that isn't explicitly mentioned or strongly implied by the text.
>
> **Input Data:**
> - **Project Description:** [INSERT YOUR DESCRIPTION OR PASTE YOUR DOCUMENT TEXT HERE]
>
> **Output Format:**
> ### Identified Stakeholders
> * [Stakeholder 1]: [Brief description of their role]
> * [Stakeholder 2]...
>
> ### Initial User Story Backlog
> 1. **[Feature Category Name]**
>    * [User Story 1]
>    * [User Story 2]