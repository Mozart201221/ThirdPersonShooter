# ThirdPersonShooter
Pattern (Game) for correct class inheritance

1. Correct placement and preparation of the object for further work
2. Adding animations to the project
3. Adding SM_G36C-SF to the character's arms and behind the character's back (Switch pose with key 1)
4. Adding Ironsights animation and aiming function along with sprint (Right Mouse Button - aiming, LeftShift - sprint)
5. We aim the weapon in the direction of the sight (Pitch)
6. Added crouching and weapon with jump (LeftCtrl - crouch) 
7. Implementing logic of logic for finding and moving to a point on the map for NPC in AiController (Not BehaviourTree!) // This is the logic behind the early version of the engine (UE4 4.19 in 2018)
8. The NPC moves to a fire, tree, and other random point
9. Added implementation of a rifle shot (LMB - shoot) 
10. Adding ammo to weapon and reload (R - reload)
11. Adding life and death to a character displaying on the screen
12. Adding taking weapons and ammunition (E - interact) 
13. Adding death animation on body or head hits
14. Fixing bugs (Shooting, acceleration, crouching, aiming in jump; the animation of taking the rifle right away without completing it; error of an NPC that does not have NavMesh)
15. Adding a laser to a weapon while aiming.
16. Adding patrol and attack system for NPC (The logic is built in the class "AIСontroller" without BehaviorTree) //  **Add a diagram for the future!!**
17. Adding an alert for NPC (Widget component)
18. Combining a widget about the status of NPC actions and components: attacks and patrols
19. Adding to attack NPC
20. Adding reloading for weapons (Attention! There is a bug here, when the reloading animation occurs, we can shoot)
21. Collecting ammo from a dead NPC 
22. Implementation of damage through the AnyDamage function, visual effect on damage and drop weapon
23. Added a pistol as a firearm **(At this stage, there are drawbacks when taking one pistol)**
