# Public Repository Publication Policy

This repository is intentionally public. Treat every committed file as globally redistributable.

## Allowed by default

Only add material that is clearly authored by this project or whose redistribution terms have been verified.

Typical allowed items:

- project-authored Python/source code
- project-authored tests
- project-authored architecture and research notes
- project-authored generated LDraw model files that contain placements/references rather than bundled third-party part geometry
- derived numerical facts or small metadata records when the underlying source permits that use
- links and citations to external sources instead of copies of the source files

## Do not publish by default

Do not commit any of the following unless redistribution rights have been explicitly checked and documented:

- LEGO building-instruction PDFs, scans, screenshots, or page images
- reconstructed official-set MPD/LDR models
- third-party MOC building files or instructions
- bulk datasets reconstructed from official or third-party building models
- copied LDraw part-library geometry (`.dat`) without preserving and complying with its applicable license/attribution
- raw NASA 3D source packages, textures, logos, insignia, or other brand assets
- private research archives, local backups, prior ZIP bundles, database state files, caches or credentials
- API keys, tokens, cookies, `.env` files, session files or private paths

## NASA-derived ISS work

Public ISS examples should contain our own code, our own model logic, and clearly described derived engineering facts. Prefer links/citations to the original NASA source rather than republishing raw source assets. Do not use NASA logos/insignia and do not imply NASA endorsement.

## LDraw

The public repository may contain code that reads an independently installed LDraw library and may refer to LDraw part identifiers. Do not copy the full library into this repository by default. If any LDraw geometry is ever redistributed, document the applicable LDraw license and attribution in the same commit/release.

## LEGO trademark

Use LEGO/Technic names only descriptively. Do not imply affiliation, sponsorship, authorization or endorsement by the LEGO Group. Do not include LEGO logos or official instruction content.

## Review gate before every public-data addition

Before adding a dataset/model/source archive, answer all of these:

1. Who authored it?
2. What is the redistribution license or permission?
3. Does it contain third-party copyrighted model geometry or instruction content?
4. Does it contain private/unreleased research material?
5. Does it contain credentials, local paths, logs, or account information?
6. Can the same purpose be served by a source URL + reproducible extraction script instead?

If any answer is uncertain, keep the material in the private repository until reviewed.

## Default rule

**Uncertain = private.**
