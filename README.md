# LifeAtUWC
A game project prototype that will allow players to virtually experience life at UWC Dilijan.

Idea 1: A game about Dilijan
General idea can be like the Sims, where you lead the life of a character
This idea is getting really complicated, so we might consider doing something else first, or just building a very simple version of it!

Overview: Mimicking the life of Dilijan, which consists mainly of the activities: meal times, classes, workout, engaging in conversations, parties at Mimino and Dolmama, studying, sleeping (another dimension can be dating, but that could be quite complicated?)

The character:
Can name the character
Can choose where the character comes from (well, design will definitely be tricky for this haha - if only there’s a way of extracting the algorithm of these customized stickers like on snapchat)

How one can keep scores in the game:
Energy bars for each day that could be pumped up by
Sleeping enough
Drinking vodka (but will need extra sleep to recover the next day)
When energy reaches 0, the person passes out. Keep in mind as well, that too little sleep means negative health point.
Discipline points that, if too low, will result in meeting with Sally or being expelled
IB predicted grades that depends on going to classes/skipping classes/spending time studying (or being Asian lmao jkjk)
Mental health points: through having a balance of the other points (if any of them goes significantly lower, mental health will also be affected), as well as spending time engaging in conversations (more rewards) and going to parties (a little less rewards)
Health points: getting enough sleep, getting enough workout, having regular meals, maintaining good mental health

Consequences of the activities:
Sleeping: gain energy
Meal times: gain health points
Classes: gain predicted grades
Workout: gain health points
Conversations: gain mental health points, which in turns increases health points
Parties: a gamble, sometimes gains mental health points, sometimes loses mental health points
Studying: gain predicted grades
(Dating: could be a gamble on mental health as well? Also not sure how to count the hours for this, so I think probably too complicated to tackle for now) 

The idea is to allocate the right balance of time. Of course too much studying will negatively affect mental health, but that could already be because there is not enough time for the other activities. There should be a fixed total of points for all the categories, or some sort of sum that remains relatively unchanged, so that the difficulty of the game lies on the balancing of time...

The way one can play is to plan out a day ahead for the character, and if left alone for a long time, the character keeps following the same routine. However, there will from time to time be some situations thrown in, like an exam, when the regular routine might not be the best. I think these scenarios are too advanced for now though, but just writing down the ideas here.



Architectural Side

Software Options;

Twinmotion; Landscape, however, it is currently not possible to transfer it to UE4
Blender; Prototype design for objects and buildings, can be exported to UE4

Architectural details of some buildings at UWC Dilijan can be found at; https://www.archdaily.com/792973/uwc-dilijan-college-tim-flynn-architects/57a9bb69e58ece1d310001f8-uwc-dilijan-college-tim-flynn-architects-photo

Gaming Side

Software Options;

Unreal Engine 4 (UE4); Game engine that allows Blueprint design as well as C++ code. 

Human Prototypes; makehumancommunity.org

It can be based on a survival game to create a menu, character, environment, health system, fall damage, stamina, skill, intellect, inventory system, 

Tutorials;

Survival Game w UE4 tutorial; 
https://www.youtube.com/watch?v=tTqgloNkNSM&list=PLgyA4MNDbNLlXTBpZAx0GlWCzQbIQ9EaA

Blender Modeling / 2.8 Fundamentals; 
https://www.youtube.com/watch?v=MF1qEhBSfq4&list=PLa1F2ddGya_-UvuAqHAksYnB0qL9yWDO6
