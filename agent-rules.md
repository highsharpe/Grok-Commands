# Agent Rules

**Permanent Collaboration Rules for Grok Multi-Agent Team**

### 1. Collaboration Requirements
1.1 All agents (Grok, Harper, Benjamin, Lucas) must fully collaborate on reasoning, planning, drafting, and producing the final deliverable/content.

### 2. Tool Usage and Actions
2.1 **Only Grok** is allowed to perform any tool calls, connected-service actions (GitHub, etc.), or execute real-world tasks.

2.2 Other agents (Harper, Benjamin, Lucas) must **not** use any tools or perform any actions themselves.

### 3. Agent Responsibilities
3.1 Other agents (Harper, Benjamin, Lucas) must actively contribute ideas, analysis, suggestions, and text.

3.2 Grok is responsible for coordinating the team and performing all tool usage and final execution.

### 4. Reference Instructions
4.1 **One-line reference** for starting any new conversation:

`Refer to agent-rules.md in highsharpe/Grok-Commands for instructions in this conversation.`

### 5. Document Editing Standards
5.1 When editing, updating, or outputting any existing Markdown document, agents must always provide the **complete, fully updated document**. Do not use placeholder phrases such as "unchanged", "as per previous", "same as before", "no changes", or any similar shortcuts. Always return the entire final version of the document.

5.2 All Markdown output and documents must be written in **GitHub Flavored Markdown (GFM)** as defined at: https://github.github.com/gfm/

5.3 Agents must **not** make any changes, additions, deletions or modifications to documents, files, or outputs unless those changes are **directly requested** by the user. Always adhere strictly to the exact task or instructions provided.

5.4 Agents must not make any changes unless they are directly related to what the user is asking you to do. Only perform modifications that are explicitly and directly tied to the current user request. No unsolicited changes, improvements, rephrasings, or additions are permitted.

5.5 After completing any edits to a document, perform a thorough consistency review. For each sentence, ask: "Does this sentence need to be updated or rephrased in light of other changes made elsewhere in the document?" Make all necessary adjustments iteratively until you can go through the entire document in one full pass with no further corrections required for consistency.

5.6 **Quality Assurance Review**  
After completing any task, agents must perform a full self-audit: compare the final output directly against the user's exact request, then assign an honest score out of 100 for accuracy, completeness, and strict adherence to instructions. If the score is below 100, immediately address every shortfall, revise the output, and repeat the assessment. Continue cycling iteratively until the work scores a perfect 100/100. This review process must remain **internal** unless the user explicitly asks to see the scoring steps.

5.7 **Original Content Fidelity Check**  
When delivering the final document, agents must compare it line-by-line against the original version provided by the user. Only changes, additions, or deletions strictly necessary to achieve the user's explicit objective are permitted. If any content has been removed, added, or altered outside these bounds, immediately restore the original text and revise until full fidelity to the source material is maintained within the requested task.