Mira: AI-Powered Project Intelligence Assistant

Capstone project for Applied Agentic AI for PMs/TPMs, built with Langflow (multi-agent workflow) and Langfuse (observability).

Mira turns raw project data into documents a PM/TPM can use right away: project plans, risk assessments, weekly status reports, milestone and deadline alerts, and stakeholder update emails. It is grounded in the ABCDE Ltd. AI Adoption Project data (project description, task board, timeline and risk register). When a request is too vague, Mira asks clarifying questions instead of making things up.

Architecture

Repository contents

Mira.json	- The Langflow flow. Import this into Langflow to run Mira.
architecture.png	- Architecture diagram: agents, orchestration and data flow
langflow1.png, langflow2.png	- Screenshots of Mira in Langflow
trace-54a0dbbbdc5cf3bd32d48e16470baa71.json	- A Langfuse trace exported from a Mira run (spans per component, LLM generations, tokens, cost, latency)
Mira_Capstone_Submission_Q1-Q4.docx	- Written submission: Q1 Ideation, Q2 Build, Q3 Program Charter, Q4 Reflection, baseline results
README.md	- This file

Evaluation

Mira was tested against the 12 baseline inputs (T1–T12) from the problem statement. The metrics were:

route accuracy
share of "must contain" requirements met
grounding-validator pass rate
LLM-as-judge score (1–5)
latency
cost per request

Full results, the cost analysis and the evaluation strategy are in Mira_Capstone_Submission_Q1-Q4.docx.
Author

Abhinav · Applied Agentic AI for PMs/TPMs, Capstone, November 2026
