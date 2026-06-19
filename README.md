# AI Visual Library Generator

This project leverages Stable Diffusion to generate a library of technical illustrations covering various computer science topics such as Networks, Operating Systems, Data Structures, Databases, and Cloud Computing.

## Project Overview

The notebook automates the creation of visual assets based on predefined prompts, styled as 'flat vector illustrations, clean minimal educational style'.

## Contents

- **Setup**: Installs necessary libraries (`diffusers`, `transformers`, `accelerate`, `torch`).
- **Model Loading**: Initializes the `StableDiffusionPipeline` using the `runwayml/stable-diffusion-v1-5` model.
- **Prompt Definitions**: Contains a comprehensive list of topics and their corresponding prompts, enriched with a consistent `STYLE_SUFFIX` for visual uniformity.
- **Image Generation**: A function `generate_library` iterates through the defined topics, generates images using the loaded model, and saves them to categorized folders within the `outputs` directory.
- **Download**: Zips the generated images and provides a download link for easy access.

## How to Use

1. Run all cells in the notebook.
2. The `generate_library` function will automatically create and save images for all defined topics.
3. A `ai_visual_library.zip` file will be generated and downloaded, containing all the generated illustrations organized by topic.
