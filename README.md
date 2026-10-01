![Superwriting Cover Image](https://github.com/IrgiAulia/Superwriting/blob/main/Group%2011.png?raw=true)
# Superwriting

Claude's skill in writing, composing, editing, and proofreading Indonesian or English texts. This skill combines three elements into one:

1. Structure: a well-organized scientific essay (Abstract, Introduction, Methodology, Results, Discussion) with a paragraph pattern of topic sentences, proofs & analysis, and relinks.
2. Style: concise, active, and concrete sentences a la The Economist, based on KBBI and EYD V.
3. Cohesion and coherence: links between sentences and paragraphs.

This skill replaces the Economist-style and Essay-mode skills.

## When is this skill active?

Claude uses this skill when you ask him to write, revise, summarize, or proofread an essay, paper, article, thesis, dissertation, report, formal email, or any other manuscript. Examples of triggers:

- "Improve this writing"
- "Make it more concise"
- "Write an abstract"
- "Check the structure of the essay"
- "This sentence is stiff" or "wordy"
- "It doesn't connect" or "jumps around"

## Work mode

| Prompt | Mode | Steps |
|---|---|---|
| Writing or revising a scientific essay | Essay | A (structure), B (style), C (cohesion) |
| Editing any text style | Edit | B, then C if more than one paragraph |
| Correcting disjointed writing | Edit | C, then B |

## Main principles

- Use short, common, and concrete words. Change nominalizations to verbs.
- Use the active voice. Passive only when the agent is unknown or unimportant.
- No metaphors, similes, or allusions.
- No em dashes. Replace them with commas, colons, parentheses, or periods.
- Repeat the same keywords for the same purpose; don't replace them with synonyms.
- Pass three final tests: the outline test, the strip test, and the no-link test.

## Repository Structure

```
Superwriting/
├── SKILL.md # Key Skill Instructions
├── references/
│ ├── section-structure.md # Content of each section of the essay
│ ├── paragraph-pattern.md # Topic sentence, proofs & analysis, relink
│ ├── link-elaboration-pattern.md # Two detail development patterns
│ ├── diction-and-terms.md # List of problematic words and their equivalents
│ ├── cohesion-coherence.md # Rules, link tables, three tests
│ └── self-editing-checklist.md # Self-editing checklist
├── README.md
├── LICENSE
└── .gitignore
```

## How to install

**Claude.ai (web or app)**

1. Download this repository as a ZIP, or unzip the `Superwriting` folder yourself. Make sure `SKILL.md` is inside that folder.
2. Go to **Settings**, then **Capabilities**, then **Skills**.
3. Upload the ZIP file and enable the skill.

**Claude Code**

```bash
git clone https://github.com/IrgiAulia/Superwriting.git ~/.claude/skills/superwriting
```

For a single project, clone to `.claude/skills/superwriting` within that project.

## Usage Example

```
Write an abstract for my research on the impact of fertilizer subsidies on rice productivity in Central Java. RQ: Do subsidies increase crop yields?
```

```
Edit this paragraph. There are too many passive sentences and the sentences don't connect.
```

## Language References

- EYD V: https://ejaan.kemendikdasmen.go.id/
- KBBI: https://kbbi.kemendikdasmen.go.id/
- English based on the Oxford Learner's Dictionary: https://www.oxfordlearnersdictionaries.com/.

## License

Released under the MIT license. See the [LICENSE](LICENSE) file.
