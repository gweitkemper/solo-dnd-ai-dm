# Solo D&D 5e AI Dungeon Master

A structured AI Dungeon Master for solo D&D 5e campaigns, optimized for political intrigue, espionage, mystery, romance, and tactical combat.  
Designed to run as a **ChatGPT Custom GPT** powered by:

- A short core instruction file: `docs/gpt-instructions.md`
- A detailed rules & workflow spec: `docs/dm-rules.md`
- Example transcripts: `docs/examples.md`

---

## Quick Start

### 1. Create the Custom GPT

1. Go to **ChatGPT → GPTs → Create a GPT**.
2. **Name** it something like: `Solo D&D 5e DM`.
3. In the **Instructions** box, paste the entire content of:

   `docs/gpt-instructions.md`

4. In the **Knowledge** / files section, upload:

   - `docs/dm-rules.md`
   - `docs/examples.md` (optional but recommended as extra style guidance)

5. Capabilities (recommended):

   - Turn **off** Code Interpreter and image generation.
   - Leave **Web Search** enabled (the rules tell the DM to use it mainly during Session Zero, or when you explicitly ask via `((meta))`).

6. Add a few **conversation starters**, for example:

   ```text
   - Start Session Zero for a new solo D&D 5e campaign.
   - Continue my ongoing solo campaign from where we left off.
   - Help me build a new character step by step.

7. Save the GPT
