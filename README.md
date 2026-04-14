Element Clash is an AI-Powered 2D Turn-Based Card Game. A 2D turn-based card battle game that showcases classical Game AI techniques such as Finite State Machines (FSM) and rule-based decision systems. The game features a Player vs AI combat system, where strategic card selection, elemental advantages, and adaptive AI behavior determine the outcome of each match.

Gameplay:
🃏 Each player selects one card per round
Cards have:
1) Attack
2) Defense
3) Element type

Element system:
Fire > Air

Air > Earth

Earth > Water

Water > Fire

Special abilities & ultimates influence gameplay
- AI adapts based on game state
- AI System
- Finite State Machine (FSM)

The AI behavior is controlled using 3 dynamic states:
🔴 Aggressive (HP > 60%)
Focus on high attack
Tries to finish the player quickly

🟡 Reactive (30% < HP ≤ 60%)
Counters player’s last move
Exploits elemental weaknesses

🔵 Defensive (HP ≤ 30%)
Prioritizes survival
Uses high-defense strategies

⚙️ Rule-Based Decision System

Each card is scored based on:
Attack value
Defense (weighted by state)
Element advantage
Finishing potential
Survival potential

The AI selects the card with the highest computed score

🔥 Game Mechanics
🌟 Elemental Abilities
🔥 Fire → Burn (+5 damage)
💧 Water → Armor Break (ignore defense)
🌪️ Air → Swift Strike (1.5x damage when advantaged)
🌍 Earth → Stone Fist (+3 damage)
⚡ Ultimate System

Builds over time
Adds powerful effects:
Element	Effect
Fire	+20 damage
Water	1.8x damage
Air	2x damage
Earth	+10 damage

How It Works:
Player selects a card
AI evaluates game state
FSM determines AI behavior
Cards are scored using rules
Best card is selected
Damage & effects are applied



https://github.com/user-attachments/assets/841e2642-77a7-4dcc-83ba-fefaac741dd1


