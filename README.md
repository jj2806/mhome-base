# MHome Base
Desktop application for controlling my smart home!

## About
It all started when, one day, I wanted to turn the lights in my house on and off from my phone.
After months of researching how to do it I found that Arduino was the best choice. Ordered some Arduino Unos with the Ethernet shield and some relays. First option I found was to load a whole HTML website from the Arduino when you connect to it through the browser but I found it really slow and lacking flexibility. To battle the flexibility I made the website show only basic information and then I used web scraping to make it look better on my phone, but I wasn't satisfied. I searched for a solution for a long time then I found Raspberry Pi and that it can communicate with the Arduino through UDP requests on my local network. To add to that I learned to connect Python programs to Google Firebase Firestore database which worked great with mobile applications.

In the meantime I named my smartified home MHome

And now I am building this application to run on my local computer and serve as the gate keeper between the Arduino side and the database side.

 - Started by Josip Mihelčić in 2016
 - Made a Github repo in 2022
