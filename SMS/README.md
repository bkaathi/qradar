# QRadar SMS Notification

Send text messages from QRadar ”Custom Actions” using Twilio API in a bash file. 

### Getting Started 

1. Create an account from http://www.twilio.com
2. Retrieve Phone number, Id, and Token generated under your dashboard
3. Apply Phone number, Id, and Token into script
4. Call script into QRadar, see QRadar setup below
 
### QRadar Setup

1. Go to _Admin_ tab and select _Define Actions_ under _Custom Actions_
2. Select _Add_ from top menu options
3. Provide the following:
   * Name
   * Description
   * Interpreter: Bash
   * Upload SMS Bash/Curl script
   * Fix Property Value
4. Click _Add_
5. Click _Save_


Uploaded scripts found in the following directories:

* /opt/qradar/bin/ca_jail/home/customactionusernew
* /opt/qradar/bin/ca_jail/custom_action_scripts
