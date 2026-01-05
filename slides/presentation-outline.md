# 🎓 **AI for Everyone – Workshop Slide Deck**

---

## **Section 0: Pre-Course Quiz**

**Slide 1 – Pre-Course Quiz**
*Goal:* Gauge baseline knowledge. This quiz helps learners self-assess and provides the trainer with a sense of experience levels.

1. What does "AI" stand for?
2. Have you used ChatGPT, Gemini, or any AI tools before? (Yes/No)
3. Do you think AI is mostly for programmers?
4. What is one thing you hope AI can help you with today?

**Trainer Tip:** Encourage open discussion to normalize curiosity. Share responses briefly and set a relaxed tone.

---

## **Section 1: Understanding AI**

**Slide 2 – What is AI?**

* **AI** = machines performing tasks that usually require human intelligence.
* Works through **patterns, probabilities, and algorithms**.
* Key takeaway: AI **augments** human capabilities, it does not replace human judgment.

**Trainer Tip:** Use an example like “AI as a tool, not a replacement.”

---

### **Group Activity: Defining AI Together**

**Slide 3 – Group Activity: What is AI?**
*Goal:* Build a group understanding of AI.

* **Instructions:** Break into small groups (3-4 people). Discuss:

  * What does AI mean to you?
  * Can you think of an example of AI in your daily life?
* After 10 minutes, each group will share their thoughts with the class.

**Trainer Tip:** Emphasize that there are no wrong answers; encourage diverse perspectives.

---

**Slide 4 – Layman Analogy**

* AI is like a **fallible, brilliant intern**.
* It's fast, mostly right, but still needs **your guidance**.
* Example: Predicting the next word in a sentence or summarizing text.

---

### **Group Activity: AI Intern Simulation**

**Slide 5 – Group Activity: AI Intern Simulation**
*Goal:* Understand AI’s capabilities through roleplay.

* **Instructions:** In pairs, role-play as an AI intern (one person is the intern, the other the human supervisor). The intern will try to predict the next word or phrase based on context provided by the supervisor. Swap roles after 10 minutes.
* **Example Scenario:** “I’m going to make a sandwich with…”

  * Intern predicts: “ham, cheese, and bread.”
* Discuss the accuracy of the prediction.

**Trainer Tip:** Stress that AI doesn’t “think” but makes educated guesses based on data.

---

**Knowledge Check #1**

Q: Which best describes AI?
A. A robot that thinks like a human
B. A tool that predicts patterns and helps humans make decisions ✅
C. Magic that solves all problems instantly

**Trainer Tip:** Highlight that AI predicts patterns, not "thinking."

---

## **Section 2: Large Language Models & Tokenization**

**Slide 6 – Large Language Models (LLMs)**

* AI trained on **billions of texts** (books, websites, conversations) to predict patterns.
* Analogy: **Autocomplete on steroids**.
* Strengths: Write summaries, essays, translations, code snippets.
* Limitation: Can hallucinate; output depends on **prompt quality**.

---

### **Group Activity: LLM Exploration**

**Slide 7 – Group Activity: Exploring LLMs**
*Goal:* Dive into LLM applications and limitations.

* **Instructions:** Break into groups. Each group will use either **Gemini** or **NotebookLM** to:

  * Write a summary of a news article.
  * Generate a creative poem on a random topic.
  * Summarize a scientific article.
* After 15 minutes, each group will present their prompt and the result.

**Trainer Tip:** Discuss how the quality of the prompt impacts the AI’s output.

---

**Slide 8 – Tokenization**

* Text is broken into **tokens** (letters, words, subwords).
* Analogy: Lego bricks → AI builds sentences from pieces.
* Helps AI understand context & predict coherent sequences.

---

### **Group Activity: Tokenization Challenge**

**Slide 9 – Group Activity: Tokenization Challenge**
*Goal:* Experience how AI constructs sentences from tokens.

* **Instructions:** In small groups, each group is given a set of tokenized words. Your task is to reconstruct the original sentence from the tokens.

  * Example Tokens: “AI”, “creates”, “new”, “ideas”, “solutions”.
  * Reconstruct the sentence: "AI creates new solutions."
* Discuss how tokenization helps AI manage text.

**Trainer Tip:** Emphasize that tokenization is key to AI’s ability to interpret and generate language.

---

**Slide 10 – Tokenization & AI Learning**

* Tokenization allows AI to build an understanding of sentence structure.
* **Example:** In the sentence "AI creates new solutions," AI analyzes the relationship between tokens to predict the correct output.
* Tokenization is the first step toward creating **contextual understanding**.

---

## **Section 3: Gemini vs. NotebookLM**

**Slide 11 – Google Gemini: The Brainstormer**

* Creative, connected to **live internet**.
* Great for brainstorming, drafting, summarizing online content.
* High “temperature” → more diverse and creative outputs.

**Trainer Tip:** Demonstrate Gemini’s creative use with examples like “generate a poem on friendship” or “create a wedding speech.”

---

**Slide 12 – NotebookLM: The Librarian**

* Grounded in **your uploaded documents**.
* Great for personal summaries, interactive learning, or audio guides.
* Uses **RAG** (Retrieval-Augmented Generation) to ensure factual consistency.

**Trainer Tip:** Emphasize NotebookLM’s ability to **ensure accuracy** with document-based content.

---

**Knowledge Check #3**

Q: To summarize your own PDF, which tool would you use?
A. Gemini
B. NotebookLM ✅

**Trainer Tip:** Explain that Gemini is best for creative tasks, while NotebookLM is great for precise summaries.

---

### **Group Activity: Gemini vs. NotebookLM Showdown**

**Slide 13 – Group Activity: Gemini vs. NotebookLM**
*Goal:* Compare Gemini’s creativity with NotebookLM’s precision.

* **Instructions:** In groups, each will:

  * Use **Gemini** to generate a 5-sentence summary of a news article.
  * Upload the article to **NotebookLM** and generate a fact-checked version.
* After 15 minutes, each group will share their findings and discuss the strengths and weaknesses of each tool.

**Trainer Tip:** Highlight Gemini’s **creativity** vs. NotebookLM’s **precision**.

---

## **Section 4: The P.R.T.C. Prompting Framework**

**Slide 14 – Why Prompting Matters**

* AI is **literal**: vague prompts = generic answers.
* Structured prompts = **actionable, reliable outputs**.

---

**Slide 15 – P.R.T.C. Method**

* **P — Persona:** Assign AI a role (e.g., “Physiotherapist”).
* **R — Request:** Specify the task (e.g., “5 senior-safe exercises”).
* **T — Target:** Define the audience and tone (e.g., “For beginners age 70+”).
* **C — Constraints:** Set word count, equipment needed, style, or safety guidelines.

---

**Slide 16 – P.R.T.C. & AI Output Quality**

* Well-crafted prompts result in **reliable outputs**.
* Example: Compare "Write a summary of this research paper" to “Summarize this paper written for 70+ year olds, focusing on physical activity.”

---

**Knowledge Check #4**

Q: PRTC helps you:
A. Write essays automatically
B. Craft **effective prompts for AI** ✅
C. Check grammar in a document

**Trainer Tip:** Demonstrate “bad prompt → PRTC prompt” live to show the difference.

---

### **Group Activity: Craft a P.R.T.C. Prompt**

**Slide 17 – Group Activity: Craft a Perfect Prompt**
*Goal:* Master the P.R.T.C. framework together.

* **Instructions:** In groups, create a detailed prompt using the P.R.T.C. framework. Choose a task such as:

  * Write a travel guide for senior citizens.
  * Generate a list of 5 beginner-level exercises for older adults.
  * Create a personalized meal plan for someone with dietary restrictions.
* After 15 minutes, each group will share their prompt and results.

**Trainer Tip:** Explain how each part of the P.R.T.C. framework improves AI’s output.

---

## **Section 5: Applying Knowledge – Sarcopenia Lab**

**Slide 18 – Lab Objective**

* Create **personalized exercise & nutrition guidance for seniors**.
* **Phase 1:** Use Gemini to draft a research-based article.
* **Phase 2:** Upload to NotebookLM to create an **audio guide**.

---

### **Group Activity: Sarcopenia Lab Collaboration**

**Slide 19 – Group Activity: Sarcopenia Lab**
*Goal:* Apply AI to real-world challenges.

* **Instructions:** In small groups, use **Gemini** to write an article on sarcopenia (muscle loss in older adults). Then, upload the article to **NotebookLM** for conversion into an audio guide.

  * Focus on **balance exercises** and **nutrition tips**.
* After 30 minutes, discuss how your article turned out and how NotebookLM improved the audio guide.

**Trainer Tip:** Encourage feedback on AI


’s **effectiveness and accuracy** in real-world applications.

---

**Knowledge Check #5**

Q: NotebookLM is safer than Gemini for:
A. Brainstorming new ideas
B. Summarizing uploaded research ✅

---

## **Section 6: AI in Daily Life**

**Slide 20 – Quick Wins with AI**

* **Excel formulas:** Tax/discount calculations.
* **Meal planning:** Using leftover ingredients.
* **Homework explanations:** Simple, clear breakdowns.
* **AI is collaborative:** You verify the output.

---

### **Group Activity: AI in Your Life**

**Slide 21 – Group Activity: Plan Your Day with AI**
*Goal:* Apply AI tools to real-life scenarios.

* **Instructions:** In groups, plan a full day using AI tools. Each member will choose one task:

  * Plan meals for the day with Gemini.
  * Generate an exercise routine with NotebookLM.
  * Plan a study schedule or homework with ChatGPT.
* After 15 minutes, present your **AI-powered day plan**.

---

**Knowledge Check #6**

Q: Plan a 3-day walking tour for a senior citizen. Which AI tool?
A. Gemini ✅
B. NotebookLM

---

## **Section 7: Ethics & Hallucinations**

**Slide 22 – Hallucinations**

* AI can produce **plausible but incorrect outputs**.
* Always **verify critical information**.
* AI should be treated as a **first draft assistant**, not the final authority.

---

### **Group Activity: Fact-Check with AI**

**Slide 23 – Group Activity: Fact-Checking with AI**
*Goal:* Practice verifying AI-generated content.

* **Instructions:** Use **Gemini** or **NotebookLM** to generate an article or answer a factual question. Then, fact-check the result using **reliable sources**.

  * Example: “Who won the World Series in 2020?”
* Discuss any discrepancies and why verifying AI content is essential.

---

## **Section 8: Machine Learning Essentials**

**Slide 24 – Core Concepts**

* **Machine Learning (ML):** AI that learns from data patterns.
* **Supervised Learning:** Uses labeled data.
* **Unsupervised Learning:** Uses unlabeled data.
* **Reinforcement Learning:** Uses trial and error.
* **Overfitting:** Learns noise and patterns → poor generalization.
* **Underfitting:** Too simple → misses patterns.

---

**Knowledge Check #8**

Q: Overfitting occurs when:
A. Model learns noise + patterns → poor on new data ✅
B. Model generalizes well
C. Model ignores labels

---

### **Group Activity: Training a Model**

**Slide 25 – Group Activity: Train Your Model**
*Goal:* Simulate machine learning with real-world data.

* **Instructions:** In small groups, each will:

  * Classify fruits by color and shape.
  * Predict customer purchases based on demographics.
* After 15 minutes, discuss overfitting and underfitting.

---

## **Section 9: Lab 2 – Home & Work Use Cases**

**Slide 26 – Path A: Excel Wizard**

* **Activity:** Create formulas for tax/discount calculations.
* **Instructions:** Use AI in Excel for real-world scenarios.

**Slide 27 – Path B: Kitchen Magic**

* **Activity:** Plan meals from leftovers.
* **Instructions:** Use **PRTC** to guide meal planning.

**Slide 28 – NotebookLM Integration**

* **Activity:** Upload recipes or tasks.
* **Instructions:** Generate shopping lists or troubleshooting guides.

---

**Knowledge Check #9**

Q: P.R.T.C. stands for:
Persona, Request, Target, Constraints ✅

---

## **Section 10: Post-Course Reflection & Quiz**

**Slide 29 – Post-Course Quiz**

1. What does "AI" stand for?
2. Which statement best describes AI?
3. Which tools did you use today?
4. How confident are you using AI now?
5. Give an example of AI application in your life.
6. Which tool for: Research current news / Summarize PDF / Brainstorm ideas?
7. One surprising thing you learned.

---

**Slide 30 – Knowledge Check #10 (Optional Discussion)**

* **Group Activity:** Reflect on key takeaways from the course.

  * Discuss practical applications learned.
  * Share how AI can assist in daily life.

---

## ✅ **Key Takeaways**

* AI **augments human capability**, not replaces it.
* **Gemini** = creative breadth; **NotebookLM** = precision & grounding.
* **P.R.T.C.** helps craft **better prompts**.
* Knowledge checks reinforce **learning & retention**.

---

