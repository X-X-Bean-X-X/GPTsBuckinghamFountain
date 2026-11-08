# GPT's Buckingham Fountain

Editable asset source by **X_Bean_X** for Cities: Skylines II.

[Paradox Mods listing](https://mods.paradoxplaza.com/mods/164642/Any) — published version **1.829.954**.

Version 1.829.954 adds park recreation, visitor attraction, citywide and local effects, and sidewalk entrances.

## Contents

- `AuthoringSource-*.zip`: retained Blender scenes, texture sources and authoring scripts. Extract all numbered archives into the same directory; each archive is independent. Historical scene revisions are retained where they form part of the authoring chain.
- `NativeDefinitions.zip`: native prefab, material, localization and identifier definitions extracted from the exact current public package. These capture the published asset configuration, including changes made after geometry generation.
- `source-manifest.json`: file inventory, SHA-256 checksums and the published package fingerprint.

## Editing

Open the `.blend` scenes in Blender. Their folder structure is preserved. Some scenes reference textures by their original local paths: relink images to the included texture directories where necessary. The scripts retain the original authoring workflow and may need path adjustments, Blender Python dependencies, the CS2 Modding Toolchain, or original authoring helpers. Review output paths before running them.

The Blender model alone is not a complete game package. Native import, material assignment, lighting, gameplay components and export are additional authoring steps. Native definitions are supplied for inspection and reconstruction; this repository does not claim a one-click reproducible build. Earlier source revisions may differ from the current published native configuration.

The playable asset remains available through Paradox Mods. This source publication does not change the installed asset or its behavior. Game assemblies and decompiled game code are excluded. Reference photographs are not included.

## Provenance

Current public package SHA-256: `56685eb57a6aa351c5534117fe46a40cef3bc42d335ab860ddece233a608a1b1`. Both the public download and its inner package passed ZIP integrity checks. Source archives were checked after creation.

No additional reuse license is granted by this source publication.

## Footprint attribution

Footprint inputs derived from OpenStreetMap are copyright OpenStreetMap contributors and remain subject to ODbL 1.0. See https://www.openstreetmap.org/copyright. Existing third-party data terms are not replaced by this repository's source-availability notice.
