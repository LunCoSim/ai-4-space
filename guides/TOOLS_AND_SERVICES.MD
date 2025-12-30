# Tools & Services

To build your lunar base, we use a specific set of tools. Think of them as the machines in your workshop. You don't need to master all of them, but it helps to know what role each plays.

## 1. LunCoSim (The Framework)
* **What it is**: The foundation of our world. It's a pre-built simulation designed specifically for space missions.
* **Role**: Provides the physics, the moon terrain, the networking (so you can play with friends), and the basic building blocks (like avatars and habitats).
* **Link**: [LunCoSim Repository](https://github.com/LunCoSim/lunco-sim)

## 2. Godot Engine (The Engine)
* **What it is**: The "Operating System" that LunCoSim runs on.
* **Role**: It renders the 3D graphics and runs the logic. We chose Godot because it is **completely free**, open-source, and runs on almost any computer.
* **Action**: You will need to download this to run the simulation.
* **Link**: [godotengine.org](https://godotengine.org)

## 3. AI-Native Editors (The Technician)
* **Examples**: Antigravity, Cursor, VS Code with AI plugins.
* **Role**: This is your interface. instead of writing code manually, you chat with these editors. You tell them "I want to add a solar panel array to the north ridge," and they write the code for Godot to make it happen.
* **Why use them**: They make the "how" easy, so you can focus on the "what".

## 4. Blender (The Workshop)
* **What it is**: A 3D modeling tool.
* **Role**: If you want to design a custom rover wheel or a specific habitat shape, you build it here.
* **Integration**: LunCoSim can import your 3D models from Blender directly into the simulation.
* **Guide**: [How to import from Blender](BLENDER_TO_GODOT_WORKFLOW.MD)

## 5. GitHub (Advanced)
* **What it is**: A platform to save and share your work.
* **Role**: If you want to backup your lunar base or work on it with a team, you will use GitHub.
* **Warning**: This requires some technical setup (SSH keys).
* **Guide**: [How to setup Git & GitHub](ADVANCED_GIT_SETUP.MD)

