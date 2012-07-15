The .xcconfig files in this folder contain generic Xcode build settings - they
can and should be used across any Xcode project. Consequently, they should NOT
contain any project- or app-specific settings (e.g. product name, info plist file,
PCH file, etc). Those settings belong in another .xcconfig file elsewhere.

To use these files, set the "Based on Configuration File" setting of the various
targets in the Project settings->Info pane in Xcode.