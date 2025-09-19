# CA_Electronics_Public

This repository contains schematics, BOMs and PCBA drawings for Copenhagen Atomics' publicly available boards.

## Folder Structure

Each board type has its own project folder, as shown in the tree below:

- boards            - Parent folder
  - project         - Project folder
    - sub-project   - Sub-project folder
  - AnotherProject  - Project folder
- datasheets        - datasheet for latest version of each board

Each project/sub-project folder contains versioned .zip files with the relevant information.

## Zip Contents

The contents of the zip file may vary, but should contain these essential components:

1. Schematic file as a PDF
2. PCBA drawing as a PDF
3. BOM as a comma (",") separated variable (CSV) file
    * This includes Manufacturers Part Numbers against Reference Designators
4. README containing outline information about the purpose of the board and some environmental conditions, ratings and parameters
5. Full text license

## License

All project zip files contain license information. The license used is Creative Commons Attribution license 4.0. Please feel free to use the drawings but remember to attribute Copenhagen Atomics. :smiley:
