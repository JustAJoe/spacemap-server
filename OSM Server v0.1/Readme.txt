This is a README file for the OSM Server virtual machine image.

This image is an export of a virtual machine appliance for the Virtualbox VM system.  To use it, download and install Virtualbox, then in Virtualbox go to File->Import Appliance.  Give Virtualbox the location of the .ovf file in this directory and it should import the machine.

  	Note:  Currently the VM is configured for only 1 processor core and 1024 Mb of RAM.  This was chosen as a MINIMUM requirement and should likely be increased depending on the machine you run it on.
   


Once the image is imported you select it and click the "Start" button to boot the virtual machine.  It should boot up and bring you to a Linux login prompt.  Log in with the following username/password and run the 'startx' command to start up the graphical environment.  The configuration and import will happen in the graphical environment and later after the machine is set up to your needs, it can be restarted and run entirely in command line only mode to avoid having the graphical overhead, while still acting as a server.  Once you are in the Graphical environment you will find a Readme on the desktop with further instructions, or you can begin installation by double clicking on the configuration icon and selecting 'Run in terminal'  Also, within the graphical environment you can press Ctrl+Alt+T to launch a terminal if you want.  Also, once logged in, the user 'osm' can sudo without a password.

	Directions summary:
	*  Boot VM image
	*  Login:  Username:   osm
	           Password:   osm
	* Run command:         startx
	* When the GUI comes up, read the readme
	* Run the 'Start Configuration Wizard' and select 'Run in Terminal'

