# Open GPS Tracker

This repository contains the legacy GPS-tracking project exported from the Google Code project `open-gpstracker`.

## Repository layout

- `MetaTracker/` contains one project area.
- `OpenGPSTracker/` contains the main named project area and external sources.
- The external source tree includes Apache HttpClient 4.1.1 and HttpCore 4.1.1 material, with Maven manifests for multiple modules.

## Working with the project

Review each subproject's own metadata before choosing platform tools or issuing build commands. Maven files in bundled dependencies are not necessarily the build entry point for the application. Establish the required Java, platform SDK, and dependency versions from the project files before attempting a build. Preserve existing third-party notices when using or redistributing bundled sources.
