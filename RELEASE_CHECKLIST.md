# Release Checklist

Repository release: **v0.1.0**  
Manuscript: **Publication Candidate v11**  
Date: **2026-09-23**

1. Create or update `dpatz46-ui/asi-alignment-beyond-control` and place the contents of this package at the repository root.
2. Confirm the default branch is `main`.
3. Enable GitHub Pages from `main` / `docs`.
4. Verify the canonical Pages routes: `/`, `/paper.html`, `/abstract.html`, `/asi-alignment-beyond-control-v11.pdf`, `/llms.txt`, and `/llms-full.txt`.
5. Create GitHub release/tag `v0.1.0` and attach the publication-candidate PDF if desired as a release asset.
6. Archive the release with Zenodo or another DOI-granting service using `metadata/zenodo.json`; once a DOI exists, add it to `README.md`, `CITATION.cff`, and the static landing page without altering the manuscript text unless desired.
7. Recompute `SHA256SUMS` after any repository-file change made before release.
8. Confirm the licensing split in `LICENSE.md`: substantive research content is CC BY-NC 4.0; discovery/citation/repository-facing content is CC BY 4.0.

This repository-facing checklist is licensed CC BY 4.0.
