This is to be used for educational purposes only.

This project implements clickjacking on http://zero.webappsecurity.com, which is a fake vulnerable website, designed to perform on and learn ethical hacking. The end user receives a phishing email containing link to this clickjacking website, which downloads a potentially suspicious file (in this case, the user has to click on the runme.bat file to print a message, but the area can be improvised and is still under development) as soon as the website loads. Additionally, if the user enters credentials to log in, the attacker immediately gets them (the email contains urgency to change credentials).

Will be improvising it as much as possible.

Following is an example phishing email which can be used to execute this project, and the sender name and email can be used as a variation of the organisation's real email one is pretending to be from.

![image](https://github.com/user-attachments/assets/8fd3c1b7-7fdb-4ef1-b534-e19cb4c01672)
