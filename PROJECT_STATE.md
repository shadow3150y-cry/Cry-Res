# Project state
Updated: 2026-10-23

## Objective
Research CryEngine Resource Compiler and develop Blender-to-CryEngine workflows, using Maya exporter analysis as an additional information source.

## Current context
- A Blender character already exists with a rig and skinning.
- The project aims to preserve up to 8 bone influences per vertex in complex areas.
- Blender FBX to RC is a proposed experiment.
- Maya plugin inspection may reveal RC flags, intermediate formats, skeleton and skin export conventions.

## Not yet verified
- Target CryEngine/RC versions and exact commands.
- RC support for direct Blender FBX conversion.
- End-to-end support for 8 bone influences.
- Specific workflows for CHR, SKIN, CDF and CAF.

## Next steps
1. Record engine/RC versions.
2. Inspect Maya exporter scripts, configuration and plugin metadata.
3. Document RC invocation and intermediate data.
4. Run Blender FBX conversion tests and record logs.
5. Verify skinning and runtime deformation empirically.
