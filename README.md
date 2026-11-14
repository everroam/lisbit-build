# Lisbit Builds and Releases

This is the build and release repository for Lisbit. It does not contain the application source code.

Please [open an issue](https://github.com/everroam/lisbit-build/issues) to report a problem or share feedback.

## Releases

Maintainers dispatch the Release workflow manually with a version tag. Builds require approval in the release environment, and publication requires a separate approval after all builds finish.

An optional tools operation builds and publishes standalone speech tools through the same approvals; they are hosted on the download service.

GitHub Releases here mirror the installers only. Updates and official downloads are served from https://lisbit.app.

This repository contains only `.github/workflows/release.yml` and `README.md`. No source code or Actions artifacts are uploaded.
