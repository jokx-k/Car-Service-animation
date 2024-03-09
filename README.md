
## Story Board:
 - A man is stranded in a desolate road where there are no people, only a cat, after
his car broke down .he is wandering aimlessly after giving up hope that anyone
will pick him up or help him from this situation, there are 4 scenes in total:
    1. The man realizes the severity of the situation after looking around and is
        depressed
    2. He wanders around the place without much hope for the next few minutes
    3. The man stumbles upon a billboard that’s conveniently advertising a Taxi
        service that comes anywhere and he proceeds to call their number
    4. The Taxi picks up the man and leaves
       
## Set of Models:
    1- Billboard (Handmade)
    2- Human Model (Premade)
    3- Phone slab
    4- Taxi (Premade)
    5- Cat(handmade)
    
## Implementation Steps:
 1- A billboard was first made by modifying some cubes for the shape of the
    board and cylinders were used to create the pole of the billboard, some
    cylinders and cubes were also used to create the poles of the lights above
    the billboard and light sources were placed respectively where the light
    lamps are.

 2- A premade human mannequin model was then added to the project and
    rigged manually and inverse kinematics were used to keep his legs on the
    ground when animating and to look more natural when the knees bend

 3- After the rigging was complete a set of actions/animations were created for The Human model
   - Idle Animation
   - Walk Animation
   - Look around Animation
   - Thinking Pose
   
 4- The animations were then used to form a nonlinear animation using the
    timeline in Blender to create the video, a Path model was also created so
    that the Human model can follow it around the area in the scene when
    using the walking animation

5- Textures were then added to the scene for the floor and an advertisement
    picture for the billboard

6- A premade taxi model was imported at the end to pick the person up
    during the ending of the animation after the person uses a cube-shaped
    phone to call it
