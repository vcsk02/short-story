# CMPE 255 Short Story — Agentic AQG for Math (Data Mining Lens)

**Author:** Vineeth  
**Repo:** https://github.com/vcsk02/short-story

> This repository hosts the short story deliverables for CMPE 255. The focus is a data-mining framing of multi-agent, inference-time techniques for Automatic Question Generation (AQG) in Intelligent Tutoring Systems.

## Deliverables (Links)

- **Medium article (original writing):** <ADD YOUR MEDIUM LINK HERE>
- **Slides (Slideshare):** <ADD YOUR SLIDESHARE LINK HERE>
- **Talk video (10–15 min):** <ADD MP4 LINK IN THIS REPO + YOUTUBE/VIMEO IF ANY>
- **Paper/topic source:** Uploaded PDF in this repo; see `paper/`

## Contents

```
.
├── paper/
│   └── 2511.03958v1.pdf
├── slides/
│   └── short_story_slides.pptx
├── video/
│   └── short_story_talk.mp4   # add your recording
├── medium/
│   └── outline.md
└── README.md
```

## TL;DR

- **Task:** Generate math Q&A aligned to a knowledge component (KC) and difficulty.  
- **Data mining angle:** Use historical student performance to **label difficulty**, then **pipeline** generation → critique → **curation** (Bloom) → **selection**.  
- **Evaluation:** Meta-eval with Relevance, Importance, Clarity, Difficulty Matching, Answerability.  
- **Result:** Curated multi-agent workflows **slightly outperform** baselines, especially on **difficulty matching**.  
- **Caveats:** Automated evaluators show ceiling effects; non-curated agents can degrade quality.

## How to Reproduce Visuals for the Article

- Redraw key diagrams (e.g., Teacher–Critic Cycle, Collective Consensus) with your own styling (Figma/PowerPoint/draw.io).  
- Recreate charts (difficulty matching vs. difficulty; average score) using your own code or spreadsheet to avoid copying figures directly.  
- Credit the original paper in captions.

## Medium Article Guidance (no AI writing)

- Write in your own words. Use the `medium/outline.md` as a scaffold only.
- Focus on **architecture, ablations, and metrics** (not heavy math).
- Include your **own visuals** and **two-cents** on where data mining principles shape the pipeline (labeling, sampling, curation, evaluator bias).

## Slide Deck

- `slides/short_story_slides.pptx` is a starter. Expand bullets; add your figures and results callouts.  
- Export to PDF and upload to Slideshare; link it above.

## Video (10–15 minutes)

- Record with your slides on screen; keep ~1 minute per slide.  
- A timeboxed talk track is in `medium/video_plan.md`.  
- Place the final MP4 in `video/` and link it above.

## References

- Cite the uploaded paper and related works you discuss (G-Eval, QGEval, AutoGen, CAMEL, MetaGPT, etc.).
- Add a short **related work** section to the Medium post to satisfy the “survey” spirit with 2024+ sources.

## License

MIT for repo content you authored. For figures, ensure you have rights or redraw them.

---

*Prepared scaffold; fill with your own writing and assets to comply with your course rules.*
