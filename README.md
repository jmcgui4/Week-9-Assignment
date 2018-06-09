# Week-9-Assignment
HoneyPots Deployed: mhn-honeypot-1 	

Issues Encountered:

1.The install.sh would not install until an edit to the install_hpfeeds.sh
Have to be logged into the Admin console then find the install_hpfeeds.sh
  Steps to recreate:
  1. Log in to Admin console.
  2. cd /opt/mhn
  3. ls
  4. cd scripts
  5. ls
  6. sudo nano install_hpfeeds.sh
      To change github repositories to pip install -e git+https://github.com/couozu/pyev.git#egg=pyev
                                and    pip install -e git+https://github.com/threatstream/evnet.git#egg=evnet-dev
 #### This is to get data from the correct github since the one given in codebath didn't work so it would not proceed with the install.sh command in Milestone 2.
 
 ####The total number of attacks that happened totalled to 2,268
 2,204 attakcs from Canada
 4 attack from Vietnam 
 3 attacks from an unknown source
 3 attacks from the US 
 another 3 attacks from the US
 
 #### The total number of ports attacked and which ones
 Port 23 attacked 12 times
 Port 514 attacked 11 times
 Port 3389 attacked 9 times
 Port 4045 attacked 8 times
 Port 9503 attacked 5 times
 
 #### Unresolved Questions
 Were all of these attacks from my nmap scan?
 If those other countries showed up in the attack report, does that mean that people in other countries tried to gain access?
 
 
