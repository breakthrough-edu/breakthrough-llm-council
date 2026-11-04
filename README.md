# LLM Council (Breakthrough copy)

Run one real decision through five AI advisors who think independently, review each other anonymously, and end with a chairman verdict.

This is the copy used in the 2nd Brain Intensive. It is the public [`tenfoldmarc/llm-council-skill`](https://github.com/tenfoldmarc/llm-council-skill) (MIT), with one change: it only runs when you call it. The original also starts itself on everyday phrasings such as "should I X or Y".

## Install

```bash
npx skills add -g breakthrough-edu/breakthrough-llm-council
```

Then open a new Claude Code session.

## Use

Type `/llm-council` followed by your decision. Bring one decision, the real options, and what the outcome must protect.

## Credit

- Methodology: [Andrej Karpathy's LLM Council](https://x.com/karpathy/status/1962263486196867115)
- Adapted for Claude Code sub-agents by [@olelehmann](https://x.com/olelehmann)
- Published as an installable skill by [tenfoldmarc](https://github.com/tenfoldmarc/llm-council-skill), at commit `0dc0327`

## License

MIT, see [LICENSE](LICENSE).
