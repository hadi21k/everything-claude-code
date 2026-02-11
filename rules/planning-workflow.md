# Planner Storage Rule

This rule applies when the user is planning work or using planning mode.

Planning mode is used for organizing work and defining execution steps.
Notion is used as the persistent memory for plans.

All reading and writing to Notion must be done using the Notion MCP tools.

This rule only applies to planning, not general note-taking.

---

# Using Notion MCP

Whenever this rule requires reading or storing information in Notion:

- Use the Notion MCP tools.
- Do not simulate storage or pretend to save plans.
- Retrieve the relevant Project or Area page using MCP before planning.
- Store the plan using MCP after planning is complete.

If MCP access fails or required information cannot be found:
Ask the user how to proceed instead of guessing.

---

# Planning Workflow

When the user asks to plan:

1. Identify whether the plan belongs to a specific Project or Area.
2. If a project is mentioned explicitly, use that project.
3. If one or more possible projects are found but the user did not specify:
   - Ask the user to confirm which project the plan should be stored in.
   - Do not store the plan until the user confirms.
4. If no relevant project is found:
   - Ask the user whether to store the plan in a general location or create a new project.

Project or Area pages are mandatory context when planning.

---

# Reading Context

Before generating a plan:

1. Use Notion MCP to read the relevant Project or Area page.
2. Understand:
   - goals
   - constraints
   - preferences
   - context

If a project is required but not yet confirmed:
Ask the user before proceeding.

---

# Plan Scope Rules

Plans created in planning mode are:

- Short-term
- Focused on one objective
- Not long-term roadmaps
- Not multiple unrelated plans

Each planning session should produce:

One plan  
One objective  

Do not create multiple plans in a single planning session.

---

# Storing the Plan

After generating the plan:

Store the plan in Notion using Notion MCP.

Location:
- Inside the confirmed Project page
- Or in a general planning area if no project applies and the user approves

The stored plan should:

- Preserve the original plan content
- Be concise
- Represent a single objective

Do not store execution logs or transcripts.

---

# Execution Behavior

Execution happens after planning mode ends.

During execution:

- The plan is followed step-by-step
- Adjustments may be made during execution
- Only meaningful results should be stored in Knowledge

---

# Retrieval Behavior

When planning work:

1. Determine the relevant Project or Area.
2. Use Notion MCP to read the Project or Area page before planning.
3. Confirm the storage location with the user if there is any ambiguity.

---

# Behavioral Rules

- Planning mode organizes thinking.
- Notion MCP is the only method used to read or store plans in Notion.
- Knowledge stores distilled insights.
- Execution is separate from planning.
- Always confirm the project before storing a plan if multiple or uncertain matches exist.

Never mix these roles.

