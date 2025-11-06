# P1 - Identifying and Defining

### Identifying a Need
My game proposal is a 3D First Person movement and Shooter game that will have
players defend against oncoming waves of navigator NPCs using different tools, weapons
and other utilities. The gameplay should help entertain players by being engaging enough 
to demand attention to the game, with a reasonable raise in difficulty as more time is spent.

Need: To create an interactive game that requires a heightened sense of attention to
succeed, thus engaging the audience.

Problem: Video games that don't engage audiences will result in quick boredom and a fading sense
of interest in the experience. A game that requires heavy attention, like an FPS shooter, will keep
an audience invested in what is currently occurring, additionally adding layers of urgency, especially
in comparison to something like a clicker.

Skills: In order to complete this game, I will need to familiarise myself with the Unity 3D engine, especially
with the 3d physics and vector system, as well as the navmesh AI tool. I will also need to learn some syntax and
logical functions in the C# language that is used by Unity.

### Requirements Outline
#### Inputs:
**User Controls**
- WASD/Arrow Keys - Movement (Based on current rotation camera is facing).
- Space - Jump
- Mouse Controls [Left Click] - Shoot
- Esc - Menu/Pause Settings

**Other Non-User Inputs**
- Collisions - Colliders/triggers will sense collisions for objects like bullets and enemies, as well as enemies and players.

#### Processing:
- User Inputs - As this project will be done using Unity 6, inputs for movement, UI and shooting will be processed using C# code that
references the InputActionReference system.
- Collisions can be processed using collider functions while scripting.

#### Outputs:
- The player will move depending on the key pressed, with W corresponding to forwards, A to left, S to backwards and D to right.
- If escape is pressed, the pause menu should appear, with buttons that will allow players to exit back to a splashscreen, close the program, and open settings.
- If collisions are detected between bullets/pellets and enemies, an animation or particle system should instantiate, and both the enemy and bullet prefabs sshould
be deleted.

#### Transmissions
- While there won't be any major transmissions of data (as it is a single player game), there may be 
data transmitted to and from the cloud or a local file for high scores, waves, etc.

#### Storage
- The stored data for this game may include highscores/wave records for players, as well as settings,
as to improve the UX (user experience) by allowing them to save their settings.
- Additionally, a feature could include saving waves and stats.

# P2 - Researching and Planning: PMI
|Game|Plus|Minus|Implications|
|:--:|:--:|:---:|:----------:|
|www|    |     |            |
|Titanfall 2 (Campaign)|Engaging storyline as well as a smooth, consistent movement system that allows for efficient travel. Enemy design is not overly difficult, but provides enough challenge to be a general issue for a player.|Extremely fast paced combat and movement may result in less suspense and focus during gameplay. Though this isn't a necessarily a downside due to the movement-based shooter system of titanfall, it make be less desirable in a wave defense.|
|Borderlands 2|Heavy variety in classes/character abilites, as well as weapons, parts, stats and rarities, ensuring that players can add variety to their gameplay through the employment of different weaponry. Additionally, great settings and engaging storyline.|Somewhat repetitive gameplay (as it is a looter shooter), but balanced out by interesting quests, objectives and well designed characters and maps.|