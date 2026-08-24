# Roadmap

The roadmap is directional, not a promise of fixed dates.

## 1. Island

Goal: make Florianópolis recognizable, navigable and technically coherent.

- terrain identity and continuity
- coastline
- bathymetry
- regional structure
- browser LOD / streaming
- navigation and scale perception
- water and material foundations

### Public gate

The first major public demo should satisfy:

- **RECOGNIZABLE_ISLAND**
- **CONVINCING_NAVIGATION**
- **VISIBLE_DIFFERENTIATOR**
- **REPRODUCIBLE_ENTRYPOINT**

## 2. Living World

- procedural vegetation
- urban refinement
- interiors
- characters
- multiple playable scales
- local agents
- reactive systems
- procedural detail

## 3. Ocean

- spectral/global ocean
- depth-aware coastal behavior
- bathymetry-driven transformation
- shoaling and breaking zones
- foam and spray
- swell / wind / period / tide parameters
- localized higher-fidelity simulation

## 4. Surf

Initial research target: **TDZ-SURF-LAB-0001**

Minimum loop:

- paddle
- catch a wave
- stand up
- descend the face
- bottom turn
- traverse laterally
- fall / recover

Architecture direction:

- inexpensive global ocean
- higher-fidelity Surf Simulation Zones near relevant beaches/player
- bathymetry influences wave height, direction, shoaling and breaking
- board physics samples water height, normal, velocity and phase
- breaking / foam / spray can be visually decoupled from expensive full-fluid simulation

Surf is intentionally downstream of the island, coastline, bathymetry, navigation and LOD foundations.
