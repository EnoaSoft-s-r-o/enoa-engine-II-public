# Development status / Stav projektu

**Public snapshot — November 2026.** This page describes what may be stated publicly based on development screenshots and the project team's reported checks. It is not a certification or independent hardware benchmark.

| Area | What has been shown / reported | Important qualification |
| --- | --- | --- |
| Windows-oriented editor & scene editing | Editor screenshots with scene hierarchy, inspector, terrain and material controls | Screenshots captured through Wine; native Windows validation not established here |
| PBR, shadows, atmosphere | Material and lighting comparisons, sky development screenshot | Visual development demonstrations, not final production quality |
| Automatic LOD | Development example reports **5.23M → 0.82M triangles** in the same scene | About **84% fewer triangles** in this example; not a promise of equivalent FPS gain |
| Terrain and vegetation | Edited landscapes, painted foliage and sample environments | Demonstrations use development assets and test scenes |
| Build/export workflow | Editor reports a successful game package build and shows a standalone game menu | The team reports that the exported executable was run in its test environment; independent native Windows shipping validation is pending |
| Gameplay systems | FPS movement, physics/collision, Lua, basic AI perception/navigation, audio, menus and cutscenes described in engine materials | Feature presence does not imply feature-complete game or polished production runtime |

## Testing environment

Development captures supplied for this public package were taken **through Wine**. Counters visible in screenshots are not a valid basis for native Windows GPU performance claims. For external performance statements, publish a reproducible native test including hardware, driver, scene, build revision, resolution and measurement method.

## Important boundaries

- **Engine ≠ game:** Enoa-Engine II is the technology; Silent Patrol: Vietnam is the game.
- **One game, two implementations:** Unreal Engine 5 and Enoa-Engine II are parallel technical paths.
- **Private development:** this repository does not publish engine source or binaries.
- **No release date announced:** do not infer one from internal experiments.
- **Screenshot order:** captures are from different stages of development and must not be interpreted as a chronological product gallery unless dated individually.

For authoritative new public milestones, this page can be updated after they are verified by the team.
