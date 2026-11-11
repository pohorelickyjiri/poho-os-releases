# Poho OS releases

This repository holds only the finished builds of Poho OS: the Windows installer, the macOS disk image, the signed update bundles, and `latest.json`, which installed copies of Poho read to find out whether a new version exists. It contains no source code.

Every update bundle is signed. Poho refuses any update that is not signed with the project's key.

The builds are not signed with a Windows or Apple certificate:

- **Windows:** the first manual install shows a SmartScreen warning. Click "Více informací", then "Přesto spustit".
- **macOS:** open the app the first time with right-click → Open.

Later versions install from inside Poho ("Nová verze — aktualizovat") without these warnings.
