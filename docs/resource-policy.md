# Resource Policy

This repository is a curated learning resources collection, not a general file mirror.

## When a local copy may be included

A third-party file may be included locally only when:

- redistribution is explicitly permitted
- the license is clearly identifiable
- attribution is provided
- the official source is linked
- the local copy has educational or offline-reference value
- the file size is reasonable for a Git repository

## When only a link should be used

A resource should only be linked, not uploaded, when:

- redistribution is unclear
- the license is missing or ambiguous
- the material is only free to read but not clearly redistributable
- the file is very large
- the official online version is clearly preferable
- the material changes frequently and a local copy would become outdated quickly

## Versioning

For each included local copy, the resource folder should document:

- title
- author or publisher
- official source
- included file name
- version or date, where available
- license
- reason for inclusion

## Checksums

Local files should be listed in `checksums/SHA256SUMS.txt`.

Checksums make it easier to verify that included files have not changed unexpectedly.

## Review rhythm

Included resources should be reviewed periodically, especially when:

- a new major version is released
- the upstream project changes its download structure
- the license changes
- the file becomes outdated
- the repository grows too large
