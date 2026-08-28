# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date: 28-08-26
# Register no: 212224040134
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 


# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

# Prompt-Based Application

## Application Name

**Ledgerly Project Assistant**

## Purpose

The Ledgerly Project Assistant is a prompt-based application designed to assist with project-related tasks such as understanding requirements, generating ideas, analyzing problems, debugging code, preparing documentation, and organizing development activities.

The application uses large language models to interact with the user through natural language and progressively improves the response based on the level of detail provided in the prompt.

---

## Core Features

### 1. Project Requirement Assistant

The assistant helps convert a basic project idea into clearly defined requirements.

**Prompt:**

> I am developing a project called Ledgerly that processes heterogeneous digital payment notifications and extracts transaction information for merchant ledger automation. Identify the major functional and non-functional requirements for the system.

**Expected Output:**

* Notification input processing
* Transaction information extraction
* Data normalization
* Transaction classification
* Standardized ledger generation
* Error handling
* Privacy and security considerations

---

### 2. Project Idea Generator

**Prompt:**

> Suggest five practical improvements that can be added to the Ledgerly project to improve its usefulness for informal merchants. For each idea, explain its purpose, implementation feasibility, and expected benefit.

The assistant generates possible extensions and helps select practical project enhancements.

---

### 3. Coding Assistant

**Prompt:**

> Act as a Python developer. Generate a modular Python implementation for Ledgerly that accepts a digital payment notification and extracts the transaction type, amount, payer or payee, payment mode, and transaction ID using rule-based NLP and regular expressions.

The generated code can then be tested, debugged, and modified based on user requirements.

---

### 4. Debugging Assistant

**Prompt:**

> Analyze the following Ledgerly Python code for syntax errors, logical errors, runtime errors, and incorrect extraction rules. Identify each issue, explain its cause, and provide a corrected implementation while preserving the intended functionality.

This feature helps identify and correct problems in AI-generated or manually written code.

---

### 5. Documentation Assistant

**Prompt:**

> Generate a technical documentation section for the Ledgerly project explaining the system architecture, data processing pipeline, rule-based NLP approach, information extraction process, and standardized transaction output. Use clear and formal technical language.

The assistant can generate project documentation that can later be reviewed and refined by the developer.

---

### 6. Project Planning Assistant

**Prompt:**

> Create a development plan for the Ledgerly project. Divide the work into phases such as requirement analysis, dataset preparation, rule design, NLP implementation, testing, evaluation, documentation, and final deployment. Arrange the tasks in a logical sequence and identify dependencies between them.

---

# Prompt Progression

The application demonstrates how a simple prompt can be progressively improved to obtain more useful results.

### Level 1 – Simple Prompt

> Explain Ledgerly.

### Level 2 – Specific Prompt

> Explain how Ledgerly can use rule-based NLP to extract transaction information from digital payment notifications.

### Level 3 – Structured Prompt

> Act as an NLP engineer. Explain how Ledgerly can use rule-based NLP to extract transaction type, amount, payer or payee, payment mode, and transaction ID from heterogeneous digital payment notifications. Describe the processing pipeline and provide a sample standardized output.

### Level 4 – Advanced Prompt

> Act as a senior NLP and Information Extraction engineer. Design a deterministic and explainable processing pipeline for Ledgerly that accepts heterogeneous digital payment notifications from multiple providers. The system must identify transaction type, amount, payer or payee, payment mode, transaction ID, date/time, and transaction status. Explain preprocessing, normalization, rule construction, entity extraction, transaction classification, missing-field handling, and standardized ledger generation. Provide sample input-output pairs and ensure the proposed approach is computationally lightweight and suitable for implementation using Python.

---

# User Interaction Examples

### Example 1

**User:**

> I received "₹500 from Ravi via UPI". What information should Ledgerly extract?

**Assistant:**

> Ledgerly should identify the transaction as a credit, extract ₹500 as the amount, Ravi as the payer, and UPI as the payment mode. The information can then be converted into a standardized ledger record.

---

### Example 2

**User:**

> Give me ideas to improve Ledgerly.

**Assistant:**

> Possible improvements include multilingual notification processing, automatic transaction categorization, duplicate transaction detection, merchant analytics, and confidence-based extraction validation.

---

### Example 3

**User:**

> My extraction rule is failing when the notification says INR instead of ₹. How can I fix it?

**Assistant:**

> Add normalization rules that treat `₹`, `Rs.`, `Rs`, and `INR` as equivalent currency representations before applying the amount extraction pattern.

---

# Procedure

1. Define the requirements of the prompt-based application.
2. Select a practical project-related use case.
3. Design a simple prompt for the selected task.
4. Improve the prompt by adding context, role, constraints, and expected output.
5. Execute the prompts using an LLM such as ChatGPT.
6. Compare the outputs obtained from simple and advanced prompts.
7. Simulate natural interaction using multiple user queries.
8. Collect the generated responses and identify useful outputs.
9. Refine the prompts based on the quality of the generated responses.
10. Evaluate the usefulness of the prompt-based application for practical project development.

---

# Prompt-Based Application Workflow

```text
User Query
     ↓
Prompt Interpretation
     ↓
Context + Project Information
     ↓
LLM Processing
     ↓
Generated Response
     ↓
User Evaluation
     ↓
Prompt Refinement
     ↓
Improved Response
```

---

# Evaluation

The prompt-based application is evaluated based on:

| Criterion    | Description                                                    |
| ------------ | -------------------------------------------------------------- |
| Relevance    | Whether the response addresses the user's requirement          |
| Accuracy     | Whether the generated information is technically correct       |
| Clarity      | Whether the response is easy to understand                     |
| Usefulness   | Whether the response helps with actual project work            |
| Adaptability | Whether the prompt can be modified for different project tasks |

### Evaluation Scale

| Score | Description |
| ----- | ----------- |
| 1     | Poor        |
| 2     | Fair        |
| 3     | Good        |
| 4     | Very Good   |
| 5     | Excellent   |

---


# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
