# Tally light ESP32 for Blackmagic ATEM switcher
A wireless (WiFi) tally light for Blackmagic Design ATEM video switchers, based on the M5StickC/M5StickCplus ESP32 development board and the Arduino IDE.

Added some features
 - Added a wifi manager to help configure settings menu in AP to change: 
	 - IP address of Atem
	 - Number of camera 
	 - Led on/off
 - Second screen to see the info description (Based on the work of josephdadams)
 - Change brightness by button (Based on the work of josephdadams)

<br>

# Tally in work
<br>

https://user-images.githubusercontent.com/12483796/181568676-afe5e105-cfe2-4e4d-999f-b96b512d1c30.mp4

<br><br><br>



# Tally setup
How to configure tally
- Go to second screen pushing M5 button<br>
<img src="./media/infoScreem.jpeg" alt="infoScreem" width="200"/><br>
![infoScreem](./media/infoScreem.jpeg =200x)
- Enter the ip that was shown on the screen <br>
<img src="./media/wifiManager-1.png" alt="wifiManager1" width="100"/>
<img src="./media/wifiManager-2.png" alt="wifiManager2" width="100"/><br>
- put the values ​​you want and click save<br>
-<img src="./media/showing.jpeg" alt="showing" width="200"/><br>
<br>


# Tally info screen and brightness



https://user-images.githubusercontent.com/12483796/181568781-cc5526f5-ce25-4fa4-b03b-b6c0be4ed463.mp4


<br><br><br>



For more information, see:
https://oneguyoneblog.com/2020/06/13/tally-light-esp32-for-blackmagic-atem-switcher/

Based on the work of Kasper Skårhøj:
https://github.com/kasperskaarhoj/SKAARHOJ-Open-Engineering


Based on the work of josephdadams :
https://github.com/josephdadams/tallyarbiter
