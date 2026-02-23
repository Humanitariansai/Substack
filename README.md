# Substack
Humanitarians AI Substacks 

# Humanitarians AI
**A 501(c)(3) nonprofit building open-source AI for social good.**

> *Learn AI by doing AI. Every project is a bridge between graduate students, international talent, and real-world impact.*

📧 info@humanitarians.ai | 🌐 [humanitarians.ai](https://humanitarians.ai) | 📺 [YouTube](https://www.youtube.com/@humanitariansai) | 👥 [Fellows Program](https://www.humanitarians.ai/fellows)

---

## Executive Summary

Humanitarians AI connects graduate students and emerging technologists with meaningful AI projects through a Fellows Program that doubles as a bridge for international students meeting OPT visa requirements. Led by Professor Nik Bear Brown (Northeastern University), the organization operates across civic accountability, public health, bioinformatics, education, marketing intelligence, music, and nonprofit storytelling. All projects are open-source, production-oriented, and grounded in the philosophy that the best way to learn AI is to build with it.

---

## Projects at a Glance

| Project | Substack | Focus |
|---|---|---|
| **80 Days to Stay** | [80daystostay.substack.com](https://80daystostay.substack.com/) | Agentic AI tools for OPT/H-1B job search transparency |
| **Boyle Project** | [boyleproject.substack.com](https://boyleproject.substack.com/) | Scientific notebook system using NotebookLM for reproducible research |
| **Branding & AI** | [brandingartificialintelligence.substack.com](https://brandingartificialintelligence.substack.com/) | Intelligent textbook for INFO 7375; contributions to the Madison Framework |
| **Dayhoff Project** | [dayhoffproject.substack.com](https://dayhoffproject.substack.com/) | Agent-based AI framework for bioinformatics and public health |
| **Humanitarians AI** | [humanitariansai.substack.com](https://humanitariansai.substack.com/) | Central hub for the 501(c)(3); project-based volunteer opportunities |
| **Learning Engineer** | [learningengineering.substack.com](https://learningengineering.substack.com/) | Engineering approaches to learning design and educational technology |
| **Lyrical Literacy** | [lyricalliteracyproject.substack.com](https://lyricalliteracyproject.substack.com/) | Neuroscience of singing applied to cognitive development and language learning |
| **Madison Project** | [madisonproject.substack.com](https://madisonproject.substack.com/) | Open-source agentic marketing and branding intelligence framework |
| **Medhavy** | [medhavy.substack.com](https://medhavy.substack.com/) | AI-powered distributed textbook platform with RAG and learner personas |
| **Musinique** | [musinique.substack.com](https://musinique.substack.com/) | Spotify curator intelligence database; music history and algorithm research |
| **Mycroft Project** | [mycroftproject.substack.com](https://mycroftproject.substack.com/) | Educational experiment using AI agents to analyze AI-sector investments |
| **Northeastern ISE** | [northeasternise.substack.com](https://northeasternise.substack.com/) | Collaborative hub for current students and recent Northeastern graduates |
| **Politics and AI** | [politicalai.substack.com](https://politicalai.substack.com/) | Data journalism and agentic AI for political transparency (B Wells platform) |
| **Popper Framework** | [popperskepticism.substack.com](https://popperskepticism.substack.com/) | Open-source computational skepticism and systematic AI validation |
| **RAMAN Effect** | [ramaneffectwpe.substack.com](https://ramaneffectwpe.substack.com/) | AI-enhanced wastewater-based epidemiology using Raman spectroscopy |
| **Wilkes** | [wilkesproject.substack.com](https://wilkesproject.substack.com/) | AI storytelling for nonprofits; bespoke narrative in the organization's own voice |
| **Zebonastic** | [zebonastic.substack.com](https://zebonastic.substack.com/) | AI-generated creative work and digital prompts for games and film |

---

---

# Appendix: Project Details (Alphabetical)

---

## 80 Days to Stay
**Substack:** [80daystostay.substack.com](https://80daystostay.substack.com/)
**GitHub:** [github.com/nikbearbrown/80-Days-to-Stay](https://github.com/nikbearbrown/80-Days-to-Stay)

Named after Phileas Fogg's famous wager, this project races against visa deadlines to connect international students with funded startups capable of sponsoring employment. The core insight: thousands of Series A/B companies desperately need talent but don't advertise visa sponsorship—often because they misunderstand OPT (which requires no immediate sponsorship and comes with a ~7.65% FICA payroll tax savings for employers).

**What it builds:** A searchable platform using SEC EDGAR Form D filings to identify funded startups ($5M+), cross-referenced against DOL LCA Disclosure Data and USCIS H-1B Employer Data Hub. LLM agents act as "Recruiting Experts" surfacing companies invisible on LinkedIn or Indeed.

**The problem by numbers:**
- 44.6% of international students employed after graduation vs. 62.1% of domestic peers
- International students apply to 2× as many jobs but receive 30% fewer offers
- ~90% of funded startups don't advertise "visa sponsorship" on job posts

**Stack:** Python, SEC EDGAR API, PostgreSQL (Supabase), FastAPI (Railway), React + Tailwind (Vercel) — ~$0/month in infrastructure costs.

**Timeline:** 80-day sprint. Week 1 MVP targets 300+ companies in Boston, SF, and NYC biotech.

---

## B Wells Platform
*(Housed under [Politics and AI](https://politicalai.substack.com/))*

Named after Ida B. Wells, who used systematic data collection to expose government complicity, the B Wells platform is a multi-agent AI system for political accountability. It tracks congressional contradictions, votes, and constitutional violations—building persistent, searchable records that create real costs for hypocrisy.

**Core capabilities:**
- Automated contradiction detection across voting records and public statements
- Visual timelines of position changes
- Conflict-of-interest surfacing
- Paltering detection (misleading through selective omission, not outright lies)

**Philosophy:** Traditional fact-checking fails because it's too slow and perceived as partisan. B Wells aims to be a neutral tool presenting verifiable facts without commentary—designed for the "exhausted majority" who see hypocrisy on both sides. Prevention through accountability: if contradictions have costs, fewer contradictions occur.

**Status:** Technical and philosophical spec complete (v1.0, January 2025). Launch site: bwells.org. Volunteer recruitment active.

---

## Boyle Project (The Boyle System)
**Substack:** [boyleproject.substack.com](https://boyleproject.substack.com/)

Named after Robert Boyle, who formalized scientific note-taking as a disciplined practice—insisting that knowledge only counts if it is traceable, repeatable, and intelligible to others. The Boyle System modernizes that principle using NotebookLM as an active cognitive partner rather than a passive archive.

**Three roles NotebookLM plays simultaneously:**
1. **Tutor** — teaches proper documentation by referencing degree requirements, project charters, and the Boyle Principles
2. **Critic** — challenges vague or incomplete entries ("This is an outcome, not a method.")
3. **Operational Guide** — treats cloud credentials, API keys, and environment variables as first-class research artifacts, not administrative noise

**Core insight:** In cloud-based research, you cannot reproduce results without reproducing access. Environment configuration is experimental context.

**How volunteers use it:** Rather than reporting hours, fellows interrogate their own work ("Based on the project charter and Boyle's principles, is this log reproducible?"). Auditing and compliance emerge naturally as byproducts of good research practice—not as goals. The constraint that you must document to get AI feedback creates the discipline.

---

## Branding & AI (INFO 7375)
**Substack:** [brandingartificialintelligence.substack.com](https://brandingartificialintelligence.substack.com/)
**GitHub:** [github.com/Humanitariansai/Madison](https://github.com/Humanitariansai/Madison)

An intelligent textbook for Northeastern University's INFO 7375 course, co-taught by Professor Nik Bear Brown and Nina Harris (40+ years at Publicis, Saatchi & Saatchi, McCann Erickson, and Charles Schwab). Students build two parallel assets: a technical contribution to the open-source Madison Framework and a complete professional brand portfolio.

**Course philosophy:** "Ship it, then make it better." 80% of success is shipping something that works.

**What students build with Madison:**
- Social media monitoring and analysis tools
- Automated content generation systems
- Competitor intelligence platforms
- Sentiment analysis dashboards
- Synthetic persona generators
- Campaign performance trackers

**Structure:** 12 modules from Foundation Setup through Final Portfolio, covering PRDs, data pipelines, n8n workflows, brand identity systems, and published articles. Each chapter produces a tangible portfolio asset.

---

## Dayhoff Project
**Substack:** [dayhoffproject.substack.com](https://dayhoffproject.substack.com/)
**GitHub:** [github.com/humanitarians-ai/dayhoff](https://github.com/humanitarians-ai/dayhoff)

Named after Margaret Belle Dayhoff, the pioneer of bioinformatics, this open-source agent-based framework orchestrates specialized AI agents for computational biology, epidemiology, and public health. Led by Professor Nik Bear Brown.

**Six agent categories:**
1. Genomic Analysis Agents — sequence processing, pattern identification
2. Epidemiological Agents — disease spread tracking and intervention modeling
3. Clinical Intelligence Agents — medical literature and treatment outcome analysis
4. Molecular Modeling Agents — protein folding, drug interactions, molecular dynamics
5. Biostatistical Agents — rigorous statistical analysis of biological data
6. Public Health Monitoring Agents — population health metrics and social determinants

**Active projects:**
- **PredictaBio** — generative AI for novel protein design with specific functional properties
- **RAMAN Effect** — AI-enhanced wastewater-based epidemiology using Surface-Enhanced Raman Spectroscopy (see separate entry)

**Tools used:** GPT-4o, LLaMA, CNNs, Transformers, PAM matrices, Neo4j, PyMOL, D3.js, agent-based modeling, molecular dynamics simulation.

---

## Humanitarians AI (Central Hub)
**Substack:** [humanitariansai.substack.com](https://humanitariansai.substack.com/)
**Website:** [humanitarians.ai](https://humanitarians.ai)

The 501(c)(3) nonprofit that houses all projects listed in this README. Operates as a bridge program connecting graduate students (including international students on OPT visas) with companies and causes that need AI solutions. 150+ active volunteer contributors.

**Fellows Program:** Project-based volunteer opportunities across all Humanitarians AI initiatives. No experience required—commitment and curiosity are the prerequisites. Fellows apply the Boyle System for documentation and use the Northeastern ISE hub for cross-cohort collaboration.

---

## Learning Engineer
**Substack:** [learningengineering.substack.com](https://learningengineering.substack.com/)

Applies engineering principles to learning design and educational technology. Grounded in Herbert Simon's 1967 vision of "learning engineering" — the discipline of using computer science + data science + learning science to create evidence-based learning systems that can be continuously iterated upon.

**Key approaches:**
- A/B testing for instructional effectiveness
- Educational data mining from student interaction with ed tech platforms
- Platform instrumentation for teachers and students
- Dataset generation to enable learning science research

Distinct from ed tech: the goal is improved student outcomes, not technology for its own sake. Sometimes the best intervention is better in-person instruction informed by data.

---

## Lyrical Literacy
**Substack:** [lyricalliteracyproject.substack.com](https://lyricalliteracyproject.substack.com/)
**GitHub:** [github.com/nikbearbrown/Lyrical-Literacy](https://github.com/nikbearbrown/Lyrical-Literacy/tree/main/Research)

Music is exercise for the brain. Lyrical Literacy harnesses AI to enhance cognitive and language development through singing, grounded in neuroscience research showing music engages more brain regions simultaneously than almost any other human activity. The project was developed by Humanitarians AI.

**What it builds:** AI-generated songbooks, interactive storybooks, and audiobooks personalized to individual learning objectives, cultural contexts, and developmental needs using tools like Suno and Udio.

**Research areas:** phonological awareness, second language pronunciation, social-emotional learning, executive function, memory formation, neural plasticity.

**Applications:** early literacy classrooms, multilingual education, speech therapy, home learning, community programs in underserved areas.

**Published research papers (7):** covering the neuroscience of singing, music and mathematical cognition, music training and second language acquisition, social-emotional barriers to learning, and neural/cognitive effects of musical training across the lifespan.

---

## Madison Project (Madison Avenue)
**Substack:** [madisonproject.substack.com](https://madisonproject.substack.com/)
**GitHub:** [github.com/humanitariansai/madison](https://github.com/humanitariansai/madison)

An open-source, agent-based AI marketing intelligence framework designed to transform branding, marketing, and advertising through five collaborative agent layers.

**Five agent layers:**
1. **Intelligence Agents** — market dynamics, reputation monitoring, trend analysis
2. **Content Agents** — creation, optimization, and multi-platform distribution
3. **Research Agents** — survey analysis, synthetic persona development
4. **Experience Agents** — AI concierge systems, customer journey transformation
5. **Performance Agents** — multi-armed bandit optimization, predictive analytics

**Key integrations:**
- **Bellman Framework** — brings reinforcement learning (Thompson sampling, value functions, RL-powered customer journeys) to marketing optimization
- **Popper Framework** — applies computational skepticism and causal validation to marketing claims, detecting bias and confounding variables before they drive strategy

**Projects built on Madison:** Brand Voice Personalization, MarketMind Research, AI Concierge Systems, multi-channel automation workflows.

---

## Medhavy
**Substack:** [medhavy.substack.com](https://medhavy.substack.com/)

A distributed, AI-native textbook ecosystem with centralized administrative control and decentralized content delivery. Each textbook is a specialized content node running a two-stage AI pipeline (RAG) grounded strictly in course-specific materials.

**Three-tier architecture:**
1. **External Services** — Clerk (auth), OpenAI (GPT-4), Orama Cloud (search)
2. **Medhavy Hub** — token minting/verification, user management, textbook registry, analytics
3. **Textbook Applications** — Physics textbook, Cancer research textbook, and a template for new instances

**Key features:**
- TEXTBOOK_ONLY mode: AI forbidden from using external knowledge; must cite specific textbook sources
- Learner Personas: composite prompting system that combines instructor persona (style/tone) with learner persona (e.g., "Pragmatic Professional" vs. "Aspiring Scholar") stored in Clerk user metadata
- Database-less architecture: all persistent state stored in Clerk's publicMetadata

**Active development:** credential security hardening, verification caching, parity between textbook instances, learner persona shells.

---

## Musinique
**Substack:** [musinique.substack.com](https://musinique.substack.com/)
**Website:** [musinique.com](https://musinique.com)

Builds AI tools for indie musicians, poets, and songwriters. Core product: the **Musinique Curator Intelligence Database** — 25,000+ Spotify playlist curators analyzed to distinguish real human taste from bot farms and pay-for-placement scams.

**Database structure (three relational files):**
- **The Playlisters** — curator names, contact methods (emails, Instagram, submission forms), total reach, Focus Score
- **The Playlists** — per-playlist analytics including genre mapping, track count, last updated, and Musinique Focus Score (0–100)
- **The Churn** — behavioral time-series analysis detecting paid-placement patterns (songs dropping off at exactly 7-day intervals = red flag)

**The Musinique Focus Score** uses entropy statistics: a playlist covering 14+ primary genres is a statistical outlier (top 7% of chaos)—a strong signal of bot farms accepting payment from anyone. A focused playlist with 3–6 genres scores high, indicating real human curation.

**Sweet spot for indie pitching:** playlists with avg. artist popularity 20–60. Above 80 = Top 40 only; below 10 = potential bot-generated artist farm.

---

## Mycroft Project (Finance)
**Substack:** [mycroftproject.substack.com](https://mycroftproject.substack.com/)

Named after Sherlock Holmes's elder brother—superior analytical ability, preferring to orchestrate from behind the scenes—Mycroft is an educational experiment in AI-powered investment intelligence, specifically focused on the AI sector itself. Tagline: *"Using AI to Invest in AI."*

**Agent categories:**
- **Analytical Agents** — Research, Verification, Comparative Analysis across AI subsectors (semiconductors, cloud infrastructure, model developers, enterprise apps, vertical solutions)
- **Portfolio Agents** — Diversification, Risk Management, Rebalancing
- **Advisory Agents** — Conversational Financial Advisors, Goal-Setting, Educational
- **Intelligence Agents** — News Monitoring, Social Sentiment, Financial Report analysis, Regulatory Monitoring

**The Mycroft Orchestration Layer** coordinates cross-agent validation, dynamic task allocation, pattern recognition, decision optimization, and continuous learning from prediction accuracy.

**Important framing:** This is an explicitly experimental, educational project. It does not claim to have solved investment intelligence—it is building to discover what approaches actually work in practice.

---

## Northeastern ISE
**Substack:** [northeasternise.substack.com](https://northeasternise.substack.com/)

A collaborative hub where current Northeastern University students and recent graduates work together on shared projects and frameworks across the Humanitarians AI ecosystem. Operates as the student chapter of Humanitarians AI, organized under the AI Skunkworks model.

**Mission (AI Skunkworks):** Advance research and innovation in AI through mentorship, professional development, and ethical stewardship. Guide students through real-time industry challenges, build competitive excellence through portfolio work, and promote responsible use of technology.

**Role in the ecosystem:** Connects student contributors to active projects (80 Days to Stay, Dayhoff, Medhavy, Wilkes, etc.), provides structure for Fellows Program participation, and serves as an onboarding point for new contributors.

---

## Popper Framework (Computational Skepticism)
**Substack:** [popperskepticism.substack.com](https://popperskepticism.substack.com/)
**GitHub:** [github.com/humanitariansAI/popper](https://github.com/humanitariansAI/popper)

Named after Karl Popper, whose principle of falsifiability revolutionized scientific methodology. The Popper Framework is an open-source platform for systematic AI validation. Rather than claiming models are "correct," it embraces the scientific method: rigorously examining evidence both for and against AI systems. Tagline: *"Evidence for and against."*

**Ten agent classes:**
1. **Data Validation Agents** — data integrity, EDA, lineage, sampling, consistency
2. **Bias Detection Agents** — algorithmic fairness, representation, historical, cognitive, power structure
3. **Explainability Agents** — SHAP, LIME, counterfactual explanations, concept activation
4. **Probabilistic Reasoning Agents** — calibration, Bayesian reasoning, uncertainty quantification, ensemble methods
5. **Adversarial Agents** — input perturbation, concept shift, deception detection, defense mechanisms
6. **RL Validation Agents** — reward hacking detection, ethical evaluation (Kantian and utilitarian), determinism analysis
7. **Visualization & Communication Agents** — perceptual transparency, misleading visualization detection, accessibility
8. **Falsification Agents** — counterfactual generation, boundary probing, contradiction search, null hypothesis testing
9. **Graph-Based Reasoning Agents** — knowledge graphs, ontology validation, network resilience
10. **Causal Inference Agents** — DAG construction, d-separation, confounding detection, IPTW, sensitivity analysis

**Philosophical foundations** draw on Popper, Hume, Wittgenstein, Plato, Kant, and Nietzsche—each agent class is grounded in a specific epistemological tradition.

**Integration:** Popper is a core validation layer for both the Madison (marketing) and Dayhoff (bioinformatics) frameworks.

---

## RAMAN Effect Project
**Substack:** [ramaneffectwpe.substack.com](https://ramaneffectwpe.substack.com/)
*(Also housed under the Dayhoff Framework)*

Revolutionizes public health surveillance by integrating Surface-Enhanced Raman Spectroscopy (SERS), Wastewater-Based Epidemiology (WBE), and AI/ML. SERS enhances Raman scattering by factors of 10⁶ to 10¹⁴ through metallic nanostructures, enabling detection of biomarkers at ultra-low concentrations—sometimes single-molecule levels.

**What WBE enables:** Non-invasive, population-level health monitoring without individual testing. Human excreta contains biomarkers for disease, drug use, AMR markers, and environmental contaminants—all detectable from community wastewater.

**Applications demonstrated:**
- COVID-19 surveillance (deployed in 58+ countries)
- Illicit drug monitoring with real-time geographic pattern detection
- Antimicrobial resistance tracking
- Environmental contaminant and heavy metal exposure assessment

**ML approaches used:** CNNs (92–96% accuracy for pathogen identification), Random Forest (drug metabolite quantification), SVM (AMR anomaly detection), ensemble methods for multi-city deployment.

**Research roadmap:** Short-term standardization of protocols → medium-term real-time monitoring systems → long-term global interconnected surveillance network with early warning coordination.

---

## Wilkes (AI Storytelling for Nonprofits)
**Substack:** [wilkesproject.substack.com](https://wilkesproject.substack.com/)
**Live pilot:** [homesofhopeindia.substack.com](https://homesofhopeindia.substack.com/)
**Contact:** bear@humanitarians.ai (subject: "Wilkes Beta")

Nonprofits doing extraordinary work forfeit 23–33% of potential donor revenue annually—not from lack of mission, but from lack of time to tell their story. Wilkes is a managed AI writing service that converts raw field material (footage, transcripts, field notes, annual reports) into publication-ready content written in the organization's own voice.

**How it works:** Before writing a single word, the system is configured specifically for each organization—learning their mission, people, language, history, and what they would never say. Multiple AI agents work in concert: one understands brand voice, one structures narrative, one formats for platform. They translate, not invent. Nothing is fabricated; the story library won't allow it.

**Five output formats:**
| Format | Description |
|---|---|
| Profile | New Yorker-style intimate portrait of a person served or serving |
| Documentary Arc | Observational narrative following a program or field journey |
| Social Entrepreneur Piece | The encounter, the scale, the ask—built for donor audiences |
| Literary Review | Response to a book or report relevant to the organization's mission |
| YouTube Package | Title, description, and hashtag set for every video in the pipeline |

**Also includes:** The Wilkes variant of the Madison Pitch Framework, adapted for nonprofits—replacing startup equity framing with mission clarity, program proof, donor economics, and partnership asks.

**Status:** Live. First article published for Homes of Hope India as of February 2026. First five nonprofit partners are free.

---

## Zebonastic
**Substack:** [zebonastic.substack.com](https://zebonastic.substack.com/)

Creates digital prompts and AI-generated creative work specifically for games and film. Serves creative technologists, game designers, and filmmakers looking to accelerate concept development and world-building with AI tools.

---

*Last updated: February 2026 | License: MIT | Contributions welcome across all projects*
