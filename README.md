# XSS steals cookies
* The current version is 1.0 and will be updated continuously
* Python version 3.6 or above
* Automatically steal cookies
* Compatible with Windows or Linux
* Added attack message push to DingDing
## usage method
  * View help information

      ```#python3 XSS.py -h```

  ![图片名称](https://github.com/MartinxMax/XSS_Cookie_Tool-V2.0_DingDing/blob/master/%C2%96%C2%96Demo_image/Command.png "Help")  

  * LAN attack

      ```#python3 XSS.py -lp (Local port)```

  * Internet attack

      ```#python3 XSS.py -t -lp (Local port) -rh (Remote host IP) -rp (Remote host port)```

  * Use DingDing to push attack messages
    ```python XSS.py -lp (Local port)  -d (Token) -k (Keyword)```
## Effect demonstration
  
* Get DingDing's Token and Keyword

    ![图片名称](https://github.com/MartinxMax/XSS_Cookie_Tool-V2.0_DingDing/blob/master/%C2%96%C2%96Demo_image/TOKEN.png "PAYLOAD")  

* You can fill in the parameters in Start.bat to facilitate next use
    
 
![图片名称](https://github.com/MartinxMax/XSS_Cookie_Tool-V2.0_DingDing/blob/master/%C2%96%C2%96Demo_image/InputTOKEN.png "PAYLOAD")  

__A test message will be sent to your DingDing when the parameters are correct__


   ![图片名称](https://github.com/MartinxMax/XSS_Cookie_Tool-V2.0_DingDing/blob/master/%C2%96%C2%96Demo_image/Test.png "Cookie")  


* Copy PAYLOAD,Inject code on the vulnerable page

    ![图片名称](https://github.com/MartinxMax/XSS_Cookie_Tool-V2.0_DingDing/blob/master/%C2%96%C2%96Demo_image/injectCode.png "Cookie")  


* Administrator visits malicious page
  The administrator is redirected to the specified page
* Got cookies

    ![图片名称](https://github.com/MartinxMax/XSS_Cookie_Tool-V2.0_DingDing/blob/master/%C2%96%C2%96Demo_image/success.png "Cookie") 
* Android View

    ![图片名称](https://github.com/MartinxMax/XSS_Cookie_Tool-V2.0_DingDing/blob/master/%C2%96%C2%96Demo_image/mobile.jpg "Cookie") 
