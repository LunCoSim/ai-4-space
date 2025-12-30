# Tools & Services

To build your lunar base, we use a specific set of tools. Think of them as the machines in your workshop. You don't need to master all of them, but it helps to know what role each plays.

## 1. LunCoSim (The Framework)
* **What it is**: The foundation of our world. It's a pre-built simulation designed specifically for space missions.
* **Role**: Provides the physics, the moon terrain, the networking (so you can play with friends), and the basic building blocks (like avatars and habitats).
* **Link**: [LunCoSim Repository](https://github.com/LunCoSim/lunco-sim)
* **Guide**: [How to use LunCoSim](USING_LUNCOSIM.MD)

## 2. Godot Engine (The Engine)
* **What it is**: The "Operating System" that LunCoSim runs on.
* **Role**: It renders the 3D graphics and runs the logic. We chose Godot because it is **completely free**, open-source, and runs on almost any computer.
* **Action**: You will need to download this to run the simulation.
* **Link**: [godotengine.org](https://godotengine.org)

## 3. AI-Native Editors (The Technician)
* **Examples**: Antigravity, Cursor, VS Code with AI plugins.
* **Role**: This is your interface. instead of writing code manually, you chat with these editors. You tell them "I want to add a solar panel array to the north ridge," and they write the code for Godot to make it happen.
* **Why use them**: They make the "how" easy, so you can focus on the "what".
* **Guide**: [How to use Workspaces](USING_WORKSPACES.MD) (Crucial for managing multiple repositories).

## 4. Blender (The Workshop)
* **What it is**: A 3D modeling tool.
* **Role**: If you want to design a custom rover wheel or a specific habitat shape, you build it here.
* **Integration**: LunCoSim can import your 3D models from Blender directly into the simulation.
* **Guide**: [How to import from Blender](BLENDER_TO_GODOT_WORKFLOW.MD)

## 5. Fathom (The Meeting Recorder)
* **What it is**: An AI-powered meeting assistant that records and transcribes your discussions.
* **Role**: Captures all your design discussions, technical decisions, and stakeholder meetings automatically.
* **Why use it**: Never lose important details from meetings. Create a searchable archive of all project conversations.
* **Guide**: [How to use Fathom for meetings](USING_FATHOM.MD)

## 6. n8n (The Automation Engine)
* **What it is**: A workflow automation tool that connects different services and automates repetitive tasks.
* **Role**: Automate social media posts, meeting notes, data monitoring, and integrations between all your tools.
* **Why use it**: Think in data flow instead of manual work. Automate everything from daily reports to team notifications.
* **Guide**: [How to use n8n for automation](USING_N8N.MD)

## 7. Crypto Wallets & Safe (The Keys)
* **What it is**: Your digital identity and security layer for global collaboration.
* **Role**: Used for signing transactions, managing assets, and co-managing project funds with a global team.
* **Wallets**: Rabby (EVM), MetaMask (EVM), Phantom (Solana).
* **Safe (Multisig)**: The standard for team treasuries and global coordination.
* **Guides**: 
    * [How to use Wallets](USING_WALLETS.MD)
    * [How to use Safe](USING_SAFE.MD) (For teams & high security)

## 8. Blockchain Services
* **What they are**: Tools to move and manage assets across different networks.
* **Bridging & Swapping**: Move tokens between chains (e.g., Ethereum to Base) or swap one token for another.
* **Networks**: Different "digital worlds" where projects live (Base, Polygon, Solana).
* **Guides**:
    * [Bridging & Swapping Guide](BRIDGING_SWAPPING.MD)
    * [Blockchain Networks Overview](BLOCKCHAIN_NETWORKS.MD)

## 9. GitHub (Advanced)
* **What it is**: A platform to save and share your work.
* **Role**: If you want to backup your lunar base or work on it with a team, you will use GitHub.
* **Warning**: This requires some technical setup (SSH keys).
* **Guide**: [How to setup Git & GitHub](ADVANCED_GIT_SETUP.MD)

