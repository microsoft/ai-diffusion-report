
# AI Diffusion Report Data

This repository contains the datasets and report materials for Microsoft’s **AI Diffusion** research, produced by the AI Economy Institute (AIEI).

The AI Diffusion report tracks global adoption of generative AI, measuring the share of people who have used AI tools across countries and over time.

## Overview

AI diffusion is defined as the **share of people who have used a generative AI product during a given period**. The measure is derived from aggregated and anonymized telemetry and adjusted to account for differences in:

- Device and operating system market share  
- Internet penetration  
- Country population  

This repository provides the **country-level datasets** used in the published reports, along with archived report PDFs.

## Citation

To cite this work and for full methodological details, see the technical paper:
- Misra, A., Wang, J., McCullers, S., White, K., & Lavista Ferres, J. (2025). *Measuring AI Diffusion: A Population-Normalized Metric for Tracking Global AI Usage*. arXiv. https://doi.org/10.48550/arXiv.2511.02781

Also available at: https://aka.ms/AI_Diffusion_Technical_Report

## Repository Structure

### `data/`
Contains country-level AI diffusion data used in the reports.

Typical fields include:
- country
- AI User Share for various periods

### `reports/`
Contains PDF versions of each published AI Diffusion report.

## Data Updates

Data is updated periodically alongside new AI Diffusion report releases (typically every 3-6 months).

Each update may include:
- revised country-level estimates
- additional countries or regions
- methodological refinements

## Usage

The data in this repository is intended for:
- research and analysis
- policy discussions
- visualization and reporting

## Limitations

AI diffusion is an evolving metric and should be interpreted with care:

- It reflects **usage, not capability or impact**
- Cross-country comparisons depend on adjustments for infrastructure differences
- Estimates are subject to revision as methodology improves

No single metric fully captures global AI adoption. This dataset should be considered alongside complementary indicators where possible.

## About

This work is produced by the **Microsoft AI Economy Institute (AIEI)** as part of ongoing research into global AI adoption and its economic and societal impacts.

For more information:
- https://www.microsoft.com/research/group/aiei/ai-diffusion/

## License
MIT License
