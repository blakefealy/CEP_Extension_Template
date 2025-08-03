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
## ✨ Optional Enhancements
To customize your UI and streamline development, consider adding the following:
1. Font Awesome
    You can include Font Awesome icons by adding the CDN to your index.html <head> section:
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    This allows you to use icons like:
    <i class="fas fa-play"></i>
2. Custom Fonts
    Use Google Fonts or other font services for improved typography. Example:
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
3. CSS Frameworks (Optional)
    Lightweight CSS frameworks can help with layout and style. Consider using:
        Milligram – minimalist and easy to override
        Pico.css – great for clean UI
        Bootstrap – if you want more utility and components (larger file size)
