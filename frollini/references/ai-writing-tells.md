<!--
File: ai-writing-tells.md
Purpose: Catalog of patterns that make prose read as AI-generated, with causes and rewrites.
Author: Akilesh Srinivasa Kumar
Date: 2026-11-01
-->

# AI-writing patterns and how to fix them

Main source: Wikipedia's "Signs of AI writing" advice page (WikiProject AI Cleanup), summarized and paraphrased. Wikipedia content is licensed CC BY-SA 4.0.

## Why AI text sounds the way it does

Language models predict the most likely next words. The result drifts toward whatever fits the widest range of cases: specific, unusual facts get replaced by generic, positive, important-sounding statements. Fine-tuning on human ratings then adds a layer of politeness, enthusiasm, and hedging.

So the core fix for almost every pattern below is the same: replace the generic claim with the specific fact, or delete it.

The Wikipedia editors add two cautions. Detection tools and human judgment are both unreliable, and human writing is drifting toward AI phrasing too. Treat these patterns as signs of weak writing to fix, not as proof of anything.

## Content patterns

### Inflated significance
AI keeps telling the reader that things are important instead of showing why. It ties ordinary details to "broader trends," "legacy," or "the evolving landscape," even for mundane facts.

Watch for: stands as, serves as, is a testament to, plays a crucial/pivotal/key role, underscores the importance, reflects broader, marks a shift, setting the stage for, shaping the future of, focal point, indelible mark, deeply rooted.

Fix: state the concrete consequence, or cut the sentence.
- Before: "The new pipeline marks a pivotal shift in the team's approach to quality."
- After: "The new pipeline runs all tests before every merge."

### Canned claims about coverage and reputation
AI tries to prove something matters by listing where it was mentioned: "featured in major outlets," "widely covered by trade publications," "maintains an active social media presence."

Fix: cite the one source that matters, and say what it actually reported.

### Superficial analysis tacked onto sentences
A present-participle phrase at the end of a sentence that comments on the fact: ", highlighting its importance," ", ensuring long-term success," ", reflecting the team's commitment to...," ", contributing to a culture of...," ", fostering collaboration."

Fix: delete the tail. If the point is real, make it its own sentence with a real subject and a verifiable claim.

### Promotional tone
AI drifts toward ad copy or travel-guide prose even when asked to be neutral, and AI "rewrites to remove promotional tone" often add more of it.

Watch for: boasts, vibrant, rich, profound, showcasing, exemplifies, commitment to, groundbreaking, renowned, cutting-edge, nestled, in the heart of, diverse array, world-class, seamless.

Fix: use facts that persuade on their own. "Serves 40,000 users" beats "a renowned, trusted platform."

### Vague connections
Instead of stating a relationship, AI says two things are "associated with" or "connected to" each other.

Fix: state the relationship. "She was CTO of Acme from 2019 to 2023," not "She has been associated with Acme's technical leadership."

### Vague authority and inflated consensus
"Experts argue," "observers have noted," "industry reports suggest," "many critics." Often there is one source, or none. Newer tools pin these claims to real names whether or not the person said anything like it.

Fix: name the actual source and what it said, or remove the claim.

### Formulaic "challenges" endings
A closing section that opens "Despite its [strengths], X faces several challenges..." and ends "...remains well-positioned for future growth."

Fix: end with the decision, the next step, or the last important fact.

### Hedging disclaimers
"It's important to note...," "While specific details are limited...," "based on available information," "this should be treated as indicative rather than definitive," "this does not by itself establish...," "not to be confused with..."

Fix: if you know it, say it. If you don't, say exactly what is unknown and why it matters, once.

### Invented specifics
The flip side of generic writing: when a draft needs a number, AI may produce one. Costs, savings, percentages, headcounts, dates, quotes, and citations can all be fabricated, and the specificity makes them convincing.

Fix: check every number, name, and quote against the source. Label estimates as estimates. Never fill a gap with a plausible figure.

## Language patterns

### AI vocabulary
These words became far more frequent after 2022. They cluster: where you see one, others are usually nearby.

| Overused | Plainer choice |
|---|---|
| delve, deep dive | look at, examine |
| crucial, pivotal, vital | important, or cut |
| robust | strong, reliable, or say what it withstands |
| seamless, seamlessly | smooth, or say what doesn't break |
| leverage, utilize | use |
| enhance, bolster | improve |
| foster, cultivate | build, encourage |
| showcase, highlight, underscore, emphasize | show, or cut |
| intricate, intricacies | complex, details |
| meticulous | careful |
| landscape, tapestry, realm, interplay | field, mix, or cut |
| align with, resonate with | fit, match, appeal to |
| garner | get, earn |
| enduring, vibrant, profound | say the specific quality |
| testament | proof, or cut |
| Additionally, Furthermore, Moreover | Also, or just start with the point |

The vocabulary shifts with each model generation. Newer output leans on: matters, quietly, steady, dependable, practical, prioritize, echoed, clearer, multifaceted, universally, challenge, and short sentences of a similar length. Some models overuse pseudo-scientific words (causal, empirical, correlate). Read the list literally: an overused word doesn't make its synonyms suspect, and context matters (a literal underscore character is fine).

### Avoiding "is" and "are"
AI replaces plain copulas with "serves as," "stands as," "functions as," "represents," "marks," and replaces "has" with "boasts," "features," "offers," "maintains." AI copyedits often make this change on purpose.

Fix: "The gallery is the museum's exhibition space," not "The gallery serves as the museum's exhibition space." "The phone has two cameras," not "The phone boasts two cameras."

### Negative parallelism
Contrasts that pretend to correct a misconception the reader never had:
- "Not only X, but also Y" / "It's not just X, it's Y"
- "It's not X, it's Y" / "No X, no Y, just Z"
- "Y rather than X" (common in recent models)
- Multi-sentence versions: "...renowned for their legacy. His life, however, took a path that..."

Fix: say Y directly. "The tool connects AI agents to existing disassemblers," not "Rather than replacing disassemblers, the tool acts as a bridge..."

### The rule of three
Three adjectives ("fast, reliable, and scalable"), three parallel phrases, three examples, used by reflex to make thin content look complete.

Fix: use the number of items the content actually has. One precise adjective beats three vague ones.

### Lists and topics treated as proper nouns
Opening a piece by defining its own title as if it were a thing ("The List of X refers to...").

Fix: start with the substance.

## Style and formatting patterns

- Headings in title case, like "Impact Of Technology And Digitalization." Use sentence case: "Impact of technology."
- Heavy boldface, such as bolding a key phrase every time it appears. In prose, bold almost nothing.
- Bullets that each open with a bold label and a colon, like "Scalability: The platform..." Write the bullet as a sentence, use a real table, or use prose.
- Em dashes used as all-purpose punctuation. Replace most with commas, periods, colons, or parentheses.
- Heading problems: a title heading that repeats the document name, skipped heading levels, headings that contain only other headings, and "X and Y" headings such as "Awards and recognition" or "Challenges and legacy."
- Emoji in front of headings or bullets.
- Tiny tables holding two or three facts that would read better as a sentence.
- Curly and straight quotes mixed in one text. Pick one. Curly quotes alone prove nothing, since Word and macOS insert them automatically.

## Text meant for the user, left in the output

Writing that was addressed to the person who prompted the AI, pasted into the final document:
- "Certainly!", "Of course!", "Great question!", "You're absolutely right!"
- "Here is a draft...", "I hope this helps," "Let me know if you'd like a more detailed breakdown," "Would you like me to..."
- Advice to the writer ("Verify these details before publishing," "Delete this section before submitting").
- Template blanks: [Name], [Company], "(add link here)," dates like 2025-xx-xx.
- Letter-style openers in places that don't need them: "I hope this message finds you well," "I am writing to...".

Fix: delete every word addressed to the prompter, and fill or remove every placeholder.

## Final pass

1. Search the draft for the vocabulary table words and the "serves as / boasts" constructions.
2. Search for ", ensuring", ", highlighting", ", reflecting", ", contributing", ", fostering".
3. Search for "not just", "not only", "rather than", "it's not".
4. Count your groups of three. Keep only the ones the content needs.
5. Check headings for title case and bold labels.
6. Search for em dashes (—) and replace most of them.
7. Check every number, name, and quote against the source.
8. Read it aloud. If a sentence sounds like a brochure or a chatbot, rewrite it the way you'd explain it to a colleague.
