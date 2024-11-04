# STATIC AND DYNAMIC num7 LIBRARIES
## _DYNAMIC LIBRARY INSTALLATION:_
Create the following soft links to libnum7.so.1.0.0 file:
	
	ln -s libnum7.so.1.0.0 libnum7.so.1 #create a soname (share object name) symbolic link
	ln -s libnum7.so.1.0.0 libnum7.so   #create a symbolic link for the num7 library linker name

and copy all 3 files (with libnum7.so.1.0.0) in the following directory:

	user@localhost:/data/data/com.termux/files/usr/lib #GENERAL TERMUX SYSTEM-LIBRARY DIRECTORY 

## _STATIC LIBRARY INSTALLATION:_
Copy libnum7.a file in the following directory:
	
	user@localhost:/data/data/com.termux/files/usr/lib #GENERAL TERMUX SYSTEM-LIBRARY DIRECTORY 

## _num7.h INCLUDE LIBRARY FILE INSTALLATION:_
Copy the only num7.h file for both STATIC AND DYNAMIC LIBRARY in the following directory:

	user@localhost:/data/data/com.termux/files/usr/include #GENERAL TERMUX SYSTEM-INCLUDE-LIBRARY DIRECTORY 	
