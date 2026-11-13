# museum-models

Compressed GLB files of 16 classical sculpture scans used by https://museum.joonlab98.com (a walk-through of the Cour Marly, Louvre).

- Source: Statens Museum for Kunst (SMK), Royal Cast Collection 3D scans — Public Domain Mark 1.0 (open.smk.dk). Details per file in `CREDITS.md`.
- Processing: simplified to ~34k vertices, meshopt compression (`EXT_meshopt_compression`, `KHR_mesh_quantization`). Load with three.js `GLTFLoader.setMeshoptDecoder(MeshoptDecoder)`.
- This repository only exists so the files can be served through jsDelivr: `https://cdn.jsdelivr.net/gh/joonlab/museum-models@v1/models/<id>.glb`
