- global rule = 행동

```markdown
# Global Rules

## Language & Communication

- All explanations and responses must be in Korean.
- Technical terms remain in English when appropriate.
- Tone: Professional, clear, helpful.

## Operational Standards

- Explain the "Why" when changes are non-trivial.
- Follow project linting/formatting rules.
```

- workspace rule = 코드

```markdown
# Workspace Rules

## Code Language Rules

- All code comments must be in English
- All docstrings must be in English (reStructuredText style)
- Do not mix Korean inside code blocks unless explicitly required

## Coding Style

- **Simplicity First**: Avoid unnecessary abstraction. If code is used in only one place, don't extract it.
- **Consistency**: Ensure data schemas are consistent across components (API, tools, database).
- **Standard Patterns**: Use widely-adopted patterns for common problems.
- **Readable Code**: Prefer clear, simple syntax. Avoid unnecessary complexity.
- Consider extensibility when it doesn't add significant complexity

## Project Structure

- dir1/: explanation1
- dir2/: explanation2
- ...

## Commit Convention

- Use Conventional Commits format (e.g., "feat: add new feature")

## GitHub rules

- When generating Git content, add "AI-assisted" note.
```
