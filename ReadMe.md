# ABOUT
	       	==============================================
	       	+-------- Current Version:  1.3-BETA --------+
	       	==============================================
	       	
	       * This is made to install archlinux with base base/devel
			
			* And then optionally setup a WM/Environment afterwards 
			
	       	
	       
				[ NOTICE ]
					- CURRENTLY UNDER DEVELOPMENT
					- RUN AT YOUR OWN RISK
		

	___________________________________________________________________
	===================================================================


		              :: Authors ::
			
			 	*  i3-Arch
			  	* trewchainz
			  	*  t60r
			
			
		-----------THIS IS A WORK IN PROGRESS -----------

             i. ** FIRST YOU WILL NEED THE OFFICIAL ARCHLINUX IMAGE **
			 	i. ** BOOT INTO LIVE ARCH IMAGE **
			  
			  
	1. :DOWNLOAD: 
		       
		       wget goo.gl/4v5IyX -O menu.sh
		       		
		       		-or-
	
		       	wget is.gd/iTNqig -O menu.sh   
		       		
		       
		       ** If Shortened URLS are 404 **
		       
		       ** Run This ** 
                       wget https://raw.githubusercontent.com/i3-Arch/Arch-Installer/master/menu.sh
           
               
                2. :RUN: 

                        source menu.sh


# POST INSTALL
				     *May Make Easier Later*
			( This below will work if VM or Wired Connection )
			( Consult the ARCH WIKI for wireless connections )
			
		1. :RUN:
			
			dhcpcd
			systemctl enable dhcpcd.service   ( This is to enable dhcpcd at boot )
			
		
			

		2. After You Have REMOVED LIVE IMAGE and boot into newly installed OS
		
				** MAKE SURE YOU CHOOSE OPTION 2 BEFORE CHOOSING OPTION 4 **


		:RUN:
			
			source post-menu.sh

			

			:: Current WM/Environment Choices ::
					1. Custom i3 Setup  		( Screenshots in my i3config repo (( i3-Arch )) )
					2. Default Xfce Setup
					3. Default Dwm Setup 		( Arch Way - ABS )
					4. Default Cinnamon Setup
					5. Default Awesome Setup
					6. Default Gnome Setup 		( gnome + gnome-extra )
					7. Default Kde Setup


# CURRENT OBJECTIVES
	
	1. [X] Make a menu that makes things easier

	2. [ ] Add More Options In General
			* LUKS
			* More Filesystem Options ( btrfs )
			* Kernel Options
			* Even More Minimal Install option
	
	3. [ ] Misc -- 
				 ___________________
				|                   |
				|   WM/DE's to ADD  |
		       	|===================|
		        |                   |
		        |    Herbstluftwm   |
		        |      Spectrwm     |
		        |      Openbox      |
		        |___________________|

	4. [ ] Cleanup

	5. [ ] Release

	       
	.... .........    .       . .. .....  .I.......  ..      .                     
	.... .......                       .  I7?.                                     
	............                    . .  .7I7=. .     .                            
	............                         IIII?. .                                  
	... ......                         .=IIIII?       .                            
	... .......                .   .  ..IIIIII?~.     .                            
	... .......                       .IIIIIIII?.                                  
	... ... ..                        .?IIIIIIII+..   .                            
	... ........                    ..?..II?IIII??.   .                            
	... .......                     .??IIIIII??????.                               
	... .......                   ..????????II????+..                               
	... ........                  .?????II?II??????+...                            
	... ........                 .:++???+?77IIIII7??+.                             
	... .......      .           .++?IIIIIIIIIIIIIII7?.      .                     
	............               ..+IIIIIIIIIIIIIIIIIIII?                            
	... ........               .7IIIIIIII?....IIIIIIIII,.                          
	... .......               .IIIIIIIII..    .IIIIIIIII.                          
	............              IIIIIIIII?       .IIIIIIII7..                        
	... .......             .=IIIIIIIII.  .    .IIIIII7III.                        
	............           .,7IIIIIIIII   .    .7IIIIII~.7I.                       
	............          ..IIIIIIIIII7        .7IIIIIIII7..                       
	... . . ..           ..IIIIIIIII7I7.       .II77IIIIIIII..                     
	... ......           .IIIII7I7..  .            ..7IIIIIII.                     
	... ........       ..III7I,                        .,7I7II...                  
	... ........       .III,.                             ..77I                    
	... ........      .?~.                    .       .       ,I.  
