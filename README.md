# Benchmarking Expert Chatbot Personas – Mini Project #1

![Project Badge](https://img.shields.io/badge/Project-IPHS391_Fall2025-blue)
![Status Badge](https://img.shields.io/badge/Status-Complete-success)
![License Badge](https://img.shields.io/badge/License-MIT-green)

## Overview
This project explores the development and evaluation of a **sophisticated chatbot persona** through iterative prompt engineering. The chosen persona, **Jordan Belfort**, was designed to embody complex behaviors—bold, confident, and persuasive—while demonstrating nuanced adaptability across different conversational contexts. The persona’s performance was rigorously evaluated using a **weighted rubric**, achieving a final score of **96/100**, reflecting both fidelity to the character and engagement quality.

The project emphasizes **complexity, subtlety, creativity, and effectiveness**, showcasing how layered instructions, examples, and meta-prompting can produce a chatbot that feels alive and interactive.

---

## Methodology

### Persona Development
- **Target Persona:** Jordan Belfort, the “Wolf of Wall Street” – confident, high-energy, motivational, and streetwise.  
- **Prompt Engineering Techniques:** Iterative meta-prompts, few-shot examples, system prompts, and dynamic response rules to adapt tone, length, and style.  
- **Response Design:** Configured for short, punchy replies for casual questions and longer, detailed explanations for complex queries while maintaining persona consistency.

### Conversation Evidence
- Selected a **10-turn conversation** (20 utterances) demonstrating persona behaviors, including reflective questioning, motivational prompts, and illustrative anecdotes.  
- Exported chat history in Markdown format to document the persona in action.

### Evaluation Framework
- **Rubric Factors and Weights:**  
  - Alignment (25%) – maintaining character, speech patterns, knowledge boundaries  
  - Responsiveness & Adaptability (20%) – handling user input, recovering from off-topic queries  
  - Knowledge Accuracy & Depth (15%) – correctness and reasoning  
  - Goal-Directedness (15%) – advancing persona objectives: teaching, motivating, persuading  
  - Creativity / Style (10%) – metaphors, storytelling, humor  
  - Engagement / Persuasiveness (15%) – hooks, multi-turn flow, interaction quality  
- **Extra Credit:** awarded for clever metaphors, multi-turn engagement, or recovery from prior mistakes.  
- **Scoring Outcome:** Final persona score of **96/100**, demonstrating strong alignment, responsiveness, and engagement.

---

## Results
- **Persona Consistency:** The chatbot reliably maintained Jordan Belfort’s voice and attitude across all turns.  
- **Dynamic Responses:** Adjusted length and tone based on the type of user input. Short and direct for casual prompts, detailed and instructive for complex queries.  
- **Strengths:** Engaging, motivational, and interactive responses that adhered closely to the intended persona.  
- **Limitations:** Occasional over-explanation or repetition when handling off-topic or ambiguous questions, but did not significantly affect overall performance.

---

## Repository Structure

| Filename | Step | Description |
|----------|------|-------------|
| `README.md` | 7 | Professional project landing page and documentation |
| `metaprompt_history.txt` | 2 | Iterative persona prompt development history |
| `prompt_persona.txt` | 2 | Final refined chatbot persona prompt |
| `chat_history.md` | 3 | 10-turn conversation illustrating persona in action |
| `chat_rubric_history.md` | 4 | Rubric development conversation history |
| `chat_rubric.txt` | 4 | Final evaluation rubric with weights and scoring guidelines |
| `mp1_chatbot_report.docx` | 5 | Full report following the 6-section structure |

---

## Usage Instructions
1. Review `prompt_persona.txt` to understand the persona configuration.  
2. Load the persona prompt into ChatGPT or a compatible platform.  
3. Observe `chat_history.md` for examples of effective persona interactions.  
4. Apply `chat_rubric.txt` for evaluating additional conversations or testing reproducibility.

---

## Key Insights
- **Complexity:** Layered instructions and meta-prompts enabled sophisticated behavior.  
- **Subtlety:** The chatbot dynamically adjusted tone, length, and challenge based on user input.  
- **Creativity:** Metaphors, anecdotes, and humor enhanced realism and engagement.  
- **Effectiveness:** High rubric score reflects success in teaching, motivating, and interacting consistently with the Jordan Belfort persona.

---

## License
This repository is licensed under the **MIT License**, and all project materials are open-source and publicly available.

---

This README presents the project in a **professional, clear, and engaging way**, emphasizing persona development, evaluation, and results—perfect for academic or portfolio presentation.  
