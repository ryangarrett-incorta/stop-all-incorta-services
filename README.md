# stop-all-incorta-services
 
This script will stop all running incorta services.


#Linux usage



Copy stop_all_incorta_services.py to server with Incorta installed

chmod 755 stop_all_incorta_services.py

#Create INCORTA_HOME varible in bashrc pointing to your file path

vi ~/.baschrc
export INCORTA_HOME=/home/incorta/IncortaAnalytics/

source ~/.baschrc

usage ./stop_all_incorta_services.py -r

#Windows usage
This script does not run in windows grasshopper
