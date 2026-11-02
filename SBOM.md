# Source SBOM

**Initial source snapshot, not a release report.** Source commit `a7ff1be0b389d287fdc56e2ea0d06962aa68127d` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/js8call `a7ff1be0b389d287fdc56e2ea0d06962aa68127d`

- sbom:role: source-root
- sbom:git-commit: a7ff1be0b389d287fdc56e2ea0d06962aa68127d
- sbom:git-tree: 3162aa99ab130bc562535be1f09e4bf8a89371cc
- sbom:source-repository: https://github.com/wave-owl/js8call
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "COPYING", "sha256": "8f7b9235765be1f4228f09b302b3f87b0f3ebd946c80d8ece6b77c0e60769351"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/js8call | a7ff1be0b389d287fdc56e2ea0d06962aa68127d | source-root | unresolved; manual review required |
| Git | unresolved | conditional-build-requirement | unresolved |
| Git | unresolved | conditional-build-requirement | unresolved |
| Git | unresolved | conditional-build-requirement | unresolved |
| ${${PREFIX}_args} | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| Subversion | unresolved | conditional-build-requirement | unresolved |
| Boost | unresolved | conditional-build-requirement | unresolved |
| FFTW3 | unresolved | conditional-build-requirement | unresolved |
| Hamlib | unresolved | conditional-build-requirement | unresolved |
| Qt6 | unresolved | conditional-build-requirement | unresolved |
| Qt6 | unresolved | conditional-build-requirement | unresolved |
| contrib | unresolved | declared-vendored-source | unresolved; manual review required |
| lib | unresolved | declared-vendored-source | unresolved; manual review required |
| vendor | unresolved | declared-vendored-source | unresolved; manual review required |
| Conditional source requirements declared by CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by debian/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by js8call.pro | unresolved | conditional-build-runtime-requirement | unresolved |
| Boost>=1.77 at default HEAD | unresolved | conditional-build-runtime-requirement | unresolved |
| FFTW3 single/threads | unresolved | conditional-build-runtime-requirement | unresolved |
| Hamlib | unresolved | conditional-build-runtime-requirement | unresolved |
| Qt6>=6.4 at default HEAD | unresolved | conditional-build-runtime-requirement | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
