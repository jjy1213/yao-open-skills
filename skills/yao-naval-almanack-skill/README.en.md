# Yao Naval Almanack Skill

Apply ideas from *The Almanack of Naval Ravikant* to career choices, service productization, long-term partnerships, and life priorities. Use the user's facts and constraints to provide a judgment, sources, practical next actions, and conditions that would change the advice.

[简体中文](README.md) · [Usage guide in Chinese](../../docs/skills/yao-naval-almanack-skill.md) · [Skill entry](SKILL.md)

## Use cases

- Review work logs for reusable outcomes, repeated effort, and a useful next step.
- Compare job offers, career directions, skill combinations, and long-term accumulation.
- Turn repetitive client delivery into reusable modules while checking quality, maintenance costs, and ownership.
- Assess partnerships using behavior, incentives, and responsibility.
- Explore tradeoffs among attention, income, freedom, family time, and social comparison.
- Explain concepts, read chapters, verify quotations, or plan a reading route.

## Install and use

Download or clone this repository and place the complete `skills/yao-naval-almanack-skill/` folder in your AI client's supported skill directory. Enable or reload it as required by the client. Keep the `references/` and `agents/` folders together with `SKILL.md`.

Install into the current Codex project with the Skills CLI:

```bash
npx skills add yaojingang/yao-open-skills --skill yao-naval-almanack-skill --agent codex
```

Explicit request:

```text
Use $yao-naval-almanack-skill to review my work log.
Identify reusable outcomes, the main source of repeated effort,
and one adjustment worth trying next week.
```

Natural request:

```text
My client reports involve many repeated steps. How can I improve delivery
and build reusable outcomes?
```

The description covers career, productization, partnership, and priority questions so clients can select the skill by intent. Actual invocation depends on the client's loading, enablement, and selection mechanism. Honor a request to disable the skill for the current task.

## Expected output

Application answers usually include a main judgment, relevant principles and sources, small next actions, and evidence that would change the advice. Concept explanations and source checks follow the question. Short requests keep a short response.

For a fictional scenario involving eight hours of similar client reports each week, an application might compare repeated steps across two deliveries, try one small reusable module, and measure time, quality, and rework. High customization or maintenance costs would narrow the scope. These actions are contextual applications; book ideas receive separate source attribution.

## Content and sources

Version **0.2.0** includes original Chinese knowledge cards for 36 main sections, introductory and appendix indexes, 28 application scenarios, 72 routing-boundary cases, and five constructed examples. The coverage baseline is Eric Jorgenson's official English edition. Read the full book at the [official website](https://www.navalmanack.com/).

The cards distinguish book paraphrases, official extras, and application design. Exact quotations require original-source checks. Published Chinese translations and page numbers require edition-specific verification.

No additional account, connector, or executable script is required. Quotation checks and current facts require available search or reading tools.

## Boundaries and license

Simple editing, arithmetic, coding, generic planning, and passing mentions of Naval follow their requested task. Investment trading and clinical care belong to their respective capabilities. Advice retains real constraints and verifiable evidence.

The public directory contains instructions, original paraphrases, and source links. User materials, work logs, the original PDF, research snapshots, and runtime outputs stay within their authorized scope.

The skill's original instructions, paraphrases, and documentation are published under this repository's [MIT license](LICENSE). The book and referenced third-party materials retain their respective rights.
