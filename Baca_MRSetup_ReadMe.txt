to connect the radios, you will need: 
	-2 meshrider wearable radios
	-2 USB-C to USB-C or Micro USB cables
	-2 USB-C charge cables (6-24V). If you are class of ’24-’26, the cables for your issued computer will work 
	-2 laptop or desktop computers capable of receiving a USB-C or Micro USB
	(note that for the wearable radios only, no antenna is necessary because the wearable model comes with an internal antenna. Contrary to the diagram on the Doodle Labs getting started page, an eval kit is also not necessary for the wearable model)
Important: your meshrider wearable radio will have several ports and lights on it. the ones which you will need to keep track of are the Power and USB ports, as well as the PWR, WiFi, and MR lights.

In order to connect the radios: 
	-connect the USB-C port labeled "Power" to your power cable. ensure the light labeled PWR turns on, ignore the other lights for now, they may blink as the radio turns on, this does not mean you have established a wireless connection. 
	-connect the USB-C port labeled "USB" to your computer using the USB-C cable
	-navigate to your computers control pannel and type "view network connections" into the search bar. 
	-when you enter network connections, if you have properly connected to the radio, you will see a new network connection labeled "Ethernet #". the number at the end does not matter. 
	-right click on this connection and select properties, then left click on Internet Protocol Version 4 and select properties. 
	-select "use the following IP Address and then input an IP Address within the 10.223.0.0/16. if you are unsure what this means, just input 10.223.0.5 	-for your first radio and 10.223.0.6 for your second radio. the IP Addresses must be different for all radios you wish to connect to the mesh. 
	-for the subnet mask, input 225.225.0.0 then select "OK"
	-at this point you should get a connection option labeled "DoodleLabsWiFi". if you are not seeing this, then reattempt the prior steps with a different IP address on the 10.223.0.0/16 subnet. 
	-if you do see DoodleLabsWifi, connect to it. once you are connected, go to a browser and type in the IP address printed on the tag of your Meshrider Wearable Radio. if you have an older version of the radio, the IP may not be printed and further steps will be neccesary to get the IP address. these steps are not detailed here, but can be found on the "Getting Started" page of any doodle labs meshrider radio product. 
	-once you do this, the WiFi light on your radio should turn green and you will be prompted for a username and password.for the wearable radios, the default password the first time you log in will be "DoodleSmartRadio". the username will be "root" and should already be present. 
	-once you have done this and accessed the configuration options with both radios, the MR light should also turn green. this light means there is a mesh radio which your radio is connected to. another way to check for connection is to go to the "mesh map" page of the configuration menu for the radio and ensure that there is at least two devices marked on your mesh map. if your devices are not connecting, the "getting started" page reccomends ensuring the radios are at least 5 meters apart. once this is completed, you can further ensure connection by pinging your radios. 

	Subsequent use of the configuration menu will require you to connect to DoodleLabsWifi. you will also likely want to change your password from the default one. the names of our two radios are BacaRadio and DinonnoRadio and the password for both of them is 431775. the password and the radio name can be changed from the config menu and if you are using new devices, it is reccomended you rename them so that the meshmap is more easily readable, especially if you are connecting more than two devices. 
