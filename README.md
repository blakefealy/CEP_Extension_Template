# CEP Extension Starter Template

This project is a starter template for Adobe CEP (Common Extensibility Platform) extensions, based on NT Production’s Extension Testing Template. It provides a basic file structure and configuration to help you quickly get started building your own extension.

All folder structures and configurations mirror the original NTProductions setup for ease of compatibility and testing.

## 🔧 Getting Started

Before building your own extension, make the following adjustments:

    1. Rename the Project Folder
    2. Change the folder name to match the name of your extension.
    3. (Optional, but recommended for clarity and organization.)

    4. Update the manifest.xml File
      - Modify the following values to suit your extension:
          - <ExtensionBundleId> — Unique identifier for your extension bundle
          - <ExtensionBundleVersion> — Version number of your bundle (optional)
          - <ExtensionBundleName> — Human-readable name of your extension
          - <Extension Id> — Unique ID for the extension itself
          - <ExtensionList> — Update the Id (and optionally the Version)
          - <ExecutionEnvironment> → <HostList> — Specify supported Adobe apps and versions (e.g., AEFT for After Effects)
          - <DispatchInfoList> → <Extension Id> — Must match your updated extension ID
          - <UI> → <Menu> — Display name in the Adobe host app UI
          - <Resources> — If you rename your JSX runner file, make sure to update its path here too
