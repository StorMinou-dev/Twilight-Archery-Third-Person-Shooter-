# Twilight-Archery-Third-Person-Shooter-
*1 month*, *2025*, *Unreal*, *Game*, *Group*, *C++*, *Nintendo Switch*


### Project Name : **Twilight Archery**
*Quick description* : Isart Digital Project, TPS boss fight coop game made in Unity.  
*Author* : Aodrenn, Liam, Kenzo

**Gameplay**  
This project is a cooperative third-person shooter developed in Unreal Engine.  
Two players control archers fighting together against a giant boss  
in a dedicated boss combat experience.  
We had to optimize the game to fit the Nintendo Switch specs.  

<img width="450" height="250" alt="image" src="https://github.com/user-attachments/assets/592f2bca-d845-4f22-b193-ba5d62e01c12" />


**Boss**  
The boss is a giant mecha creature inspired by Godzilla.  
Its behavior is entirely driven by a Behavior Tree,  
allowing structured and readable AI logic.  
The boss reacts to player position by switching attacks  
in its arsenal.  
[Boss Image]  


**Attacks**  
We made an Attack class that each of the boss  
attacks inherits from.  
The boss features four distinct attacks :  
Laser – A quick beam attack  
Fireball – A projectile-based ranged attack  
Slap – A close-range melee attack  
Rockets – Auto aimed rockets attack  
[Attacks Image]  


**Optimization (Nintendo Switch)**  
We needed the game to run smoothly on Nintendo Switch devices so we had  
to  give a special attention to performance optimization.  
This includes reducing game's quality, not using dynamic lights and shadows,  
and disabling tools such as lumen.  
[Optimization Image]  

**Other Informations**  
This project was developed as a group project using Unreal Engine.  
All models, animations, and textures were sourced from third-party  
assets, including the Unreal Engine Asset Store and Mixamo.  





