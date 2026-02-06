# 🐙 Parasite Dottopus

**Parasite Dottopus** is a specialized stealth-action game developed for the **Halloween Game Jam**. Built with Unity, the game focuses on a unique "Takeover" mechanic where the player, as a parasitic entity, must navigate through high-security environments by possessing hosts and managing their physical capabilities.

## 👻 Jam Theme & Story
Developed under the Halloween theme, the game puts you in control of a lab-grown parasite. Your goal is to escape the facility by possessing the minds of scientists and soldiers. The tension is built through a dark atmosphere, stealth-heavy gameplay, and the constant threat of being discovered.

## 🕹 Core Gameplay Mechanics
* **Possession System (Takeover):** Leap onto hosts to gain control of their movement and abilities.
* **Host Fatigue Management:** Each host has a limited "stability" period. Players must monitor fatigue levels and switch hosts strategically before the possession fails.
* **Stealth & Hiding:** Utilize environmental "Hiding Spots" and dynamic cone-of-sight mechanics to evade high-security patrols.
* **Complex Game Loop:** Features an integrated Intro storyboard, stealth-based lab levels, and a challenging End-Game Boss encounter.

## 🛠 Technical Features
This project demonstrates advanced Unity implementation techniques:
* **Architecture:** Modular controller system (Boss, Enemy, Player) ensuring decoupled logic.
* **Visuals:** Universal Render Pipeline (URP) with custom **Shader Graph** effects (Alert Shaders, Fake Lighting) for atmospheric depth.
* **AI Systems:** Enemy AI with state-based patrolling, vision detection, and fatigue-response logic.
* **UI/UX:** Dynamic health bars, fatigue indicators, and an interactive storyboard system.

## 📁 Project Structure
```text
Parasite-Dottopus/
├── Assets/
│   ├── Scripts/        # Core logic (Boss, Characters, UI, World)
│   ├── Prefabs/        # Reusable entities (Enemies, Projectiles, VFX)
│   ├── Animations/     # Frame-by-frame character & environment anims
│   ├── Sprites/        # Original hand-drawn jam assets
│   └── Shader/         # Custom URP Shader Graphs & Materials
```
<img width="1918" height="1080" alt="Ekran görüntüsü 2025-11-07 041336" src="https://github.com/user-attachments/assets/65710f37-8e62-4df9-8dae-df59b5c8838a" />
<img width="1922" height="1080" alt="Ekran görüntüsü 2025-11-07 041401" src="https://github.com/user-attachments/assets/64a59f0c-1081-4179-8e92-a2e735e982da" />
<img width="1916" height="1080" alt="Ekran görüntüsü 2025-11-07 041541" src="https://github.com/user-attachments/assets/566d72ab-964b-4d89-9682-d913ed1af006" />
<img width="1914" height="1080" alt="Ekran görüntüsü 2025-11-07 041317" src="https://github.com/user-attachments/assets/cf9d865d-8fe5-495b-8f7e-d50ab4366962" />
<img width="1918" height="1080" alt="Ekran görüntüsü 2025-11-07 041325" src="https://github.com/user-attachments/assets/2fc25bd7-de80-4056-9cad-32a48e2019cf" />
