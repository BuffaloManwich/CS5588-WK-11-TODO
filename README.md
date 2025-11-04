# Week 11 — Video LLM (VLM → SVD)

**Scope:** Multi-modal retrieval + Vision-Language reasoning + Stable Video Diffusion from a curated source image.

**Models (local):**
- Qwen2-VL-2B-Instruct (preferred) or Intern3.5-VL-4B (fallback), both under `~/projects/capstone/hw-rag/models/`
- Stable Video Diffusion (image→video), GPU-gated with memory-safe settings

**Key notebooks:**
- `notebooks/Week11-HO-1.ipynb` — system probes, graph build (v2), PDF image extraction
- `notebooks/Week11-HO-2.ipynb` — VLM answer + SVD clip pipeline, curated artifact export

**Artifacts (curated for rubric):**
- `artifacts/curated/faucet_spout.png`
- `artifacts/curated/svd_example.mp4`

**Notes:** The end-to-end process <u>could</u> be accomplished, but automated image selection remains the bottleneck and requires human curation; video quality is highly sensitive to source image and parameters. See `reports/Report.md`.
