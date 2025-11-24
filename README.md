# Module Two Team Project Plan

## 🚀 The Team

| Name | Role |
| --- | --- |
| Crystal | Programmer |
| Rayna | Artist |
| Austin | Level Design |
| Giancarlo | Floater (Leader) |
| Joshua | UI/UX |

**Note:** All members will be helping often in other areas to learn them/get them done at appropriate pacing.

## 👾 Game Concept

  * **Genre:** Horror
  * **Visual Style:** Low poly - styling - Pixelated Ps1
  * **Theme:** 1900s doom undead
  * **Primary Weapon:** Gun - Finger gun

### Enemies

  * **Seeker:** Clickers - Blind
  * **Attacker:** Zombie - non-special - varying difficulty based on eye color
  * **Stationary:** Weeping angels - stops when seen
  * **Final boss:** Necromancer?

## 🎮 Core Mechanics

### Pickups

  * **Health:** Food
  * **Drink - Stamina:** Flasks
  * **Drink - Over shield:** Flasks
  * **Ammo:** Fingers
  * **Lights:** Glow Sticks?
  * **Grenade:** Thumb
  * **Room Keys:** Blood Offering?
  * **Room Keys:** (Undecided)
  * **Room Keys:** Soul?

*(Note: Items may vary depending on how many we will need within the game)*

### Environment

  * **Elevators:** Rooms transference
  * **Capillaries:** Secrets? (Crawling into them will lead to secret area)
  * **Reproduction:** Spawning of enemies

## 🗓️ Development Timeline

  * **Week 1:**
      * Set up repository (make sure everyone is able to access/work on game)
      * Brainstorm ideas for game
      * Look up animations/pre-made packs, items we can use within game
  * **Week 2:**
      * Create basic character functions
      * Create basic map layout
      * Create basic enemy AI
      * Create basic boss AI
      * Create basic mechanics of shooting/pickups
      * Create basic mechanics for doors opening/elevator moving
  * **Week 3:**
      * Make sure all mechanics are functional
      * Can make it to the end of the game loop
      * Fix anything that may be having issues
      * **Alpha release (turn in)**
      * Begin working on adding in texturing/lighting
      * Create animations
      * Create sounds
  * **Week 4:**
      * Make sure all texturing is done
      * Make sure all enemies are completed with sound/animations
      * Make sure main character is completed with sound/animations
      * **Turn in Beta release**
  * **Week 5:**
      * **Final Submission for project**
      * Make sure everything looks good and we are happy with it
      * Make sure everything works and no issues occur after some runs of the game

## 🎯 Milestone Goals

<details>

<summary><strong>Alpha Goals (Core Functionality)</strong></summary>

### Core player systems

  * First person controller
  * Pickups [Will be finalized in beta]
  * Magic shooting [edited]

### Basic enemy AI

  * **Seeker**
      * Moves toward sound
      * Wanders when no sound source
  * **Attacker**
      * Vision-based chase AI
      * Multiple variants based on difficulty (eye color changed/speed)
  * **Stationary**
      * Moves when not looked at
      * Freezes completely when in players direct view
        *(Note: None polished animations, just need functional logic)*

### Early game loop

  * Player navigates rooms
  * Basic key-door system functions
  * Elevator system transitions between floors

### Map layout

  * Greybox/ Blockout for main playable area
  * First safe room
  * Hallways?
  * 2-3 enemy encounter rooms
  * 1 capillary secret crawlspace
    *(Note: No texture or final lighting yet – shape/navigation only)*

### Final Boss [still being debated on ?]

  * Necromancer AI
  * Summons enemies
  * Has phases/shield?
  * Weak points exposed after doing something?

### UI/UX

  * Create general map
  * Create an item holding area?
  * Create an intro too game

</details>



<details>

<summary><strong>Beta Goals (Polish & Completion)</strong></summary>


### Visual/Style polish

  * Low-poly PS1 shader across characters and environments
  * Pixelated retro render pipeline
  * Blood/flesh/undead thematic color palette

### Sound/Atmosphere

  * Footsteps/breathing? /Heartbeat (when low health)
  * Horror ambient loops for rooms
  * Clicker screech, Zombie moans, Angel sone-grind movement
  * Elevator bell & chains?

### Animation Pass

  * Enemy idle/ walk animations improved
  * Angel movement
  * Gun for hand animation for firing/reloading

### Game Balance

  * Ammo scarcity
  * Stamina usage pacing
  * Enemy health/speed tuning
  * Final boss encounter feels tense, not fair [debated]

### Environment Pass

  * Replace greyboxes with final art
  * Lighting pass
  * Flickering lights
  * Dark corners
  * Glow sticks as light source

### UI/UX Polish

  * Proper HUD
  * Inventory icon clarity
  * Clear pickup prompts

</details>

## 💬 Collaboration Workflow

  * **Preferred Communication:** Calls in class discord; messages/other calls within the group.
  * **Meeting Frequency:** Tuesdays/Sundays - Calls within class discord. (We want to play this by ear and if needed add in more calls/meet in small groups to help one another out).
  * **Task Management:** Gantt chart. We will write in there what we are working on/what we have done. Anyone can help one another create things and will be played by ear if someone needs help/would like to do something specific.

---

# Module Three Team Project Log

## Play Test (Preproduction Stage)

Play testing begins as soon as basic mechanics and prototype assets are functional. This stage focuses on validating the core gameplay loop, verifying mechanics, and identifying whether the game’s direction is fun and feasible.

#### Preproduction Testing Activities

*   Testing the player controller (movement, stamina, health)
*   Testing prototype enemy AI behavior (Seeker, Zombie, Weeping Angel)
*   Testing early room layouts and elevator transitions
*   Testing item functionality such as Finger ammo, health food, flasks, glow sticks
*   Testing damage systems, collision, and interactions

#### Preproduction Goals

*   Determine whether the core idea is fun
*   Verify that the game’s mechanics work fundamentally
*   Catch major logic errors before building full levels
*   Adjust the design document early to avoid costly changes later

## Demo Testing

*   Running through the complete level
*   Ensuring enemy behavior is predictable and bug-free
*   Ensuring pickups function properly
*   Verifying elevators and room transitions
*   Testing atmosphere: lighting, sound, pacing
*   Checking UI elements (HUD, prompts, messages)
*   Fixing anything that breaks immersion or clarity

#### Demo goals

*   Ensure the demo flows smoothly without crashes or dead ends
*   Fix any issues that would confuse players in a first impression
*   Confirm performance is stable
*   Validate that gameplay reflects the intended horror and PS1 visual style

## Code Release Testing

*   Running through the entire game start-to-finish
*   Checking all implemented systems against the test plan
*   Regression testing (ensuring old bugs weren’t reintroduced)
*   Stress testing AI and spawning systems
*   Ensuring the final boss (Necromancer) functions properly
*   Checking level geometry and collision
*   Testing all pickups, puzzles, keys, and elevators

## Test Checklist

#### Player Systems:

*   Player can move, run, crouch, jump
*   Stamina drains and regenerates properly
*   Health, shield, and damage operate correctly
*   Finger Gun fires and consumes ammo
*   Thumb Grenade explodes and deals damage

#### Enemy AI

*   Seeker reacts to sound only
*   Zombies detect player visually and chase
*   Weeping Angels freeze when looked at
*   Enemy spawning system functions correctly
*   Pathfinding works in every room

#### Environment:

*   Elevators move between floors without issue
*   Room keys open the correct doors
*   Capillaries (crawlspace secrets) function
*   Level geometry has no collision issues
*   Lighting and atmosphere load properly

#### Gameplay Flow

*   Final boss starts, fights, and ends properly
*   HUD updates correctly (health, ammo, stamina)
*   All pickups spawn with correct values
*   Game can be completed start to finish

## Updating Test Plan

The test plan is updated any time the design document changes, including:
*   Adding a new enemy type
*   Adjusting item behavior
*   Rebalancing weapons
*   Changing room layout
*   Introducing new mechanics or interactions

**The update process:**

1.  Identify any changes made to gameplay, mechanics, or level structure.
2.  Update the design document first.
3.  Adjust the test plan to match the new expected behavior.
4.  Add new test items or remove obsolete ones.
5.  Notify testers of updated procedures before the next test session.

## Bug Reporting Process

**Bug report format:**

*   **Title:** (short description)
*   **Category:**
*   **Severity:**
*   **Reproduction steps:**
*   **Expected result:**
*   **Actual result:**

*(We have created an excel spreadsheet in order to keep this tidy and keep track of all bugs overtime so we can look back on them if needed)*


---

# Module Four Team Project Log

## What part of the testing process did the team perceive to go well? 

*  Early QA helped us catch major animation issues with the original finger-gun mechanic. 
*  Playtesting each mechanic in small pieces allowed us to find issues before they affected larger systems. 
*  Identifying the animation failure early allowed us to pivot smoothly to a full-body mesh that shoots from the hand. 
*  QA helped ensure gameplay functions were tested as soon as they were implemented.

## What bugs were identified and corrected?  

*  Bugs were discovered through repeated playtests focused on individual mechanics (shooting, movement, pickups, etc.). 
*  Animation issues were found by reviewing state machines and rig behavior.
*  Logic errors were corrected by inspecting Blueprint nodes and checking events, collisions, and transitions.
*  The grenade mechanic bug led to a creative redesign, switching from an animated throw to picking up finger “grenades” from the ground.

## In terms of the QA testing process, what would you do differently to improve the process?

*  Create more structured test cases early in development instead of relying mainly on reactive testing.
*  Add checklists for animation blending, input handling, projectile behavior, and mesh replacements.
*  Schedule regular testing intervals to ensure consistency instead of testing only after new features are added.
*  Maintain clearer documentation of bugs, their causes, and the fixes applied.

## What tools did you find successful in the development of your Alpha project? Why? 

*  Unreal Engine Blueprint visual scripting — easy debugging, fast iteration, and clear logic flow.
*  Animation preview tools and the animation state machine — helped diagnose why finger-gun animations failed.
*  Collision and event debugging tools — helped verify pickups, shooting triggers, and environmental interactions.

## Were there any tools or techniques that you did not find helpful in the success of your project development? Why? 

*  Advanced profiling tools were not very useful due to the small scope of the Alpha project.
*  Large-scale version control systems were unnecessary for a small team with limited content.
*  Some animation tools were less helpful once we switched from finger-gun animations to a full-body mesh approach.

## What did the team approach to the initial analysis of the game design document contribute to the decision to use these tools and techniques? 

*  The GDD emphasized quirky mechanics (finger-gun, finger grenades), which required tools supporting rapid iteration.
*  Blueprint and animation debugging tools were chosen because they allowed the team to quickly adjust mechanics without losing design intent.
*  The GDD gave the team clear expectations for movement, shooting, and pickup mechanics, helping QA recognize deviations early.
*  Alignment on the core design vision made it easier to adapt when animations failed, allowing for the hand-shooting mesh and new grenade pickup concept. 
