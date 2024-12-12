# Tower Defense Game in Unity

This repository contains the source code and assets for a simple Tower Defense game created using Unity. The game involves placing towers to defend against waves of enemies. Players can strategically place different types of towers along the path to prevent enemies from reaching the end point. The game includes mechanics like tower upgrades, enemy waves, and scoring.

Features
- Tower Placement: Players can place various types of towers at predefined locations on the map to defend against waves of enemies.
- Multiple Tower Types: Different towers with unique abilities (e.g., slow down, damage over time, splash damage) are available for strategic gameplay.
- Enemy Waves: Enemies spawn in waves with increasing difficulty. Each enemy has unique health, speed, and behavior.
- Tower Upgrades: Players can upgrade towers to improve their effectiveness in stopping enemies.
- Score System: Players earn points for each enemy defeated and can spend these points to place and upgrade towers.
- Visual Effects: The game features effects for attacks, enemy destruction, and tower upgrades.

How to Play
1. Start the Game: Press the "Play" button in Unity to start the game.
2. Place Towers: Use the in-game interface to select a tower type and place it on the map. Towers will automatically attack enemies within range.
3. Defend the Path: Enemies will follow a path to the goal. Place towers strategically to stop them.
4. Upgrade Towers: Earn points by defeating enemies, which can be used to upgrade your towers for better damage or special effects.
5. Survive the Waves: Continue defending against increasingly difficult enemy waves. The game ends when enemies reach the goal.

Gameplay Mechanics
- Towers: Towers are placed on the map and automatically target and attack enemies within range. Towers can be upgraded to increase damage, attack speed, or range.
- Enemies: Enemies follow a path towards the goal. They have health and speed attributes, and more challenging enemies appear in later waves.
- Waves: The game consists of multiple waves, with each wave increasing in difficulty. Players must manage resources and place towers to defeat enemies before they reach the goal.
- Resources: Players earn resources by defeating enemies. These resources can be used to place new towers or upgrade existing ones.

Technologies Used
- Unity: Game engine used to build and run the game.
- C#: Programming language used for game logic and interactions.
- UI System: Unity's UI system for in-game menus, tower placement, and HUD elements.
- NavMesh: Unity's navigation system for pathfinding, enabling enemies to follow predefined paths.
- Particle Effects: Used for visual effects when enemies are defeated or towers fire.

Project Structure
  Assets:
    - Scripts: Contains all the C# scripts for tower behavior, enemy movement, wave management, etc.
    - Prefabs: Includes prefabricated objects for towers, enemies, and environment.
    - Scenes: Contains the main game scene with the tower defense map and UI elements.
    - Materials: Assets for textures and materials used in the game.
    - UI: Contains assets for the game interface (buttons, health bar, score display).
    
  Scripts:
    - Tower.cs: Script for defining tower properties and behaviors.
    - Enemy.cs: Handles enemy movement, health, and behavior.
    - WaveManager.cs: Manages the spawning of enemy waves.
    - GameManager.cs: Controls the overall game state, score system, and win/lose conditions.
    - UIManager.cs: Manages the user interface elements like tower placement, score display, and game over screens.

Contributing
Feel free to contribute to this project by opening issues or submitting pull requests. You can help by:
- Adding new tower types and enemy behaviors.
- Improving graphics or animations.
- Enhancing gameplay mechanics, such as adding more tower upgrade options.
