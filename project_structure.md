# Project Structure for Hijos del Yvy Marae'ỹ

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
│   │   ├── HUD/             # Heads-up display assets
│   │   ├── Menus/           # Menu assets
│   │   └── Icons/           # Icon assets
│   ├── Audio/               # Audio assets
│   │   ├── Music/          # Music tracks
│   │   ├── SFX/           # Sound effects
│   │   └── Voice/         # Voice acting files
│   ├── Animations/         # Animation assets
│   │   ├── Player/        # Player character animations
│   │   ├── Enemies/       # Enemy animations
│   │   └── Cutscenes/     # Cinematic animations
│   └── Levels/            # Game levels
│       ├── Prototype/     # Prototype level
│       └── MainGame/      # Main game levels
├── Source/                # C++ source code
│   ├── Characters/       # Character classes
│   ├── Combat/          # Combat system
│   ├── AI/             # AI systems
│   ├── GameFramework/  # Core game framework
│   └── UI/            # UI implementation
└── Documentation/     # Project documentation
    ├── Art/          # Art guidelines and references
    ├── Technical/    # Technical documentation
    └── Design/       # Design documentation
```

## Key Directories and Their Purpose

### Content/
- Contains all game assets including models, textures, materials, blueprints
- Organized by asset type and functionality
- Following Unreal Engine's content structure guidelines

### Source/
- C++ source code for game systems
- Organized by functionality
- Follows Unreal Engine coding standards

### Documentation/
- Contains all project documentation
- Includes art guidelines, technical specs, and design documents
- Reference materials and guidelines

## Naming Conventions

### Files
- PascalCase for all asset names
- Prefix with appropriate type identifier
  - BP_ for Blueprints
  - M_ for Materials
  - T_ for Textures
  - SK_ for Skeletal Meshes
  - A_ for Animations

### Folders
- PascalCase for folder names
- Clear, descriptive names
- Logical grouping of related assets

## Version Control Guidelines

### Git
- Use .gitignore for Unreal Engine projects
- LFS for large binary files
- Regular commits with clear messages
- Feature branch workflow

### Backup
- Regular backups of project
- Version control for all code and documents
- Asset backup strategy
