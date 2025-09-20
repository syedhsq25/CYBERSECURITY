# CYBERSECURITY
Learning and understanding Cybersecurity with tools.

#day1
1. Installed Splunk
2. Installed Splunk Universal Forwarder
3. Tried and tested both the tools

#day2
1. Ingested Logs by using Splunk Forwarder into Splunk,
2. Configured Inbound rules of the firewall.
3. In the splunk enterprise, in the FORWARDERS and RECEIVERS, added a RECEIVING PORT of 9997
4. Learnt new shortcuts Windows+X
5. Used commands :
   >**For starting SPLUNK **: net start splunkd
   >** For Stopping Splunk ** : net stop splunkd
   >** For starting splunk forwarder ** : net start splunkforwarder
   >** For stopping splunk forwarder ** : net stop splunkforwarder
   >** For changing the username and password ** : splunk.exe add forward-server 192.168.0.103:10514 -auth admin:password
   >** For checking if the port is listening ** : netstat -an | findstr 9997, anyport number you use.
6. Generated Dashboard with the outputs as follows. <img width="468" height="760" alt="Screenshot (502)" src="https://github.com/user-attachments/assets/a22db1a1-e133-4840-9610-444ae074d2b5" />

