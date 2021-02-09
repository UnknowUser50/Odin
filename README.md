# Odin script - UnknowUser50 - 2021

```bash
git clone https://github.com/UnknowUser50/Odin
```
![Odin-Logo](https://i.pinimg.com/originals/90/8c/ec/908cecb9bb0eaddc8e25f2709f73db3c.jpg)

* ## Requierements : 
 * Hydra
 * Nmap 
 
* ## Warning : 
In order to run the script, you must have an internet connection. 

* ## Run Odin : 
You have to pass different parameters in order to work :
  * @ arg 1 : The target's ip address in this format : 1.1.1.1
  * @ arg 2 : The path indicating the list of the text file containing the list of user names - format : /usr/share/wordlists/name_list.txt
  * @ arg 3 : The path indicating the list of the text file containing the list of password - format : /usr/share/wordlists/pass_list.txt
  
Example : 

```bash
sudo ./odin.sh 1.1.1.1 /usr/share/wordlists/common_user.txt /usr/share/wordlists/common_pass.txt
```
  
If you do not fill in all these parameters, the script will not be able to run.

To display the help, you can pass as first argument :
```bash
sudo ./Odin --help
sudo ./Odin -h
sudo ./Odin help
```

A wordlist directory is added in order to use the most classic and most used combinations.

For any problem, you can open an issue directly on the github directory.

* # Supported services : 

 * FTP on 21/tcp
 * SSH on 22/tcp
 * Telnet on 23/tcp
 * MySQL on 3306/tcp

As and when different services will be added to make this script more complete.

* ## Disclamers :
Odin is a tool reserved for **professional** or **educational** use ! Under no circumstances should it be used for the purpose of harming others or a system that does
not belong to you. As a reminder, **any intrusion or attempted intrusion is punishable by law !**
I am no way responsible for your actions, thank you for your understanding
