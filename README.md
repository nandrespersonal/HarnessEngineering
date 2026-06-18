# Harness Engineering

Harness Engineering is the practice of turning human judgment, workflows, tools, feedback, and institutional knowledge into AI-supported learning loops that **compound over time**.

This project started from the idea that the future of AI at work is not just picking the best model. The durable advantage comes from building the harness around models: the context, guardrails, evals, workflows, memory, and human-in-the-loop behaviors that let people and AI get better together.

The central claim of this project is simple:

> Daily work should not evaporate when the meeting ends, the chat scrolls away, or the incident closes. Each meaningful work session should leave the harness stronger than it was before.

## Why this matters

AI can summarize, draft, search, reason, and automate, but it does not know what matters inside a specific team or organization unless people teach it through repeated, structured use. Harness Engineering gives that teaching process a shape.

The goal is to help daily workers use AI without surrendering agency:

- Humans define goals, constraints, and judgment.
- AI helps organize context, identify patterns, draft options, and challenge assumptions.
- Workflows capture reusable lessons.
- Private evals measure whether the system is improving against outcomes that matter.
- The organization keeps control of its own knowledge and operating model.

## The compounding loop

Harness Engineering compounds when the output of today's work becomes the starting advantage for tomorrow's work.

The loop looks like this:

1. Do real work.
2. Use AI to help frame, reason, summarize, challenge, draft, or validate.
3. Capture what was learned.
4. Convert the learning into a reusable asset.
5. Use that asset in the next similar situation.
6. Improve the asset again based on the next outcome.

In shorthand:

> Daily work -> AI-assisted reflection -> captured pattern -> improved template/eval/playbook -> better next execution -> stronger captured pattern

That is compounding. The repo should become more useful because it stores the reusable parts of experience: not private details, not noise, and not raw transcript dumps, but the patterns that make the next execution better.

## What compounds

The project compounds through small artifacts that improve future behavior.

| Asset | How it compounds |
|---|---|
| Playbooks | Turn one good workflow into a repeatable operating habit. |
| Templates | Reduce blank-page effort and make good structure the default. |
| Private evals | Convert judgment into measurable checks that can catch regressions. |
| Guardrails | Prevent repeated mistakes and clarify where humans must stay in control. |
| Decision logs | Preserve why a choice was made, not just what was chosen. |
| Prompt patterns | Capture tested ways to frame work so future AI sessions start stronger. |
| Case studies | Generalize lessons from real work without exposing sensitive specifics. |
| Backlog issues | Turn vague improvement ideas into visible, trackable work. |
| Glossary terms | Stabilize language so people can coordinate around the same concepts. |

The point is not to document everything. The point is to capture the pieces that create leverage.

## What does not compound

Not every AI interaction creates durable value.

These usually do not compound:

- One-off answers that are never reused.
- Raw chat dumps with no extracted lesson.
- Prompts that only work because of hidden context.
- Summaries that do not distinguish fact, assumption, and interpretation.
- Tool use that succeeds once but leaves no reusable pattern.
- Lessons that remain in a person's memory instead of becoming part of the harness.

Harness Engineering asks a different question at the end of meaningful work:

> What did this teach the harness?

If the answer is clear, capture it. If the answer is not clear, do not create noise.

## The compounding unit

The smallest useful unit of compounding is a **learning capture**:

- What happened?
- What mattered?
- What surprised us?
- What pattern should be reused?
- What mistake should be prevented?
- What template, eval, checklist, prompt, or playbook should change?

The learning capture should be generalized enough to help future work and sanitized enough to avoid storing sensitive operational details unnecessarily.

## Human capital becomes token capital

Human capital is the knowledge, judgment, relationships, context, and pattern recognition that people bring to work.

Token capital is the reusable AI capability the organization builds around models: prompts, workflows, evals, memories, tools, playbooks, agents, and feedback loops.

Harness Engineering is the conversion mechanism between the two.

Human judgment identifies what matters. AI helps process, compare, draft, and challenge. The harness captures the reusable lesson. The next worker starts from a better place. Over time, the organization is not merely using AI; it is building an internal learning system that preserves and amplifies its own expertise.

This is why the value compounds. A single interaction may save minutes. A captured pattern can save hours repeatedly. A private eval can prevent a class of errors. A mature playbook can make a whole team more consistent. A well-designed harness can let the organization swap models without losing its way of working.

## Core idea

Every knowledge worker can build a small learning loop into their day:

1. Frame the work.
2. Feed relevant context.
3. Ask AI to reason, not just summarize.
4. Keep humans in charge of decisions.
5. Capture reusable learning.

At team and organization scale, these loops become token capital: durable AI capability built from human capital.

## Daily operating behavior

A daily worker can apply the compounding loop without changing jobs, tools, or org charts.

Before work:

- Ask AI to help frame the goal, constraints, known context, and decision needed.
- Tell AI what role to play: summarize, challenge, track assumptions, draft, or validate.

During work:

- Feed relevant context as it arrives.
- Ask AI to separate facts, assumptions, risks, and open questions.
- Ask for the next validation step, not just a confident answer.
- Keep the human owner in charge of decisions.

After work:

- Ask what changed.
- Ask what pattern emerged.
- Ask what should be reused next time.
- Convert the answer into a small repo improvement: a template, eval, checklist, issue, or playbook update.

The habit is lightweight, but the effect is cumulative.

## How to operate this repository

Use this repo as the durable home for the harness.

For each meaningful improvement:

1. Create or update a small artifact.
2. Link it to the relevant project track.
3. Add an issue if more work is needed.
4. Keep examples generalized unless the repo is explicitly private and the details are safe to store.
5. Prefer reusable patterns over long narrative archives.

Good repo changes include:

- Adding a new harness pattern.
- Improving a daily worker prompt.
- Creating a private eval.
- Capturing a generalized case study.
- Updating a guardrail after a repeated failure.
- Turning an insight into a GitHub issue.

Bad repo changes include:

- Dumping raw private chats.
- Storing secrets or sensitive operational data.
- Adding vague advice that cannot change behavior.
- Creating duplicated guidance without reconciling conflicts.

## Project tracks

| Track | Purpose |
|---|---|
| Manifesto / Narrative | Explain Harness Engineering and why it matters. |
| Daily Worker Playbook | Define practical habits workers can use every day. |
| Harness Patterns | Create reusable templates for meetings, incidents, decisions, and learning capture. |
| Tooling & Workflow | Show how tools such as Copilot, CoWork, Scout, GitHub Issues, and agents can fit together. |
| Private Evals | Define checks that measure whether AI is improving on real work. |
| Adoption Experiments | Run small pilots and capture lessons. |
| Governance / Guardrails | Define what AI can do, what humans must own, and how context/IP stays controlled. |

## Getting started

Start with:

- `docs/article.md` - the north-star article.
- `docs/daily-worker-playbook.md` - the practical behavior loop.
- `PROJECT_BACKLOG.md` - initial GitHub Project / issue backlog.
- `issues/` - issue drafts that can be copied into GitHub Issues.

## Working definition

Harness Engineering is not prompt engineering. It is the broader discipline of designing the system around AI so that models, tools, people, and organizational memory work together safely and improve with each use.
