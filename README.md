# PortfolioProjectLinks

*Tekno (Final Year Project)*

Game Description - A PC 3D Action Rhythm Platformer game where music BPM plays a big role with the gameplay and environment in changeing the speed of the game

**Contribution** 
  - Level Building for Tutorial and Gameplay Scene
  - Environment reacts to music
    
    Code Snippets - https://github.com/qiuji10/Tekno/blob/06bb393862d31e8ed22e5035d6d50a19de2d2bde/Assets/3_Scripts/MusicSystem/MusicSync.cs#L119C1-L178C14


information about the Script
  - MusicSync script is easy to use for developers to customize how GameObjects will react to music based on their liking by enabling the booleans.
  - MusicSync  script allows you to dynamically adjust the scale, rotation, and position of specific game objects in response to the music's rhythm.
  - Scaling can occur along the X, Y, and Z axes, and the degree of scaling is controlled using ScaleX, ScaleY, ScaleZ, and scaleMod.
  - Rotation can happen around the X, Y, and Z axes, with angles determined by the music's beat data and specified by RotateX, RotateY, and RotateZ.
  - Movement is supported along the X, Y, and Z axes, with the extent of movement defined by MoveX, MoveY, MoveZ, and moveMod.


[On Shallow Waters (Mobile Game Project)]
Game Description - 3d action rougelike dungeon-crawler mobile game 
**Contribution**
- Helped out with Player Controls and Attack system

  Basic Attack code  - https://github.com/namejeb/on-shallow-waters/blob/02d6fe84eb2dbf5be95f6daef7594f6f8f81d5d6/OnShallowWaters/Assets/04%20Scripts/03%20Character/Player/DashNAttack.cs#L219-L281

  Heavy Attack code - https://github.com/namejeb/on-shallow-waters/blob/02d6fe84eb2dbf5be95f6daef7594f6f8f81d5d6/OnShallowWaters/Assets/04%20Scripts/03%20Character/Player/DashNAttack.cs#L175C4-L211

- Sound System
  Sound System - https://github.com/namejeb/on-shallow-waters/blob/02d6fe84eb2dbf5be95f6daef7594f6f8f81d5d6/OnShallowWaters/Assets/04%20Scripts/00%20Audio_System/SoundManager.cs#L29-L81

  Sound Data - https://github.com/namejeb/on-shallow-waters/blob/02d6fe84eb2dbf5be95f6daef7594f6f8f81d5d6/OnShallowWaters/Assets/04%20Scripts/00%20Audio_System/SoundData.cs#L6-L11

  Soubnd file - https://github.com/namejeb/on-shallow-waters/blob/02d6fe84eb2dbf5be95f6daef7594f6f8f81d5d6/OnShallowWaters/Assets/04%20Scripts/00%20Audio_System/SoundFile.cs#L6-L15

information about the script 
- This code simplifies audio management, allowing easy control of sound effects and background music in the game. It also enables developers to customize their audio experience by adjusting volume settings.

  
- VFXs For Abilities

  [Train Trap (2D PC Game)]
Game Description - Narrative puzzle Game similar to the game called 12 minutes, where player exprience endless loop of the same event until they solve the narrative puzzle of the game to escape the loop

 **Contribution** 
 - Guard behaviors
     - Code Snippet: https://github.com/qiuji10/Train_Trap/blob/7d9b8de532413b1c4b17433189d900726c519538/Assets/2_Scripts/Guard/GuardPatrol.cs#L24-L70

information about  the Script 
- This code defines the behavior of a guard character in the game, managing their patrol route and interactions with the player.
- Patrol Points: The guard follows a predefined patrol route, with waypoints represented as a list of transforms (**`points`**).
- Player Interaction: The code checks for the player's presence in the guard's range and responds when the player interacts with certain objects (lockers).
- Movement and Orientation:
    - The guard moves between patrol points using **`Vector2.MoveTowards`**, adjusting its position according to a **`WalkSpeed`**.
    - The guard's orientation changes based on the direction of movement, flipping its sprite.
- **Patrol Loop**: The guard patrols between the waypoints in a loop, moving forward and backward along the patrol route.


- Seamless Scene Transitions
- **Inventory System**
Information about this System
- Handles picking up items and adding them to the inventory.

  picking up items
  **code snippet** : https://github.com/qiuji10/Train_Trap/blob/7d9b8de532413b1c4b17433189d900726c519538/Assets/2_Scripts/interaction/Pickup.cs#L25-L57

   Update slot Name 
  **code Snippet** : https://github.com/qiuji10/Train_Trap/blob/7d9b8de532413b1c4b17433189d900726c519538/Assets/2_Scripts/interaction/Pickup.cs#L58-L64

  inventory
  **code Snippet** :  https://github.com/qiuji10/Train_Trap/blob/7d9b8de532413b1c4b17433189d900726c519538/Assets/2_Scripts/Inventory/Inventory.cs#L5-L9

  Drop Items
  **Code Snippet** : https://github.com/qiuji10/Train_Trap/blob/7d9b8de532413b1c4b17433189d900726c519538/Assets/2_Scripts/Inventory/Slot.cs#L20-L34  



    
