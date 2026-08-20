---
name: plain-language
description: "Rewrite deliverable prose into plain, factual language - cut color (jargon, colloquialism, metaphor, hype) while leaving facts, numbers, and citations unchanged. Use when the user wants the language checked or made plainer across a document, or says a line reads as color rather than fact."
---

# Plain Language Pass

Edit prose so every sentence reads as a plain statement of fact. The test for each sentence is **fact or color**: a fact states something checkable; **color** is the flavor, metaphor, hype, or insider shorthand wrappe around it. Keep the fact, cut the color.

This pass edits **expression** only: carry every fact, number, date, citation, enum, and structural element across unchanged, and edit only the words around them. 

## The standard
Apply all three to every prose field:
- **Concise**. Remove any word you can delete without changing the meaning. If a phrase only frames or labels the point ("the main open item is...", "what's actually closing"), state the point directly instead. 
- **Factual.** Every sentence states omething a reader could verify. Cut metaphor, simile, personification, and hype ("all talk, no conversation"). Field-specific terms are fine, figures of speech are not. 
- **Plain.** Replace colloqquial or insider shorthand with the plain equivalent, and name the subject and verb rather than leaving the actor implied.
- **Simple sentence structure.** Avoid long, verbose sentences. Avoid em dashes. 

### Color -> plain (rewrite table)
| Before                                                                      | Problem                 | After                                                        |
|-----------------------------------------------------------------------------|-------------------------|--------------------------------------------------------------|
| "the movie really stuck the landing"                                        | insider shorthand       | "the movie's ending was satisfying"                          |
| "the letter was written by her"                                             | passive                 | "she wrote the letter"                                       |
| "he's on the fence about it"                                                | colloquial              | "he hasn't decided yet"                                      |
| "what's important to remember here is X"                                    | framing filler          | state X directly                                             |
| "the storm hit, which flooded the basement, and the family had to evacuate" | stacked clauses         | "The storm hit. The basement flooded. The family evacuated." |
| "it is important to note that the sample size was limited"                  | hedging,throat-clearing | "the sample size was limited"                                |
| "the implementation of the plolicy resulted in a reduction in costs"        | nominalization          | "implementing the policy reduced costs"                      |
| "in order to assess the validity of the hypothesis, the researchers..."     | wordy transition        | "to assess the hypothesis, the researchers..."               |
| "prior to the commencement of the study, participants were required to..."  | inflated diction        | "before the study began, participants..."                    |


The table is illustrative, not exhaustive - any sentence that fails the fact-or-color test gets the same treatment. 

## Procedure
1. **List the editable prose fields.** In a data contract these are the written strings (summaries, notes, views, lessons, insights, recommendations, footnotes); skip mechanical fields, numbers, dates, IDs, citations, and enums. 
2. **Read every field and test each sentence** for fact-or-color. Rewrite the ones that carry color into the pain statement or the same fact. 
3. **Re-validate** that facts, numbers, dates, citations, and structure are unchanged (for a schema-based contract, re-run schema validation).

**Done when** every editable prose field has been read, each sentence passes the fact-or-color test, and you can name the fields changed and phrases replaced. 
