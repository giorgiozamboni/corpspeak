# Contributing to corpspeak

Thanks for wanting to make corpspeak better. This is a writing skill, so most contributions are about *language*, not code.

## Good first contributions

- **Lexicon entries.** Add plain to corporate mappings in `references/lexicon-it.md` or `references/lexicon-en.md`. Real office phrases beat invented ones.
- **Bridge phrases and idioms** that managers actually use.
- **Anti-AI rules.** If you spot a structural "AI tell" that slips through, add it to `references/anti-ai-gate.md` with a before/after example.
- **Sector flavors.** Propose a finance-only, tech-only, or consulting-only variant.

## Ground rules

1. **Keep the reconciliation intact.** Business jargon is wanted; structural AI tells (em dashes, forced rule of three, significance inflation) are not. Do not break that balance.
2. **No em dashes in examples.** The skill bans them, so the repo does too.
3. **Italian stays Italian.** The itanglese is a feature, not a bug. Do not "correct" it into pure Italian.
4. **Show, don't tell.** New rules need a concrete before/after example.

## How to submit

1. Fork the repo and create a branch.
2. Make your change. If you touched `SKILL.md`, keep the `description` under 1024 characters.
3. Open a pull request describing what you changed and why, with an example.

## Reporting issues

Found a case where corpspeak produces something that still smells like AI, or a phrasing that misses the mark? [Open an issue](https://github.com/giorgiozamboni/corpspeak/issues) with the input, the output you got, and what you expected.
