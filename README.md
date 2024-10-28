# 🍪Chromium Cookie extractor
This is a tool which permits to retrieve cookies from the latest versions of the Google Chrome browser (both 129+ and older versions), Microsoft Edge and other Chromium-based browsers, it is fully controlled via telegram bot and doesn`t requiere nor a dedicated server neither any additional software, you can read how exactly does it work below. Contact me on Telegram to buy: **@shinyenigma**

## 🌐About the issue:
Since august of 2024 Google Chrome is user a new type of cookie protection called Device Bound Session Credentials (DBSC). Because of it, the decryption of Chrome`s cookies has become much more complicated. Here is the idea of this type of protection:
![Screenshot 2024-07-26 2 15 06 PM](https://github.com/user-attachments/assets/3ca32f75-7d41-4c5d-afbf-aba2111dcc8b)

Here you can see more about this topic: [Click](https://security.googleblog.com/2024/07/improving-security-of-chrome-cookies-on.html?m=1)
In the end of october 2024 Microsoft Edge has introduced the same protection, which made the old cookie grabbing method useless of more then 77% of users (about 65% of users worldwide use Chrome and about 12% use Microsoft Edge). So, I`ve decided to develop a solution to this problem

## 🔑About the tool: 
This tool is able to decrypt cookies from the newest Chrome, Edge and other Chromium-based browsers without admin priveleges. It can be used as an addition to any remote access tool (RAT) or stealer as most of them have lost the possibility to grab cookies from Chrome and Edge since this security update was released
### How does it work:
Once the person starts the infected file (or it can be uploaded with manually using a RAT), you`ll be able to grab cookies from all the existing chrome profiles. The remote controllling is realised completely via telegram. The tool has several additional option to make the usage more comfortable, like screenshot grabbing etc. The tools permits to control several PCs at the same time with the same telegram bot. Here are some screenshots:
#### Builder:
![image](https://github.com/user-attachments/assets/465ac97c-5eb2-4ac8-8097-f1b5881ffcb6)

#### Avaliable commands:
![image](https://github.com/user-attachments/assets/918f58d6-f0a9-46d9-8dde-d48003a91a50)

#### Grabbing cookies (NETSCAPE format):
![image](https://github.com/user-attachments/assets/d7bbf1f6-f765-4acc-b098-dead9d9cd2dd)

## ♦️DISCLAIMER: This tool is for educational purposes only, I do not take any responsibility for the potencial damage caused with it
