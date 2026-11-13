# museum-models

Compressed GLB files of 16 classical sculpture scans used by https://museum.joonlab98.com (a walk-through of the Cour Marly, Louvre).

- Source: Statens Museum for Kunst (SMK), Royal Cast Collection 3D scans — Public Domain Mark 1.0 (open.smk.dk). Details per file in `CREDITS.md`.
- Processing (tag v3+): simplified to ~75k vertices, Draco compression (`KHR_draco_mesh_compression`, position 12 bit, normal 8 bit). Load with three.js `GLTFLoader.setDRACOLoader(...)`. Tags v1–v2 hold an older meshopt version.
- This repository only exists so the files can be served through jsDelivr: `https://cdn.jsdelivr.net/gh/joonlab/museum-models@v3/models/<id>.glb`
- `fonts/` (from tag v2): the site's Korean subset web fonts (Noto Serif KR 500/700 — OFL; Pretendard variable, renamed internally to «Museum Sans KR» — OFL). Licenses in `fonts/OFL-*.txt`.
