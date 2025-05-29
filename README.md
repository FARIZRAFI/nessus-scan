# nessus-scan
scanning a local host or ip address using nessus scan
1) INSTALLING NESSUS ESSENTIALS
 -includes serveral steps to get on the track ie,
 -first of all we have to download from the site ie,nessus later take on the terminal and some commands has to perform
-take out the download folder cd ~/Downloads
-sudo dpkg -i Nessus-*.deb
-sudo systemctl enable nessusd
-sudo systemctl start nessusd
-sudo systemctl status nessusd
![Screenshot_2025-05-29_07_19_17](https://github.com/user-attachments/assets/e9037113-628c-4b2a-8245-9e77b64f550b)
- later we have get in to a https://localhost:8834
site requires additional permission.

2)NOW A SETUP A SCAN FOR LOCAL HOST OR IP ADDRESS :
   here requires some details like windows or linux etc
   some credentials like username and password.
3)START A FULL VULNERABILTY SCAN :   ![Screenshot_2025-05-29_07_18_28](https://github.com/user-attachments/assets/ad4ecc3a-8147-48cf-8346-8512c5baf46c)

4)WAIT FOR SCAN TO COMPLETE:will take some time.....

5)REVIEW THE VULNERABILITIES:
![Screenshot_2025-05-29_07_17_16](https://github.com/user-attachments/assets/12823db9-a786-4917-8bdd-28e5c52fcce4)
![Screenshot_2025-05-29_07_16_35](https://github.com/user-attachments/assets/ec41b7a3-dd6b-4e64-9caa-dd3e0222a6c7)
![Screenshot_2025-05-29_07_16_59](https://github.com/user-attachments/assets/44cee079-487d-4430-a0b6-d3240e68d71b)

6)RESEARCH SIMPLE FIXES OR MITIGATION FOR FOUND VULNERABILITIES:
ssl certificates absence is the reason for vulnerability.

![Screenshot_2025-05-29_07_31_58](https://github.com/user-attachments/assets/9cae1554-a47b-48e3-8e78-2e7bbc118223)
![Screenshot_2025-05-29_07_31_35](https://github.com/user-attachments/assets/6f839295-2a62-4db5-a265-61c27c3f1441)

7)MOST CRITICAL ONE IS FOUNDED: its sorted by CVSS 
![Screenshot_2025-05-29_07_16_59](https://github.com/user-attachments/assets/f0d4c5e9-fa76-4d42-8aac-1586e04a5543)
8) SCAN RESULTS ALREADY UPLOADED WITH RESPECTIVE INSTANCES!!!!




