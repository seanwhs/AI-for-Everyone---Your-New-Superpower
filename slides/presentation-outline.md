# 🎓 **AI for Everyone – Workshop Slide Deck**

---

## **Section 0: The Baseline**

**Slide 1 – Welcome & Vision**

* **The Goal:** Moving from AI "Magic" to AI "Mastery."
* **Workshop Motto:** "AI won't replace humans, but humans using AI will replace those who don't."

**Slide 2 – Pre-Course Quiz (Self-Reflection)**

1. What does "AI" stand for?
2. How many times have you used AI today? (Think: Siri, Maps, Netflix).
3. On a scale of 1-10, how much do you trust AI outputs?
4. What is the #1 manual task you want to delegate to an "AI Intern"?

**Slide 3 – Group Activity: The AI Scavenger Hunt**

* **Task:** In groups of 3, look at your phones. Find **three** apps that use AI to make your life easier.
* **Discussion:** Does the AI in these apps make decisions *for* you, or does it give you *options*?

---

## **Section 1: AI Foundations**

**Slide 4 – What is AI? (The Core)**

* **Not Magic:** It is advanced statistics—predicting the most likely "next piece" of information.
* **Augmentation:** It enhances your brain; it doesn't replace your judgment.
* **The Rule:** Human (Strategy) + AI (Execution) = Peak Productivity.

**Slide 5 – Layman Analogy: The "Fallible Intern"**

* AI is a **brilliant intern** who has read every book in the world but lacks "life experience."
* It is fast and mostly right, but it needs **your guidance** to stay accurate.

**Slide 6 – Knowledge Check #1: The AI Nature**

* **Question:** If an AI gives you a wrong answer, whose fault is it?
* **A)** The AI’s (It’s broken).
* **B)** Yours (The instructions were vague). ✅
* **C)** Nobody’s (It’s just magic).

---

## **Section 2: The Engine Room (LLMs & Tokenization)**

**Slide 7 – Large Language Models (LLMs)**

* Trained on **billions of conversations**.
* It is **Autocomplete on Steroids**.
* It predicts the "next token" based on the patterns it learned from the internet.

**Slide 8 – Deep Dive: What is Tokenization?**

* AI doesn't see "words" like humans do. It breaks text into **Tokens**.
* **Tokens** are the atoms of language. They can be whole words, single letters, or even sub-words.
* **Analogy:** If a sentence is a Lego castle, tokens are the individual Lego bricks used to build it.

**Slide 9 – Why doesn't AI just use "Words"?**

* **Efficiency:** Common words (like "the") are one token. Rare words are broken down.
* **Grammar:** By seeing `[walk]` and `[ed]` as separate tokens, AI understands that `[ed]` means "past tense" across *all* verbs.
* **Math:** AI converts these tokens into numbers so it can do "math" on language.

**Slide 10 – Tokenization Example: Breaking it Down**

* **Sentence:** "Eating healthy is unbelievable."
* **How AI sees it:**
1. `[Eat]`
2. `[ing]` (Suffix meaning action)
3. `[healthy]`
4. `[is]`
5. `[un]` (Prefix meaning not)
6. `[believ]`
7. `[able]` (Suffix meaning capable of)


* **Total:** 4 words, but **7 tokens**.

**Slide 11 – Group Activity: The Tokenization Puzzle**

* **Task:** Reconstruct this sentence from tokens: `[AI]` `[helps]` `[peo]` `[ple]` `[work]` `[smart]` `[er]`.
* **Reflection:** Why did the AI break "smarter" into `[smart]` and `[er]`?
* **Answer:** Because `[er]` means "more," and the AI can apply that logic to `[fast]` + `[er]` or `[strong]` + `[er]`.

**Slide 12 – Knowledge Check #2: Token Mastery**

* **Question:** In the word "Cooked," how many tokens does the AI likely see?
* **A)** 1 (`[Cooked]`)
* **B)** 2 (`[Cook]` + `[ed]`) ✅
* **C)** 6 (`[C]` `[o]` `[o]` `[k]` `[e]` `[d]`)

---

## **Section 3: Tool Selection (Gemini vs. NotebookLM)**

**Slide 13 – Google Gemini: The Creative Generalist**

* **Internet-connected.** Best for brainstorming, latest news, and creative drafts.

**Slide 14 – NotebookLM: The Targeted Specialist**

* **File-grounded.** Best for your personal PDFs, medical reports, or work notes.
* **Superpower:** It cites its sources directly from *your* documents.

**Slide 15 – Knowledge Check #3: Tool Match-Up**

* Which tool for...
1. Summarizing your personal health check report? (**NotebookLM**)
2. Writing a funny speech for a friend's birthday? (**Gemini**)
3. Finding a recipe for a cake based on 2026 food trends? (**Gemini**)



---

## **Section 4: The P.R.T.C. Framework**

**Slide 16 – Why P.R.T.C. is Your "Command Center"**

* Vague Prompt = Generic Junk.
* Structured Prompt = Professional Output.

**Slide 17 – The P.R.T.C. Breakdown**

* **P — Persona:** Who is the AI? (e.g., "Medical Researcher")
* **R — Request:** What is the specific job? (e.g., "Analyze these lab results")
* **T — Target/Template:** How should it look? (Table? Email? List?)
* **C — Constraints:** What are the boundaries? (Simple language, max 100 words).

**Slide 18 – Group Activity: The "Persona" Shift**

* **Task:** Get a recipe for "Chicken Soup."
* **Group 1:** Persona = "A busy parent on a budget."
* **Group 2:** Persona = "A Michelin-star Italian chef."
* **Observation:** The *data* is the same, but the *Persona* changes the soul of the output.

**Slide 19 – Knowledge Check #4: P.R.T.C. Essentials**

* **Question:** You want a summary of a report. You tell the AI "Be brief." Which part of P.R.T.C. did you just use?
* **A)** Persona
* **B)** Constraints ✅
* **C)** Target

---

## **Section 5: Ethics & Safety**

**Slide 20 – Hallucinations: Confident Lies**

* AI predicts the *next likely token*. It doesn't check a "truth database."
* If "Fact A" is rare, it might substitute "Fact B" because it's more mathematically likely.

**Slide 21 – Group Activity: The Fact-Check Duel**

* **Task:** Ask AI for a "Surprising historical fact about your hometown."
* **Challenge:** Use your phone to verify it. Does it exist? Is the date correct?

---

## **Section 6: Deep Dive into Machine Learning (ML)**

**Slide 22 – Overfitting vs. Underfitting**

* **Overfitting:** Memorizing the practice test but failing the real exam (Too specific).
* **Underfitting:** Not studying enough and guessing "B" for every answer (Too general).

**Slide 23 – Group Activity: Training the Fruit Classifier**

* **Task:** "Train" a model to identify an Apple.
* **Group Rules:** It must be Red, Round, and have a Stem.
* **The Test:** Show the group a picture of a **Red Onion**.
* **Discussion:** Did your "model" fail? How do we refine the tokens/data to fix it?

---

## **Section 7: Final Reflection & Action Plan**

**Slide 24 – The "Excel Wizard" Strategy**

* Don't memorize formulas. Use P.R.T.C. to **describe** the logic, and let AI write the code.

**Slide 25 – Final Knowledge Check #5: Graduation Quiz**

1. What is a "Token"?
2. When should you use NotebookLM over Gemini?
3. Name the 4 parts of P.R.T.C.
4. What is a "Hallucination"?

**Slide 26 – Group Activity: Your AI Roadmap**

* **Task:** Draft **three** P.R.T.C. prompts you will use this week.
* 1. Personal (e.g., Health/Travel)


* 2. Professional (e.g., Email/Reports)


* 3. Creative (e.g., Hobby/Learning)



**Slide 27 – Conclusion: You are the Craftsman**

* AI is the brush; you are the artist.
* **Stay Curious. Stay Critical.**


