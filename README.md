
Built by https://www.blackbox.ai

---

# Hijos del Yvy Marae'ỹ (La Tierra sin Mal)

## Project Overview
Hijos del Yvy Marae'ỹ is an action-adventure, third-person video game set in a semi-open world inspired by Guaraní mythology. Players control Tupá Rendy, a demigod tasked with restoring balance to the spiritual realm while battling corrupted mythological beings. Utilizing the power of Unreal Engine 5, the game promises a rich, immersive experience enhanced by a dynamic weather system and a deep narrative rooted in cultural authenticity.

## Installation
To set up the project, follow these steps:

### Prerequisites
- Ensure you have the latest version of Unreal Engine 5 installed.
- Git for version control.
- A PC or console development kit for platform-specific builds.

### Steps
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd HijosDelYvyMaraey
   ```
2. Open the project in Unreal Engine 5 by selecting the `.uproject` file.
3. For initial setup, install any required plugins as prompted by the engine.

## Usage
To playtest the current build:
1. Open the project in Unreal Engine.
2. Navigate to the prototype level.
3. Use the Play button to start testing gameplay mechanics, including character controls, combat interactions, and environmental explorations.
4. To make changes, modify the relevant assets or scripts within the `Source/` and `Content/` directories.

## Features
- **Dynamic Weather System**: Weather conditions affect gameplay and visuals.
- **Combat Mechanics**: Engage in light and heavy attacks, dodging, and utilizing spirit powers.
- **Spirit Power System**: Unlock and use unique abilities based on progression paths.
- **Deep Narrative**: Experience a story inspired by Guaraní myths, featuring rich character development and moral choices impacting gameplay.

## Dependencies
The game utilizes several key dependencies as noted in the `package.json`. Below are the basic ones:
- Unreal Engine 5 (specific features such as Nanite, Lumen)
- C++ programming language (for custom game mechanics)
- Additional plugins may be required as the project develops.

## Project Structure
The project is organized to maintain clarity and improve workflow efficiency:

```
HijosDelYvyMaraey/
├── Config/                     # Engine and game configuration files
├── Content/                    # All game content
│   ├── Characters/            # Character assets
│   │   ├── TupaRendy/        # Main character assets
│   │   ├── Enemies/          # Enemy character assets
│   │   └── NPCs/             # Non-player character assets
│   ├── Environments/          # Environment assets
│   │   ├── Jungle/           # Jungle environment assets
│   │   ├── Villages/         # Village environment assets
│   │   └── Temples/          # Temple environment assets
│   ├── VFX/                  # Visual effects
│   │   ├── Combat/           # Combat visual effects
│   │   ├── Magic/            # Magical effects
│   │   └── Environment/      # Environmental effects
│   ├── UI/                   # User interface assets
│   ├── Audio/               # Audio assets
│   ├── Animations/         # Animation assets
│   └── Levels/            # Game levels
├── Source/                # C++ source code
│   ├── Characters/       # Character classes
│   ├── Combat/          # Combat system
│   ├── AI/             # AI systems
│   ├── GameFramework/  # Core game framework
│   └── UI/            # UI implementation
└── Documentation/     # Project documentation
```

### Key Directories and Their Purpose
- **Content/**: Houses all game assets categorized by type and functionality following Unreal Engine guidelines.
- **Source/**: Contains the C++ codebase organized by functionality for easy access and modification.
- **Documentation/**: Includes necessary design documents, art guidelines, and technical specs for reference and consistency.

## Conclusion
Hijos del Yvy Marae'ỹ is a project grounded in vibrant storytelling, dynamic gameplay, and cultural authenticity. With a solid development roadmap and commitment to continual improvement, the team aims to create a unique gaming experience that resonates with players and celebrates the Guaraní culture.