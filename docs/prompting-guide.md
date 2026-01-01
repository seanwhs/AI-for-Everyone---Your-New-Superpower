# Prompting Guide (`docs/prompting-guide.md`)

## 🎯 The Secret to Great AI Results

Talking to an AI is not like searching Google. On Google, you use keywords. With AI, you use **conversation and context**.

### 1. The P.R.T.C. Framework

This is the "Golden Formula" for a perfect prompt.

* **P - Persona:** Give the AI a job title.
* *Instead of:* "Give me a recipe."
* *Try:* "Act as a **professional Italian chef** with 20 years of experience."


* **R - Request:** Be specific about the task.
* *Try:* "**Write a dinner recipe** for a healthy pasta dish."


* **T - Target:** Who is the output for?
* *Try:* "The recipe should be easy for **a senior citizen with limited kitchen tools** to follow."


* **C - Constraints:** Set the boundaries.
* *Try:* "It must be **under 500 calories** and contain **no added salt**."



---

### 2. The "Chain of Thought" Technique

If a task is complex, don't ask for the final answer immediately. Ask the AI to **think step-by-step**.

* *Prompt:* "I want to start a small garden. **First**, ask me 3 questions about my space. **Then**, once I answer, suggest 3 plants that will grow well there."

---

### 3. Iterative Prompting (The "Polishing" Phase)

Rarely is the first answer perfect. Use follow-up prompts to refine the result:

* "Make that shorter and more professional."
* "Put the key points into a table."
* "Re-write this for someone who has never used Excel before."
* "Give me three different options for that headline."

---

### 4. Prompting for Gemini vs. NotebookLM

| Tool | Prompt Style | Example |
| --- | --- | --- |
| **Gemini** | **Creative & Open:** Ask it to imagine, research, or brainstorm. | "Gemini, brainstorm 5 gift ideas for a retiree who loves gardening and tech." |
| **NotebookLM** | **Grounded & Specific:** Ask questions only about the files you uploaded. | "Based on the PDF I uploaded, what are the specific dates for the community center classes?" |

---

### 💡 The "Magic Phrases"

If you get stuck, try adding these phrases to your prompt:

* *"If you aren't sure of the answer, tell me you don't know rather than guessing."* (Prevents Hallucinations).
* *"Ask me any clarifying questions you need before you start the task."* (Ensures Accuracy).
* *"Explain your reasoning behind this answer."* (Helps you Learn).

---

