# Public Release Manifest

## Release bundle

`releases/public_release_source.zip`

This archive was prepared from the project files supplied for publication review.

Included:

- `iss_build_iss.py` — project-authored ISS generation script
- `iss_real_parts.ldr` — project-authored generated/model placement file using LDraw part references

## Excluded from the public repository

The following categories were intentionally not published in this pass:

- official LEGO instruction PDFs or page images
- reconstructed official-set MPD corpus
- official-set connection datasets
- third-party MOC instruction/model files
- raw NASA ISS 3D source assets and brand imagery
- full LDraw part library geometry
- `state.sqlite`
- private/legacy ZIP archives
- large internal diagnostic datasets with unclear redistribution provenance
- local `mnt/user-data/...` duplicate paths
- the larger concatenated source bundle, pending a file-by-file provenance/license pass before normal source-tree publication

## Private-to-public workflow

The private development repository remains the source for experimental and provenance-sensitive material.

Recommended promotion flow:

1. Develop and test in the private repository.
2. Select a small candidate change for publication.
3. Run secret/path/provenance review.
4. Verify third-party redistribution rights.
5. Copy only the approved files to this public repository.
6. Record the source/provenance decision in the commit or this manifest.

## Current limitation

This first public pass publishes a reviewed minimal ISS example snapshot as a release archive plus repository documentation. The broader source can be progressively unpacked into normal browsable GitHub directories after a file-by-file provenance/license review.
