# CT-to-Ultrasound Synthesis — My Research

## Problem

CT and ultrasound have different imaging mechanisms. A useful virtual ultrasound training system should preserve the relationship between **probe position**, **patient anatomy**, and **the generated view**, rather than simply produce a visually plausible grayscale image.

## Team research context

| Approach | Purpose in the research |
|---|---|
| Field II | Physics-based ultrasound simulation reference |
| Ray-based simulation | Approximate wave/tissue interaction with potentially faster computation |
| 2.5D Pix2Pix | Image-to-image translation from CT context to ultrasound-like appearance |

These three approaches were examined across the **team project**, not all independently authored by me.

## My work

I investigated CT-to-ultrasound synthesis and contributed to developing two approaches for creating ultrasound-like views from 3D CT-derived anatomy. I focused on anatomical fidelity, realism, and comparing technical tradeoffs.

**To complete this page using real evidence:**

1. Identify approach A by actual script/notebook filename and explain the input, computation, and output.
2. Identify approach B by actual script/notebook filename and explain the input, computation, and output.
3. Attach a side-by-side comparison for the same anatomy or properly labeled examples.
4. Explain what failed or proved difficult, supported by the experiment logs.
5. Add dependency/command instructions only if the code is actually publishable and reproducible.

## Results format

| Test case | Approach | Real output image | Observed strengths | Observed limitations |
|---|---|---|---|---|
| Example 1 | [Exact method] | [Link to real image] | [Based on evidence] | [Based on evidence] |

Avoid made-up SSIM, FID, or real-time FPS claims. Only add metrics computed under documented conditions.

## Notes on responsible sharing

Check source licenses, patient confidentiality, dataset terms and supervisor/team permissions before posting original scans, screenshots, or weights.
