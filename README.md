# board-defs

To install: 
Add 
`https://raw.githubusercontent.com/TomWhitwell/board-defs/master/package_musicthing_samd21_index.json
`
to the "Additional Boards Manager URLs" list in Arduino Preferences
 
Notes on collecting data for board definitions json file

Create Zip without Apple cruft: 
`zip -r musicthing_samd_0.1.9.zip 0.1.9 -x "*.DS_Store"` 

Create Checksum:  
`shasum -a 256 musicthing_samd_0.1.9.zip`

Check size:  
`ls -l` 


Different versions are described as 'Platforms' in the json 
* Each platform has common name / category / architecture 
* But different version / URL / size / checksum 





