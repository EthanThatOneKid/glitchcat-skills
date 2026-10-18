# glitchcat-skills

Agent skills distilled from GlitchCatClub AI practitioner content — "No Guru BS", build in public, receipts over claims.

Skills are generated with [distilly](https://github.com/titanwings/distilly) from public content and structured as colleague persona + work skills.

## Skills

| Skill | Description |
|-------|-------------|
| [`skills/kem`](skills/kem) (`colleague-kem`) | Kem at Wazoo — AI practitioner / agentic systems: multi-agent orchestration harnesses, skills, agent loops, model routing |

### colleague-kem

- **Work**: harness design (orchestrator → git-worktree branches → merge-through-quality-gates, claimed writes), model routing economics (cheap models for testable multi-attempt tasks, strongest model for reasoning), build-in-public workflow, CR focus on structural orchestration
- **Persona**: blunt, evidence-first, ships unfinished, mentors generously, debunks guru hype

Source material: [@kem_glitch](https://www.instagram.com/kem_glitch) on Instagram (bio, posts, live classes, artefacts), distilled October 2026.

## Layout

```
skills/
  <slug>/
    SKILL.md      # combined, self-contained skill (invoke as colleague-<slug>)
    work.md       # work skill: scope, standards, workflow, knowledge base
    persona.md    # 5-layer persona
    manifest.json # metadata
```

## Contributing

New skills go through the same distilly flow: research → intake → distill → review. See `skills/<slug>/manifest.json` for each skill's knowledge sources.
