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
 
 
