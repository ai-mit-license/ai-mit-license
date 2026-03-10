# Contributing to AI-MIT License

Thank you for your interest. This is a community-driven project — the quality of the license depends on diverse input from developers, lawyers, and open-source practitioners worldwide.

## What we need most

### 1. Legal review
The license text must be robust across jurisdictions. If you are a lawyer (or work closely with one), please review the text and open an issue noting:
- Jurisdiction
- Specific clause you're reviewing
- Whether it achieves its stated goal in that jurisdiction
- Suggested language improvements

We are especially looking for reviewers familiar with: EU, UK, Russia, China, Japan, India, Brazil.

### 2. Edge case scenarios
Open an issue titled `[EDGE CASE] <short description>` and describe a real-world scenario where the current license text is ambiguous, insufficient, or creates an unexpected outcome. Good examples:
- "An AI agent generates code, a human fixes one bug — which box do you check?"
- "A company uses AI-MIT code to train a new AI model — does condition 2 apply?"

### 3. Translations
Non-authoritative translations help the license reach more communities. See `/translations/TRANSLATION_GUIDE.md` for instructions. Each translation file must include a header noting it is non-authoritative and linking to the English original.

### 4. Tooling
See open issues tagged `tooling`. Priority items:
- CLI: `ai-mit init` — generates a pre-filled LICENSE file interactively
- GitHub Action: validates that AI-MIT repositories have a completed Authorship Declaration
- Badge generator

## How to contribute

1. **Fork** the repository
2. **Create a branch**: `git checkout -b fix/clause-3-wording`
3. **Make your changes**
4. **Open a Pull Request** with a clear description of what you changed and why

For significant changes to the license text itself, please open an **issue first** to discuss before writing a PR. Changes to core legal text require broader consensus.

## Conduct

This project follows the [Contributor Covenant](https://www.contributor-covenant.org/) Code of Conduct. Be respectful, be precise, be honest about uncertainty.

## A note on authorship of contributions

By submitting a contribution, you agree that:
- Your contribution may be AI-assisted, but you take responsibility for its content
- The contribution will be released under the same terms as the repository (AI-MIT-1.0)
- You have the right to make the contribution (it's not proprietary to a third party)

If your contribution is substantially AI-generated, please note this in your PR description. It's fitting — and it helps us track the meta-irony.
