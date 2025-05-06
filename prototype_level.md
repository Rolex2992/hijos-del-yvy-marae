# Prototype Level Design Document
# Hijos del Yvy Marae'ỹ

## Overview
The prototype level serves as a vertical slice demonstrating core gameplay mechanics, visual style, and narrative elements of Hijos del Yvy Marae'ỹ.

## Level Objectives
1. Introduce core gameplay mechanics
2. Showcase combat system
3. Demonstrate environmental interaction
4. Present narrative elements
5. Test technical features

## Level Layout

### Area 1: Tutorial Grove
```
[Starting Area]
     │
     ▼
[Basic Movement Tutorial]
     │
     ▼
[Combat Training Arena]
     │
     ▼
[Spirit Power Introduction]
```

#### Features
- Open space for movement practice
- Training dummies for combat
- Spirit essence collectibles
- Basic platforming elements
- Interactive tutorial triggers

### Area 2: Sacred Temple Approach
```
[Forest Path] ──► [Temple Courtyard] ──► [Temple Entrance]
     │                    │                      │
     ▼                    ▼                      ▼
[Side Path]        [Combat Arena]          [Puzzle Room]
```

#### Features
- Dense jungle environment
- Basic enemy encounters
- Environmental puzzles
- Collectible items
- Spirit realm portals

### Area 3: Temple Interior
```
[Main Hall]
    │
    ├─── [West Wing] ──► [Ritual Chamber]
    │
    ├─── [East Wing] ──► [Combat Trial]
    │
    └─── [Central Chamber] ──► [Boss Arena]
```

#### Features
- Complex architecture
- Advanced combat scenarios
- Spirit-based puzzles
- Mini-boss encounter
- Narrative elements

## Gameplay Elements

### Combat Scenarios
1. Tutorial Combat
   - Basic attacks
   - Blocking
   - Dodging
   - Simple combinations

2. Enemy Encounters
   - Basic enemies (2-3 types)
   - Group combat scenarios
   - Environmental hazards
   - Spirit power usage

3. Mini-Boss Fight (Corrupted Guardian)
   - Multiple phases
   - Special attacks
   - Environmental interaction
   - Spirit realm mechanics

### Puzzle Elements
1. Spirit Essence Puzzles
   - Energy redirection
   - Pattern matching
   - Timing challenges

2. Environmental Puzzles
   - Platform manipulation
   - Spirit realm transitions
   - Physical obstacles

### Collectibles
1. Spirit Essences
   - Power upgrades
   - Narrative fragments
   - Combat enhancements

2. Lore Items
   - Guaraní artifacts
   - Ancient texts
   - Spirit memories

## Technical Features to Test

### Combat System
- Melee combat mechanics
- Spirit power implementation
- Enemy AI behavior
- Hit detection and feedback
- Combat camera system

### Movement System
- Character controller
- Platform interaction
- Climbing mechanics
- Swimming mechanics
- Spirit realm transition

### Visual Effects
- Combat effects
- Spirit power visualization
- Environmental effects
- Particle systems
- Post-processing

### Audio Implementation
- Combat sounds
- Environmental audio
- Music system
- Voice acting integration

## Level Metrics

### Space Metrics
- Corridor width: 5m
- Room heights: 6-12m
- Combat arena size: 20x20m
- Platform spacing: 3-5m
- Clearance height: 3m

### Combat Metrics
- Enemy spawn points: 12
- Combat arenas: 3
- Training areas: 2
- Boss arena size: 30x30m

### Progression Metrics
- Playtime: 30-45 minutes
- Collectibles: 20
- Upgrade points: 5
- Lore items: 10

## Art Requirements

### Environment
1. Jungle Assets
   - Trees and vegetation
   - Rock formations
   - Water features
   - Spirit realm elements

2. Temple Assets
   - Ancient architecture
   - Ritual objects
   - Sacred symbols
   - Lighting fixtures

### Visual Effects
1. Combat VFX
   - Weapon trails
   - Impact effects
   - Spirit powers
   - Environmental reactions

2. Environmental VFX
   - Spirit essence
   - Portal effects
   - Weather effects
   - Ambient particles

## Level Flow

### Player Journey
1. Introduction Phase
   ```
   Start ──► Movement Tutorial ──► Combat Training
   ```

2. Exploration Phase
   ```
   Forest Path ──► Temple Discovery ──► Initial Puzzles
   ```

3. Challenge Phase
   ```
   Combat Trials ──► Spirit Puzzles ──► Mini-Boss
   ```

### Narrative Elements
1. Introduction
   - Character background
   - World setting
   - Basic mythology

2. Discovery
   - Temple history
   - Spirit realm connection
   - Ancient prophecies

3. Conflict
   - Guardian corruption
   - Spirit realm disturbance
   - Personal challenge

## Testing Focus Areas

### Gameplay Testing
- Combat feel
- Movement fluidity
- Puzzle clarity
- Difficulty balance
- Progression pacing

### Technical Testing
- Performance metrics
- Loading times
- Memory usage
- Streaming systems
- Physics interactions

### User Experience
- Tutorial effectiveness
- Navigation clarity
- Combat readability
- Puzzle understanding
- Narrative delivery

## Success Criteria
1. Technical Performance
   - Stable 60 FPS
   - No major bugs
   - Smooth loading
   - Stable physics

2. Gameplay Goals
   - Clear tutorial completion
   - Engaging combat
   - Solvable puzzles
   - Satisfying progression

3. Player Experience
   - Understanding of mechanics
   - Engagement with story
   - Desire to continue
   - Technical comfort

## Implementation Schedule

### Week 1-2: Basic Layout
- Level blockout
- Basic navigation
- Essential mechanics
- Core systems

### Week 3-4: Core Features
- Combat implementation
- Puzzle mechanics
- Enemy AI
- Basic VFX

### Week 5-6: Polish
- Art implementation
- Sound design
- VFX refinement
- Performance optimization

### Week 7-8: Testing
- Playtesting
- Bug fixing
- Balance adjustments
- Final polish

## Deliverables
1. Playable prototype level
2. Technical documentation
3. Art assets list
4. Bug report template
5. Testing feedback form
