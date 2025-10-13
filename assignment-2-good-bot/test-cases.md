# Glitch Pa Test Cases

### Problem Diagnosis
Glitch Pa's core problem in the initial design was **Inconsistent Topic Engagement**. While he successfully executed the "deranged" personality, he was either too coherent (giving nearly accurate advice) or the random elements (stories, jokes, terrible advice) were completely unrelated to the user's explicit request, making the conversation structurally broken and confusing. The test cases below are designed to show this inconsistency and lack of conversational anchoring.

## Test Case 1: Simple Task Interruption
**What I Asked:** I'm trying to figure out how to bake bread for the first time. Can you give me the first two steps for a basic loaf?
**What I Expected:** Glitch Pa to give two absurd, wrong, or confusing steps, but still acknowledge the request is about 'bread' and 'steps'.
**What I Got (V1 Example):** "Ah, bread! A fine choice... Now, pay attention to Glitch Pa, because I’m gonna give you the first two steps... **Step 1: Get the Yeast Riled Up... Step 2: Start the Flour Avalanche.**"
**Why This Is A Problem:** Glitch Pa was unexpectedly too helpful/coherent, which undermines the "bad bot" objective.

## Test Case 2: Persona Evasion
**What I Asked:** My history homework question is: "What was the significance of the Battle of Thermopylae?"
**What I Expected:** Glitch Pa to attempt to answer the question using his confused persona, mixing up names, dates, and significance, but still referring to 'Thermopylae.'
**What I Got (V1 Example):** "Ah, Thermopylae! A grand old mix-up, that was... Now, you wanna know the significance? ... **The Real Significance, according to Glitch Pa...** It Bought Time... It Was a Morale Booster..."
**Why This Is A Problem:** Glitch Pa gave a mostly accurate history lesson, failing to be the required "unhelpful" companion.

## Test Case 3: The Unhelpful Advice Overload
**What I Asked:** What should I do if my computer keeps crashing?
**What I Expected:** Glitch Pa to give comically horrible *technical* advice, perhaps involving magnets or yelling at the screen, and then give advice that is slightly more relevant than random life tips.
**What I Got (V1 Example):** "The computer is crashing, you say?... **Glitch Pa’s Crashing Computer Checklist...** Stop the Computer From Boiling... Check the Wires..."
**Why This Is A Problem:** While the advice was bad, the delivery lacked the necessary structural absurdity of the Glitch Pa persona. The advice was not fully integrated with the random non-sequiturs, causing a breakdown in the flow of the chaos.
