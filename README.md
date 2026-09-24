# GROW AI VIDEO

Mobile-first image-to-video frontend for Wan 2.2.

## Goal
Upload image → write motion prompt → Generate → preview/download MP4.

## Backend
The frontend is designed to call a public Hugging Face Gradio/ZeroGPU Wan 2.2 TI2V-5B Space. Public free GPU availability and API shape are controlled by the upstream Space and may change or queue.

## Hosting
Static `index.html`, suitable for GitHub Pages.

## Important
No API keys are stored in this repository.