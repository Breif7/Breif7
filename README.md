# Hi, I'm Miguel 👋

I build serverless systems on AWS, from the Terraform to the dashboard, and I automate content and data pipelines with Python. I'm currently doing an MSc in Artificial Intelligence (UNIR), and I apply every course to a real project, measured against a baseline.

*Construyo sistemas serverless en AWS y automatizo pipelines con Python. Cursando la Maestría en IA (UNIR).*

## 🧰 Tools I made and use

| Project | What it does | Proof |
| --- | --- | --- |
| [**blender-shard-render**](https://github.com/Breif7/blender-shard-render) | Renders Blender animations with parallel workers, verifies every frame, re-renders broken ones and resumes after crashes | Cut a long episode from 2 h 51 min to 1 h 55 min; [benchmark + case study](https://github.com/Breif7/blender-shard-render/blob/main/docs/case-study.md) |
| [**cfdi-tools**](https://github.com/Breif7/cfdi-tools) | Mexican SAT invoices (CFDI XML) → CSV, expense categories, monthly ISR (RESICO) and IVA estimate | 70 % → 100 % categorization with one month of user rules; [case study](https://github.com/Breif7/cfdi-tools/blob/main/docs/case-study.md) |
| [**bibcheck**](https://github.com/Breif7/bibcheck) | Lints LaTeX citations against BibTeX: CLI, pre-commit hook and GitHub Action | Tested on real thesis templates: 21 noisy findings removed, the real error kept; [case study](https://github.com/Breif7/bibcheck/blob/main/docs/case-study.md) |
| [**terraform-aws-security-baseline**](https://github.com/Breif7/terraform-aws-security-baseline) | Org-wide GuardDuty + Security Hub, KMS-encrypted alerts and opt-in auto-remediation of leaked IAM keys | `terraform test` with mocked providers, 0 Checkov failures; [case study](https://github.com/Breif7/terraform-aws-security-baseline/blob/main/docs/case-study.md) |

Every repo above has tests in CI and a case study written as a loop: measure → change → measure again, including the hypotheses that turned out wrong.

## 🏗️ Other things I've built

- **[LifeOS](https://github.com/Breif7/LifeOS):** my personal operating system. A Python engine, Google Sheets finance sync and a local AI assistant (Ollama) that logs habits and spending from plain text. The public repo is an early snapshot with 28 tests; my private working version has 380+.
- **[MSc in AI · applied portfolio](https://github.com/Breif7/maestria-ia-portfolio):** one project per course, each measured against a trivial baseline:
  - a 3D-print time estimator: error 0.62 h → 0.16 h;
  - anomaly detection on spending;
  - a STRIPS planner;
  - a neural net from scratch;
  - an ACT-R spaced-repetition model;
  - PERT/Monte Carlo scheduling;
  - demand forecasting with backtests.
- **AI apps (Next.js + Supabase):** [receipt-accountant](https://github.com/Breif7/receipt-accountant), [second-brain-ai](https://github.com/Breif7/second-brain-ai), [personal-library](https://github.com/Breif7/personal-library), [day-board](https://github.com/Breif7/day-board), [daily-review-assistant](https://github.com/Breif7/daily-review-assistant).
- **Private work:**
  - serverless point-of-sale systems: Next.js + Lambda + DynamoDB + Cognito, all in Terraform;
  - AWS security labs: IAM least privilege, network firewall + WAF, centralized multi-account logging;
  - an automated video pipeline: Blender + TTS + AI script QA;
  - a GIS master's thesis in QGIS.

## 🛠️ Stack

| | |
| --- | --- |
| **Cloud / IaC** | AWS (Lambda, DynamoDB, API Gateway, Cognito, CloudFront, S3, IAM, GuardDuty, Security Hub) · Terraform · CDK · SAM · Amplify |
| **Backend** | Python, Node.js / TypeScript |
| **Frontend** | Next.js, React, Tailwind |
| **ML / AI** | scikit-learn, NumPy, pandas, Ollama, Claude API, embeddings + RAG |
| **Other** | Blender scripting, QGIS, Docker, GitHub Actions |

## 📫 Contact

- 💼 [LinkedIn](https://www.linkedin.com/in/miguel-martinez-ortega/)
