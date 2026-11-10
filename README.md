# in-class-activities
## Devlogs
### W1
Write your W1 activity Devlog here.
1. When I move the camera out of the Cat Object the camera stays in the same place while the cat moves around. This happpens because, the camera is no longer a child of the cat so it is no longer one with the cat and acts as a separate object.
2. https://hrajeev.itch.io/week-1-activity 

### W2
Create future Devlog sub-headers with the three # symbols, then write your Devlogs below them.
1. They are floats because the color wheel supports decimal values so in order to store those decimal values we need to write float.
2. The _bounce variable is an int becuase, the amount of times the ball bounces would be a whole number instead of decimals.
3. It told us that the statement of code was incomplete so in order to complete the line of code we had to add a semicolon so the code compiles.

### W3
Activity 1
1. public string GetResponse (int friendshipLevel, bool KnowSecret)
2. The players sanity level is an input and the players return type is an void so there isn't an output.
3. public bool DidHitBeat (float timeHit)
Activity 2
1. The spellbook is our classes that we use as the basis to cast spell, the spells are the components, and the casters are the member variables.

### W4
1. We added rigid bodies to the game objects Cat and SoccerBall. We added the isTrigger for the Goal because, the goal post has an action triggered when the soccer ball goes through the goal. So it has to be a non solid object (is Trigger) in order to do that.
2. We had to fix the freeze rotations for the ball and the cat because when it moved the cat flew out of the bounds and rotated constantly. We had to add specific positions so it stays in place.

### W5
Activity 1
- To understand the Deer W5 script, we need to look at Cat script from last week since the code is quite similar (copy paste the code from that)
- It might also help to look at the minigame from last week (the fish code) to help with movement (the key movements)
- The member variables that this class needs is NavMeshAgent and Transform.
- The methods that this class needs is the Start() and Update() to initialize the game and update the movements of the animals by each frame.
### W6
Activity 1
https://docs.google.com/document/d/1ZtUXbaq48lSscmZFjwwkLhq-6Y2Undi4IIagxdTtJH4/edit?tab=t.0
Activity 2
- We are planning on using the bird manager code from the minigame to help with the code for class
- The methods that we are p;aning to use so sar are Start(),RunTo,Update()
- The member variables I defined in the bat class was speed,animator,directions
- The methods should control the start of the game (Start()), how the bats run to the player (Runto), it runs the animation every frame (Update())

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
