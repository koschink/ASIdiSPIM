# ASIdiSPIM

This is a modification of the ASIdiSPIM micromanager plugin (from Jon Daniels, jon@asiimaging.com) with adaptions to control a single objective light sheet microsope (Mr. Snouty), based on ASI hardware.

Changes in comparison to the original version:
- Export of files which are directly compatible to cudaDeconv and LLSpy by Tally Lambert (changes in naming schemes) - in progress
  - Writes a "fake" Settings.txt which stores LatticeLightSheet acquisition settings
 
- Cropping of files during export to a ROI - Completed

Planned changes:
- Reducing the numbe rof tabs to simplify user interaction
- Adding stage controllers for light sheet angle
- Support for ASI CRISP during acquisition
