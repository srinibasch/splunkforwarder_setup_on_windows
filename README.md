# splunkforwarder_setup_on_windows
connect splunk and splunk forwarder to receive system, application and security logs.
Install splunlk enterprise.
START INSTALLING SPLUNK FORWOARDER
1.<img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder1.png">

2. give your user name and set passowrd

3.give deployment server ip and port(you can enter the default port)
  
  <img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder2.png">

4.give recieveing indexer ip (default 9997)

<img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder3.png">
5.click on Install and finish

<img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder4.png">
6.follow the path and find out outputs.conf
 
 ```C:\Program Files\SplunkUniversalForwarder\etc\system\local```

<img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder5.png">

7.copy the outputs.conf and rename it as inputs.conf.
  and inside inputs.conf write following (host name you can find in command prompt by writing command ``` hostname```)

<img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder6.png">

8.go to splunk eneterprise and click on forwarding and recieving.
 
 <img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder7.png">

9.next click on add new.

<img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder8.png">

10.<img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder9.png">

11.Disable firewall on your system

<img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder10.png">

12.press win+R in the run box type services.msc
   and restart the service splunkforwarder

<img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder11.png">

13.go to splunk enterprise 
   go to search and reporting
   enter ```host=< as per your machine host name >```

<img src="https://github.com/srinibasch/splunkforwarder_setup_on_windows/blob/main/splunkforworder12.png">
   here are the outputs
