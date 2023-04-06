# Sinhala-English_Dictionary
Dictionary for Sinhala - English words for macOS

Download Xcode Additional tools from this link: https://developer.apple.com/download/all/ (Registeration is required with your apple id.)

Move the Dictionary Development Kit folder to /Applications/Utilities/Dictionary Development Kit/ (without the spaces), and copy the project_templates folder to your desired location

Open project_templates (from your location) and change DICT_BUILD_TOOL_DIR from ``` /DevTools/Utilities/Dictionary Development Kit ``` to ```/Applications/Utilities/Dictionary Development Kit```

Open your terminal (Drag and drop project_templates folder into the terminal window.)

```
cd ~/{YOUR LOCATION}/project_templates/; make && make install [ENTER]
```

Or otherwise (Drag and drop project_templates folder into the terminal window.)

```
cd {YOUR LOCATION} [ENTER]
```

```
make [ENTER]
```

```
make install [ENTER]
```
