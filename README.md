# XSS steals cookies
* The current version is 1.0 and will be updated continuously
* Python version 3.6 or above
* Automatically steal cookies
* Compatible with Windows or Linux
* Added attack message push to DingDing
## usage method
  * View help information

      ```#python3 XSS.py -h```
  ![图片名称](https://raw.githubusercontent.com/MartinxMax/XSS_Cookie_Tool/master/%C2%96%C2%96Demo_image/Command.png "Help")  

  * LAN attack

      ```#python3 XSS.py -lp (Local port)```

  * Internet attack

      ```#python3 XSS.py -t -lp (Local port) -rh (Remote host IP) -rp (Remote host port)```

  * Use DingDing to push attack messages
    ```python XSS.py -lp (Local port)  -d (Token) -k (Keyword)```
## Effect demonstration 
 * Here, XSS will be demonstrated in the local DVWA shooting range, and cookies will be stolen through the internet

_If your machine has a public IP address, just listen to the local port_

* Enable port forwarding (Ngrok is used for demonstration)
![图片名称](https://raw.githubusercontent.com/MartinxMax/XSS_Cookie_Tool/master/%C2%96%C2%96Demo_image/TCP.png "Port forwarding")  
* Get DingDing's Token and Keyword

    ![图片名称](https://raw.githubusercontent.com/MartinxMax/XSS_Cookie_Tool/master/%C2%96%C2%96Demo_image/PAYLOAD.png "PAYLOAD")  

* You can fill in the parameters in Start.bat to facilitate next use
    
 
![图片名称](https://raw.githubusercontent.com/MartinxMax/XSS_Cookie_Tool/master/%C2%96%C2%96Demo_image/PAYLOAD.png "PAYLOAD")  

__A test message will be sent to your DingDing when the parameters are correct__


* Copy PAYLOAD,Inject code on the vulnerable page

    ![图片名称](https://raw.githubusercontent.com/MartinxMax/XSS_Cookie_Tool/master/%C2%96%C2%96Demo_image/ADMIN.png "Cookie")  


* Administrator visits malicious page
  The administrator is redirected to the specified page
* Got cookies
      ![图片名称](https://github.com/MartinxMax/XSS_Cookie_Tool/blob/master/%C2%96%C2%96Demo_image/Cookie.png?raw=true "Cookie") 
* Android View
    ![图片名称](https://github.com/MartinxMax/XSS_Cookie_Tool/blob/master/%C2%96%C2%96Demo_image/Cookie.png?raw=true "Cookie") 
