[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Audrey Custodio
### Student number: 47301414

## 1. Player Experience (~700 words)
### 1.1. Discovery
**Discovering the mechanics of the weapons**
**Section 1 - Staff**

At the start of the level, I intentionally put the destructible column and chomper next to each other. The purpose of this was so that the player recognises that the staff can be used to destroy things. If it can destroy a destructible column, it would be reasonable to propose that it can also destroy a chomper. By forcing the player to break the destructible column with the staff to progress, it is ensured that they learn this mechanic.

![Staff encounter](DocImages/GameScreenshots/Staff.png)

**Section 1 - Gun**

I wanted the player to discover they can use the gun on switches. To achieve this, I presented a problem for the player: a switch that can’t be walked through or jumped to. They will need to find an alternative way of flipping the switch. This is present in two areas of Section 1 and is used to gate progression before the player learns the gun’s mechanics. 
By again trapping the player in a room, they discover that the gun can be used to shoot switches. 
They may then recognise the placement of the switch being similar to the one in the other room, and then use the gun there.
Through this level design, I believe the player engages in the experience of discovery by finding out the dynamic between the gun and switch and recognising the pattern of the layout.

![Gun encounter](DocImages/GameScreenshots/Gun.png)

### 1.2. Drama
**Section 1 - Falling**

Since this is towards the beginning of the level, I wanted the player to feel excited to start. I included this falling section to give the player a sense of exhilaration and thrill, similar to how a drop tower ride would.

![Falling](DocImages/GameScreenshots/fall.png)

**Section 2 - Rest room**

In the middle of all the intense platforming and encounters with enemies, I wanted to give the player a break. The room provides health packs and is absent of any dangers.

![Rest](DocImages/GameScreenshots/rest.png)

### 1.3. Challenge
**Section 2 - Optional challenge rooms**

The player can engage in optional challenge rooms that are more difficult than the other route. Each room is dedicated to challenging the player in both platforming and combat, inviting them to showcase their skills in these aspects.

The first room is dedicated to platforming. In this level, players must jump over obstacles as they ride the moving platforms. Completing this challenge requires players to react quickly and maneuver themselves around the limited space they have.

![Challenge room 1](DocImages/GameScreenshots/room1.png)

The second room requires the player to be good at platforming and combat. In combat, players will need to dodge enemy spitter bullets and accurately hit enemies while navigating the small platforms provided. Completing this challenge requires players to be precise with their movements and gunshots.

![Challenge room 2](DocImages/GameScreenshots/room2.png)

**Section 3 - Final platforming challenge**

For Section 3, I really wanted to explore this idea of a level that’s easy to enter but harder to escape. Initially, it’s easy to hop on stationary platforms and get to the other side. However, when the switch at the end is flipped, all those platforms from before will now be moving, making it considerably harder. Completing this challenge requires players to be fast and precise with their movements so that don’t fall into the acid or hit the spikes.

![Challenge room 3](DocImages/GameScreenshots/room3.png)

### 1.4. Exploration
**Section 1 - Two directions**

In the first section, I didn’t want the player to just move in one direction. To get a better sense of exploration, I wanted the player to go back and forth between places and invite the player to explore and take note of distinct landmarks.

I believe the most distinct parts of this section are the parts that gate progression to the next section, Section 2. Which is the trigger door on the left and the acid pool to the right. 
By gating parts of the section, I invite the player to explore and find out how to get past the trigger door and gate.

![Gate Progression](DocImages/GameScreenshots/gate.png)

**Section 2 - Two paths**

I wanted this section to be a bit less linear than the first section, which has optional routes. Multiple paths can give players a sense of freedom. When they’re able to make their own choices, they’re more likely to be invested in the outcomes of those choices and the journey to reaching these destinations while exploring.

I placed two routes for the player, one easy and the other challenging. They both require the player to navigate large spaces through platforming, making it engaging to move around and explore.

| Route without paths | Route with paths |
| ------------- | ------------- |
| ![Route 1](DocImages/GameScreenshots/routes2.png) | ![Route 2](DocImages/GameScreenshots/routes1.png)  | 

## 2. Core Gameplay (~400 words)

### 2.1 Weapon Pickup (Staff) and Destructible Column
| Panel 1 | Panel 2 | Panel 3 |
| :------------- | :------------- | :------------- |
| ![2.1 Panel 1](DocImages/Storyboards/Slide1.PNG) | ![2.1 Panel 2](DocImages/Storyboards/Slide2.PNG)  | ![2.1 Panel 3](DocImages/Storyboards/Slide3.PNG) 
| The player is trapped in a room with a destructible column blocking the exit. | The player picks up the staff. | The player uses the staff to break the destructible column to exit and progress. They have now learned that the staff can be used to break certain things. |
### 2.2 Chompers
| Panel 1 | Panel 2 |  |
| :------------- | :------------- | :------------- |
| ![2.2 Panel 1](DocImages/Storyboards/Slide4.PNG) | ![2.2 Panel 2](DocImages/Storyboards/Slide5.PNG)  | 
| The player sees the chomper at a distance. Similar to breaking a destructible column, players can “break” an enemy, such as the chomper,  the same way. | A chomper sees the player in sight and then pursues them, intending to attack. | 
| **Panel 3 - Player response 1** | **Panel 4 - Player response 2** | **Panel 5 - Player response 3** |
| ![2.2 Panel 3](DocImages/Storyboards/Slide8.PNG) | ![2.2 Panel 4](DocImages/Storyboards/Slide6.PNG)   | ![2.2 Panel 5](DocImages/Storyboards/Slide7.PNG) 
| Players may use the staff to defend themselves as a reflex gained from breaking the destructible column earlier. | They may also jump over the enemy. An ample amount of space above the player is made to accommodate jumping. | Alternatively, if they fail to react in time, they may be damaged by the chomper. |
### 2.3 Pass-through Platforms, Switches and Trigger Doors
| Panel 1 | Panel 2 | Panel 3 |
| :------------- | :------------- | :------------- |
| ![2.3 Panel 1](DocImages/Storyboards/Slide9.PNG) | ![2.3 Panel 2](DocImages/Storyboards/Slide10.PNG)  | ![2.3 Panel 3](DocImages/Storyboards/Slide11.PNG) 
| The player is trapped again, and the only way out is by activating the switch to open the door. | Have it so the player can only get to the switch through the pass-through platform, block off anywhere else. | By activating the switch, the player will be able to open the door right next to it, so there is a direct correlation between the door and the switch for the player. |
### 2.4 Spikes and Health Pickups
| Panel 1 | Panel 2 | Panel 3 |
| :------------- | :------------- | :------------- |
| ![2.4 Panel 1](DocImages/Storyboards/Slide12.PNG) | ![2.4 Panel 2](DocImages/Storyboards/Slide13.PNG)  | ![2.4 Panel 3](DocImages/Storyboards/Slide14.PNG) 
| The player will fall down into spikes. | Once the player is damaged from the spikes, health pick-ups will be nearby. They may also have the chance to land on them after being damaged. | The player will gain 1 health point by picking it up. |
### 2.5 Acid, Moving Platforms, Checkpoints, and Weapon Pickup (Gun)
| Panel 1 | Panel 2 | Panel 3 |
| :------------- | :------------- | :------------- |
| ![2.5 Panel 1](DocImages/Storyboards/Slide15.PNG) | ![2.5 Panel 2](DocImages/Storyboards/Slide16.PNG)  | ![2.5 Panel 2](DocImages/Storyboards/Slide17.PNG)  | 
| The player encounters acid, there is a platform for the to jump onto. | The player goes past a checkpoint and jumps onto the (currently stationary) moving platform. They then jump from the stationary moving platform and onto a ledge. | They continue on. | 
| **Panel 4** | **Panel 5** | **Panel 6** |
| ![2.5 Panel 3](DocImages/Storyboards/Slide18.PNG) | ![2.5 Panel 4](DocImages/Storyboards/Slide19.PNG)   | ![2.5 Panel 5](DocImages/Storyboards/Slide20.PNG) |
| Once they move to the right, they fall onto the switch that activates the moving platform. The moving platform goes into the acid and can no longer be jumped on. | The player picks up the gun and jumps to a ledge closer to the other switch. | They shoot the switch, and the trigger door opens. |
| **Panel 7** | **Panel 8** |  |
| ![2.5 Panel 3](DocImages/Storyboards/Slide21.PNG) | ![2.5 Panel 4](DocImages/Storyboards/Slide22.PNG)   | 
| They have no choice but to jump into the acid. | They discover they respawn back to the checkpoint. |
### 2.6 Keys
| Panel 1 | Panel 2 | Panel 3 |
| :------------- | :------------- | :------------- |
| ![2.6 Panel 1](DocImages/Storyboards/Slide26.PNG) | ![2.6 Panel 2](DocImages/Storyboards/Slide27.PNG)  | ![2.6 Panel 3](DocImages/Storyboards/Slide28.PNG) 
| The key will be locked behind a door, implying it has significant value. | To get the key, the player will have to find a switch somewhere to unlock the door. | Only after flipping the switch will they be able to unlock the door and get the key. |
### 2.7 Spitters
| Panel 1 | Panel 2 | Panel 3 |
| :------------- | :------------- | :------------- |
| ![2.7 Panel 1](DocImages/Storyboards/Slide23.PNG) | ![2.7 Panel 2](DocImages/Storyboards/Slide24.PNG)  | ![2.7 Panel 3](DocImages/Storyboards/Slide25.PNG) 
| The spitter will be on a high ledge that the player cannot get on. The spitter has a height/range advantage against the player. | The player will have to run past the spitter's bullet and utilise a platform to gain height and shoot the spitter. | The player may also jump and hit the spitter with a staff. |

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

![Molecule Diagram](DocImages/Maps/molecule-diagram.PNG)
*note this isn't representative of the final level design

### 3.2. Level Map - Sections 1, 2, and 3 (labelled)
| Key |  |
| ------------- | ------------- |
| ![Map key](DocImages/Maps/key-grid-map.png) |  |
| **Map with paths** | **Map without paths** |
| ![Map 1](DocImages/Maps/grid-level-map.png) | ![Map 2](DocImages/Maps/grid-level-map-plain.png)  | 

## 4. Iterative Design (~400 words)
**Idea generation on paper**
To start, I put a lot of my ideas on paper to help me work through different concepts and see how the player could navigate these aspects of a level. Once they were all laid out, I began to see how they could be pieced together and flow into one another. 
| Idea 1 | Idea 2 | Idea 3 |
| :------------- | :------------- | :------------- |
| ![2.5 Panel 1](DocImages/Storyboards/Slide15.PNG) | ![2.5 Panel 2](DocImages/Storyboards/Slide16.PNG)  | ![2.5 Panel 2](DocImages/Storyboards/Slide17.PNG)  | 
| The player encounters acid, there is a platform for the to jump onto. | The player goes past a checkpoint and jumps onto the (currently stationary) moving platform. They then jump from the stationary moving platform and onto a ledge. | They continue on. | 
| **Idea 4** | **Idea 5** | **Idea 6** |
| ![2.5 Panel 3](DocImages/Storyboards/Slide18.PNG) | ![2.5 Panel 4](DocImages/Storyboards/Slide19.PNG)   | ![2.5 Panel 5](DocImages/Storyboards/Slide20.PNG) |
| Once they move to the right, they fall onto the switch that activates the moving platform. The moving platform goes into the acid and can no longer be jumped on. | The player picks up the gun and jumps to a ledge closer to the other switch. | They shoot the switch, and the trigger door opens. |

**Initial Level Map**
While I had initially thought about a left-to-right format for my level, I wanted to try a semi-linear format where the player would have to go in all sorts of directions. This was mainly because I wanted to have a better sense of exploration in my game’s level design. 

![Initial Map](DocImages/Maps/initial-layout.png)

**Rough map sketch**
Before I made the grid map, I wasn’t quite sure what my rooms were going to look like. I made this rough sketch to record my ideas for layouts, progression, challenges, and direction. I expanded on the initial level map I made, adding in specific features and piecing together the ideas I did on paper.

![Rough Map](DocImages/Maps/level-map.png)

**Grid map**
While the rough map sketch had given me a sense of how I could lay out features and arrange tiles within the level, I wasn’t sure of its practicality. The annotated level map (grid map) helped me to organise the layout of my level and reflect on the flow of the game. The grid format also allowed me to use this map as a guide and easily translate my design into Unity’s tilemap editor.

**Final Level Design: Design changes made in Unity**
I found that testing my design within an actual playable level would give me the best understanding of how I could improve the player experience. Mainly because I would be the player, testing the level. The most changes I would make to the level at this stage would be the ceilings of some of my rooms. I underestimated how high the player could jump, and for my initial map design, the player would often hit their head. Due to underestimating the jump, I had to change a lot of the tile layouts and platforms accordingly. 

![Final Map](DocImages/GameScreenshots/final-level.png)

**Aspects to be improved**
I would’ve liked to expand and improve on Section 3 through iterative design, as I believe it’s the least developed in my level of design. To improve it, I think I needed to playtest it more as I feel the current layout is clunky. Playtesting further would’ve allowed me to organise the layout better and potentially set up more encounters and interesting dynamics.

