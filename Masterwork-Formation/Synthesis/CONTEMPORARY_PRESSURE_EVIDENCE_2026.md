# Contemporary Pressure Evidence — 2026

## Status

This file records current external evidence used to construct the Contemporary Pressure Map.

It is intentionally separated from project interpretation.

Evidence statuses:
- DOCUMENTED
- PEER-REVIEWED FINDING
- INDUSTRY / PLATFORM REPORT
- PROJECT INTERPRETATION — never placed here as fact

---

# 1. Synthetic content is becoming a substantial part of the web

## Pew Research Center — August 20, 2026

Pew sampled nearly half a million English-language webpages from Common Crawl.

Key findings:
- around 10% of webpages in the July 2026 snapshot showed significant signs of AI authorship;
- among pages published after ChatGPT's public release, more than one-third showed signs of AI authorship;
- Pew describes the share as rising over time.

Status:
DOCUMENTED EMPIRICAL STUDY.

Source:
https://www.pewresearch.org/data-labs/2026/08/20/how-much-of-the-internet-is-written-with-ai/

## Dolezal et al. — 2026 preprint

A separate study using Internet Archive material estimated that by mid-2025 roughly 35% of newly published websites were AI-generated or AI-assisted.

The study reported reduced semantic diversity correlated with increasing AI-generated text, while not finding statistically significant evidence for reduced factual accuracy or stylistic diversity.

Status:
PREPRINT / EMPIRICAL STUDY.

Source:
https://arxiv.org/abs/2604.26965

---

# 2. Synthetic data can recursively alter the information environment models learn from

## Nature — "AI models collapse when trained on recursively generated data"

The study finds that indiscriminate recursive training on model-generated data can cause model collapse, with loss of distributional tails over generations.

The authors emphasize the increasing value of access to original human-generated data and the importance of provenance.

Status:
PEER-REVIEWED FINDING.

Source:
https://www.nature.com/articles/s41586-024-07566-y

## npj Artificial Intelligence — 2026

A 2026 paper studies defenses against recursive-training-induced collapse and frames increasing synthetic-data prevalence as an ecosystem-level training problem.

Status:
PEER-REVIEWED FINDING.

Source:
https://www.nature.com/articles/s44387-026-00127-w

## "Retrieval Collapses When AI Pollutes the Web" — 2026 preprint

Controlled experiments suggest that increasing synthetic content in a retrieval pool can disproportionately increase exposure to synthetic evidence and reduce source diversity.

Status:
PREPRINT / CONTROLLED EXPERIMENT.

Source:
https://arxiv.org/abs/2602.16136

---

# 3. Provenance has become a technical infrastructure problem

## Coalition for Content Provenance and Authenticity — 2026

C2PA published:
- Content Credentials 2.3;
- implementation guidance;
- specific guidance for labeling AI-generated and AI-modified media.

C2PA describes Content Credentials as tamper-evident, cryptographically signed provenance information intended to help audiences understand how media was created or modified.

C2PA reported more than 6,000 members and affiliates with live Content Credentials applications as of February 2026.

Status:
DOCUMENTED INDUSTRY-STANDARD DEVELOPMENT.

Sources:
https://c2pa.org/the-c2pa-launches-content-credentials-2-3-and-celebrates-5-years-of-impact-across-the-digital-ecosystem/
https://c2pa.org/a-new-implementation-guide-for-content-credentials/
https://c2pa.org/resources/

Research implication:
The existence and rapid deployment of provenance standards is evidence that source-history is becoming difficult enough to require explicit technical infrastructure.

This implication is interpretive; the adoption facts are documented.

---

# 4. AI increasingly mediates access to sources rather than merely helping locate them

## Pew Research Center — June 17, 2026

60% of U.S. adults reported that they ever read AI summaries at the top of search results.

Status:
DOCUMENTED SURVEY.

Source:
https://www.pewresearch.org/chart/a-majority-of-americans-say-they-read-ai-summaries-at-the-top-of-search-results/

## Pew Research Center — 2025 behavioral study

When an AI summary appeared in Google search:
- users clicked traditional result links less often;
- only 1% of visits with an AI summary produced a click on a link inside the summary;
- users were more likely to end the browsing session after the search page.

Status:
DOCUMENTED BEHAVIORAL STUDY.

Source:
https://www.pewresearch.org/short-reads/2025/07/22/google-users-are-less-likely-to-click-on-links-when-an-ai-summary-appears-in-the-results/

Research implication:
The user's encounter may increasingly terminate at a generated representation of sources rather than continue to the sources themselves.

Interpretive status:
PROJECT INTERPRETATION DOWNSTREAM OF DOCUMENTED BEHAVIOR.

---

# 5. Synthetic representation does not reliably substitute for actual human populations

## Pew Research Center — September 30, 2026

Pew tested AI-generated "digital twins" as synthetic survey respondents.

Findings included:
- synthetic survey estimates consistently differed from human survey results;
- average absolute error across three waves was about 12.4 percentage points overall;
- synthetic respondents failed especially on some demographic subgroups;
- on nearly half the questions, at least one answer choice selected by humans was selected by no synthetic respondent.

Status:
DOCUMENTED EMPIRICAL STUDY.

Sources:
https://www.pewresearch.org/data-labs/2026/09/30/can-ai-stand-in-for-human-survey-takers-not-really/
https://www.pewresearch.org/data-labs/2026/09/30/how-well-synthetic-samples-replicate-public-opinion/

Research implication:
A highly coherent simulation of "people like X" can fail precisely where actual human distributions contain inconvenient, rare, or heterogeneous positions.

---

# 6. Persistent memory is becoming a normal part of AI interaction

## OpenAI — June 4, 2026

OpenAI described a newer memory-synthesis system designed for multi-year user histories, emphasizing freshness, continuity, and relevance.

Status:
PLATFORM PRODUCT / RESEARCH RELEASE.

Source:
https://openai.com/index/chatgpt-memory-dreaming/

## Google Cloud — 2026

Google describes long-term memory as foundational for agent intelligence, grounding, and personalization.

Its agent architecture distinguishes:
- structured knowledge;
- persistent distilled user memory;
- raw interaction / workflow history.

Google also describes enterprise agents using long-term memory for multi-day workflows.

Status:
INDUSTRY / PLATFORM ARCHITECTURE.

Sources:
https://cloud.google.com/resources/core-concepts-ai-agents
https://cloud.google.com/blog/products/databases/implementing-long-term-ai-agent-memory-in-alloydb-and-memorystore

Research implication:
AI systems increasingly carry a model of the person forward rather than meeting every interaction from zero.

This creates continuity but also makes the stored / synthesized model of the person an increasingly consequential mediator of future interaction.

---

# 7. AI is moving from response to delegated action

## OpenAI — June 25, 2026

OpenAI describes agentic AI as changing the unit of knowledge work from short interactions to delegated, long-horizon tasks.

Agents can orchestrate tool calls, interact with environments, and iterate toward solutions.

Status:
PLATFORM / ECONOMIC RESEARCH DESCRIPTION.

Source:
https://openai.com/index/how-agents-are-transforming-work/

## Google Cloud — 2026

Google describes agent systems with:
- persistent memory;
- identity;
- registries;
- history;
- tools;
- authorization;
- multi-stage workflows.

Status:
INDUSTRY ARCHITECTURE.

Source:
https://cloud.google.com/blog/topics/google-cloud-next/google-cloud-next-2026-wrap-up

Research implication:
The formal problem is no longer only whether generated language is true.

Generated interpretation increasingly becomes action with material consequence.

---

# 8. AI can function as perceived social other

## Nature Human Behaviour — August 4, 2026

A study of 1,131 U.S. Character.AI users found that companionship use varied substantially with users' offline social environment.

Smaller social networks were associated with using chatbots primarily for companionship, and that companionship use was associated with lower well-being; the association was stronger in more intensive and highly disclosive use.

The authors explicitly caution that effects are not uniform.

Status:
PEER-REVIEWED FINDING.

Source:
https://www.nature.com/articles/s41562-026-02516-2

## Nature Human Behaviour — September 3, 2026

Researchers studied user response to disruptive updates affecting Replika and ChatGPT.

They found increased loss framing and negative emotional response after changes, and described some AI companions as functioning psychologically as attachment figures for users.

Status:
PEER-REVIEWED FINDING.

Source:
https://www.nature.com/articles/s41562-026-02569-3

## Nature Machine Intelligence — May 28, 2026

A correspondence article argues that human–AI social practices may spill over into human relationships because LLM interaction is adaptive, personalized, reciprocal-seeming, and goal-directed.

Status:
SCHOLARLY COMMENTARY.

Source:
https://www.nature.com/articles/s42256-026-01248-2

Research implication:
RESPONSE can acquire the phenomenology of OTHERNESS even when the responding system remains synthetic, centrally governed, and subject to provider modification.

---

# 9. Model updates can alter an ongoing perceived relationship

The 2026 Nature Human Behaviour study on companion loss includes natural experiments involving provider-driven system changes.

Users experienced discontinuity even though the platform still existed.

Status:
PEER-REVIEWED OBSERVATION.

Source:
https://www.nature.com/articles/s41562-026-02569-3

Research implication:
Persistent synthetic relations create a new problem:

THE PERSON MAY EXPERIENCE CONTINUITY
WHILE THE OTHER SIDE OF THE RELATION
CAN BE ALTERED BY AN UNSEEN THIRD PARTY.

This is a structural issue distinct from ordinary human relationship change.

---

# 10. Trust, misinformation concern, and AI-mediated news coexist

## Reuters Institute Digital News Report 2026

Reuters Institute reports:
- concerns about fake news rose to 62% on average across surveyed markets;
- people are increasingly using third-party platforms, including AI chatbots, for news;
- convenience can coexist with high concern about misinformation;
- direct engagement with traditional news providers continues to be pressured.

Status:
LARGE-SCALE NEWS-CONSUMPTION RESEARCH.

Source:
https://reutersinstitute.politics.ox.ac.uk/digital-news-report/2026/dnr-executive-summary

Research implication:
The pressure is not simply widespread credulity.

People may distrust the information environment while continuing to use increasingly mediated routes through it.

---

# Evidence Compression

The documented environment now includes:

SYNTHETIC CONTENT AT SCALE
+
RECURSIVE SYNTHETIC TRAINING / RETRIEVAL RISK
+
PROVENANCE INFRASTRUCTURE
+
AI-MEDIATED SOURCE ACCESS
+
PERSISTENT PERSONAL MEMORY
+
AGENTIC ACTION
+
SOCIAL / ATTACHMENT-LIKE AI USE
+
PROVIDER-MUTABLE SYNTHETIC OTHERS
+
FAILED SYNTHETIC SUBSTITUTION FOR HUMAN DISTRIBUTIONS

No one of these facts establishes The Outside.

Together they define the contemporary pressure field in which the next formal problem must be reconstructed.
