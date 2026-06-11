# ReCoVLA Anonymous Project Website

This folder contains the anonymous supplementary website for the CoRL submission:

**ReCoVLA: VLM-Guided Reward Compilation for Failure Recovery in Vision-Language-Action Policies**

## How to View

Open the following file in a web browser:

```text
ReCoVLA website.html
```

No server or installation is required. The page is a static HTML website and uses the local videos and figure in this folder.

## Folder Contents

- `ReCoVLA website.html`: Main anonymous project website.
- `styles.css`: Styling for the website.
- `Appendix along with main paper.pdf`: Supplementary PDF containing the main paper and appendix material.
- `Video source files/`: Source videos and the reward-compiler figure used by the website.

## Website Structure

- **Method Overview**: Shows the reward compiler pipeline and summarizes the residual VLA recovery method.
- **Overview Video**: Provides a compact supplementary video summary of the full pipeline.
- **Performance**: Summarizes the main simulation, physical robot, OOD, ablation, baseline, and Behavior-1K Challenge results as HTML tables.
- **Simulation Failure Collection**: Shows simulation failure states used to ground reward functions with an external VLM and reward compiler.
- **Zero-shot Recovery Demonstrations**: Shows three recovery clips after residual RL training. These videos are physically clipped to the recovery-relevant segments and encoded as short sped-up clips.
- **OOD Stress Tests**: Shows three clipped and sped-up physical OOD experiment videos for vegetable sorting, soda-can disposal, and toolbox organization.
- **Behavior-1K Challenge**: Shows three 10x videos for sorting vegetables, bringing in wood, and preparing a lunch box on a different simulated robot platform.
- **Resources**: Links to the supplementary PDF.

## Anonymity Note

The website intentionally omits author names, affiliations, repository links, and other identifying information for anonymous review.

## Browser Notes

Recent versions of Chrome, Edge, Firefox, and Safari should play the videos directly. The recovery videos are already trimmed and sped up, so they do not rely on browser timestamp fragments.
