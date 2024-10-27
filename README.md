# LCSC Importer for KiCad

A KiCad plugin that allows you to easily import parts (symbols, footprints, and 3D models) from LCSC directly into KiCad, using the easyeda2kicad command line tool.

### Key Features
- **Seamless Import**: Quickly import LCSC parts by entering their part number.
- **Direct Access**: Integrated into the toolbar for easy access within the PCB editor.
  
![Toolbar Screenshot](https://github.com/user-attachments/assets/d925aedc-483a-429f-ae3e-cf4fea454317)

### How It Works
1. **Enter LCSC Part Number**: Type in the LCSC part number to import its symbol, footprint, and 3D model directly into KiCad.

![Import Menu Screenshot](https://github.com/user-attachments/assets/8438877e-8ba5-46f7-bc8d-0552915c4243)

2. **Auto-Save**: Imported parts are stored in `/KiCad/easyeda2kicad`, ready for use.

---

## Installation

1. **Clone the Repository**  
   Clone this repository to your downloads folder.

2. **Move Files to KiCad Plugin Folder**  
   Move all contents to your KiCad plugins directory:  
   `KiCad/(version)/scripting/plugins`

3. **Organize the Files**  
   Ensure `LCSC Importer.py` is not inside any subfolder.

4. **Launch KiCad**  
   Start KiCad and open the PCB editor. Run the plugin once to initialize.

5. **Setup Part Libraries**  
   Follow the instructions for [easyeda2kicad](https://github.com/uPesy/easyeda2kicad.py) to configure the new part libraries in KiCad.

---

Enjoy simplified part importing from LCSC directly into your KiCad designs!
