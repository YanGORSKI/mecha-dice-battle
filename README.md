# MECHA DICE BATTLE
This is a minimalist game of Mecha Combat, played using only a set of die (and optionally an extra d20).
You'll have to attack your opponent, defend from him, while managing your mecha's energy reserve
and swithing from an offensive stance to a defensive stance according to the flow of battle.

## Components
You'll need a complete set of RPG die (and optionally an extra d20) for the following purposes:
* **d20** - This will keep record of your mecha's **Core**, starting at 20,
and decreasing as you suffer damage of increasing as you ***Repair*** yourself (max of 20)
* **d20** [*optional*] - this will keep record of your **Energy Reserves** that will decrease as you use
your mecha's **Energy Cells** and increase as you ***Recharge*** your energy reserves
* **d12** and **d10** - these will be your **Pilot Focus** die, that you'll place on the **Evasion Control** and **Target Control**
according to the Combat Stace you want. If your d12 is placed on your **Target Control** you'll have an Offensive Stance,
while if you place your d10 on your **Evasion Control**, you'll have a Defensive Stance.
* **d8**, **d6** and **d4** - these will be your **Energy Cells**, they will use up or ***Recharge*** your **Energy Reserves**.
They are placed on you **Energy Chambers** decreasingly in clockwise order.
This order of **Energy Cells** can't change, but the player can rotate the **Energy Chambers** clockwise and counter-clockwise
and start the game in any of the 3 possible arrangements shown below:
```
   d8      |    d4      |    d6      
 /    \    |  /    \    |  /    \    
d4 -- d6   | d6 -- d8   | d8 -- d4   
```

### Battle Mat
The Battle Mat is where all the info on you Mecha is. There are different **Systems** and **Controls**.

* **Weapons Systems**: Directly linked to the left-most **Energy Cell** in the **Energy Chamber**.
There are 3 different Weapons that can be powered in combat:
  * **Focused Laser Blaster**: Simple Ranged Weapon which main focus is to create openings in the opponent's defenses. Uses the least amount of energy while having the least amount of potential damage, however there's a high chance of having a **Power Surge** (rolling the max number at the Dice), wearing down the opponent for an easy hit.

  * **High Energy Photon Sword**: Balanced Melee Weapon, consumes a moderate amount of Energy but having a decent amount of potential damage, while it's **Power Surge** may cause the damage to bypass some enemy's protection.

  * **Plasma Assault Rifle**: High-Damage Ranged Weapon, consumes the most amount of energy while dealing the most amount of damage. Its **Power Surge**, while rarer than the other weapons, can be devastating, dealing extra damage to the **Energy Reserves** of the opponent.

* **Defense Systems**: Directly linked to the upper-most **Energy Cell** in the **Energy Chamber**, they'll focus on protecting the mecha from incoming damage or even repair some of the damage dealt to the mecha's **Core**:
  * **Anti-Kinectics Shield**: A physical Shield that excels in close-combat while remaining effective to deflect ranged attacks. Uses the most amount of energy, but its **Power Surge** allows a immediate counter-attack to any melee attacker while at full power.

  * **Electromagnetic Forcefield**: A personal forcefield shields the mecha's from incoming attacks, weakening melee attacks and blocking ranged. Its **Power Surge** is extremely effective against ranged attacks, completely negating the damage of the first ranged attack suffered while in full power.

  * **Self-Repairing Nanobots**: A swarm of Nanobots programmed to repair some of the damage the mecha receives. While in **Power Surge** it can boost the mecha's maneuverability to increase its evasion.

* **Thruster System**: A unique System that allows different **Maneuvers** based on the amount of **Energy** given:
  * **Offensive Dash**: Thrusts forward while wielding the **Photon Sword**, granting an advantage to the strike.

  * **Gravitational Stabilizer**: Advanced stabilization allowing a better aim while making it easier to be hit due to the low level of mobility.

  * **Evasive Maneuvers**: Focusing on evading attacks, quickly moves erratically in the battlefield, making it easier to dodge enemy attacks.

* **Pilot Focus**: Here is where the player decides which approach to have on the battlefield, whether to be *Offensive* or *Defensive*, which also defines the order of turns depending on the stance of the different players involved:
  * **Offensive Stance**: the d12 is placed on the **Target Control**, giving the player advantage on landing attack on the opponent. Makes it easier to land attacks, however it's harder to land a critical hit or a critical miss. Mechas in an **Offensive Stance** will always strike first against Mechas in **Defensive Stance**. If both Mechas are on **Offensive Stance** they roll the dice on their **Target Control** and whoever rolls higher takes the lead.
  * **Defensive Stance**: the d12 is placed on the **Evasion Control**, giving the player advantage on evading attacks. Their own attack will have an lower overall chance to hit the opponent, but will have a higher chance to land a critical hit and take a critical miss. Mechas in an **Defensive Stance** will always strike last against Mechas in **Offensive Stance**. If both Mechas ar on **Defensive Stance** they roll the dice on their **Target Control** and whoever rolls higher goes last.

* **Energy Reserves**: Here is where the Mecha's **Energy** is managed. In the center of the **Energy Reserve** you can place an extra d20 to keep track of the Mecha's **Energy** which starts at 20 and decreases as the **Energy Cells** are used.
  * **Energy Chambers**: Is the triangular shaped core of **Energy**. It contains 3 **Energy Cells** with different capacities that can activate different equipment in each of the **Systems**. The placement of the **Energy Cells** in the **Chamber** cannot be changed, but the **Energy Chambers** can be rotate in either direction, moving all of the **Energy Cells** at once. This rotation can only occur during a **System Recalibration** Action and only if there are no active **Energy Cells**.
  * **Energy Cells**: Represented by different die, the **Energy Cells** can provide different amounts of **Energy** to a **System**, activating the according equipment or performing the according **Maneuver**. They can also be used to activated the **Energy Flux Inversion**, ***Recharging*** the **Energy Reserves** based on its roll.
  * **Energy Flux Inversion**: Dedicated System focused on ***Recharging*** the **Energy Reserves**. You can choose an **Energy Cell** to activate it during a **System Recalibration**. At the end of the player's turn you can roll the dice in the **Energy Flux Inversion** to ***Recharge*** the **Energy Reserves** by the amount rolled. You can also choose to deactivate the **Energy Flux Inversion** and release the **Energy Cell** back to the **Energy Chambers**.
  * **Overcharging Module**: The **Overcharging Module** is used together with the activation of the **Weapons System**. You can deploy a second **Energy Cell** to increase the power output of the activated **Weapon System**, however this means your Mecha will be vulnerable as it can do nothing else for the first turn, while it's charging the attack, and will only deliever the overcharged attack on the end of the turn order of the next turn. If more than one Mech is activating the **Overcharge Module**, the first to activate it will deliever the attack first, ignoring any difference in **Combat Stances**.

* **Mecha Controls**: There are 2 main controls, the **Evasion** and the **Target** **Controls** and they go against each other in battling mechs:
  * **Evasion Control**: This determines the difficulty of landing a hit at your Mecha. Whichever dice you place from the **Pilot Focus** the base value will the ```half the max value of the dice + 1```.
  For an enemy to hit you, they'll have to roll on their **Target Control Dice** a value higher than the one on your **Evasion Control Dice**. This amount can change during the game, but the value is always ***Estabilized*** after a **hit** of a **dodge**.
If the value of the **Evasion Control Dice** is higher than its base, after avoiding an attack it goes back to the base value (if the enemy suffers a Critical Miss, it is **NOT** considered a **DODGE**, and the bonus carries on to the next turn).
If the value of the **Evasion Control Dice** is lower than its base, after taking a hit it goes back to the base value (in this case, a Critical Hit is still a Hit, and will ***Estabilize*** the **Evasion Control Dice**).
  * **Target Controll**: This is the dice you roll to land a hit at your opponent. No matter the dice you have, rolling a 1 is always a **Critical Miss** and rolling the max number on the dice is a **Critical Hit**.
In a **Critical Miss**, in addition to not landing the attack, the **Energy Cell** activating the **Weapon System** becomes stuck, while stuck the **Energy Cell** cannot be released from the **Weapon System**, so the next turn the player is forced to either use the same **Weapon System** or none at all.
In a **Critical Hit**, in addition to landing the attack, you roll whichever damage die a second time, however with no chance of **Power Surges**. This includes dice from an **Overcharge**.

## Playing the Game
The game can be played in 3 modes:
Duel (1x1), Double Combat (2x2), Arena (3-Player Free-for-all). In any game mode other than the duel, at the beginning of a turn, BEFORE defining turn order, the players declare who is their target. This can be done in no particular order.

The first thing to start the game is to place the **Battle Mat** and the dice in their initial position as described before. If you're not using a second d20 to keep track of the **Energy Reserves** you can do so by marking a papersheet, starting at 20 and reducing and increasing as the game is played.
In this initial moment, you can set the initial **Combat Stance** and **Energy Chambers** position as you like (respecting the **Energy Cell** order).

### Turn Order
To define the order of the turns, first split the players in **Offensive** and **Defensive**.
The **Offensive** mechas will take their turn before any **Defensive** mechas.
If there are more than 1 mecha in each **Combat Stance**, they roll their **Target Control Dice** and decide according to the highest number rolled.
**Offensive** mechas that roll higher will go first, **Defensive** mechas that roll higher will go last.

### Player Turn
The player have some **Actions** to choose to take on their own turn, and some activations can be done together or as a response to receiving an attack. Every action that involves activation via **Energy Cell** could result in a **Power Surge**, which grants additional effects immediatly. A **Power Surge** happens when rolling the max number on a **Energy Cell Dice**.
* **Activate a Weapon System**: You turn on an use one of the **Weapon Systems** according to the **Energy Cell** placed on the left-most **Energy Chamber**. Each weapon has a different dice representing it, different properties and a different **Power Surge** effect.
  * **Focused Laser Blaster**: roll a d4 and deal this much damage to the target Mecha. **Power Surge**: Roll a d4 again and subtract this much to the target's **Evasion Control Dice**.

  * **High Energy Photon Sword**: roll a d6 and deal this much damage to the target Mecha. **Power Surge**: If your target has a **Forcefield** active, ignore its protection.

  * **Plasma Assault Rifle**: roll a d8 and deal this much damage to the target Mecha. **Power Surge**: Roll a d8 again and remove this much from the target's **Energy Reserves**. If the **Energy Reserves** reaches 0, any surplus damage is dealt directly to the target's **Core**.

* **Activate a Defense System**: You deploy an **Energy Cell** to the corresponding **Defense System** activating the appropriate equipment.
  * **Anti-Kinectics Shield**: Roll a d8, you have this much protection from incoming attacks. The **Energy Cell** is deployed until the amount is depleated or it is released by the player in a **System Recalibration**. **Power Surge**: While on its maximum, after receiving a melee attack, immediately make an attack against your attacker.

  * **Electromagnetic Forcefield**: Roll a d6, you have this much protection from incoming attack. This particular protection is more effective against ranged attacks. To consume 1pt from the Shield the attacker must deal 2pts of damage from ranged weapons, objectively nullifying attacks that would deal 1 damage from ranged weapons. **Power Surge**: While on its maximun, completely negates the damage from the first ranged attack dealt to you.

  * **Self-Repairing Nanobots**: Roll a d4, you repair this much of your **Core** health. **Power Surge**: Roll a d4 again, add this much to your **Evasion Control Dice**.

* **Overcharge a Weapon System**: You deploy a secondary **Energy Cell** to a Weapon. The turn you choose this activation you spend ***Overcharging*** and will deliever the attack at the end of the next Turn Order. Once decided to **Overcharge** the action can't be cancelled, as all the **Energy** is expended in the turn you choose this activation. The extra dice rolled does not contribute to a **Power Surge**, only the main **Energy Cell** of activating the **Weapon System** rolls for a **Power Surge**.

* **System Recalibration**: This Action involves a series of other possible actions that can all be taken together as long as there is no blockage between them:
  * **Release Energy Cells**: Place all deployed **Energy Cells** back at the **Energy Reserve**.
  * **Rotate Energy Chambers**: The **Energy Chambers** can be rotate to either side, moving all the **Energy Cells** at once. This cannot be done if there's any deployed **Energy Cell**. It can be done the same **System Recalibration** that ***Releases*** any deployed **Energy Cell**.
  * **Activate Energy Flux Inversion**: Deploys an **Energy Cell** to activate the **Energy Flux Inversion**, ***Recharging*** the **Energy Reserves**. This can be done after ***Rotating*** the **Energy Chambers**. Can be done the same **System Recalibration** that ***Releases*** **Energy Cells**. Cannot be done while ***Stabilizing Evasion Control***.
  * **Stabilize Evasion Control**: Resets the **Evasion Control Dice** to its base value. Cannot be done while ***Activating Energy Flux Inversion***.
  * **Switch Combat Stance**: Switches the 2 **Pilot Focus Die**, alternating beetween an **Offensive Stance** and a **Defensive Stance**. Can be done after ***Stabilizing Evasion Control***.

#### Thruster System
The **Thruster System** can be activated together with the **Weapons Systems** or as a **Reaction** to being attacked.
  * **Offensive Dash**: Choose to make an **Offensive Dash** when activating the **Photon Sword**. Roll a d4, add this much to your **Target Control Dice Roll**.

> **Power Surge**: The extra mobility makes it harder to be hit. Roll a d4 again and add it to your **Evasion Control Dice**.

  * **Gravitational Stabilizer**: Choose to activate the **Gravitational Stabilizer** when activating the **Plasma Assault Rifle**. Roll a d6, add this much to your **Target Control Dice Roll** and subtract the same amount to your **Evasion Control Dice**.

> **Power Surge**: Subtract only half the value to your **Evasion Control Dice**.

  * **Evasive Maneuvers**: Choose to make **Evasive Maneuvers** when you'll be the target of an attack, but BEFORE you know if the attack will land. Roll a d8, add this much to your **Evasion Control Dice**. No matter the dice placed on it, if the amount rolled is higher than the maximum value of the dice, the surplus will be added after the **Evasion Control Dice** is ***Stabilized***, potentially granting additional **Evasion** for more than 1 turn. When this happens, however, the **Energy Cell** stays deployed to the **Thruster System** until the last bonus is added to the **Evasion Control Dice**.

> **Power Surge**: The first **Dodge** does not ***Stabilize*** the **Evasion Control Dice**.
