# Lock issues in Ubuntu system
 To troubleshoot follow these steps: 

 1.  Lock issues of apt or dpkg. Find PID using either of :
  * `lsof /var/cache/apt/archive/lock`   
  or   
  *`lsof /var/lib/dpkg/lock`  
  or  
  * `ps aux | grep -i apt`


 2. 
 ```git
  Sudo kill -9 <PID>
  sudo killall apt apt-get
  ```
 3.
 ```  
  sudo rm /var/lib/dpkg/lock
  sudo rm /var/lib/apt/lists/lock
  ```


