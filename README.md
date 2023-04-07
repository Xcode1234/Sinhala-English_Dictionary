# Sinhala-English_Dictionary for macOS
Dictionary for Sinhala - English words for macOS

Download Xcode Additional tools from this link: https://developer.apple.com/download/all/ (Registeration is required with your apple id.)

Move the Dictionary Development Kit folder to /Applications/Utilities/Dictionary Development Kit/.

Clone or download this repository into your computer. Locate to inside the folder to the makefile open it via vim (on the terminal) or any other programme.

Change DICT_BUILD_TOOL_DIR from ``` /DevTools/Utilities/Dictionary Development Kit ``` to ```/Applications/Utilities/Dictionary Development Kit```

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

# Files

MyInfo.plist contains the related information for dictionary.

MyDictionary.xml contains the definitions.
