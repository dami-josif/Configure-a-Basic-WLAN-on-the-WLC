Objectives


In this activity, you will troubleshoot various issues in home wireless and enterprise wireless networks.


• Troubleshoot wireless LAN connectivity issues in a home network.

• Troubleshoot wireless LAN connectivity issues in an enterprise network.


Background / Scenario


Now that you have learned how to configure wireless in home and enterprise networks, you need to learn how
to troubleshoot in both wireless environments. Your goal is to enable connectivity between hosts on the
networks to the web server by both IP address and URL. Connectivity between the home and enterprise
networks is not required.


To access the Home Wireless Router, the username and password is admin.
The WLC management interface username is admin and the password is Cisco123.


Instructions


Part 1: Troubleshoot the Network


Note: You will only be troubleshooting the Home Wireless Router, WLC and wireless host devices in this
activity.


Step 1: Test connectivity.


a. Test connectivity between the various wireless hosts and the web server by both IP and URL
www.netacad.pt.


b. Record the hosts that cannot access the web server in the table in Step 2.


Step 2: Investigate issues and record findings.


a. Investigate the connectivity issues with each host. Issues may be with the host configuration, or with other
wireless network components.


b. Complete the table.


OBSERVATIONS AND SOLUTIONS


Fix DNS Server IP in the DHCP Pool on the Home Admin after cable connecting to the router, Go to 192.168.0.1 on the browser

Click the dropdown currently showing Static IP.


Select Automatic Configuration – DHCP because that's what required for internet on Wireless Home Router


<img width="1366" height="768" alt="Screenshot (71)" src="https://github.com/user-attachments/assets/d0aa4792-d1c2-41c2-9e7b-71e3c91d8e3b" />

Don't manually enter an Internet IP address, subnet mask or gateway. DHCP will obtain these automatically.
1. Stay on Setup → Basic Setup.
2. Scroll down to the Network Setup section.
3. Find DHCP Server Settings.
4. Look for the DNS field, usually labelled Static DNS 1.
5. Enter: 10.100.100.254


Configured the Wireless Security Mode for laptop 2 and changed the network settings for Tablet PC to DHCP

Configured the Wireless LAN Controller WLC-1 Wireless VLAN 10 Security Mode and Enabled Wireless VLAN 20 Interface

WLAN VLAN10 SSID-10 to WPA-2 PSK/Personal

WLAN VLAN 20 SSID-20 to WPA-2 802.1x/Enterprise 



<img width="1366" height="768" alt="Screenshot (69)" src="https://github.com/user-attachments/assets/cafa7169-4a58-4e75-bd7c-cb8aca55bd98" />


<img width="1366" height="768" alt="Screenshot (70)" src="https://github.com/user-attachments/assets/58736c1a-de12-4779-8ed1-d592b6ab13a4" />

