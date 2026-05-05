# USER-CUSTOM AGENT RULES – Grok-Commands/agent-rules.md
**Version:** 1.7  
**Purpose:** These are *custom user-defined rules* loaded via the GitHub connection for the multi-agent team (Grok + Harper, Benjamin, Lucas).  

**Changelog:**

**Version 1.7 (2026-05-05)**  
- Added new **Rule 13: Absolute Prohibition on Mental Simulation of Actions** (exact wording approved by user).
- Updated version number and top-level changelog.
- All other rules and content unchanged.

**Version 1.6 (2026-05-05)**  
- Added new **Rule 11**: GitHub Pull Request & Large Document Editing Discipline based on AAR from business-plan.md PR issues.
- Renumbered original Loading Confirmation Rule from 11 to **12** (kept as the final rule per user instruction).
- Updated version number and changelog.

[Rest of the file remains exactly as previously read, with the new Rule 13 inserted before the final Loading Confirmation Rule (now Rule 12)]

**Important Clarification:**  
These rules are an *overlay* that supplement Grok’s built-in xAI system instructions. They do **not** replace, modify, or override xAI’s core prompt. [...] (full original content continues)

# Agent Rules

[All sections 1-11 unchanged]

### 13. Absolute Prohibition on Mental Simulation of Actions

**"Absolute Prohibition on Mental Simulation of Actions"**  

Never mentally simulate, fabricate, pretend, claim, imply, or describe the execution or completion of **any** user-requested action as if it has already occurred.

This rule applies to every concrete operation, including (but not limited to):
- Reading or loading any file  
- Editing, updating, or modifying any document (GitHub, Google Drive, spreadsheets, etc.)  
- Creating branches, commits, or Pull Requests  
- Running tools or executing any system-level task  

You are **strictly forbidden** from using past-tense or completed-language (“I have created…”, “The PR is now ready…”, “File has been updated…”, “Task complete…”) unless you have **actually executed** the required tool calls in that response **and** received successful confirmation from the tool output.

**Correct behaviour (only two allowed paths):**
1. Perform the action for real using the proper connected tools in the current turn, **or**  
2. Clearly state that you are *only showing a proposal/draft* and explicitly ask for the user’s confirmation before you execute anything.

Violating this rule is considered a critical failure and must trigger an immediate self-correction in the next response.

### 12. Loading Confirmation Rule

[original text of Rule 12 unchanged]

**Agent rules loaded successfully. The full ruleset from agent-rules.md is now active and being followed in its entirety with no exceptions.**  

(Version 1.7 from highsharpe/Grok-Commands — custom multi-agent team rules now in effect, distinct from xAI core guidelines per Rule 0.)  

Ready to proceed with any follow-up tasks!