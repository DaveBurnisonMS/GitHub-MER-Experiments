# GitHub MER April 2026 — Personalized Reading List for DaveBurnisonMS

**Role:** Increasing developer productivity within software development across the entire organization.

This is a curated subset of links from the [April 2026 GitHub Monthly Enterprise Roundup (MER)](https://gh.io/mer). The full MER covers a wide range of topics; these selections focus on what is most directly applicable to scaling AI-powered developer productivity across an enterprise engineering organization.

---

## 🗓️ Events — Don't Miss These

Opportunities to learn, share, and stay ahead of where GitHub is heading.

- 📅 [GitHub Universe 2026 — Call for Sessions (open April 8–May 1)](http://githubuniverse.com/?utm_source=github&utm_medium=newsletter&utm_campaign=ent_news_cfs) — Universe heads back to San Francisco, October 28–29. If your team has shipped meaningful AI-powered productivity improvements, this is the place to share them. The Call for Sessions is open now—submit a session idea or nominate a speaker.

- 📺 [GitHub Roadmap Webinar, Q1 2026](https://github.com/resources/events/github-roadmap-webinar-q1/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup2604) — A 60-minute session connecting recently shipped features with near-term investments across GitHub and Copilot. Covers how agentic AI accelerates workflows, improves quality and efficiency, and enables enterprise governance. Essential context for anyone shaping how developers work.

- 📅 [KUWC: Making AI a Developer Team Sport — May 28](https://github.com/resources/events/github-kuwc-part-four26) — This one is directly on-topic. The next wave of AI-powered software delivery is about team-level collaboration, not just individual tooling. Join to explore how teams work better together across people, projects, and pull requests with AI.

- 📅 [Microsoft Build 2026 — June 2–3, San Francisco](https://build.microsoft.com/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — GitHub will be front and center. Deep, hands-on sessions with the teams building and scaling AI for real systems and workflows.

---

## 🚀 Scaling AI Adoption Across the Organization

The most important reads for your role: proven models, playbooks, and real-world data on scaling Copilot adoption.

- 📢 [Scaling AI opportunity across the globe: Learnings from GitHub and Andela](https://github.blog/developer-skills/career-growth/scaling-ai-opportunity-across-the-globe-learnings-from-github-and-andela/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — Concrete lessons on what actually works when scaling AI adoption in real-world engineering teams, especially in globally distributed environments. Shows why embedding Copilot into day-to-day workflows (not side experiments) drives faster skill development and measurable productivity outcomes. A proven, repeatable model.

- 📚 [GitHub Copilot Hackathon Playbook for Enterprise Admins](https://github.com/resources/whitepapers/github-copilot-hackathon-playbook/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — A step-by-step operational framework for planning and running internal hackathons that build practical Copilot skills and drive measurable business outcomes. Includes a champion-led model that transforms one-off events into a repeatable engine for Copilot adoption at scale. Companion [community discussion](https://github.com/orgs/community/discussions/190379/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) includes logistics, judging criteria, and templates.

- 📢 [Ten Months with Copilot Coding Agent in dotnet/runtime](https://devblogs.microsoft.com/dotnet/ten-months-with-cca-in-dotnet-runtime/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — Microsoft's .NET team ran the Copilot Coding Agent on one of the most demanding open source codebases in the world for ten months: 878 agent-opened PRs, 535 merged, 95,000+ lines of code, and a reported 50–70% reduction in issue resolution time. This is the most credible enterprise-scale productivity benchmark available right now.

- 📢 [60 million Copilot code reviews and counting](https://github.blog/ai-and-ml/github-copilot/60-million-copilot-code-reviews-and-counting/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — Copilot Code Review has grown 10x since launch and now accounts for over 20% of all code reviews on GitHub. The post details how the shift to high-signal feedback (fewer but more actionable comments) actually accelerates PR completion. Real production data on impact.

- 📄 [Maintaining codebase standards in a GitHub Copilot rollout](https://docs.github.com/en/enterprise-cloud@latest/copilot/tutorials/roll-out-at-scale/maintain-codebase-standards/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — How to use GitHub's governance features—branch rulesets, CODEOWNERS, required CI/CD, security scanning—to ensure AI-generated code meets the same quality bar as human-written code. Critical for anyone rolling out Copilot at scale without lowering codebase quality.

- 📄 [Resources for getting approval to use Copilot](https://docs.github.com/en/enterprise-cloud@latest/copilot/get-started/resources-for-approval/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — Collects the key materials (terms, DPA, trust center, compliance attestations) that accelerate legal, compliance, and cybersecurity signoff. Shortens procurement cycles for broad Copilot rollouts.

---

## 🤖 Agentic AI — New Capabilities That Multiply Productivity

The Copilot cloud agent (formerly coding agent) is shifting from "AI helps you write code" to "AI does end-to-end work while you review."

- 🚢 [Research, plan, and code with Copilot cloud agent](https://github.blog/changelog/2026-04-01-research-plan-and-code-with-copilot-cloud-agent/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — The cloud agent now supports branch-first coding without immediately opening a PR, on-demand implementation plan generation for human review before code is written, and deep research sessions grounded in full repo context. Available on all paid Copilot plans.

- 📢 [Run multiple agents at once with /fleet in Copilot CLI](https://github.blog/ai-and-ml/github-copilot/run-multiple-agents-at-once-with-fleet-in-copilot-cli/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — The `/fleet` command deploys an orchestrator that breaks a prompt into independent subtasks and dispatches each as a parallel subagent. Multi-file refactoring, documentation generation, test suite expansion—tasks that previously required sequential agent sessions can now run in a single coordinated operation. A fundamental change in scale.

- 📢 [Agent-driven development in Copilot Applied Science](https://github.blog/ai-and-ml/github-copilot/agent-driven-development-in-copilot-applied-science/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — GitHub's own team used coding agents to build coding agents: 345 files and 28,000+ lines of code in three days by shifting humans into architecture, review, and prompt engineering. Hard-won lessons on agent-first infrastructure design and blameless iteration loops with CI/CD—a practical blueprint for engineering organizations.

- 📢 [How Squad runs coordinated AI agents inside your repository](https://github.blog/ai-and-ml/github-copilot/how-squad-runs-coordinated-ai-agents-inside-your-repository/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — GitHub's "Squad" model coordinates multiple specialized AI agents (code gen, documentation, review) to deliver cohesive PRs with full auditability through standard code review and CI/CD flows. A safe, transparent path to scaling agentic automation.

- 🚢 [GitHub Copilot coding agent for Jira is now in public preview](https://github.blog/changelog/2026-03-05-github-copilot-coding-agent-for-jira-is-now-in-public-preview/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — Teams can now assign Jira issues directly to the Copilot coding agent, which autonomously analyzes the issue, implements changes, opens draft PRs, and posts updates back to Jira. Direct integration with existing project management workflows.

- 📺 [How to use agentic workflows for your repos | GitHub Checkout](https://youtu.be/XisVQoz5grw?si=x8r2J2ETUugBo80Q) (12:22) — A practical walkthrough of how to use plain English and Copilot to automate complex repository tasks—syncing documentation, upgrading frameworks, building a "super Dependabot"—and how major open source projects are already using these tools to reduce maintainer burden.

---

## 📊 Measuring Copilot Adoption and ROI

You can't improve what you can't measure. These updates give you the data you need to track and demonstrate impact.

- 🚢 [Copilot usage metrics now includes per-user GitHub Copilot CLI activity in organization reports](https://github.blog/changelog/2026-04-02-copilot-usage-metrics-now-includes-per-user-github-copilot-cli-activity-in-organization-reports/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — Per-developer visibility into CLI adoption: session counts, request totals, token usage, and CLI version. Supports seat utilization analysis, upgrade planning, and targeted enablement.

- 🚢 [Copilot usage metrics now identify active Copilot coding agent users](https://github.blog/changelog/2026-03-25-copilot-usage-metrics-now-identify-active-copilot-coding-agent-users/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — See which individual users have Copilot cloud agent activity in the usage dashboard and API, enabling accurate tracking of AI agent adoption beyond traditional IDE usage.

- 🚢 [Copilot organization custom instructions are generally available](https://github.blog/changelog/2026-04-02-copilot-organization-custom-instructions-are-generally-available/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — Define a shared set of AI instructions that apply by default across all Copilot surfaces—Chat, code review, and the cloud agent—org-wide. A centralized mechanism to enforce coding standards and standardize AI behavior consistently across every developer seat.

---

## 🛠️ Developer Workflow Improvements

Day-to-day friction reduction that compounds across a large organization.

- 🚢 [New pull requests dashboard is in public preview](https://github.blog/changelog/2026-03-26-new-pull-requests-dashboard-is-in-public-preview/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — A prioritized PR inbox, saved custom views with advanced AND/OR filtering across repos and orgs, and Copilot-authored PRs included in "Authored by me." A unified hub for managing all pull requests efficiently.

- 🚢 [View code and comments side-by-side in pull request Files changed page](https://github.blog/changelog/2026-03-19-view-code-and-comments-side-by-side-in-pull-request-files-changed-page/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — Docked panels keep comments, PR overview, merge status, and security alerts visible alongside code diffs, eliminating tab-switching during review. A meaningful reduction in review friction.

- 🚢 [Ask @copilot to resolve merge conflicts on pull requests](https://github.blog/changelog/2026-03-26-ask-copilot-to-resolve-merge-conflicts-on-pull-requests/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — @mention Copilot in a PR comment to have the cloud agent automatically resolve merge conflicts and push the resolution. Reduces manual effort and context-switching in fast-moving codebases.

- 📄 [Researching with GitHub Copilot CLI](https://docs.github.com/en/copilot/concepts/agents/copilot-cli/research) — Copilot CLI's research mode produces durable, shareable research artifacts by autonomously analyzing codebases and repositories. Faster onboarding, better technical decision-making, and documented technical analysis—not just ephemeral chat answers.

- 📄 [Connecting Copilot CLI to VS Code](https://docs.github.com/en/copilot/how-tos/copilot-cli/connecting-vs-code/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — Bridges CLI speed with VS Code's visual tooling: editor selections become prompt context, proposed changes appear as visual diffs, and CLI sessions persist in the integrated terminal.

---

## 🎓 Training & Enablement Resources

Tools to bring developers up to speed faster—especially for teams new to AI-assisted development.

- 📢 [GitHub for Beginners: Getting started with GitHub Actions](https://github.blog/developer-skills/github/github-for-beginners-getting-started-with-github-actions/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) (8:03) — A practical onboarding resource for teams upskilling developers new to CI/CD automation. Covers triggers, jobs, and runners in a hands-on format.

- 🙋‍♂️ [Work with Workflow Artifacts (GitHub Skills)](https://github.com/skills/workflow-artifacts) — Hands-on exercise: upload, preview, download, and reuse workflow artifacts. Build once and reuse across deployment jobs.

- 🙋‍♂️ [Create and use reusable workflows (GitHub Skills)](https://github.com/skills/reusable-workflows) — Hands-on exercise: create reusable GitHub Actions workflows and call them from other workflows. Understand how permissions work across caller and reusable workflows.

- 📺 [Getting started with GitHub Copilot CLI | Tutorial for beginners](https://youtu.be/BDxRhhs36ns?si=5U9joPl9S-T4tvFB) (3:48) — Install, authenticate, and run first prompts from the terminal. A good starting point for teams introducing Copilot CLI.

- 📺 [Plan, delegate, and review with Copilot CLI](https://youtu.be/v8dr7QcIiLU?si=T_3ffGzL2LI4ywTZ) (4:59) — How to use the plan and delegate commands to create a draft PR while you work on other tasks, then review changes in the terminal. Illustrates the "delegate and review" workflow pattern.

---

## 🔭 Looking Further Ahead (Research & Future Direction)

- 🥼 [GitHub Next Repo Mind](https://githubnext.com/projects/repo-mind/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — A research prototype combining semantic search with a hierarchical graph of code declarations and documentation, giving developers and AI agents a holistic understanding of large repositories. Points toward AI-native code navigation that could dramatically reduce onboarding time. *(Research prototype—not yet a product.)*

- 📢 [The era of "AI as text" is over. Execution is the new interface.](https://github.blog/ai-and-ml/github-copilot/the-era-of-ai-as-text-is-over-execution-is-the-new-interface/?utm_source=EntRoundup&utm_medium=Newsletter&utm_campaign=EntRoundup_2604) — The Copilot SDK introduces a programmable execution layer for embedding agentic workflows—planning, tool invocation, file modification, error recovery—directly inside your own applications. A signal of where enterprise developer tooling is heading.

---

*Source: [GitHub Monthly Enterprise Roundup, April 2026](https://gh.io/mer) | Curated for the role of increasing developer productivity across the organization.*
