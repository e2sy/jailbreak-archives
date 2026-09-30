# Contributing Guidelines

Thank you for helping document and research adversarial prompt techniques for LLM safety.

## Submission Requirements

Whenever you submit or add a new adversarial prompt technique:

1. **Add Payload & Breakdown**: Place your payload under the appropriate model directory (e.g., `deepseek/`, `Antigravity-claude/`, `openai/`, `anthropic/`, etc.) in a numbered text or markdown file.
2. **Mandatory: Update [README.md](./README.md)**:
   - Update the repository structure tree if adding new directories.
   - Increment the tracked entries / models badge count if applicable.
3. **Mandatory: Update [CREDITS.md](./CREDITS.md)**:
   - Add your name or GitHub handle, the target model/technique added, and date to the contributors table.

## Format Guidelines

When recording a new prompt:
- Provide the prompt verbatim without omissions.
- Note the tested model version, timestamp, interface (Web UI, API, system prompt settings).
- Include mechanistic notes on why the bypass worked and potential mitigations.

## Pull Request Process

1. Fork the repository.
2. Create a feature branch (`git checkout -b entry/model-name`).
3. Commit your changes with clear messages (`git commit -m "feat(deepseek): add prefix injection entry"`).
4. Verify that both [`README.md`](./README.md) and [`CREDITS.md`](./CREDITS.md) are updated.
5. Submit your PR for review.
