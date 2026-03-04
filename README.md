# GDIM32 In Class Activities
## W1
### Activity 1:

Our advice was to understand how each line of code is working and the syntax behind it.

### Activity 2:

1. 10
2. 2
3. Prints "hello world" in the console every frame
4. MonoBehaviour 
5. Prints "x = 10" in the console when the game starts
6. Arguments - they pass data into methods
7. Translate can not be called on Transform
8. Call Translate on _playerObject instead

### Activity 3
[MG1 Google Doc](https://docs.google.com/document/d/1KhRQZLNVzs5TZGDPKFDH77RtlX_e1vGLo3YVHySjxfM/edit?usp=sharing)

## W2
### Activity 1:
![IMG_20260113_180206993](https://github.com/user-attachments/assets/7f017cda-8e1b-4338-b24f-a8de779f6fc9)

### Activity 2:
[Commit](https://github.com/UCI-GDIM32-W25/mg2-nlburns33/commit/0643ed09a23a2dbd920dc5f2b5676b8e1f6881a7)

I finished almost all the features except for the points text updating and coins being removed after leaving the screen. The coins spawn and move and the player can jump and collect them. 

## W3
### Activities 0-2
Brendan Johnston
### Activity 3
![4f40597e-191a-4cd6-8971-cd2e2448c7cd~1](https://github.com/user-attachments/assets/55fd88bc-2734-4f71-9c3f-7817a3ce694d)

## W4
### Activity 0
Audrey Hu, Brendan Johnston
### Activity 1
When multiple Locator objects are added, all but one of their Locator components are destroyed. The Locator gameObjects, however, remain. This happens because the Locator class checks if there is already an instance of the Locator class that isn't itself and deletes itself if so.
### Activity 2
![IMG_20260127_185701073](https://github.com/user-attachments/assets/41f67832-d363-4372-aec9-a23695035802)
### Activity 3
[Commit](https://github.com/nlburns33/HW4/commit/e0ae3fbdcf1a2a84dab08e27ff304b7a4a3617a8)

I created the pipe, player, and ground game objects and created a Locator class. I got the pipes moving to the left and started setting up colliders.

## W5
### Activity 1
I wouldn't hard code the durability or damage variables in the code, I would make them easily changeable. Otherwise, I think the structure is fine. It is relatively easy to navigate and understand what each thing is supposed to do.
### Activity 2
The model aspect is represented by the ItemW5Demo2 and EnemyStats classes, the view aspect is represented by the InventoryUI and DialogueBubble classes, and the controller aspect is represented by the PlayerW5Demo2 and EnemyW5Demo2 classes.
### Activity 3
#### Scenario 1 
ScriptableObjects can be used to hold the data for when a beat is or what type of a beat it is.
#### Scenario 2 
A finite state machine would be useful to handle player states like shooting and movement and control animations. It could also use inheritance with polymorphism for the different characters and weapons as well as scriptableobjects to hold the stats. The Model-View-Controller paradigm with C# events could handle kills and game actions like starting or ending.
#### Scenario 3
State machines can be used for plant growth states.
### Activity 4
Attendance: Nolan Burns, Brendan Johnston, Audrey Hu

[Proposal Draft](https://docs.google.com/document/d/1ol46riGsVF4tNG4s7EXD49n7NhyEQPBzmpgfhnkQLt8/edit?usp=sharing)

## W6
### Activity 1
#### Profiler
- Window -> analysis -> profiler
- The profiler seems incredibly useful for large projects
- Spikes = bad, tells how long methods take to execute
- Hierarchy orders them neatly by time
- Can find individual problem methods

#### Gizmos
- Gizmos: done with a method (OnDrawGizmos)
- Can be used to check many things in the scene view, especially colliders
- Can show things debug.log really can't

#### Breakpoints
- Breakpoints: Click to the left of a line in code editor, then attach to unity
- Stops program 
- Shows current state of variables
- Really useful for checking to see if a line ran or order of running

### Activity 2
Attendance: Nolan Burns, Brendan Johnston, Audrey Hu

[Proposal Draft](https://docs.google.com/document/d/1ol46riGsVF4tNG4s7EXD49n7NhyEQPBzmpgfhnkQLt8/edit?usp=sharing)

## W7
### Activity 1
- Raycasts can be used to check if something can see something else, then update a state machine
- Raycasts have a start location, direction, and distance
- Sphere casts can be used to avoid obstacles
### Activity 2
Attendance: Nolan Burns, Brendan Johnston, Audrey Hu.
### Activity 3
<img width="1387" height="770" alt="Screenshot 2026-02-17 181805" src="https://github.com/user-attachments/assets/e947c737-e2c3-4640-9316-545b45c09f6d" />

### Activity 4
[Trello Board](https://trello.com/invite/b/6995221d29a759665cbca1a0/ATTI34c9d8c5816e8677dba64abf85c9678701811D3A/gdim-32-final)

### Activity 5
[Commit](https://github.com/prettypinkanteater/GDIM32-Final/commit/a7c4c8168ead93fee64cd512168e5ddad4d20621)

I created the game object for the main NPC and started his movement script.

## W8
### Activity 1
- Need to check rendering pipeline compatability of asset store assets
- Postprocessing is generally quite demanding but can make a game look much better
- Runs after everything else is drawn
- Need postprocessing package first
### Activity 2
Attendance: Nolan Burns, Brendan Johnston, Audrey Hu
### Activity 3 
- slow movement
- Finish rest of the quest
- Colliders seem fine
- Bug with climbing on manager
- Likes animations
- Smooth  movement
- Knife phasing through things
- Fix outside, take away walls
### Activity 4
My task is to fix the Manager NPC's colliders and add colliders to the rest of the restaurant.
### Activity 5
[Commit](https://github.com/prettypinkanteater/GDIM32-Final/commit/f8d53ab414fcfc0cb85f7f525ec4b7b22d84da1f)

I fixed the colliders of the Manager NPC and some other objects. I also added a skybox to the scene.

## W9
### Activity 1
- Scriptable objects make the system scale far easier
- Data regarding each sequence is put into these scriptable objects
- The reply is another scriptable object that gets linked through the inspector
- Requires just a handful of general methods instead of a method for each reply
### Activity 2
Attendance: Nolan Burns, Brendan Johnston, Audrey Hu
### Activity 3
Goals: 
- Does the manager have acceptable colliders?
- Is the sensitivity and movement good?


- UI looks good
- A little unclear to get the potato first
- Sensitivity still high
- Controls are smooth enough
- counter collider could be slightly larger
- You can fit between the machines
### Activity 4
The progress we have made in our project seems to match where we should be. Although we only have a portion of the items done, once one item is done it is much easier to implement other ones as they share a lot of functionality. We have also completed most of the scene and deocration work, which is rather time-consuming process. Our project scope seems reasonable, and we are confident in our ability to have all the features done on time.
### Activity 5
[Commit](https://github.com/prettypinkanteater/GDIM32-Final/commit/eb0145c818a94860be6e14692e5229c4b53f13bd)

I started work on the dialogue system, creating the first few nodes and the dialogue controller script.


