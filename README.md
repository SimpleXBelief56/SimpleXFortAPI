# SimpleXFortAPI

Python Based Fortnite API Console  
Compatible with  
  Windows 10 {Python 2.7 (Python 3 Support coming soon!)}   
  Linux {Python 2.7 / Not Tested Yet!}   
  
 Installation:   
  -> Download as Zip / Git Clone to Directory   
  -> Open Terminal inside of SimpleXFortnite Folder   
  -> run "python install.py"   
  -> once installation is done, the API will be runned 
  
# Requirements

  - Python 2.7 installed 
  - Windows (Environment Variable should be set!)
  - Linux (Ubuntu -> apt-install python2.7 python-pip)
  
  (Note) -> Modules will be installed for you
  
# Process
  1. Make sure the correct modules are installed
  2. Make a request to the endpoint url -> (https://fortnite-public-api.theapinetwork.com/)
  3. Make a request to the documentation url
  4. Display the menu
  5. Depending on the selection, the function required to run the selection will be called
  6. Finally, it will return back to the menu
  
# Note
  - The script will somtimes log json data into a seperate file, depending on the error, you can remove it if you want to
  - Have not tested it on Linux, any issues email SimpleXTeam@gmail.com
  - Improvments soon!
  
 # FAQ
 
 I get a TypeError!  
 A: If you recieve a TypeError, or any type of error please release an issue ticket with the error
 
 It says to "run SimpleXFortnite.py again!" but never actually runs the script?  
 A: This is probably because of a interferance with install.py when opening module.txt. Fix coming soon!
 
 Recursion Error?  
 A: While loop interferance while running two functions at the same time.
 
 Thanks to https://fortniteapi.com/ for the JSON API  
 Thanks to SimpleXTeam for the teamwork  
