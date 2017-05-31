Converter Read Me

It is possible to create a file that is exicutable for the Logisim version of the LC3 from a full memory dump of the LC3 Simulator

to get a memory dump of the LC3 Simulator, load the desired program into the LC3 Simulator. 
After this is complete navigate to [File->Save Memory Contents] or press [Control] + S. 
Input the data range from x0000 to xFFFF.
DESELECT the "Save Registers" option!!!!!!!!
Click save after entering in a desired name for your memory dump file.


--To convert a memory dump file to a file readable by the Logisim LC3:--

Drag the memory dump file to the "LC3 to hex converter.exe" and drop it on the file.
If this is done correctly, a command window will open and convert the file.
The converted file will be saved as "Output.txt" in the same directory as the converter .exe

A file named "Uncompressed.txt" will also be created. 


Files made in this manner will work correctly in the Logisim LC3 despite promting an error message from the Logisim hex editor.


-----------------------NOTE--------------------------------- 
The Logisim LC3 comes pre-set to start the PC at location x3000, if the program created by the user does not begin at memory location x3000, this must be changed. memory location x0003 contains the starting location of the program (set by default to x3000) and can be changed from within the Logisim hex editor to point to the correct starting address.