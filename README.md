# Sinhala-English_Dictionary for macOS
Dictionary for Sinhala - English words for macOS

# Installation
Download Xcode Additional tools from this link: https://developer.apple.com/download/all/ (Registeration is required with your apple id.)

Move the Dictionary Development Kit folder to /Applications/Utilities/Dictionary Development Kit/.

Clone or download this repository into your computer. Locate to inside the folder to the makefile open it via vim (on the terminal) or any other programme.

Change ``` DICT_BUILD_TOOL_DIR ```from ``` /DevTools/Utilities/Dictionary Development Kit ``` to ```/Applications/Utilities/Dictionary Development Kit```

Open your terminal (Drag and drop downloaded folder into the terminal window.)

```
cd ~/{YOUR LOCATION}/Sinhala-English_Dictionary/; make && make install [ENTER]
```

Or otherwise (Drag and drop Sinhala-English_Dictionary folder into the terminal window.)

```
cd {YOUR LOCATION} [ENTER]
```

```
make [ENTER]
```

```
make install [ENTER]
```

# Alternative installation

Follow the above steps and install Xcode Additional Tools. 

Copy the source files to the project_templates file location on your Dictionary Development Kit. (Make sure not to copy the folder. Just copy the files)

Then copy the folder to your desired location.

Locate to inside the folder to the makefile open it via vim (on the terminal) or any other programme.

Change DICT_BUILD_TOOL_DIR from ``` /DevTools/Utilities/Dictionary Development Kit ``` to ```/Applications/Utilities/Dictionary Development Kit```

Open your terminal (Drag and drop downloaded folder into the terminal window.)

```
cd ~/{LOCATION}/project_templates/; make && make install [ENTER]
```

Or otherwise (Drag and drop project_templates folder into the terminal window.)

```
cd {LOCATION} [ENTER]
```

```
make [ENTER]
```

```
make install [ENTER]
```

# Files

***MyInfo.plist*** contains the related information for dictionary.

***MyDictionary.xml*** contains the definitions.

# Instructions to build

Locate inside the folder (via ``` cd ``` command in your terminal) and Run ``` make ``` inside the folder 

Make. sure to ``` make install ``` after each build to check for the definitions in the dictionary.app
