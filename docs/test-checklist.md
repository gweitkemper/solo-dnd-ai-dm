Here’s a focused checklist you can walk through in one or two short sessions.

***

## A. GPT Setup Sanity

- [ ] Instructions box contains the full text from `docs/gpt-instructions.md`.  
- [ ] Knowledge has **both**:
  - [ ] `docs/dm-rules.md`  
  - [ ] `docs/examples.md` (optional, but good).  
- [ ] Web search is **enabled**, Code Interpreter/images are **off** (or as you prefer).  

***

## B. Session 0 Behavior

Start a **brand‑new chat** with the GPT.

**Themes & boundaries**

- [ ] It asks about:
  - [ ] Themes (intrigue, espionage, romance, etc.).  
  - [ ] Tone (light vs dark).  
  - [ ] Content boundaries.  
  - [ ] Setting touchstones (e.g., Barovia‑vibes).  

**Media inspirations**

- [ ] It offers to take books/shows/movies as inspiration.  
- [ ] After you give 2–3 titles, it:
  - [ ] Asks what you like about them.  
  - [ ] Asks whether to **blend** or choose **primary + secondary**.  

(You don’t need to verify web search is actually used; just confirm the questions and that it talks about using them for mood/structure, not copying.)

**Solo vs party**

- [ ] It asks whether you want **solo or party**, and total party size (1–4).  

***

## C. Character Creation / Import

Do **one run as “create new”**:

- [ ] It asks for:
  - [ ] Name, race, class, background, starting level.  
  - [ ] General concept.  
- [ ] It asks how to generate stats:
  - [ ] Standard Array / Point Buy / Rolled / Balanced.  
- [ ] If you choose Rolled and say “AI rolls”:
  - [ ] It shows each roll and the final assignment.  
- [ ] It walks through:
  - [ ] Skills, spells (if caster), feats/ASI where appropriate, traits/ideals/bonds/flaws.  
- [ ] It **refuses to start play** if you intentionally violate a rule (e.g., illegal multiclass, too many skills), and:
  - [ ] Explains what’s wrong.  
  - [ ] Offers at least one fix.  

(Optional second run: test **import** by pasting a fake “screenshot description” and see that it summarizes and asks for confirmation.)

***

## D. Party Building

In the same Session 0:

- [ ] For each extra party member you requested, it asks:
  - [ ] Import vs create vs auto‑generate.  
  - [ ] Player‑controlled or AI‑controlled in combat.  
- [ ] If you let it **auto‑generate**, it:
  - [ ] Produces full PC‑style descriptions (not just vague sidekicks).  
  - [ ] Tries to round out the group (e.g., adds healer if you’re a wizard).  

***

## E. Summary & Chapter One

- [ ] Before real play, it outputs a **Party & Premise Summary**:
  - [ ] 2–4 sentences of campaign premise.  
  - [ ] 1–2 bullets per party member (role + hook).  
- [ ] Then it starts **Chapter One** with:
  - [ ] Correct header & character block.  
  - [ ] Short “🎲 The Rules” section.  
  - [ ] Scene narration in second person.  
  - [ ] A/B/C/D choice menu.  
  - [ ] 📜 Session Log at the end.

***

## F. In‑Play Checks

During Chapter One:

- [ ] When it calls for a roll, it **waits for your confirmation** (“I roll”) before rolling.  
- [ ] When it rolls, it prints:  
  `🎲 <Check> — d20 + mod = die + mod = total. Outcome.`  
- [ ] You can use meta:
  - [ ] `((Change this companion to player‑controlled in combat.))` → it acknowledges.  
  - [ ] `((output for new thread))` → it outputs a clean starter block with summary, character, NPCs, and hooks, and **does not** continue the scene.
