# Hackintosh-EFI-Dell-Inspiron-5559
## Hackintosh (OpenCore) Dell Inspiron 15 5559 i7 6500u | Tested on Bigsur, Monterey
Check the setup guide below to make sure install macOs successfully.

# Result 
<center>![image](https://user-images.githubusercontent.com/103339137/162856527-c54d0173-04eb-453b-88e8-1d5fdfbc561a.png)</center>
![image](https://user-images.githubusercontent.com/103339137/162856449-2161f3ee-4539-444a-a217-6547cc70bfe5.png)
![image](https://user-images.githubusercontent.com/103339137/162856547-55255ed3-9688-410c-9a41-4ce66a482798.png)

# System's Configuration:

 - Laptop Dell Ins 5559
## Specifications 	Details
| Specifications  | Details                        |
| -------------   | -------------------------------|
| Laptop Model    | Dell Inspiron 5559             |
| Processor       | Intel Core i7-6500U @ 3.10GHz  |
| RAM             | 2 X 8GB                        |
| Storage         | SSD 950GB                      |
| Graphics        | Intel HD Graphics 520          |
| Display         | LED HD 1920X1080 (15.6 inches) |
- macOS Bigsur 11.6 (working)
- macOS Monterey 12.3.1
- OpenCore 0.7.9

#
# What's Working :

- Intel HD Graphics 520
-Audio :
        Internal Speaker out, Headphone out
        Internal Mic In, Headphone Mic in
- Battery Indicator
- Sleep + Wake + Restart + Shutdown
- Brightness Slider and Brightness Fn key [ F11, F12]
- Trackpad with both I2CHID And PS/2
- HDMI + HDMI Audio
- Ethernet
- WIFI + Bluetooth
- Boot Chime
- SD Card Reader


# Changes You Need To Make :-
<details><summary>Generate a Serial</summary>
 <ol>1. Download and open GenSMBIOS</ol>
 <ol>2. Select 3 to Genrate SMBios with ROM</ol>
 <ol>3. Now Type "MacBookPro13,2" this will genarate 5 SMBios with ROM</ol>
 <ol>4. Check the Serial validity on Apple's check coverage We have to use only invalid serial</ol>
 <ol>5. Copy the serial in the config
   <il> - Type Goes in Generic -> SystemProductName</il>
   <il> - Serial goes in Generic -> SystemSerialNumber</il>
   <il> - Board Serial goes in Generic -> MLB</il>
   <il> - SmUUID part goes in Generic -> SystemUUID</il>
   <il> - Apple Rom goes in Generic -> ROM</il></ol>
 </details>
 
# Not working
Amd Radeon R5 M335

