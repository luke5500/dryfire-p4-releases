# DryFire secured P4 firmware

This repository distributes encrypted updates for secured DryFire P4 units.
The live update manifest is [secure/latest.json](secure/latest.json).
Each supported P4 revision has its own authenticated encrypted `.dfu` payload.

Unsecured `.bin` releases and the old root update feed are retired.
Existing unsecured lab boards require the owner-authorized Production Station
USB migration; downloading a secured OTA does not perform that migration.

Source, factory packages, signing keys and per-board recovery archives are not
published here. Product source remains in the separate private repository.
