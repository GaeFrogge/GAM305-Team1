Project Log Assignments



Module Two Team 1 Project Plan

-Notes: 

Hayley - Programming
Chris - Lead / Programming / Float
Miranda - Modeling / texturing
Aidan - Level design
Cleve - float/Level design

-Content: 

Military Hospital - dingy
Kill method - shooting, possibly alternate
Virus - some ranged, some contact, maybe explode, splitting viruses, 
pickups - health, see through walls goggles, shields, damage up, high jump, speed, fire rate, ammo pickups, infinite stamina, different ammo (freeze
Elevators - vert and Horiz
Teleports

-Timeline:

Week 3 - QA and testing
Week 4 - Alpha Release
Week 5 - Beta Release
Week 6 - Final Release
Week 7 - Final Project Submission

Alpha - Basic mechanics, Static meshes, Test environment design

Beta - Most Mechanics, Most animations/rigging finished

Discord for communication

Frequency - Regular discussion Weekly meetings Thursday 8PM EST

Channels in discord for assigning and reporting tasks


Module Three Project Log - Team Development: QA and Testing Plan


Christopher, Miranda, Hayley, Cleve, Aidan

Schedule: Alpha - Module 4, Beta - Module 5, Release - Module 6


- Alpha -

Playtest : Player movement and interaction with pickups, AI functionality, Projectiles do damage, Pickups function as intended, meshes have collision

What's being tested : WASD keys move player in correct directions, Mouse movement moves camera in correct direction, Interact key activates correctly, Fire button spawns Projectiles, Projectiles collisions cause damage, AI moves and targets player, Pickups accomplish desired functions


- Beta - 

Playtest : Different AI types, Different pickups, Actor animations

What's being tested : Ai's correctly display variety of actions, Various pickups function as intended, Actor animations functional and clean

Demo : Having friends, family, or others, play the project to check for functionality as outlined above.

What's being tested : map exploration and navigation, Are the functions and mechanics intuitive, Difficulty, Artifacts or mesh issues


- Release -

Code Release : Have all bugs been fixed, Can game be played from beginning to end, Have debug menus been removed, Does the build run smoothly


- Update Test Plan - 

Excel Spreadsheet to include all test factors, updated as needed


- How will bugs be reported - 

Developer will submit bug report in bug report discord channel


- How will bugs and their changes be tracked over time -

Bug database in a Microsoft excel sheet, cause of bug, and whether fixed or not updated based on bug report channel in discord




Module Four Project Log - Team Reflection

Christopher - Lead
Hayley - Programming
Miranda - Modeling
Cleve - Environment
Aidan - Environment

- QA -

: Programming :

~ What's Being Tested ~

Character Movement, AI Movement, Projectiles, Keybinds, Pickup

Character moves with WASD keys as intended, Spacebar causes player to jump, projectiles on LMB, E key interacts, Pickups function and disappear after being collected, AI wanders

No bugs currently in programming

: Environment :

~ What's Being Tested ~

Blocked out levels, light emission inconsistent

Rooms are Blocked out waiting for assets, Lighting is initialized

- Lighting needs tweaking for beta

: Art :

~ What's Being Tested ~

Static models for AI and pickups

All models created

# QA and testing #

:What went well:

- Programming -

    1. Quickly discovered bug only allowing one pickup to be interacted with, solved by disabling consume input
    

- Environments -

    1. Adjusting lighting to make level more appealing

- Art - 

    1. All models functioned and imported as intended

- Overall - 

Everything worked smoothly and readily


:What would we do differently:

We are fairly satisfied with our current process

: Bug Identifying and correcting :

- Version Control -

    1. Issues with devs on different UE versions - FIXED (Aligned everyon onto same version of editor)

- Programming -

    1. AI wandering not working correctly - Fixed (realigned navmesh)

- Environments - 

    1. Lighting inconsistent, areas too dark - WIP

- Art - 

    1. Vertex missing from normal when importing - FIXED (Corrected settings)

# Tools and Techniques #

- Overall - 
Testing as we work to ensure proper function has allowed us to move forward with very little issue

Team aligned with initial outline provided  covering what each "department" is responsible for in reference to alpha release

as follows :

Reposting this in here so it's in the right area and easy to find:

While we will be covering our QA process in module three, I wanna get info aligned for our more major milestones.

Module four is our first major step with it being the submission of our alpha build. For that reason I want to outline the basics of what each “department” should have accomplished in that time

Programming - We need to have player and enemy classes, a base game mode,  a rough ai/movement for enemies, basic projectile code, and a baseline for our pickups and additional features that we can copy and build from, for the shooting mechanic, we can use a basic cylinder projectile until we determine how far we wanna take that!

Modeling - static meshes for the player and enemies (3 types) I don’t personally know much about the art side so if I say anything that is outside the scope of what you can do please tell me! I’d also like some basic meshes for the pickups outlined in our meeting notes (ammo, speed, health, etc.) Aside from those models, you can work on any extras like elements for the level designers or whatever. 

Level design - for now, use primitives within the unreal modeling mode to start blocking out and laying out your rooms. Try to make things in a way that allows you to easily replace the primitives with meshes once art is done with their end. For example tables could just be cubes scaled to fit in the place you want them, bottles could be small cylinders. Have fun and give us lots of “lived in dingy run down”  vibes!

Myself maintaining the repo, I’ll also work on programming for menu and hud systems for the game, and help anywhere else I’m needed.

Lastly, as far as audio, I have access and licensing for a LARGE amount of music and sound effects that I do have legal rights to use in video games, so unless someone wants to create music and foley, I have that covered.

Thank you everyone, let’s kick some butt and have fun!
NEW

that was for the alpha deadline

# Module Five Project Log - Team Reflection

## Team Members
    - Christopher : Lead, UI/UX
    - Hayley : Programming, AI
    - Cleve : Environment
    - Aidan : Environment
    - Miranda : Art, Enemy Models, Pickups

### What went well

- Production
	- Course correction from previous weeks issues and keeping team on track

- Programming
	- Implementation of exploding enemies
	- Troubleshooting of previous bugs

- Environment
	- Portals to move about level
	- Implementation of environmental objects to fit the theme and add immersion into the world
	- Learning and utilizing Niagara system effects

- Art
	- Texture mapping of enemy models
	- Pickup materials adjusted and improved

### What Went Wrong
	- Could have created an asset spreadsheet to better inform the team of where to focus efforts
	- Issues with rigging models
	- Not meeting current alpha stage goals
	- Slightly behind on beta stage goals

### Integration of Previous Evaluations
	- Creating asset spreadsheet, covering what assets we have, and still need to meet our release goals
	
### Do Differently
	- Creating a more organized game design document, with checklists, and better documentation to more easily communicate what is needed
	- Version control - ensuring everyone is on the correct version of UE from day one
	- More clear deadlines - better laid out plans for what to have done at specific times
	- MORE CHECKLISTS
	- Better organization of discord channels

### Tools/Techniques Not Helpful?
	- More so not implementing an array of tools and techniques highlighted where we could have done better within the project. We did not find any tools or techniques provided to be unhelpful

### Beta Stage Status Assessment
	- Beta Stage goals were mostly met, Some last minute polish and finalizing all intended mechanics and animations for final release.
	- Asset Spreadsheet URL : https://docs.google.com/spreadsheets/d/1sENu1GCSPzAS0iUhPI7fuPlksencdNji-TArxZgN9bk/edit?gid=0#gid=0

### Outline for Beta Release
Module 5 Outline

Hello everyone, I am doing this writeup to help us stay on pace for our beta release at the end of next week (module 5)

 -I. Programming - Primarily the enemy ai needs to target and 'attack' the player class, as well as incorporating relevant mechanics. Influenza should explode when near a player, Phages should shoot at the player, and Pneuma should multiply at some given rate. Pickups should have their separate functions, and should maybe spin in place or some other effect. and lastly, we need a base HP and HUD implemented, as well as a main menu (I will add my graphics to that system once implemented ^_^ )

 -II. Modeling - texturing and animations for the 3 enemy models. Pickups do not need to be animated as that can be handled in the editor. I know rigging will be the pain that it is so reach with any ideas or concerns. 

 -III. Environment - Keep up the good work, its time to replace the blocked in features with appropriate assets, and not just primitives. I really like the direction I'm seeing here, so keep fleshing it out. for lighting, add an ambient light source, and uncheck casts shadows, then play with the amount of emission and color, it should help with the 'too dark' areas.

Once again reach out to me with any issues, I will be happy to help with anything you may need, or any questions you may have. 
Thank you all for your hard work, and I remain excited to see what we can make together!
