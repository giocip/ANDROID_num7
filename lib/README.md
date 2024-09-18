# STATIC AND DYNAMIC num7 LIBRARIES
## _DYNAMIC LIBRARY INSTALLATION:_
Create the following soft links:
	
	ln -s libnum7.so.1.0.0 libnum7.so.1 #create a soname symbolik link
	ln -s libnum7.so.1.0.0 libnum7.so  #create a symbolik link for the library num7 name linker

and copy them in the following directory:

	user@localhost::/data/data/com.termux/files/usr/lib #GENERAL TERMUX SYSTEM-LIBRARY DIRECTORY 
