<pre>
# ESPortal

Proof of Concept
ESP8266 Fake Access-Point/WiFi-Portal that Captures User Credentials using Spoofed Pages
Written by Corey Harding
www.legacysecuritygroup.com

Software used:
Arduino IDE: Arduino IDE 1.6.11
Board Manage/Libraries: esp8266 by ESP8266 Community version 2.3.0

Hardware used($3.26):
NodeMCU 1.0(ESP-12E Module) Chinese Clone: wemos.cc - LoLin new NodeMcu V3 with: CH340G USB Chip

Instructions:
Open ESPortal Sketch in Arduino IDE
Edit config.h
  Name Access Point
  Configure custom domain names and login url redirects for Site1, Site2, and Site3
  Configure catch-all redirect
  Configure web portal welcome domain name and URL
OPTIONAL: Edit HTML of site1.h, site2.h, site3.h, and site_other.h
Upload Sketch
Test your three custom domain names, welcome, and catch-all
View captured login credentials at fake.exploit.agency/esportal

We are not affiliated in any way with ouraccesspoint.com, fakesite1.com, fakesite2.com, or fakesite3.com.
We take no responsibility for your use of this tool.  Please obey all local, state, federal, and international laws.
This is provided for proof-of-concept only.

NOTE: This does not support HTTPS/SSL.  Cached DNS/Pages redirecting to https:// addresses will fail.
Though sometimes it can be fairly convincing for some people when using the proper html templates you must educate users to spot a fake login!
https://legacysecuritygroup.com/index.php/categories/12-software/28-esportal-fake-wifi-portal-credential-harvester
</pre>