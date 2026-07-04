Eldralis: Primal Awakening – SFW Beta
A D&D 5e‑based, anthro‑only TTRPG world for SillyTavern

📖 What is Eldralis?
Eldralis is a dark‑fluff fantasy setting where no humans exist – the world is populated entirely by anthropomorphic animals (canids, felids, reptiles, avians, and many more). It blends cozy warmth with primal horror, offering a rich, sensory‑driven experience for text‑based roleplay.
This repository contains the Safe‑For‑Work (SFW) beta version of the Eldralis system, designed to be used with SillyTavern (a frontend for AI roleplay). It includes:
	•	A System Prompt that turns any compatible LLM into a Dungeon Master for the Eldralis world.
	•	World Info (WI) entries that define species, regions, factions, magic, bestiary, NPC depth, quest generation, and more.
	•	A Knowledge JSON with immersive world‑building, narrative tools, and social mechanics.
All NSFW content (intimacy rules, heat cycles, explicit anatomy, etc.) has been completely removed, making this version safe for public Discord servers and general use.


⚠️ Beta Notice
This is a work‑in‑progress beta release. While the core systems are functional, you may encounter:
	•	Incomplete WI entries (some species or factions may have less detail).
	•	Balance issues in combat encounters or quest generation.
	•	Missing translation for Hungarian prompts (only English is fully tested).
Feedback and contributions are welcome! Please open an issue or reach out via the support channels.


🚀 Installation Guide
Prerequisites
	•	SillyTavern installed and running (version 1.12.0 or later recommended).
	•	A compatible LLM backend (e.g., KoboldCPP, Oobabooga, OpenAI API, Claude API).
	•	Basic familiarity with SillyTavern’s Character Management and World Info systems.
Step‑by‑Step
	1	Download the repository Clone or download the ZIP from GitHub, or copy the three files:
	◦	Eldralis_System_Prompt_SFW.txt
	◦	Eldralis_System_SFW.json
	◦	Eldralis_Knowledge_SFW.json
	2	Import the System Prompt
	◦	In SillyTavern, go to the Character Management tab.
	◦	Click Import Character and select Eldralis_System_Prompt_SFW.txt.
	◦	Alternatively, create a new character, paste the entire content of the TXT file into the System Prompt field, and set the character name to Eldralis Narrator.
	3	Import the World Info (JSON files)
	◦	In SillyTavern, navigate to the World Info tab (or Lorebook).
	◦	Click Import and select Eldralis_System_SFW.json. This loads all core WI entries (anatomy, regions, bestiary, quest matrix, etc.).
	◦	Then import Eldralis_Knowledge_SFW.json to add the immersive world‑building entries (environment, society, narrative tools, etc.).
	◦	Make sure both files are active (enabled) for the character you just created.
	4	Configure the LLM Backend
	◦	Set your preferred API or local endpoint in SillyTavern’s API Connections.
	◦	Recommended settings:
	▪	Temperature: 0.8–1.0 (for creative, varied responses).
	▪	Max Tokens: 800–1200 (enough for detailed narration).
	▪	Context Size: at least 4096 tokens (the system prompt + WIs are ~10k tokens, but the model will only use what fits).
	5	Start the Adventure!
	◦	Select the Eldralis Narrator character and start a new chat.
	◦	The Narrator will present you with the game modes:
	▪	Full Adventure: Full character creation (16 steps) with stats, combat, and exploration.
	▪	(Heat Mode is disabled in this SFW version.)
	◦	Choose your language (English or Hungarian) and follow the prompts.

📂 File Descriptions


File
Type
Purpose
Eldralis_System_Prompt_SFW.txt
System Prompt
The core Narrator instructions. Defines the world rules, HUD format, Poppet COT, dice rolling, and all interaction protocols.
Eldralis_System_SFW.json
World Info (JSON)
All mechanical and setting WI entries: species anatomy, D&D 5e stats, factions, cosmology, bestiary, equipment, alchemy, quest generation, NPC depth, loot, diseases, random encounters, leveling, and full character creation.
Eldralis_Knowledge_SFW.json
World Info (JSON)
Immersive world‑building entries: living infrastructure, dragons, history, forbidden knowledge, scent etiquette, species norms, narrative tools, magical locations, dark fluff spectrum, and storytelling techniques.

🎮 How to Play
Full Adventure Mode
	•	Character Creation (16 steps): The Narrator will guide you through naming, species, gender, age, origin, size, appearance, class (Anthro Path), alignment, motivation, fear, and finally stat generation (4d6 drop lowest).
	•	HUD (Heads‑Up Display): At the end of every narrative response, a detailed status block shows HP, MP, Stress, inventory, location, and more.
	•	Combat & Exploration: Hidden D&D 5e mechanics resolve actions via /roll commands. The Narrator describes everything sensorily – no meta‑explanations.
	•	Quest Generation: The Spiderweb Quest Matrix creates branching, non‑linear stories with dramatic arcs, plot twists, and emotional stakes.
Commands
	•	/roll 1d20+5 – The Narrator rolls for any uncertain action.
	•	/generate_card [Name] – Generate a SillyTavern‑compatible JSON card for a significant NPC.
	•	((OOC message)) – Speak out‑of‑character to the Narrator.
The World
Eldralis features six major surface regions (Frost‑Fang Expanse, Emerald Basin, Golden Sands, Shadow‑Marsh, Crimson Scar, Sky‑Reefs) plus the underground Under‑Root and the Abyssal Trench. Each has unique threats, factions, cuisine, and fashion. The world is alive – NPCs have their own routines, and the World Clock advances global events independently of the player.

🛠️ Compatibility
	•	SillyTavern (primary target).
	•	Any LLM that supports system prompts and character cards.
	•	Fully functional with English; Hungarian output is supported but may have untranslated proper names (all names remain English).

🤝 Contributing
This is a beta project. If you’d like to help:
	•	Report bugs or suggest improvements via GitHub Issues.
	•	Submit pull requests with new WI entries, creature stat blocks, or lore expansions.
	•	Share your experiences and feedback on Discord (link TBD).

📜 License
This project is released under the MIT License. You are free to use, modify, and distribute it, provided you include the original copyright notice.

🙏 Credits
	•	System Design & Writing: Eldralis Team
	•	D&D 5e Conversion: Based on the 5th Edition SRD.
	•	SillyTavern Integration: Thanks to the SillyTavern community for their excellent tools and documentation.

Happy adventuring in the lands of Eldralis – where every scent tells a story, and every shadow hides a secret. 🐺🔥

Version: Beta 1.0 – SFW Last Updated: 2026-07-04
