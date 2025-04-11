# AI Energy Score Visualization Project
## Overview
Artificial intelligence (AI) is revolutionizing industries, but its energy consumption is raising critical concerns about sustainability. AI models require vast computational power, often relying on energy-intensive data centers. These impacts vary significantly depending on the task being performed and the geographic region's electricity sources.

This project uses HuggingFace's AI Energy Score framework to visualize the energy consumption of AI models across various tasks, highlighting the differences between efficient and inefficient models. It also explores regional environmental impacts based on metrics like Abiotic Depletion Potential (ADPe) and Primary Energy Consumption (PE).

## Goals
The project aims to:

Provide a clear understanding of AI energy consumption across tasks and models.

Highlight the environmental impacts of AI energy use on different regions.

Encourage policymakers in technology and energy sectors to consider these intricacies when crafting regulations for sustainable AI development.

## Visualizations
This project includes several interactive and responsive visualizations:

### Energy Consumption Per Task:

A chart illustrating the average energy consumption across ten common AI tasks.

Highlights how tasks like image generation are far more energy-intensive than simpler tasks like text classification.

### Top 5 Most Energy-Efficient Models:

A horizontal bar chart showing models that consume minimal GPU energy while maintaining high performance.

### Top 5 Least Energy-Efficient Models:

A horizontal bar chart showing models that consume significantly more GPU energy due to their computational intensity.

### Environmental Impacts by Region:

Interactive charts (desktop and mobile versions) comparing regions based on ADPe and PE metrics.

### Energy Consumption by Region:

Interactive charts (desktop and mobile versions) highlighting regional differences in electricity generation methods and their environmental impacts.

## Key Metrics
### Abiotic Depletion Potential (ADPe):

Measures the depletion of non-renewable abiotic resources like minerals and metals during electricity production.

Higher ADPe values indicate greater environmental strain due to resource depletion.

### Primary Energy Consumption (PE):

Represents the total amount of primary energy required to produce one kilowatt-hour (kWh) of electricity.

Higher PE values reflect inefficiencies in electricity generation, often leading to a larger environmental footprint.

## How It Works
The project uses data from HuggingFace's AI Energy Score framework to create interactive visualizations using Python, Matplotlib, and Adobe Illustrator with ai2html for responsive components. The visualizations are embedded into an HTML webpage for easy accessibility and scalability.

## Datasets
The datasets used in this project are publicly available through HuggingFace's AI Energy Score framework:

HuggingFace AI Energy Score

## Insights
This project reveals critical insights into AI energy consumption:

Smaller models like distilgpt2 are optimized for efficiency, making them ideal for lightweight applications.

Larger models like phi-4 consume significantly more energy but excel at complex tasks like image generation or reasoning.

Regional differences in electricity generation methods influence environmental impacts, with countries like China relying heavily on coal while France benefits from nuclear power.
