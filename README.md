![Made with Nine Ether](https://img.shields.io/badge/built%20with-.nine-blueviolet)

# 🧠 NineSamples  
Official sample library for **Nine Ether Statechain** `.nine` contracts, rendering tests, and Web4 game prototypes.

This repository houses **canonical reference samples** used for:
- Research & experimentation  
- Renderer integration (Web, Godot, Unity, Unreal)  
- Pipeline testing for the NineVM + Statechain Fabric  
- Gameplay, UI, and world-state patterns for building Web4 experiences  

---

## 🌟 What’s Inside

### 📁 `/Nine`
A curated set of sample `.nine` contracts demonstrating how to build scenes, worlds, UI, and mechanics using the NineVM deterministic model.

| File                              | Description                                                         |
|----------------------------------|---------------------------------------------------------------------|
| `EmojiVault.nine`                | Tile-based emoji dungeon with live entity movement                  |
| `GemCollector.nine`              | Classic collectible game in pure .nine syntax                       |
| `NineGemCollectorUI.nine`        | Gem collector upgraded with UI, minimap, timer, and HUD elements    |
| `NineGemCollectorNewLevel.nine`  | Expanded version with an additional level + entity logic updates    |
| *(More samples coming soon)*     | Renderer-specific tests, NPC AI loops, and world templates          |

These files serve as **blueprints** for anyone studying .nine design patterns or building their own Nine-powered games.

---

## 🖥️ Updated Rendering Pipeline (NEW)

This repo now aligns with the **multi-renderer architecture** of the Nine Fabric:

### **1️⃣ Web Native Renderer**
- Uses the NineVM directly  
- Interprets `.nine` contracts in real time  
- Perfect for rapid iteration and browser-based games  

### **2️⃣ Godot Renderer**
- Converts contract output into Godot scenes and objects  
- Supports tilemaps, arches, entity spawning, and scripted behaviors  

### **3️⃣ Unity Renderer**
- Converts NineVM world + entity state into Unity prefabs  
- Supports both 2D and 3D workflows  
- Ideal for prototyping Nine-powered console experiences  

### **4️⃣ Unreal Renderer**
- Experimental  
- Bridges Nine deterministic world updates into Unreal Actors  
- Used for large-scale world simulation tests  

The samples here are used across all renderers for **validation, benchmarking, and visual consistency testing**.

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/CoollifeCLC/NineSamples.git
   cd NineSamples
````

2. Open any `.nine` file in the [Contract OS NineBuilder](https://contract-os.com/ninebuilder)

3. Paste the sample and give it a name.

4. Click **Compile + Deploy**, then **Play** to see it rendered through the Nine Fabric.


## 🛠 Built With

* **Nine Ether (.nine) Language**
* **NineVM Deterministic Compute Fabric**
* **Contract OS — NineBuilder**

---

## 💡 Contributing

This repository is currently **read-only**.

If you’d like to:

* Submit new `.nine` samples
* Propose renderer tests
* Share UI/gameplay patterns

…please open an [Issue](https://github.com/CoollifeCLC/NineSamples/issues) or fork the repo and tag us.

Community contributions will help shape the Web4 ecosystem.

---

## 🎮 Live Sample Gallery

Try these samples directly on Contract OS:

🔹 [EmojiVault.nine — Play Live](https://contract-os.com/play/game/0x436f6e7472616374313735303737383930313130)
🔹 [EmojiFootball.nine — Mechanics Test](https://contract-os.com/play/game/0x466f6f7462616c6c205465737431373633313638?mode=auto)
🔹 [FusionLabUI.nine — UI Demo](https://contract-os.com/play/game/0x564d2054657374202d2032313736343033363731?mode=auto)
🔹 [GemCollector.nine — Two Levels + Minimap](https://contract-os.com/play/game/0x4e696e652047656d20436f6c6c6563746f72204d)
🔹 [Test Casino.nine — Casino Logic](https://contract-os.com/play/game/0x4e696e6520436173696e6f20456d6f6a69204564)
🔹 [Original Gem Collector — Pre-UI Version](https://contract-os.com/play/game/0x47656d20436f6c6c6563746f72204c6172676572)

---

## 📜 License

This repository is licensed under **MIT**.
Use these samples freely in your own Nine projects.

---

## ✨ Stay Connected

* 🌐 **Contract OS** — [https://contract-os.com](https://contract-os.com)
* 🧠 **CoollifeCLC** — [https://github.com/CoollifeCLC](https://github.com/CoollifeCLC)
* 🔥 Follow the mission as we build the future of Web4, deterministic computing, and game-native smart contracts.
