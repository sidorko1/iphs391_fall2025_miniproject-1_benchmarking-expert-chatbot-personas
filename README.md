# Benchmarking Expert Chatbot Personas

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)
![GitHub Repo Size](https://img.shields.io/github/repo-size/sidorko1/iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas)
![GitHub Last Commit](https://img.shields.io/github/last-commit/sidorko1/iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas)

## Overview
This repository contains the materials, analysis, and results from **IPHS 391 Fall 2025 Mini-Project 1**, focused on **benchmarking expert chatbot personas**. The project explores the design and evaluation of AI chatbot personas through **persona prompt engineering**, turn-level evaluation rubrics, and structured conversational testing. 

The work demonstrates both the practical implementation of AI persona prompts and rigorous academic evaluation to assess alignment, responsiveness, and goal achievement of chatbot interactions.

## Methodology
The project methodology involved the following steps:

1. **Persona Design**
   - Crafted detailed persona prompts specifying personality, tone, background, and conversational objectives.
   - Designed for high engagement, motivational, and domain-specific expertise (e.g., Jordan Belfort persona).

2. **Chat Simulation**
   - Generated multi-turn chatbot conversations using the persona prompts.
   - Saved raw chat logs for subsequent analysis (`chat_history.md`, `metaprompt_history.txt`).

3. **Evaluation Rubric**
   - Developed a **turn-level evaluation rubric** with weighted factors:
     - Persona Alignment
     - Responsiveness & Adaptability
     - Knowledge Accuracy & Depth
     - Goal-Directedness & Objective Achievement
   - Scores assigned per turn (0–100), aggregated with weights to assess overall persona performance.

4. **Analysis**
   - Applied rubric to chatbot conversations.
   - Highlighted strengths and areas for improvement in persona fidelity and conversational effectiveness.

## Key Findings
- Well-crafted prompts result in high alignment and engaging dialogue.
- Recovery and adaptability are critical for maintaining persona consistency across unexpected user input.
- Extra credit observed when chatbots demonstrated clever phrasing or corrected prior misalignment.
- Turn-level scoring provides nuanced insight into conversational strengths and weaknesses.

## Files Description
| File | Description |
|------|-------------|
| `prompt_persona.txt` | Original persona prompt specifications for chatbot design |
| `chat_history.md` | Full conversation logs with the chatbot persona |
| `chat_rubric.txt` | Detailed evaluation rubric used for scoring chatbot turns |
| `chat_rubric_history.md` | Scored conversation history showing rubric application |
| `metaprompt_history.txt` | Meta-prompt adjustments and engineering iterations |
| `mp1_chatbot_report.docx` | Comprehensive project report including methodology, results, and discussion |
| `.gitignore` | Standard Git ignore file |
| `LICENSE` | MIT license for repository |

## Usage Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/sidorko1/iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas.git
   cd iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas
