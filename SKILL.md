# Skill: Create-Skill (agent-customization)

Purpose
- Provide a repeatable workflow for extracting and codifying a conversation-driven agent/skill.

Scope
- Workspace-scoped guidance for authoring `SKILL.md` files and pairing `.agent.md` agents.

Step-by-step Process
1. Review conversation history and project context to identify recurring workflows and decisions.
2. Extract the step-by-step process being followed, decision points, and quality criteria.
3. Decide scope: workspace-scoped vs personal; concise checklist vs full multi-step workflow.
4. Draft the `SKILL.md` containing Purpose, Steps, Decisions, and Completion Criteria.
5. Draft a paired `.agent.md` if a specialized agent/persona is needed.
6. Iterate with the user on ambiguous parts; update the skill accordingly.
7. Finalize with example prompts and suggested follow-up customizations.

Decision Points
- Outcome type: checklist (quick) vs full workflow (detailed).
- Scope: should the skill operate only in this repo, or be a personal helper?
- Tooling: which tools are allowed/forbidden for the agent.

Quality Criteria / Completion Checks
- Steps are actionable and ordered.
- Decision points clearly documented with branching guidance.
- Examples and 3–5 prompt templates are included.
- User has at least one clear next action (e.g., run a prompt, edit file).

Iteration Guidelines
- Mark unclear items in the file with a TODO and ask targeted clarifying questions.
- Keep the first draft short (one page), then expand based on user feedback.

Example Prompts
- "Create a concise `SKILL.md` for automating PR reviews in this repository." 
- "Draft a SKILL.md that extracts a CI troubleshooting workflow from our chat." 

Related Customizations
- Add `.agent.md` for a persona that uses this skill.
- Create templates for consistent skill metadata in a repository.

EOF
