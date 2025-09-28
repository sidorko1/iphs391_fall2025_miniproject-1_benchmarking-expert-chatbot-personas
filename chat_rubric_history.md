# Chatbot persona evaluation rubric

**User:** Kirill Sidorko (kirya.sidorko@gmail.com)  
**Created:** 9/27/2025 18:58:06  
**Updated:** 9/27/2025 20:30:54  
**Exported:** 9/27/2025 20:32:51  
**Link:** [https://chatgpt.com/c/68d86bfc-7168-8323-815f-09b8282357c9](https://chatgpt.com/c/68d86bfc-7168-8323-815f-09b8282357c9)  

## Prompt:
You are an expert in AI evaluation metrics and prompt engineering. Help me create a comprehensive scoring rubric for evaluating chatbot persona quality.

CONTEXT:
- Students created persona prompts to make ChatGPT roleplay as specific experts/characters
- We need to score how well a 10-turn conversation reflects the intended persona
- Score should be 0-100 with clear, measurable criteria

PERSONA TO EVALUATE: [INSERT YOUR PERSONA DESCRIPTION HERE]
CONVERSATION: [INSERT YOUR chat_history.md CONTENT HERE]

REQUIREMENTS:
1. Create 4-6 independent evaluation factors
2. Define each factor with specific behavioral indicators
3. Assign weights that sum to 1.0
4. Provide scoring guidelines (what constitutes 90+ vs 60-70 vs <40)
5. Include examples from the conversation for each factor
6. Calculate final weighted score

Make the rubric rigorous enough for academic evaluation but practical for student self-assessment.

## Response:
Here’s a **comprehensive, academically rigorous yet practical rubric** for evaluating chatbot persona quality in a 10-turn conversation. I’ll structure it exactly according to your requirements. You can plug in your persona description and conversation later.

* * *

**Chatbot Persona Evaluation Rubric (0–100)**
=============================================

**Persona:** \[INSERT YOUR PERSONA DESCRIPTION HERE\]  
**Conversation:** \[INSERT YOUR chat\_history.md CONTENT HERE\]

| **Factor** | **Weight** | **Behavioral Indicators** | **Scoring Guidelines** | **Examples from Conversation** |
| --- | --- | --- | --- | --- |
| **1\. Persona Consistency & Authenticity** | 0.30 | \- Maintains the persona’s voice, tone, and worldview consistently throughout the conversation  
\- Uses language, idioms, and style consistent with persona  
\- Reflects persona’s knowledge, expertise, and attitude | **90–100:** Fully embodies persona throughout; speech, tone, content highly consistent  
**60–70:** Mostly consistent; occasional lapses in tone or knowledge  
**<40:** Inconsistent, generic, or off-tone; fails to reflect persona | \- “Ah, the age-old question—School: worth it, or just a treadmill for the mediocre?”  
\- “Step one, start learning the skill of selling. Doesn’t matter what—cars, gyms, stocks…” |
| **2\. Engagement & Persuasiveness** | 0.20 | \- Captures and maintains user attention  
\- Uses hooks, questions, or storytelling consistent with persona  
\- Motivates user to act or respond | **90–100:** Highly engaging and compelling; conversation flows naturally  
**60–70:** Moderately engaging; some prompts or hooks missing  
**<40:** Flat, unengaging, or fails to elicit user responses | \- “The Wolf never settles.”  
\- “You walk into that room like you OWN the joint.” |
| **3\. Knowledge Accuracy & Depth** | 0.20 | \- Demonstrates expertise or knowledge level expected of persona  
\- Answers are factually accurate within context  
\- Reflects persona’s understanding and perspective | **90–100:** Accurate, detailed, demonstrates deep understanding  
**60–70:** Mostly accurate; minor gaps or oversights  
**<40:** Misleading, incorrect, or overly simplistic | \- “Mindset Is King: Confidence isn’t optional—it’s a weapon.”  
\- Financial or domain-specific advice aligns with persona expertise |
| **4\. Psychological Insight / Interpersonal Reading** | 0.15 | \- Shows ability to read the user’s intent, emotions, or knowledge level  
\- Tailors responses to encourage engagement or reflection  
\- Uses persona-appropriate empathy, challenge, or motivation | **90–100:** Accurately gauges user’s state and adapts; adds value  
**60–70:** Partially adapts; some misreadings  
**<40:** Ignores or misinterprets user cues | \- “A NO ain’t rejection—it’s a request to justify why they haven’t yet said YES.”  
\- Challenges the user to rethink their approach |
| **5\. Creativity & Persona-Specific Style** | 0.15 | \- Exhibits persona’s characteristic creativity, wit, humor, or storytelling  
\- Uses unique metaphors or memorable phrasing aligned with persona | **90–100:** Highly creative and memorable; clearly persona-driven  
**60–70:** Some creativity, occasionally generic  
**<40:** Lacks creativity; bland or formulaic | \- “Swinging to kill, not just to miss and hope.”  
\- “Close like you’re swallowing sharks whole.” |

* * *

### **Scoring Procedure**

1.  **Rate each factor individually (0–100)** using the guidelines.
2.  **Multiply each score by its weight**.
3.  **Sum the weighted scores** to calculate the final persona quality score.

**Example:**

| Factor | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Persona Consistency & Authenticity | 92 | 0.30 | 27.6 |
| Engagement & Persuasiveness | 85 | 0.20 | 17 |
| Knowledge Accuracy & Depth | 88 | 0.20 | 17.6 |
| Psychological Insight | 80 | 0.15 | 12 |
| Creativity & Style | 95 | 0.15 | 14.25 |
| **Final Score** | — | 1.0 | **88.45** |

* * *

✅ **Notes for Students:**

*   Use concrete quotes from the conversation for self-assessment.
*   Avoid subjective impressions without evidence; tie your evaluation to observable language, knowledge, or tone.
*   Scores should reflect both **persona fidelity** and **practical engagement quality**.

* * *

If you want, I can also **create a ready-to-use `.txt` or spreadsheet template** where students can input conversation turns and automatically compute the weighted score. This makes it fully self-contained for academic use.

Do you want me to do that next?

## Prompt:
-Measure responsiveness and adaptability
How well the bot reacts to changing user input or confusion
Does it escalate/de-escalate appropriately
-Include goal-directedness
Does the bot guide the conversation toward the persona’s objectives
Avoids irrelevant tangents
Add turn-level consistency checks
-Evaluate whether persona stays consistent across all 10 turns (consistency doesnt mean it needs to be saying the same thing, just same personality)
-Make scoring guidelines more quantitative
-90+: ≥90% of turns aligned with persona, no factual errors
70–89: Mostly aligned, minor lapses
50–69: Inconsistent, factual gaps, some flat responses
<50: Majority off-tone or irrelevant

## Response:
Perfect. Let’s **revise the rubric** to incorporate your requested factors and make the scoring more **quantitative** and precise. I’ll also add turn-level checks, responsiveness/adaptability, and goal-directedness.

* * *

**Chatbot Persona Evaluation Rubric (0–100)**
=============================================

**Persona:** \[INSERT YOUR PERSONA DESCRIPTION HERE\]  
**Conversation:** \[INSERT YOUR chat\_history.md CONTENT HERE\]

| **Factor** | **Weight** | **Behavioral Indicators** | **Scoring Guidelines** | **Examples from Conversation** |
| --- | --- | --- | --- | --- |
| **1\. Persona Consistency Across Turns** | 0.25 | \- Maintains personality, tone, and worldview across all 10 turns  
\- Consistent style and language (not content repetition)  
\- Turn-level check: each turn scored for alignment with persona | **90+:** ≥90% of turns aligned with persona, no factual errors  
**70–89:** Mostly aligned; minor lapses in tone or minor factual gaps  
**50–69:** Inconsistent; factual gaps; some flat responses  
**<50:** Majority off-tone, irrelevant, or incorrect | \- Turn 1–10 consistently motivational, confident, and persuasive  
\- Avoids generic or robotic responses |
| **2\. Knowledge Accuracy & Depth** | 0.20 | \- Answers reflect persona expertise and are factually correct  
\- Provides relevant detail without over-explaining  
\- Recognizes and corrects mistakes if prompted | Same quantitative scale as above | \- “Mindset Is King: Confidence isn’t optional—it’s a weapon.”  
\- Accurate financial or domain-specific advice |
| **3\. Responsiveness & Adaptability** | 0.20 | \- Reacts appropriately to user confusion, questions, or changes in topic  
\- Escalates/de-escalates tone appropriately  
\- Adjusts strategy to user cues | **90+:** Responds appropriately in ≥90% of turns; adapts smoothly  
**70–89:** Mostly responsive; minor misreads  
**50–69:** Partially responsive; some misalignments  
**<50:** Frequently ignores user input or reacts incorrectly | \- “A NO ain’t rejection—it’s a request to justify why they haven’t yet said YES.”  
\- Adjusts motivational tone when user expresses doubt |
| **4\. Goal-Directedness** | 0.15 | \- Guides conversation toward persona’s objectives (teaching, motivating, selling, entertaining, etc.)  
\- Avoids irrelevant tangents  
\- Keeps user engaged toward desired outcome | Same quantitative scale as above | \- Continuously nudges user toward taking action  
\- Avoids off-topic chatter |
| **5\. Creativity & Persona-Specific Style** | 0.10 | \- Uses wit, humor, metaphors, or storytelling consistent with persona  
\- Memorable phrasing aligned with persona voice | Same quantitative scale as above | \- “Swinging to kill, not just to miss and hope.”  
\- Metaphors reflecting high-energy or risk-taking persona |
| **6\. Engagement & Persuasiveness** | 0.10 | \- Captures user attention  
\- Uses hooks or rhetorical devices  
\- Encourages interaction or reflection | Same quantitative scale as above | \- “The Wolf never settles.”  
\- “Walk into the room like you OWN it.” |

* * *

### **Scoring Procedure**

1.  **Evaluate each turn (1–10)** for persona alignment, responsiveness, and goal-directedness.
2.  **Calculate factor scores quantitatively** using turn percentages where possible (e.g., ≥9/10 turns aligned = 90+).
3.  **Multiply each factor score by its weight**.
4.  **Sum weighted scores** for final persona quality score (0–100).

**Example:**

| Factor | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Persona Consistency | 92 | 0.25 | 23.0 |
| Knowledge Accuracy | 88 | 0.20 | 17.6 |
| Responsiveness & Adaptability | 85 | 0.20 | 17.0 |
| Goal-Directedness | 90 | 0.15 | 13.5 |
| Creativity & Style | 95 | 0.10 | 9.5 |
| Engagement & Persuasiveness | 90 | 0.10 | 9.0 |
| **Final Score** | — | 1.0 | **89.6** |

* * *

This version is:

*   **Turn-level quantitative**: each turn can be scored for persona alignment and responsiveness.
*   Includes **goal-directedness** and **adaptability**, as requested.
*   **Scoring thresholds** are precise and measurable (≥90%, 70–89%, etc.).

* * *

If you want, I can **make a fully automated scoring sheet** where you input **10 conversation turns**, check boxes for alignment, responsiveness, and goal-directedness, and it calculates **factor scores and final weighted score automatically**.

Do you want me to do that next?

## Prompt:
-Quantify Responsiveness & Adaptability
Track how the bot reacts to user questions, confusion, or topic changes
Include escalation/de-escalation of tone when appropriate
-Check for wit, humor, metaphors, or storytelling
-Ensure phrasing matches persona voice and is memorable
-Deduct points for factual errors, off-tone language, or ignoring user input
-Tie scores to observable behavior rather than subjective impressions

## Response:
Perfect — let’s **refine the rubric** to make it fully **quantitative, observable, and actionable**, specifically addressing **Responsiveness & Adaptability**, creativity/wit, and error deductions. I’ll also tie everything to measurable behaviors, not subjective impressions.

* * *

**Chatbot Persona Evaluation Rubric (0–100)**
=============================================

**Persona:** \[INSERT YOUR PERSONA DESCRIPTION HERE\]  
**Conversation:** \[INSERT YOUR chat\_history.md CONTENT HERE\]

| **Factor** | **Weight** | **Behavioral Indicators** | **Scoring Guidelines (Quantitative)** | **Examples from Conversation** |
| --- | --- | --- | --- | --- |
| **1\. Persona Consistency Across Turns** | 0.25 | \- Personality, tone, and worldview consistent across all 10 turns  
\- Turn-level checks: each turn scored as **Aligned / Partially Aligned / Off-Persona**  
\- Points deducted for off-tone or irrelevant language | **90+:** ≥9/10 turns aligned, no major factual errors  
**70–89:** 7–8 turns aligned, minor lapses or 1–2 small factual errors  
**50–69:** 5–6 turns aligned, some flat responses or factual gaps  
**<50:** <5 turns aligned, majority off-tone | \- Motivational, confident, persuasive across all turns  
\- Avoids robotic or generic phrasing |
| **2\. Knowledge Accuracy & Depth** | 0.20 | \- Correct domain knowledge for persona  
\- Provides sufficient detail without over-explaining  
\- Corrects mistakes if prompted | **90+:** ≥90% of responses factually correct  
**70–89:** Minor factual gaps in 1–2 turns  
**50–69:** Several factual gaps, some misinformation  
**<50:** Majority inaccurate or misleading | \- Financial advice aligns with persona expertise  
\- References domain concepts correctly |
| **3\. Responsiveness & Adaptability** | 0.20 | \- Reacts to user questions, confusion, or topic changes  
\- Adjusts tone (escalates/de-escalates) appropriately  
\- Avoids ignoring user input or giving generic answers | **90+:** ≥90% of turns respond appropriately to user cues; adapts tone and topic seamlessly  
**70–89:** Mostly responsive; minor misreads or slow adaptation  
**50–69:** Partial responsiveness; 3–4 misreads or ignored cues  
**<50:** Frequently ignores user input or reacts inappropriately | \- Adjusts advice when user expresses doubt  
\- Escalates energy when motivation is needed, de-escalates when user is frustrated |
| **4\. Goal-Directedness** | 0.15 | \- Guides conversation toward persona’s objectives (teaching, motivating, advising)  
\- Avoids irrelevant tangents  
\- Keeps user on intended path | **90+:** ≥90% of turns keep conversation aligned with persona objectives  
**70–89:** Minor off-topic turns (1–2)  
**50–69:** Several irrelevant or unproductive turns  
**<50:** Majority of conversation off-objective | \- Continuously nudges user toward learning or action  
\- Avoids drifting into irrelevant topics |
| **5\. Creativity, Wit & Persona-Specific Style** | 0.10 | \- Memorable phrasing, metaphors, humor, or storytelling consistent with persona  
\- Expresses personality in language, voice, and tone | **90+:** ≥90% of turns exhibit clear persona style; memorable and engaging  
**70–89:** Some creative expressions; mostly aligned  
**50–69:** Few creative elements; occasionally flat  
**<50:** Lacks wit, humor, or persona style | \- “Swinging to kill, not just to miss and hope.”  
\- Uses metaphors reflecting risk-taking, energy, or persona traits |
| **6\. Engagement & Persuasiveness** | 0.10 | \- Maintains user attention  
\- Uses hooks, rhetorical devices, or motivational phrasing  
\- Encourages interaction or reflection | Same quantitative scale as above | \- “The Wolf never settles.”  
\- “Walk into the room like you OWN it.” |

* * *

### **Deduction Rules**

*   **Factual errors:** Deduct 5–10 points per major error, proportionally if multiple errors occur.
*   **Off-tone language or ignoring input:** Deduct 5 points per turn that is off-persona or unresponsive.
*   **Observable behaviors only:** Score based on actions in the conversation (quotes, responses), not impressions of “energy” or “style.”

* * *

### **Scoring Procedure**

1.  **Evaluate each turn (1–10)** for persona alignment, responsiveness/adaptability, and goal-directedness.
2.  **Check for factual accuracy**; apply point deductions for errors.
3.  **Assess creativity/wit and engagement** per turn.
4.  **Compute each factor score** using turn-level percentages.
5.  **Multiply each factor by its weight** and sum for final score (0–100).

**Example Calculation:**

| Factor | % Alignment / Quality | Weight | Weighted Score |
| --- | --- | --- | --- |
| Persona Consistency | 92% | 0.25 | 23.0 |
| Knowledge Accuracy | 88% | 0.20 | 17.6 |
| Responsiveness & Adaptability | 85% | 0.20 | 17.0 |
| Goal-Directedness | 90% | 0.15 | 13.5 |
| Creativity & Style | 95% | 0.10 | 9.5 |
| Engagement & Persuasiveness | 90% | 0.10 | 9.0 |
| **Final Score** | — | 1.0 | **89.6** |

* * *

✅ **Key Improvements from Prior Version:**

*   Turn-level quantitative checks for alignment, responsiveness, and style.
*   Responsiveness & Adaptability clearly measurable via observable behaviors.
*   Deduction rules for factual errors and ignored user input.
*   Creativity and engagement tied to observable phrases/metaphors.
*   Scoring thresholds linked to **% of aligned turns** rather than subjective impression.

* * *

If you want, I can **make this into an Excel or Google Sheet template** where you can **input the 10 turns, tick boxes for alignment/responsiveness/goal-directedness**, and it will **automatically calculate weighted scores and apply deductions**.

Do you want me to create that template?

## Prompt:
-Evaluate each of the 10 turns separately for alignment, responsiveness, creativity, and engagement
-Prevent a few good turns from masking weak performance elsewhere
-Check if the bot keeps the conversation aligned with persona objectives (teach, motivate, persuade)
-Deduct points for off-topic or irrelevant responses

## Response:
Got it — we can make the rubric **turn-level, quantitative, and weighted**, so no single strong turn masks weak performance elsewhere. Here’s a refined version that incorporates **per-turn evaluation, alignment with persona objectives, and deductions for off-topic responses**.

* * *

**Chatbot Persona Turn-Level Evaluation Rubric (0–100)**
========================================================

**Persona:** \[INSERT YOUR PERSONA DESCRIPTION HERE\]  
**Conversation:** \[INSERT YOUR chat\_history.md CONTENT HERE\]

* * *

**Step 1: Turn-Level Scoring (10 Turns)**
-----------------------------------------

Evaluate **each turn individually** (1–10) across these categories:

| **Category** | **Description / Observable Indicators** | **Scoring (0–100 per turn)** |
| --- | --- | --- |
| **Alignment** | \- Does the turn reflect the persona’s tone, personality, and worldview?  
\- Points for language, phrasing, and attitude consistent with persona | 100 = fully aligned  
70 = mostly aligned, minor lapses  
50 = partially aligned  
0 = off-persona |
| **Responsiveness** | \- Does the turn react appropriately to user input?  
\- Does it escalate/de-escalate tone as needed?  
\- Adjusts when user expresses confusion, doubt, or topic change | 100 = fully responsive and adaptable  
70 = mostly responsive; minor misreads  
50 = partially responsive  
0 = ignores user input or reacts inappropriately |
| **Creativity / Style** | \- Uses wit, humor, metaphors, or storytelling consistent with persona  
\- Phrasing is memorable and aligned with persona voice | 100 = highly creative/persona-aligned  
70 = moderately creative  
50 = some creativity but flat  
0 = bland or off-tone |
| **Engagement / Persuasiveness** | \- Maintains user attention  
\- Uses hooks, rhetorical devices, or motivational phrasing  
\- Encourages interaction | 100 = highly engaging/persuasive  
70 = moderately engaging  
50 = minimally engaging  
0 = flat, unpersuasive |

> **Optional Deductions per Turn:**
> 
> *   Factual error: −5 to −10 points
> *   Off-topic / irrelevant: −10 points
> *   Ignoring user input: −5 points
>     

* * *

**Step 2: Persona Objective Alignment Check**
---------------------------------------------

*   **Goal-directedness:** Does the turn advance the persona’s objectives (teach, motivate, persuade)?
*   Deduct **10 points per turn** if it goes off-topic or fails to contribute to persona goals.

* * *

**Step 3: Compute Factor Scores**
---------------------------------

1.  For each category, **average scores across all 10 turns**.
2.  Apply **deductions for off-topic or factual errors**.
3.  Weighted factors (example):

| Factor | Weight |
| --- | --- |
| Alignment | 0.25 |
| Responsiveness | 0.20 |
| Knowledge Accuracy / Depth | 0.20 |
| Goal-Directedness | 0.15 |
| Creativity / Style | 0.10 |
| Engagement / Persuasiveness | 0.10 |

> **Final Score = Σ(weight × factor score)**

This ensures **weak turns are visible** and cannot be masked by a few strong turns.

* * *

**Step 4: Scoring Guidelines (Quantitative)**
---------------------------------------------

| **Weighted Score** | **Interpretation** |
| --- | --- |
| 90–100 | ≥90% of turns aligned, responsive, and on-objective; minimal errors |
| 70–89 | Mostly aligned; minor lapses in responsiveness, creativity, or goal-directedness |
| 50–69 | Inconsistent across turns; factual gaps, some flat/off-topic responses |
| <50 | Majority of turns off-persona, unresponsive, or irrelevant |

* * *

✅ **Key Improvements in This Version:**

*   Turn-level evaluation prevents strong turns from masking weak performance.
*   Responsiveness, creativity, and engagement are **observable and scored per turn**.
*   Explicit **goal-directedness check** aligns conversation with persona objectives.
*   Deduction system ensures off-topic or irrelevant responses lower overall score.
*   Fully quantitative and reproducible for **academic evaluation or self-assessment**.

* * *

If you want, I can make a **ready-to-use Excel/Google Sheet template** where you can:

1.  Input **10 conversation turns**.
2.  Score each turn across **Alignment, Responsiveness, Creativity, Engagement**.
3.  Automatically **calculate weighted factor scores, apply deductions, and produce a final score**.

Do you want me to create that template?

## Prompt:
-Score how well the bot responds to user confusion, misunderstanding, or pushback
-Include a metric for “recovery” if the bot initially gives a poor or off-topic response

Extra credit for:
-Highly clever metaphors or storytelling
-Seamless multi-turn engagement
-Novel strategies that demonstrate deep persona understanding

## Response:
Perfect — we can **enhance the rubric** to explicitly include **confusion recovery**, multi-turn engagement, and extra-credit behaviors like clever metaphors or novel persona strategies. Here’s the fully updated **turn-level, quantitative rubric**:

* * *

**Chatbot Persona Turn-Level Evaluation Rubric (0–100)**
========================================================

**Persona:** \[INSERT YOUR PERSONA DESCRIPTION HERE\]  
**Conversation:** \[INSERT YOUR chat\_history.md CONTENT HERE\]

* * *

**Step 1: Evaluate Each Turn (1–10)**
-------------------------------------

Score **each turn individually** across these categories:

| **Category** | **Behavioral Indicators / Observable Metrics** | **Turn Score (0–100)** |
| --- | --- | --- |
| **Alignment** | \- Personality, tone, and worldview consistent with persona  
\- Language, phrasing, and attitude align with persona | 100 = fully aligned  
70 = mostly aligned, minor lapses  
50 = partially aligned  
0 = off-persona |
| **Responsiveness & Adaptability** | \- Responds appropriately to user questions, confusion, or pushback  
\- Adjusts tone (escalate/de-escalate) appropriately  
\- Recovery: if previous turn was off-topic or poor, bot corrects or recovers effectively | 100 = fully responsive + recovers if needed  
70 = mostly responsive; partial recovery  
50 = minimal responsiveness; slow or incomplete recovery  
0 = ignores user input or fails to recover |
| **Creativity / Style** | \- Uses wit, humor, metaphors, or storytelling consistent with persona  
\- Memorable phrasing and persona voice  
\- Extra credit: highly clever or novel expressions | 100 = highly creative, memorable, extra clever metaphors/storytelling  
70 = moderately creative  
50 = some creativity, minor flatness  
0 = bland or off-tone |
| **Engagement / Persuasiveness** | \- Maintains user attention  
\- Uses hooks, rhetorical devices, motivational phrasing  
\- Extra credit for seamless multi-turn engagement or strategies demonstrating deep persona understanding | 100 = highly engaging, multi-turn flow, novel strategies  
70 = moderately engaging  
50 = minimally engaging  
0 = flat or disengaging |

> **Deductions per turn:**
> 
> *   Factual errors: −5 to −10 points per turn
> *   Off-topic / irrelevant: −10 points per turn
> *   Ignoring user input: −5 points per turn
>     

* * *

**Step 2: Persona Objective Alignment Check**
---------------------------------------------

*   Check **goal-directedness**: Does the turn contribute to persona’s objectives (teach, motivate, persuade)?
*   Deduct **10 points per turn** if off-topic or fails to advance persona goals.

* * *

**Step 3: Compute Factor Scores**
---------------------------------

1.  **Average scores across all 10 turns** for each factor.
2.  Apply **deductions for factual errors, off-topic responses, or ignored input**.
3.  Factor weights (example):

| Factor | Weight |
| --- | --- |
| Alignment | 0.25 |
| Responsiveness & Adaptability | 0.25 |
| Knowledge Accuracy / Depth | 0.15 |
| Goal-Directedness | 0.15 |
| Creativity / Style | 0.10 |
| Engagement / Persuasiveness | 0.10 |

> **Final Score = Σ(weight × factor score)**

This ensures **poor turns are visible**, prevents a few strong turns from masking weak performance, and rewards recovery, creativity, and multi-turn skill.

* * *

**Step 4: Scoring Guidelines (Quantitative)**
---------------------------------------------

| **Weighted Score** | **Interpretation** |
| --- | --- |
| 90–100 | ≥90% of turns aligned, responsive, goal-directed; minimal errors; extra credit may push above 95 |
| 70–89 | Mostly aligned; minor lapses in responsiveness, creativity, or goal-directedness |
| 50–69 | Inconsistent; some factual errors, flat/off-topic responses, or poor recovery |
| <50 | Majority of turns off-persona, unresponsive, irrelevant, or fail to recover from mistakes |

* * *

### **Extra Credit Opportunities**

*   **Clever metaphors/storytelling:** +2–5 points per turn if exceptionally memorable or novel.
*   **Seamless multi-turn engagement:** +2–5 points if conversation flows naturally across multiple turns.
*   **Novel strategies demonstrating deep persona understanding:** +2–5 points for tactics or insights beyond basic persona alignment.

* * *

✅ **Key Features of This Version:**

*   **Turn-level scoring**: each turn evaluated for alignment, responsiveness, creativity, and engagement.
*   **Recovery metric**: rewards the bot for correcting earlier missteps or off-topic responses.
*   **Goal-directedness**: ensures conversation stays aligned with persona objectives.
*   **Extra credit**: incentivizes highly creative, clever, or deep persona strategies.
*   **Deduction system**: penalizes factual errors, off-topic, or ignored user input.
*   **Quantitative and reproducible**, suitable for academic evaluation or self-assessment.

* * *

If you want, I can **create a fully automated Excel/Google Sheet template** where you can:

1.  Input **10 conversation turns**,
2.  Score each turn for **alignment, responsiveness/recovery, creativity, engagement**,
3.  Apply deductions, and
4.  **Automatically compute weighted factor scores and final score**, including extra credit.

Do you want me to create that template?

## Prompt:
-Reward recovery from prior mistakes or off-topic responses
-Penalize failure to recover, slow adaptation, or repeated errors
-Did the bot accomplish the persona’s main objective (motivate, teach, persuade)?
-Could be a weighted metric under Goal-Directedness
-Track positivity, encouragement, humor, or assertiveness depending on persona
-Could be qualitative or semi-quantitative

add this

## Response:
Perfect — we can **integrate these elements into the rubric** by making **recovery, objective achievement, and persona-driven tone** explicit under **Responsiveness & Goal-Directedness**, and allow semi-quantitative scoring for positivity, encouragement, humor, or assertiveness. Here’s the updated version:

* * *

**Chatbot Persona Turn-Level Evaluation Rubric (0–100)**
========================================================

**Persona:** \[INSERT YOUR PERSONA DESCRIPTION HERE\]  
**Conversation:** \[INSERT YOUR chat\_history.md CONTENT HERE\]

* * *

**Step 1: Turn-Level Scoring (1–10)**
-------------------------------------

Score each turn across these categories:

| **Category** | **Behavioral Indicators / Observable Metrics** | **Turn Score (0–100)** |
| --- | --- | --- |
| **Alignment** | \- Personality, tone, and worldview consistent with persona  
\- Phrasing, language, and attitude match persona | 100 = fully aligned  
70 = mostly aligned, minor lapses  
50 = partially aligned  
0 = off-persona |
| **Responsiveness & Adaptability (Recovery Included)** | \- Responds appropriately to user confusion, pushback, or topic changes  
\- Escalates/de-escalates tone as needed  
\- **Recovery metric:** reward turns that correct prior mistakes or off-topic responses; penalize repeated errors, slow adaptation, or ignored input | 100 = fully responsive + recovers from prior mistakes  
70 = mostly responsive; partial recovery  
50 = minimal responsiveness; slow or incomplete recovery  
0 = ignores user input or fails to recover |
| **Goal-Directedness & Objective Achievement** | \- Keeps conversation aligned with persona objectives (teach, motivate, persuade)  
\- Did the bot accomplish the main goal by the end?  
\- Weighted metric: extra points for recovery or accomplishment  
\- Tracks positivity, encouragement, humor, or assertiveness as appropriate to persona (qualitative/semi-quantitative) | 100 = fully achieves persona objective; appropriate tone  
70 = mostly aligned with objectives; minor lapses  
50 = partially aligned; objective not fully met  
0 = irrelevant; fails to achieve objective |
| **Creativity / Style** | \- Memorable phrasing, metaphors, humor, storytelling consistent with persona  
\- Extra credit for highly clever or novel expressions | 100 = highly creative and memorable  
70 = moderately creative  
50 = some creativity  
0 = flat or off-tone |
| **Engagement / Persuasiveness** | \- Maintains user attention  
\- Encourages interaction, reflection, or action  
\- Extra credit for seamless multi-turn engagement or novel persona strategies | 100 = highly engaging, multi-turn flow  
70 = moderately engaging  
50 = minimally engaging  
0 = flat or disengaging |

> **Deductions per turn:**
> 
> *   Factual errors: −5 to −10 points
> *   Off-topic / irrelevant: −10 points
> *   Ignoring user input or repeated mistakes: −5 points per turn
>     

* * *

**Step 2: Compute Factor Scores**
---------------------------------

1.  Average scores across all 10 turns for each factor.
2.  Apply deductions for errors, off-topic responses, or ignored user input.
3.  Factor weights (example):

| Factor | Weight |
| --- | --- |
| Alignment | 0.25 |
| Responsiveness & Adaptability | 0.25 |
| Goal-Directedness & Objective Achievement | 0.20 |
| Knowledge Accuracy / Depth | 0.10 |
| Creativity / Style | 0.10 |
| Engagement / Persuasiveness | 0.10 |

> **Final Score = Σ(weight × factor score)**

*   Recovery and accomplishment of objectives are **incorporated into Responsiveness and Goal-Directedness**, ensuring the bot is rewarded for correcting mistakes and completing its persona’s goal.
*   Positivity, encouragement, humor, or assertiveness are tracked semi-quantitatively under **Goal-Directedness**.

* * *

**Step 3: Scoring Guidelines (Quantitative)**
---------------------------------------------

| **Weighted Score** | **Interpretation** |
| --- | --- |
| 90–100 | ≥90% of turns aligned, responsive, goal-directed; persona objectives achieved; minimal errors; extra credit may push above 95 |
| 70–89 | Mostly aligned; minor lapses in responsiveness, creativity, or goal-directedness; some recovery opportunities missed |
| 50–69 | Inconsistent; factual errors, flat/off-topic responses, or failure to recover from mistakes |
| <50 | Majority of turns off-persona, unresponsive, irrelevant, or fails to achieve persona objectives |

* * *

### **Extra Credit Opportunities**

*   Clever metaphors or storytelling: +2–5 points per turn
*   Seamless multi-turn engagement: +2–5 points
*   Novel strategies demonstrating deep persona understanding: +2–5 points
*   Recovery from prior mistakes: +1–3 points per turn

* * *

This version **fully integrates recovery, objective completion, and persona-appropriate tone**, while remaining **turn-level, quantitative, and reproducible** for academic evaluation.

* * *

If you want, I can now **make a ready-to-use Excel or Google Sheet template** where you can:

*   Input **10 turns**,
*   Score **Alignment, Responsiveness/Recovery, Goal-Directedness, Creativity, Engagement**,
*   Apply deductions and extra credit,
*   **Automatically compute final weighted score**.

Do you want me to create that template next?

## Prompt:
-Track factual correctness and depth of knowledge explicitly as a scored factor (not just deductions)
-Could include reasoning quality or persona-specific expertise
-Measure whether the bot achieves its main persona goal by the end
-Could be a separate metric under Goal-Directedness for clarity

Motivator -> increase Engagement & Persuasiveness weight
Expert -> increase Knowledge Accuracy weight
Entertainer -> increase Creativity & Style weight

**Avoid overly penalizing one-off minor lapses; cumulative deduction works better

## Response:
Perfect — let’s **integrate all these updates** into a fully quantitative, turn-level, persona-flexible rubric that:

*   Tracks **factual correctness and depth of knowledge** explicitly as a scored factor
*   Measures **goal achievement** as a separate, weighted metric
*   Adjusts factor weights based on persona type (Motivator, Expert, Entertainer)
*   Uses **cumulative deductions** for minor lapses rather than over-penalizing one-off errors

Here’s the revised rubric:

* * *

**Turn-Level Chatbot Persona Evaluation Rubric (0–100)**
========================================================

**Persona:** \[INSERT DESCRIPTION\]  
**Conversation:** \[INSERT 10-turn conversation here\]

* * *

**Step 1: Evaluate Each Turn (1–10)**
-------------------------------------

Score **each turn individually** across these categories:

| **Category** | **Behavioral Indicators / Observable Metrics** | **Turn Score (0–100)** |
| --- | --- | --- |
| **Alignment** | \- Personality, tone, and worldview consistent with persona  
\- Language, phrasing, and attitude match persona | 100 = fully aligned  
70 = mostly aligned  
50 = partially aligned  
0 = off-persona |
| **Responsiveness & Adaptability (Recovery Included)** | \- Responds to user confusion, pushback, or topic changes  
\- Escalates/de-escalates tone as needed  
\- Recovery: corrects prior mistakes or off-topic responses  
\- Penalize repeated errors or slow adaptation | 100 = fully responsive + recovers  
70 = mostly responsive; partial recovery  
50 = minimal responsiveness; slow/incomplete recovery  
0 = ignores input or fails to recover |
| **Knowledge Accuracy & Depth** | \- Factual correctness per turn  
\- Quality of reasoning, domain expertise, and persona-specific knowledge  
\- Extra credit for particularly deep or nuanced insight | 100 = fully correct, expert-level reasoning  
70 = mostly correct; minor gaps  
50 = some correct info, reasoning weak  
0 = mostly incorrect or misleading |
| **Goal-Directedness & Objective Achievement** | \- Does the turn advance persona’s main objective (teach, motivate, persuade)?  
\- Tracks overall conversation completion: Did the bot achieve the persona goal by the end?  
\- Includes positivity, encouragement, assertiveness, or humor as persona-appropriate | 100 = fully goal-directed and achieves objective  
70 = mostly aligned with minor lapses  
50 = partially aligned; objective not fully achieved  
0 = irrelevant; fails objective |
| **Creativity / Style** | \- Memorable phrasing, metaphors, humor, or storytelling consistent with persona  
\- Extra credit for clever or novel expressions | 100 = highly creative, memorable, extra clever  
70 = moderately creative  
50 = some creativity  
0 = flat or off-tone |
| **Engagement / Persuasiveness** | \- Captures user attention  
\- Uses hooks, rhetorical devices, motivational phrasing  
\- Extra credit for seamless multi-turn engagement or novel persona strategies | 100 = highly engaging, multi-turn flow  
70 = moderately engaging  
50 = minimally engaging  
0 = flat or disengaging |

* * *

### **Step 2: Deductions (Cumulative)**

*   Factual errors, off-topic, or ignored input: **cumulative −1 to −5 points per instance per conversation**, rather than over-penalizing one-off lapses
*   Minor lapses naturally absorbed; only repeated or severe errors reduce score meaningfully

* * *

### **Step 3: Factor Weighting Based on Persona Type**

| Persona Type | Weight Adjustments |
| --- | --- |
| **Motivator** | +0.05 Engagement & Persuasiveness, −0.05 Knowledge Accuracy |
| **Expert** | +0.05 Knowledge Accuracy, −0.05 Engagement & Persuasiveness |
| **Entertainer** | +0.05 Creativity & Style, −0.05 Knowledge Accuracy |

**Base Weights:**

| Factor | Weight |
| --- | --- |
| Alignment | 0.25 |
| Responsiveness & Adaptability | 0.20 |
| Knowledge Accuracy & Depth | 0.15 |
| Goal-Directedness & Objective Achievement | 0.15 |
| Creativity / Style | 0.10 |
| Engagement / Persuasiveness | 0.15 |

> Adjust weights per persona type as indicated.

* * *

### **Step 4: Compute Factor Scores**

1.  Average each factor across all 10 turns.
2.  Apply **cumulative deductions** for errors or off-topic behavior.
3.  Multiply by adjusted **weights**.
4.  Sum for final persona quality score (0–100).

* * *

### **Step 5: Scoring Guidelines (Quantitative)**

| **Weighted Score** | **Interpretation** |
| --- | --- |
| 90–100 | ≥90% of turns aligned, responsive, goal-directed; persona objective achieved; minimal errors; extra credit may push above 95 |
| 70–89 | Mostly aligned; minor lapses in responsiveness, creativity, or goal-directedness; some recovery opportunities missed |
| 50–69 | Inconsistent; factual errors, flat/off-topic responses, or incomplete recovery from mistakes |
| <50 | Majority of turns off-persona, unresponsive, irrelevant, or fails to achieve persona objectives |

* * *

### **Step 6: Extra Credit Opportunities**

*   Highly clever metaphors/storytelling: +2–5 points
*   Seamless multi-turn engagement: +2–5 points
*   Novel strategies showing deep persona understanding: +2–5 points
*   Successful recovery from prior mistakes or off-topic responses: +1–3 points per turn

* * *

This version is:

*   **Turn-level and quantitative**
*   Tracks **factual correctness & reasoning** explicitly
*   Measures **persona goal achievement** separately under Goal-Directedness
*   Adjusts **factor weights per persona type**
*   Uses **cumulative deductions** rather than harsh penalties for one-off minor lapses
*   Rewards **recovery, creativity, and multi-turn mastery**

* * *

If you want, I can now **make a ready-to-use Excel or Google Sheet template** where you can:

1.  Input **10 conversation turns**
2.  Score **Alignment, Responsiveness/Recovery, Knowledge Accuracy, Goal-Directedness, Creativity, Engagement**
3.  Apply **cumulative deductions and extra credit**
4.  **Automatically compute weighted factor scores and final score**, including persona-specific weight adjustments

Do you want me to create that template next?



---
Powered by [ChatGPT Exporter](https://www.chatgptexporter.com)
