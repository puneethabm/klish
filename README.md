klish
=====

Navigate to the klish folder from the command prompt and enter the following commands. This will build the necessary configuration files.  
   make clean;
  ./configure
	make
	sudo make install
To set the SYSTEM_NAME and clish path enter the following command
	SYSTEM_NAME=openflowCLI CLISH_PATH=xml-examples/klish/etc/clish bin/clish
SYSTEM_NAME can be set to any name (Ex: myCLI). 
We get the prompt with the SYSTEM_NAME set as shown below
openflowCLI>

-----------------------------------------------------------------------------------------------------------------------
Place the file pluribuscli.xml inside the folder xml-examples/klish/etc/clish

Place the file types.xml inside the folder xml-examples/klish/etc/clish-xml
-----------------------------------------------------------------------------------------------------------------------
