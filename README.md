# Mat Niznik

Applied AI engineer in Long Beach, CA. I put AI into real workflows and own the result: the model takes the first pass at scale, tests sit behind it, and a person makes the calls that carry real stakes.

Ten years shipping web and mobile in TypeScript, React, React Native, Node.js, Python, Flask, Django, PostgreSQL and AWS. I also teach programming at Bethesda University of California. Open to Forward Deployed and Applied AI engineering roles.

## Projects

| Repo | What it shows |
| --- | --- |
| [rag.irs.mniznik](https://github.com/mattniznik/rag.irs.mniznik) | Answers U.S. tax questions from 11 IRS publications and checks every quote word for word against its source before showing it, or says "not found". Hybrid search, Claude, a 150-question evaluation with a CI gate. [Live demo](https://rag.irs.mniznik.com) that shows how each answer was made. |
| [recall-desk.mniznik](https://github.com/mattniznik/recall-desk.mniznik) | A support agent for a fictional auto parts store. Claude answers recall, complaint, safety-rating and parts questions from NHTSA's public data with seven tools, and six code rules check every answer before a customer sees it. A 50-case evaluation, CI, and AWS Lambda behind CloudFront. [Live demo](https://recall-desk.mniznik.com) with a system map that lights up each step of a real run. |
| [ledger-desk.mniznik](https://github.com/mattniznik/ledger-desk.mniznik) | The accounts-payable desk of a fictional coffee roastery. Claude reads each supplier bill with the line every key field came from and looks into the bills that do not match. Code checks each bill against the order, the delivery, paid bills and bank details, and every approval is a signature the books verify. A LangGraph workflow, Postgres row-level security, a 50-bill evaluation and CI, on Microsoft Azure (Container Apps, Database for PostgreSQL, Key Vault, Static Web Apps) set up with Terraform. [Live demo](https://ledger-desk.mniznik.com) with a walkthrough of a morning in accounts payable. |
| [ai-rubric-grader](https://github.com/mattniznik/ai-rubric-grader) | Claude grades a submission against a rubric under a strict JSON contract. Every grade stays a draft until a person approves it. |
| [agent-lanes](https://github.com/mattniznik/agent-lanes) | Rules that keep unattended AI agent runs safe with the Claude Code and Codex CLIs: fallback between them, deny rules, no task done twice, capped automatic fixes. |
| [job-radar](https://github.com/mattniznik/job-radar) | A config-driven job finder over public job boards. It sorts, scores and dedupes postings, flags the dealbreakers you list and stores every run in SQLite. |

Most of them come out of tools I use every week, with the personal parts taken out. They all have tests and CI.

## Elsewhere

- Portfolio: [mniznik.com](https://www.mniznik.com)
- LinkedIn: [linkedin.com/in/matniznik](https://www.linkedin.com/in/matniznik)
