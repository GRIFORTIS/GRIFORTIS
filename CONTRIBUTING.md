## Contributing to GRIFORTIS Projects

Thank you for your interest in contributing to the GRIFORTIS ecosystem.  
Our repositories focus on **long-term digital inheritance, backup robustness, and self-sovereign security**. Many of our projects, such as **Schiavinato Sharing**, are directly related to the protection of real financial assets.

Because of that, we ask contributors to follow the guidelines below so that collaboration remains safe, respectful, and technically rigorous.

---

## Where to Start

- **Choose a repository**
  - Each project under the [`GRIFORTIS`](https://github.com/GRIFORTIS) organization has its own `README.md` describing goals, status, and scope.
  - Some projects may also have project-specific contributing notes in their own `CONTRIBUTING.md`. If such a file exists in a project repository, treat it as an extension of this document.

- **Open an issue first (recommended)**
  - For substantial changes (new sections in a whitepaper, major rewrites, or new tools / reference implementations), please open a GitHub issue in the relevant repository before investing large amounts of time.
  - Use the issue to:
    - Describe what you’d like to change or add.
    - Explain why it improves security, clarity, or usability.

---

## Types of Contributions

- **Documentation and whitepapers**
  - Propose clarifications, fix typos, or reorganize sections to improve readability.
  - Highlight ambiguous wording, unstated assumptions, or missing threat-model considerations.
  - When changing security-relevant text, keep or strengthen existing warnings and caveats rather than weakening them.

- **Technical and mathematical validation**
  - Check derivations, formulas, and constructions for correctness.
  - Validate examples and test vectors (for example, in finite fields such as \\(GF(2053)\\)).
  - Provide minimal, well-explained counterexamples if you believe you have found an error.

- **Reference implementations and tooling**
  - Implement small, auditable libraries or utilities that follow the relevant whitepaper or specification.
  - Prefer minimal dependencies and clear, readable code over cleverness.
  - Include tests or examples (such as reproducing provided test vectors) where practical.

---

## Pull Request Guidelines

1. **Keep changes focused**
   - Prefer small, well-scoped pull requests over large, mixed ones.
   - When possible, separate:
     - Editorial changes (typos, formatting),
     - Conceptual changes (definitions, constructions),
     - Security-relevant changes (threat model, warnings, workflows).

2. **Explain your reasoning**
   - In your PR description:
     - State what you changed.
     - Explain *why* the change is needed.
     - Describe how it aligns with the project’s goals (e.g., human executability, auditability, safety for non-experts).

3. **Respect safety warnings**
   - Do not remove or weaken warnings, caveats, or security notes without careful discussion.
   - If you think existing wording is unclear or too alarmist, propose alternative language that remains honest about risks.

4. **Follow existing style**
   - Use Markdown consistently: `##` / `###` headings, bullet lists, fenced code blocks, and LaTeX for math when appropriate.
   - Match the tone of the project you are editing: precise but accessible, with concrete examples when they help understanding.

---

## Code and Security-Sensitive Changes

Many GRIFORTIS projects are **security-sensitive**. When contributing code or changes that could affect real users:

- Keep implementations:
  - **Small and auditable**,
  - **Dependency-light**, and
  - **Explicit about their status** (experimental, unaudited, production-ready, etc.).

- Add tests or example usage whenever possible, particularly where subtle arithmetic or encoding is involved.

- If your contribution might impact real-world safety (for example, it changes how shares are generated, recovered, or verified), please:
  - Call this out explicitly in your PR description.
  - Consider opening an issue first to discuss the design.

For **suspected security vulnerabilities** or subtle failure modes, please follow the process described in the organization-wide `SECURITY.md` (in the `.github` repository) and any project-specific security notes.

---

## Recognition and Attribution

We value contributions of all kinds—editorial, conceptual, and technical.

Where appropriate, we may:

- Acknowledge contributors in the repository or release notes.
- Credit substantial contributions in future revisions of whitepapers or documentation, subject to maintainers’ discretion and your preferences.

If you are contributing on behalf of an organization, please mention this in your pull request so we can acknowledge both individuals and institutions where appropriate.


