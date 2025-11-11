# Medium Article Outline (Scaffold Only — Write in Your Own Words)

> Working title: **Agentic AQG for Math: A Data-Mining Pipeline for Controllable Difficulty**

## 1) Setup & Motivation
- Why AQG matters for ITS; need for controllable difficulty and clarity.
- Data-mining lens: labels from student performance; pipelines and curation.

## 2) Problem Formulation (Plain-English)
- Inputs: knowledge component (KC), example set, target difficulty.
- Output: question–answer pair aligned to KC + difficulty.
- Constraints: clarity, answerability; avoid trick questions.

## 3) Dataset & Labeling
- Problem Bodies (ASSISTments extension): percent-correct → empirical difficulty bins.
- Implications: real-world grounding; label noise considerations.

## 4) Agentic Workflows
- Teacher–Critic Cycle (TCC): iterative generate → critique → refine.
- Collective Consensus (CC): multiple “versatile” agents, randomized decoding seeds; CEO selects.
- Toggle studies: AutoCoT vs. solution-only.

## 5) Difficulty Prompting Strategies
- Empirical, Prompting-Empirical, Simple/Random; what each gives up/gains.
- Sampling and exposure bias as data-mining issues.

## 6) Self-Curation via Bloom
- Bloom agent assigns cognitive-demand score; filter aggressively.
- Compare against random curation; tie to ranking/selection paradigms.

## 7) Evaluation (Meta-Eval)
- Metrics: Relevance, Importance, Clarity, Difficulty Matching, Answerability.
- Caution: automated evaluators (ceiling effects, bias); outline your plan for human sanity checks.

## 8) Results (Describe Trends in Your Own Words)
- Curated TCC/CC outperform baselines overall; bigger gains on difficulty matching & relevance.
- Hard problems remain hardest; performance declines with difficulty.
- Few-shot prompting variants show minimal differences; inference compute has diminishing returns.

## 9) Takeaways for Data Mining Folks
- Label quality and curation pipelines dominate outcomes.
- ITC (inference-time compute) is a budget to allocate; measure ROI.
- Build evaluator robustness; consider human-in-the-loop labeling.

## 10) Related Work (Survey Flavor, 2024+)
- Briefly contrast with multi-agent debate/role-play frameworks and NLG evaluators.
- Place this approach among AutoGen, CAMEL, MetaGPT; G-Eval, QGEval; recent benchmarks.

## 11) Limitations & Future Directions
- Evaluation bias; generalization to other domains.
- Richer difficulty controls; feature-based difficulty predictors.

## 12) Acknowledgments & Links
- Credit original authors. Link your slides, video, and repo.
