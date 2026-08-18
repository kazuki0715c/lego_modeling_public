# Mechanical Brick CAD Research

A public research repository for experimenting with mechanical CAD, constraint solving, kinematics, and engineering-to-brick translation using LDraw-compatible part references.

The current public focus is a mechanically meaningful truss / rotary-joint prototype inspired by publicly available International Space Station engineering information.

## What is included

- a small mechanical-CAD kernel (`src/legocad`)
- mates, constraints, joints, rigid groups, collision checks and simple kinematics
- LDraw parsing/export support (the LDraw parts library itself is **not** bundled)
- public-safe ISS S3/SARJ example code derived from published engineering facts
- tests and architecture notes

## What is intentionally not included

- LEGO Group building-instruction PDFs or scans
- reconstructed official-set MPD files
- third-party MOC building files whose redistribution rights were not verified
- bulk connection datasets reconstructed from official or third-party models
- the LDraw parts library itself
- raw NASA 3D source assets, textures or NASA logos/insignia
- private research archives and earlier ZIP bundles

## External data

The software can work with an independently installed LDraw parts library. LDraw parts have their own licenses; see LDraw.org legal information and preserve the required attribution for any redistributed part data.

The ISS example uses dimensions and mechanical facts from publicly available NASA sources. Raw NASA source assets are not redistributed here. Use of NASA material must follow NASA media and brand guidelines and must not imply NASA endorsement.

## Trademark notice

LEGO® is a trademark of the LEGO Group of companies which does not sponsor, authorize or endorse this project.

This repository does not include the LEGO logo or official LEGO building instructions.

NASA names and identifiers are used only descriptively. This repository is not sponsored, authorized, or endorsed by NASA.

## Status

Experimental research software. The generated structures are diagnostic prototypes, not validated physical products.

## Repository policy

See `docs/PUBLICATION_POLICY.md` before adding datasets, models or third-party material.
