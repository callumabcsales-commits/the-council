# The Council

Five business brains. A neutral Chair. One clear recommendation.

An AI advisory council built from the public work of **Alex Hormozi, Gary Vee, Sam Altman, Brian Chesky and MrBeast**. Each advisor uses their own frameworks; the Chair weighs their advice against your business and recommends your next actions.

## Download and start

1. Click **Code → Download ZIP** on this repository and extract it anywhere on your computer. Or clone it:

   ```sh
   git clone https://github.com/callumabcsales-commits/the-council.git
   cd the-council
   ```

2. Open the extracted `the-council` folder as your workspace in Codex or Claude Code, or give your folder-based AI assistant access to it.
3. Say: **“Read AGENTS.md and set up my council.”**
4. Answer the business interview. The assistant creates your private `my-business/Business-Profile.md` from the blank template.
5. Ask: **“Ask the council: should I raise my prices or focus on getting more customers?”**

No application build, API key or Python installation is needed to use the included council. You need an AI assistant that can read the folder. The optional cloning tools have their own requirements in `clone-a-brain/CLONE-PROCEDURE.md`.

## Ways to use it

- **Ask the council:** get several perspectives and the Chair’s recommendation.
- **Ask Hormozi:** consult one advisor. Gary, Sam, Chesky and MrBeast also work.
- **Debate Hormozi vs Chesky:** compare two approaches.
- **Hot seat:** let the advisors question you before making a recommendation.
- **Board review:** review your numbers and set priorities.
- **Quick poll:** get a short answer from each advisor.
- **Update my profile:** keep your business context current.
- **Clone [name]'s brain:** use the included kit to add another advisor.

Ready-to-copy prompts are in `prompts/`.

## What is included

| Folder or file | Purpose |
| --- | --- |
| `advisors/` | Five advisor brains, instructions, sources and individual setup guides |
| `council/` | Roster, meeting protocol and project instructions |
| `prompts/` | Setup, meetings, debates, hot seats and board reviews |
| `templates/Business-Profile.md` | Blank profile for each new user |
| `clone-a-brain/` | Reusable procedure, prompts, templates and transcript tool for adding advisors |
| `docs/` | Optional web-project setup guides |
| `AGENTS.md` | Instructions for the assistant running the council |
| `CLAUDE.md` | Loads those instructions in Claude Code |

## Your business stays local

This repository starts with no saved sessions, personal business profile, revenue evidence, growth plans, portfolio or content handoff. Your assistant creates `my-business/` and `sessions/` when needed; both are ignored by Git. Keep private material in those folders, and review any other files before sharing your copy. Git ignore rules do not stop your AI assistant provider from processing files you give it.

To fill in your profile by hand, copy `templates/Business-Profile.md` to `my-business/Business-Profile.md`, complete the fields and set `Status: filled in`.

For a web project, paste `council/Council-Instructions.txt` into the project instructions and add the roster, protocol and five brain files as knowledge. Add your own completed profile separately. See `docs/` for the original setup guides; platform limits and interfaces may change.

## About the advisors

These are AI interpretations of public work, not the real people, and are not affiliated with or endorsed by them. The source material is dated September 2026; newer developments require updating the brains. Check the source lists and verify important claims before acting.
