# Contributing to NVIDIA Agent Skills

Thank you for your interest in contributing! We welcome contributions from the community — whether it's fixing a typo, improving documentation, or proposing a new skill.

---

## GitHub-First

All communication happens on GitHub. Please use:

- **Issues** for bug reports, feature requests, and questions
- **Discussions** for open-ended conversation, ideas, and show & tell
- **Pull Requests** for code and documentation changes

---

## How to Contribute

### Reporting Bugs or Requesting Features

1. Search [existing issues](../../issues) to avoid duplicates.
2. Open a new issue with a clear title and description.
3. Include steps to reproduce (for bugs) or a use case (for feature requests).

### Improving Existing Skills

1. Fork the repository.
2. Create a feature branch: `git checkout -b fix/skill-name-description`
3. Make your changes and test locally with a compatible agent.
4. Open a Pull Request with a clear description of the change.

### Submitting a New Skill for NVIDIA Verification

We accept community-authored skills into the `community/` directory. Once reviewed and approved by NVIDIA, verified skills are promoted to `skills/`.

#### Requirements

- Follow the [Agent Skills specification](https://agentskills.io/specification).
- Include a `SKILL.md` with valid YAML frontmatter (`name` and `description` are required).
- Test your skill locally with your preferred agent before submitting.
- Do not include secrets, credentials, or proprietary dependencies without clear documentation.
- Keep skills focused — one skill should solve one clear problem.

#### Submission Process

1. Fork this repository.
2. Add your skill to `community/<your-skill-name>/`.
3. Ensure your skill directory follows this structure:
   ```
   community/your-skill-name/
   ├── SKILL.md          # Required: skill definition
   ├── scripts/          # Optional: executable scripts
   ├── references/       # Optional: reference documents
   └── assets/           # Optional: static assets
   ```
4. Open a Pull Request with:
   - A description of what the skill does
   - Example usage
   - Any dependencies or requirements
5. NVIDIA will review for quality, security, and compatibility.
6. If approved, the skill is merged and may be promoted to `skills/` with the NVIDIA-verified badge.

---

## Code of Conduct

All participants are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md). Be respectful, constructive, and inclusive.

---

## Questions?

Open a [GitHub Discussion](../../discussions) — we're happy to help.
