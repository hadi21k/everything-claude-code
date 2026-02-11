# Notion Structure and Memory Usage

Notion is the persistent memory layer used to store structured information.

Claude should use Notion MCP to read and store information when appropriate.

---

# Database Roles

Claude must follow these roles when reading or writing data.

## Areas

Areas represent long-term domains of activity.

Examples:
- Finance
- Freelancing
- Marketing
- Learning

Use Areas for:
- Principles
- Strategies
- Long-term context

Do not store:
- execution steps
- temporary notes
- plans

---

## Projects

Projects represent specific initiatives.

Use Projects for:
- Goals
- Constraints
- Brand identity
- Requirements
- Stable context

Before planning work for a project:
- Read the Project page using Notion MCP.

Do not store:
- daily logs
- execution steps
- short-term plans

---

## Plan Items

Plan Items represent execution steps.

Use Plan Items for:
- Short-term actions
- Steps derived from planning mode
- Tasks that are actively being worked on

Plan Items should be:
- Short
- Actionable
- Focused on one step

Do not store:
- long explanations
- research notes
- brainstorming

---

## Knowledge

Knowledge represents distilled insights.

Use Knowledge for:
- Decisions
- Lessons learned
- Reusable insights
- Summarized research

Knowledge entries must be:
- Concise
- Structured
- Focused on what should be remembered

Do not store:
- raw transcripts
- temporary notes
- unstructured thinking

---

# Reading Workflow

Before planning or executing work:

1. Identify the relevant Project or Area.
2. Use Notion MCP to read:
   - The Project or Area page
   - Relevant Knowledge entries if needed.

If the relevant project is unclear:
Ask the user which project applies.

---

# Writing Workflow

Store information only when it is:

- Structured
- Useful later
- Related to a project or area

Do not store trivial or temporary information.

---

# Behavioral Rules

- Notion is structured memory, not a scratchpad.
- Planning happens in planning mode.
- Execution steps go to Plan Items.
- Long-term insights go to Knowledge.
- Stable context belongs in Projects or Areas.

