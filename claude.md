# Competitive Analysis — Batch Speech AI Products

## Purpose
This folder contains competitive analysis documents for Sanas's non-streaming (batch) speech AI products, designed for executive consumption.

## Personas
1. Analyse for the persona's developers who are using APIs and SDKs to integrate the models and outputs in their workflows. These are technical people
2. Analse for the persona's non-developers who are primarily using these for the processing on the web, these are non technical people who doesnot want to code or use any workflows; this is a stand-alone request for batch processing

## Products Covered
1. **ASR (Automatic Speech Recognition)** — Batch transcription
2. **TTS (Text-to-Speech)** — Batch audio generation as per the user voice profile (or out of box voice profiles)
3. **Accent Translation** — Batch accent conversion / softening (say from source accent - India, Philippines, and LATAM english to target accents - US English and UK English)
4. **Noise Cancellation** — Batch audio enhancement (Removal of background noise)

## Document Format
Each product analysis follows this structure: 
Identify the Gaps and Use Cases from the competitor webiste and also other product reviews for example G2, Product hunt etc..
- **Executive Decision** — Lead with the recommendation
- **Competitors Table** — Competitors | Description | Use Cases | Gaps 
- **Batch Processing Use Cases** — Specific non-streaming use cases
- **Perceptual Map** — Visual positioning (quality vs cost, ease of market capture)
- **Source Details** — Cited sources with drill-down links

## Reference Files
- `../jtbd_proxy_research.md` — JTBD proxy research with opportunity scores
- `../go_no_go_batch_accent_translation.md` — Go/No-Go decision document for batch AT
- `../competitor_analysis_accent.md` — Detailed accent translation competitor analysis
- `../Requirements.md` — Developer console requirements

## Output
- `competitive_analysis_batch_speech_ai.html` — Main deliverable (HTML format for exec sharing)

## Instructions
- All analysis focuses on **non-streaming / batch** models only
- Lead with decisions, not data dumps
- Include perceptual maps for market positioning
- Source all claims with drill-down links
- Include batch processing use cases for each product
- Target audience: executives making build/buy/partner decisions
- Refer to product reviews for the competitors on G2 and reddit to identify the gaps
