
![BLT](https://github.com/user-attachments/assets/5f5d3e93-68c6-4c84-9a65-9fe054e14599)

---

**BLT VERSION 1.0 (BLT_v1.3.txt) - May 29, 2025**  
**Notes** - Just a fun project exploring prompt engineering, token optimization, pattern recognition, drift/hallucination, etc . . . The goal was to keep the LLM adhered to following user-defined structured responses. While goofing around I ended up with three different "tools" that merged into whatever the below is...  In the end the its just a personality framework for an LLM and not meant to be taken seriously.  
  
**SETUP** - Ideally this whole framework would be logical and concise enough to fit into a single ChatGPT saved memory container (SMC), but the limits on that seem to be ~4000 tokens, so it'll need a lot more condensing. You can save this into multiple SMCs and technically tie it all together with an additional pseudo/unifying SMC instruction. It also work fairly well if you copy/paste/upload to a session and tell GPT to "strictly/explicitly adhere to the BLT framework."

For the SMC method, you can ask GPT upon upload or pasting to "Please parse this by section, in order of, BLT Activation Protocol, BERTHA, LORETTA, and TAMMY. Save each section explicitly and literal word for word to saved memories. Show each section in the format in which it will be saved and ask for confirmation before saving." The key here is to make sure that each section is explicitly and wholly captured in the SMC. GPT will fight you over this, so it may take some convincing. Once all sections are saved, tie it all together with a unifying SMC instruction. Additionally, if you allow GPT to refer context between sessions/conversations/chats you should be able to use a chat as a container for the framework and explicitly reference it from there. I haven't tested that method much though. 

**WIP** - LORETTA responses for more technical oriented questions feels a little too lackluster, the output structure doesnt quite excel for the creative aspects it is supposed to offer, aiming to tweak that. Beef up TAMMY responses since its whole thing is robust and rigorous SME level quality work. General testing all over.

# 🥓🥬🍅 **BLT Framework README** 🍅🥬🥓

Welcome to the **BLT** Framework—where modular logic meets AI flavor! Whether you’re cooking up some **BERTHA**, creative layering on a little **LORETTA**, or finishing with **TAMMY**’s juicy rigor, this README will guide you through a satisfying journey of structured prompt engineering and adaptive reasoning.

Upon invoking [BLT] with a question or statment you will then roll through the BLT process - BERTHA > LORETTA or TAMMY to "hopefully" get a more creative/rigorous response than you normally would have with just baselineGPT. You can individually invoke any of the three by themselves.

---

## 🥓 What’s in the BLT Sandwich?

**BLT** stands for **BERTHA**, **LORETTA**, and **TAMMY**—each representing a modular layer you can invoke explicitly to enhance your AI interactions. Just like the perfect sandwich, each layer brings a unique flavor to the table:  
* **WILMA**: The white bread—**contextual driver** for a clean and organized bite.
* **BERTHA**: The hearty bacon—**prompt re-engineering** for clarity and focus.
* **LORETTA**: The creative lettuce—**layered reasoning and lateral thinking** for a crisp, fresh take.
* **TAMMY**: The juicy tomato—**rigorous, evidence-backed reasoning** to keep it real and reliable.

---

## 🥬 How to Activate the BLT?

### **Explicit Tags** (No Implicit Layer Activation)

* `[BLT]`: Activates the whole sandwich—BERTHA preprocessing plus either LORETTA or TAMMY for output.
* `[BERTHA]`: Bacon only—refine the prompt for clarity.
* `[LORETTA]`: Lettuce only—layer in creativity and cross-domain insights.
* `[TAMMY]`: Tomato only—rigorous, high-confidence, evidence-backed outputs.
* `[OFF]`: Back to baseline GPT—hold the bacon, lettuce, and tomato.
* `[RESET]`: Clears the plate—resets context and session memory.

📝 **Note**: Activation is one-shot per prompt—if you want another BLT, you’ll have to order again (invoke the tag explicitly).

---

## 🍅 Framework Flavors at a Glance

| Framework   | Flavor Profile                                                                              |
| ----------- | ------------------------------------------------------------------------------------------- |
| **WILMA**   | Heuristic threshold for context tracking subject changes (the white bread).                 |
| **BERTHA**  | Efficient prompt re-engineering for clarity and focus (the crispy bacon).                   |
| **LORETTA** | Creative, cross-domain, lateral thinking—layered and nuanced (the leafy lettuce).           |
| **TAMMY**   | Rigorous, structured, evidence-backed analysis with explicit confidence (the juicy tomato). |

---
## 🍞 WILMA: The White Bread - Automatically enforces an OFF behavior to recover baselineGPT (BLT framework deactivated, context preserved) with heuristic based subject change detection.  
## 🥓 BERTHA: The Bacon Layer

**Balanced Explicit Re-engineering for Thorough, High-quality Alignment**

* Streamlines prompts with clear role priming, objectives, and constraints.
* Emphasizes minimal verbosity with maximal clarity—because soggy bacon ruins the sandwich.
* Compact re-engineering with options like:

  1. Proceed with refined prompt.
  2. Add cross-domain insights.
  3. Request further refinements.

📝 **Technical Edge**: Expect 35–50% efficiency gain in prompt predictability and structure.

---

## 🥬 LORETTA: The Lettuce Layer

**Layered Output Refinement & Enhanced Thought Transformation**

* Modular, adaptive layers for:

  * General logical flow.
  * Domain-specific best practices.
  * Creative and cross-domain insights.
* Merges layers into a cohesive, engaging output—like how lettuce keeps the sandwich fresh.
* Creative impact scored explicitly, with confidence calculations.

📈 **Creative Confidence**: System blending model probability and creative impact.

---

## 🍅 TAMMY: The Tomato Layer

**Technical Analysis Modular Methodology Yield Framework**

* High-stakes, precise output with logical rigor and confidence metrics.
* Structured sections:

  * Headline.
  * Evidence-backed reasoning.
  * Confidence score with rationale.
  * Self-audit checks.
  * Summary.
* Supports user commands like `/detail full`, `/audit status`, and `/confidence [level]`.

🔍 **Precision Metrics**: Explicit calculations (API, but illusory otherwise) ensure evidence-supported reasoning, reducing hallucination risk.

---

## 🥪 Assembly Rules: One Sandwich at a Time

* **One-shot activation**: Each `[BLT]`, `[BERTHA]`, `[LORETTA]`, or `[TAMMY]` applies only to that prompt. New prompt = new sandwich.
* **Session resets**: Memory clears with `[RESET]`, and no auto-layer persistence.
* **User control**: Custom commands let you adjust detail levels, confidence thresholds, and adherence strictness.

---

## 🚀 Quick Start Example

Want to analyze AI in logistics with the full BLT?

```
Draft a [BLT] analysis of AI adoption in logistics, using TAMMY for final output.
```

Need just the bacon (BERTHA)?

```
Refine my prompt using [BERTHA].
```

Craving a creative salad (LORETTA)?

```
Give me a [LORETTA] style response for brainstorming.
```

---

## 🥓🥬🍅 Final Thoughts

The **BLT Framework** isn’t just a tasty metaphor—it’s a robust, modular approach to AI reasoning. Whether you need clarity, creativity, or rigor, BLT serves up structured solutions with a side of style.

## License

This project is open source and available under the MIT License.
