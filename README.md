# LoopRaetsel (LoopPuzzle)

Interactive puzzle game from the *Game Dev 1* module at Hochschule Bonn-Rhein-Sieg.

---

## Table of Contents

1. [Game Concept](#game-concept)  
2. [Key Features](#key-features)  
   - Conceptual / Gameplay Features  
   - Technical Features  
3. [Theory & Design](#theory--design)  
   - Formal Game Elements  
   - Game Feel / Funativity  
   - Storytelling & Character Design  
   - Interaction & UI  
4. [Team & Credits](#team--credits)  
5. [Sources & Tools](#sources--tools)  
6. [How to Run](#how-to-run)  
7. [License](#license)

---

## Game Concept

- An interactive puzzle game set in a magical fantasy world.  
- Players roam an open world, exploring various areas and solving puzzles of **progressively increasing difficulty**.  
- Often, previously visited rooms must be revisited to uncover new clues that advance the story or unlock next puzzles.  
- **Inspirations** include *The Legend of Zelda: A Link to the Past*, *Enter the Gungeon*, *Deponia*, *Escape Simulator*.

---

## Key Features

### Conceptual / Gameplay Features

- Core Gameplay: Progressive puzzle solving via unlocking new items.  
- Variety of Puzzle Types: Environment-based puzzles and item-interactions.  
- Focus on Atmosphere: Numerous mysterious areas, shadow effects, immersive music and sound.  
- No Combat: purely exploratory and puzzle-oriented.  
- No Waypoints or Markers: players must interpret clues themselves and find their path.  
- Storytelling: uncovering narrative and clues within a magical spellbook.

### Technical Features

- Inventory System: collect items, use them, deploy them strategically.  
- Interactive Spellbook: stores story and hints.  
- Handcrafted Pixel Art: textures and tilemaps designed and pixelated by the team.  
- Save System: players can save freely at any time.  
- Dynamic Shadow Effects: e.g., shadows cast by torches.  
- Diverse Item Interactions: puzzles that depend on different item usage.  
- Camera: smooth following movement with restricted field of view for atmosphere.  
- Top-down Control: free movement, animated sprite directions.  

---

## Theory & Design

### Formal Game Elements

| Element       | Implementation Detail |
|----------------|--------------------------|
| **Player**     | Single player, plays as the wizard / spellcaster |
| **Objectives** | Solve the final puzzle, brew the magical potion |
| **Procedures** | Movement, interaction, item usage |
| **Rules**      | Some puzzles must be solved in specific order |
| **Resources**  | Items, hotbar, inventory management |
| **Conflicts**  | Puzzles as obstacles to get the necessary ingredients |
| **Boundaries** | Walls, camera constraints, limited vision |
| **Outcomes**   | Game restarts from beginning; journey / puzzle solving is primary goal |

### Funativity / Game Feel

- **Mental Fun**: puzzles that demand thought and logic.  
- **Series of Convexities**: multiple puzzle paths, non-linear progression.  
- **Concept of Flow**: gradual increase in challenge to keep engagement.

### Storytelling & Character Design

- Linear storyline revealed through the quest book.  
- Character archetype: *The Wizard*.  
- Use of stereotypical wizard traits: long beard, cloak, hat.  

**Character Design Visuals**:

- Friendly appearance: small mouth, large nose, relaxed posture, high eyebrows, oversized clothing.  
- Masculine traits: beard, large nose, classic wizard silhouette.

### Interaction & UI

- Controls: mouse & keyboard using standard conventions.  
- Interfaces:

  - *Shell / Menu Interface*: main menu, credits.  
  - *In-Game Interface*: quest book, inventory, settings, hotbar.  

- UI Design: unified, intuitive, aesthetic, robust to errors.  
- User Feedback: sound effects for actions, interactions, UI & puzzles.

---

## Team & Credits

**Development Team**  
- Lead Programmers: Jasper Stolp, Jannik Sandkuhl  
- Lead Artist / Game Designer / Programmer: Marek Görs  

**Narrative & Design Team**  
- Narrative Designer & Game Designer: Zoneira Najam  
- Game Designer & Artist: Amal Ouald Chaib  

---

## Sources & Tools

**Tutorials and Inspiration**  
- *Game Code Library – Top Down Tutorial Series* (Unity 2D) – YouTube playlist :contentReference[oaicite:0]{index=0}  
- Games: *Deponia*, *Enter the Gungeon*, *A Link to the Past*, *Escape Simulator*

**Tools Used**  
- Unity (Editor version: 6000.0.46f1)  
- GIMP (v2.10)  
- Aseprite – pixel art & sprite editing tool  

---

## How to Run

To play the game just donwload the zip and extract it.
If you like to look at the code and the unity project open the unity file with **Unity** (version 6000.0.46f1).

---

