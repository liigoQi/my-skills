# Book Analysis Framework

## How to Extract Skills from Books

### Step 1: Book Type Classification

Identify what type of book you're dealing with:

| Type | Characteristics | Skill Extraction Focus |
|------|----------------|----------------------|
| Method/Framework | Has repeatable systems | Extract the system as a workflow skill |
| Self-help/Toolkit | Has exercises/tools | Turn tools into interactive skills |
| Technical/Manual | Step-by-step processes | Create step-by-step guidance skills |
| Case Study/Analysis | Analyzes examples | Extract diagnostic/analysis frameworks |
| Theory/Concept | Explains why | Create explanation/teaching skills |

### Step 2: Deep Reading Strategy

**For method books:**
1. Find the core framework (often in intro/conclusion)
2. Identify 3-5 key practices/tools
3. Look for checklists, templates, exercises
4. Note common use cases and scenarios

**For technical books:**
1. Map the workflow/process steps
2. Identify decision points
3. Extract anti-patterns (what NOT to do)
4. Find best practice checklists

### Step 3: Skill Direction Identification

Ask these questions for each chapter:

```
Q: What repeatable action does this enable?
Q: What decision does this help make?
Q: What problem does this diagnose?
Q: What template/checklist is defined?
Q: What conversation/script is provided?
Q: What assessment rubric is given?
```

### Step 4: Skill Name Generation

**Naming patterns:**

| Pattern | Format | Example |
|---------|--------|---------|
| Capability | {verb}-{noun} | habit-build, code-review |
| Tool | {tool-name} | okr-planner, swot-analyzer |
| Process | {process}-{stage} | project-kickoff, bug-triage |

**Rules:**
- hyphen-case only (lowercase, hyphens)
- Max 40 characters
- Should be searchable and memorable
- Reflect the skill's purpose clearly

### Step 5: Skill Description Template

For each skill, define:

```markdown
**name**: {skill-name}

**description**: One paragraph explaining:
1. What the skill does
2. WHEN to use it (trigger scenarios)
3. WHAT it helps accomplish

**Example triggers:**
- "Help me [doing X]..."
- "I need to [action]..."
- "Generate [template] for [situation]..."
```

## Quality Checklist

Before presenting skills to user:

- [ ] Skill name is clear and searchable
- [ ] Description explains when to use
- [ ] Skill is genuinely derived from book content
- [ ] Skill solves a real, recurring problem
- [ ] Skill can be executed by Claude effectively
- [ ] Skill doesn't require copyrighted full text to use
