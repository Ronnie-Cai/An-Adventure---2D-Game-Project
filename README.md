# 🎮 An Adventure — 2D Game Project

[![Unity Version](https://img.shields.io/badge/Unity-2022.3.58f1_LTS-blue?logo=unity&logoColor=white)](https://unity.com/)
[![Language](https://img.shields.io/badge/Language-C%23-green?logo=c-sharp&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?logo=windows&logoColor=white)](#)

A captivating 3-level 2D platformer demo built from scratch using the Unity engine. This project represents my journey as a developer, transitioning from foundational tutorials to implementing advanced standalone mechanics.

---

## 📖 Game Overview & Level Design & In-game Screenshot

The game features a progressive difficulty curve across three unique stages:

**Level 1 (The Essentials):** Focuses heavily on precision platforming, jumping mechanics, and learning to navigate environmental traps.
<img width="709" height="400" alt="level1" src="https://github.com/user-attachments/assets/f2328f7d-da75-4705-b600-9c39c3640e16" />

**Level 2 (The Confrontation):** Introduces  a  **Boss Fight** encounter.
* Hint for the bossfight: Continuously move and lure the boss to smash onto the yellow spikes on the ground to deplete its health.
<img width="712" height="401" alt="level2" src="https://github.com/user-attachments/assets/cb76b574-cb98-4b0a-bf3a-270ef1986acb" />

**Level 3 (The Ultimate Challenge):** A comprehensive culmination of all mechanics, emphasizing strategic level design, polished pacing, and combined obstacles.

<img width="712" height="399" alt="level3" src="https://github.com/user-attachments/assets/8e6589c2-1487-44f7-97f2-6094e6a03674" />


### 📈 Development Journey
I initially built the foundational movement and first level by following structured online documentation and tutorials. Subsequently, I successfully expanded the project to implement Levels 2 and 3, utilizing **AI-assisted development** to debug complex state machines, optimize boss behavior, and refine script architectures.

---

## 🎮 Gameplay & Controls

### Objective
Explore the levels, survive the traps, defeat the boss, and **collect as many cherries as possible**! 🍒

### Controls Mapping
| Action | Keybindings | Notes |
| :--- | :--- | :--- |
| **Move Left** | `A` / `←` | Smooth horizontal deceleration |
| **Move Right**| `D` / `→` | Smooth horizontal acceleration |
| **Jump** | `Space`   | Supports variable jump height based on hold |
| **Shoot / Fire**| `J`     | 🔒 *Unlocks automatically after acquiring the Gun item* |

---

## 🛠️ Tech Stack & Assets Credit

### Core Engineering
* **Game Engine:** Unity 2022.3.58f1 (LTS)
* **Scripting Language:** C# (Object-Oriented Architecture)

### Open-Source Asset Credits
Huge thanks to the creators of these fantastic free community assets:
* **Art & Sprites:** [Pixel Adventure 1](https://assetstore.unity.com/) — Main characters, tilesets, and animations.
* **Audio & SFX:** [Casual Game Sounds U6](https://assetstore.unity.com/) — Ambient effects and action cues.
* **Typography:** [Thaleah Pixel Font] — UI and retro HUD elements.

---

## 🚀 How to Play (Installation)

You can run the compiled build on your Windows PC using either of the following methods (Method 1 is highly recommended for players):

### 📥 Method 1: Download the Pre-compiled Release (Recommended)
1. Head over to the [🎮 GitHub Releases](https://github.com/Ronnie-Cai/An-Adventure---2D-Game-Project/releases) page.
2. Under the latest version (e.g., `v1.0.0`), download the **`2D Project.zip`** file.
3. Right-click the downloaded file and choose **Extract All...** to completely unzip the package. 
   > ⚠️ **Crucial:** Running the game directly inside the `.zip` archive will cause it to crash due to missing directory path references. Always extract first!
4. Open the extracted folder and double-click **`2D Project.exe`** to launch the game!

### 🛠️ Method 2: Run via Unity Editor (For Developers)
1. Click the green **`Code`** button at the top right of this repository page and select **`Download ZIP`** (or clone the repository using Git).
2. Open **Unity Hub**, click **`Add` -> `Add project from disk`**, and select the project root folder.
3. Ensure you have **Unity 2022.3.58f1** installed, open the main scene, and press the **`Play`** button to inspect or debug.
