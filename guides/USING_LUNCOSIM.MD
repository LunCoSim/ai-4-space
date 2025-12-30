# Using LunCoSim

## What is LunCoSim?
**LunCoSim** is an open-source lunar simulation platform built on Godot Engine. It provides a realistic, interactive environment where you can build and test lunar bases, rovers, spacecraft, and mission scenarios.

Think of it as a "living sandbox" for space missions - you can create entities, control them, observe interactions, and even collaborate with others in real-time.

## Getting Started

### Step 1: Open LunCoSim in Godot
1. Download and install **Godot Engine** from [godotengine.org](https://godotengine.org)
2. Clone or download the LunCoSim repository: [LunCoSim Repository](https://github.com/LunCoSim/lunco-sim)
3. Open Godot and import the LunCoSim project
4. Click "Import" and navigate to the `project.godot` file in the LunCoSim folder

### Step 2: Run the Simulation
1. Once the project is loaded, click the **Play** button (▶) in the top-right corner of Godot
2. The simulation will launch, and you'll see the lunar environment
3. You're now ready to start creating!

## Creating Entities

LunCoSim provides **four predefined entity types** that you can create instantly. You can use either keyboard shortcuts or the UI to spawn them.

### Quick Creation (Keyboard Shortcuts)
- **Alt + 1**: Create a **Spacecraft** (Landers/Rockets)
- **Alt + 2**: Create a **Rover**
- **Alt + 3**: Create a **Character** (Astronaut/Person)
- **Alt + 4**: Create an **Operator** (Observer entity)

### Using the UI
Alternatively, you can use the in-game user interface to create entities:
1. Look for the entity creation menu (typically in the top-left or accessible via a menu)
2. Select the entity type you want to create
3. Click to place it in the world

## Entity Types Explained

### 1. Spacecraft
**Purpose**: Model landers, rockets, or any flying/landing vehicle.

**Controls**:
- **W/S**: Thrust forward/backward
- **A/D**: Rotate left/right
- **Q/E**: Strafe left/right
- **Space**: Thrust upward
- **Shift**: Thrust downward

**Use Cases**:
- Lunar lander simulations
- Rocket descent/ascent testing
- Orbital transfer vehicles

### 2. Rover
**Purpose**: Ground vehicles for lunar surface exploration.

**Controls**:
- **W/S**: Drive forward/backward
- **A/D**: Steer left/right
- **Space**: Brake

**Use Cases**:
- Surface exploration
- Cargo transport
- Mobile science platforms

### 3. Character
**Purpose**: Astronauts or human operators on the lunar surface.

**Controls**:
- **W/A/S/D**: Walk in directions
- **Space**: Jump
- **Shift**: Sprint

**Use Cases**:
- EVA (Extra-Vehicular Activity) simulations
- Human-scale perspective
- Base construction scenarios

### 4. Operator
**Purpose**: Observer entity that can watch and monitor the simulation without physical interaction.

**Controls**:
- **W/A/S/D**: Move camera
- **Mouse**: Look around
- **Scroll**: Zoom in/out

**Use Cases**:
- Mission control perspective
- Cinematic views
- Monitoring multiple entities

## Building with AI

One of LunCoSim's most powerful features is **AI-assisted scene creation**. Instead of manually coding every detail, you can describe what you want, and AI will help build it.

### How It Works
1. **Describe Your Vision**: Tell the AI what you want to create
   - Example: *"I want a lunar base with three habitat modules connected by tunnels, a solar panel array on the ridge, and a landing pad 50 meters away."*

2. **AI Generates the Scene**: The AI will:
   - Create the necessary entities
   - Position them correctly
   - Set up connections and relationships
   - Configure physics and interactions

3. **Iterate and Refine**: You can ask the AI to modify the scene
   - *"Move the landing pad closer"*
   - *"Add a rover charging station near the habitats"*
   - *"Make the solar panels face east"*

### Example Prompts
Here are some example prompts you can use with AI:

**Simple Base**:
```
Create a small lunar outpost with one habitat module, 
a rover, and a small landing pad nearby.
```

**Complex Mission**:
```
Build a lunar mining operation with:
- Main habitat cluster (3 modules)
- Mining rover with drill attachment
- Resource storage tanks
- Solar power array
- Landing zone for cargo spacecraft
```

**Testing Scenario**:
```
Set up a rover endurance test with:
- Starting point at base
- Waypoint markers at 100m, 500m, and 1km
- Rough terrain obstacles
- Return path to base
```

## Tips for Success

### 1. Start Simple
Begin with one or two entities. Get comfortable with the controls and physics before building complex scenes.

### 2. Use Operator Mode
Switch to Operator mode (Alt+4) to get a bird's-eye view of your creation. This is great for planning and observation.

### 3. Experiment with Physics
LunCoSim simulates realistic lunar gravity (1/6th of Earth's). Test how this affects:
- Rover handling
- Spacecraft landing
- Character movement

### 4. Save Your Work
Don't forget to save your scenes! Use Godot's save functionality to preserve your creations.

### 5. Leverage AI
Don't be afraid to ask the AI for help. It can:
- Explain how models work
- Create complex scenes quickly
- Debug issues
- Suggest improvements

## Multiplayer & Collaboration

LunCoSim supports **networked multiplayer**, allowing multiple users to interact in the same simulation.

**To connect**:
1. One person hosts the simulation
2. Others join using the host's IP address
3. Everyone can create and control entities
4. Perfect for team mission planning!

## Next Steps

Now that you understand the basics:
1. **Experiment**: Create different entities and explore their capabilities
2. **Build**: Start designing your first lunar base or mission scenario
3. **Collaborate**: Invite team members to join your simulation
4. **Iterate**: Use AI to rapidly prototype and test ideas

## Need Help?

- **AI Assistance**: Use the [ai-4-space repository](https://github.com/LunCoSim/ai-4-space) to give your AI the knowledge to help you
- **Documentation**: Check the [LunCoSim Repository](https://github.com/LunCoSim/lunco-sim) for technical details
- **Community**: Join discussions and share your creations

---

**Remember**: LunCoSim is your creative playground. There's no wrong way to explore. Start building, and let AI help you bring your lunar vision to life!
