# Project 2 model explainer

Open `index.html` in a browser for the expanded, self-contained walkthrough. It works offline and needs no package installation or local server.

The page now follows the current two-cell notebook: shared setup, then one combined Stage 1–3 pipeline. It explains the annotation and caliper assumptions, pseudo-mask limits, augmentation and empty-patch sampling, each of the six model outputs and loss terms, resumable training, fold assignment and checkpoint selection, detection and mask metrics, Stage 2 tile geometry and mask-aware consensus fusion, and optional Stage 3 BCL6 classification. The full speaker-note manuscript, including the improvement record and research context, is embedded in an expandable section.

The threshold and fold demonstrations use invented/schematic information only. The page does not load project images, CSV annotations, model weights, or checkpoints.

## GitHub Pages

The public repository is `https://github.com/cm5t/googleaiaccel`. If GitHub Pages publishes from the repository root, place the contents of this `model-explainer` folder there or configure Pages to publish this folder. The page is static and needs no build step.
