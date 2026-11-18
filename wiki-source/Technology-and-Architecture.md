# Technology & Architecture

This page is a **high-level public overview**, not an internal API or source-code reference.

| Area | Technology / role |
| --- | --- |
| Core | C++17 project with separated engine components |
| Renderer | Direct3D 11 for Windows-oriented editor/runtime rendering |
| Editor | Scene hierarchy, inspector, gizmos, asset management, project tools |
| World | Terrain, foliage, scene composition, material definitions |
| Models | glTF 2.0 / GLB; Blender import/export workflow |
| Scripting | Lua-based gameplay scripting system |
| Navigation & perception | Navigation grid, pathfinding and basic AI perception |
| Movement & collisions | First-person controller and collision handling |
| Audio | WAV/OGG support and spatial audio functions |
| UI and cinematics | Game menus, camera paths, cutscene tools |
| Packaging | Development workflow to package an executable game |

## Development philosophy

The engine is designed around reusable systems while **games remain separate projects**. Sample projects, procedural content and test scenes are for validation and do not imply that the bundled assets are approved production content.

The engine and **Silent Patrol: Vietnam** are separate in purpose: one supplies technology, the other is the game being developed.

For end-user availability and validation limits, see [[Development-Status]].
