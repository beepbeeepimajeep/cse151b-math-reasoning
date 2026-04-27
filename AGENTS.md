# Project Instructions

This is a CSE 151B Kaggle competition project.

## Hard Constraints

- Final inference must use `Qwen/Qwen3-4B-Thinking-2507`.
- Do not use external tools, hosted APIs, or network services at inference time.
- Do not modify files under `data/` unless explicitly asked.

## Output Format

- Model answers must be in `\boxed{<answer>}` format (letter for MCQ, value/expression for free-form)
- Ensure inference code extracts answers by parsing `\boxed{}` consistently

---

## Implementation Style

- Prefer simple, readable Python over clever abstractions.
- Keep changes scoped to the requested task.
- Preserve starter-code assumptions unless there is a clear reason to change them.

## Agent Roles

- Claude is the planning/reasoning lead when the user asks for strategy or review.
- Codex is the implementation arm: inspect the repo, make concrete edits, and verify them.
- If instructions conflict, prioritize the hard constraints above.
