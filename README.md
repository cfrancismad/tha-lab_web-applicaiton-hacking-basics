Hacker Academy
==============
http://hackeracademy.com

### WEB APPLICATION HACKING BASICS

#### Purpose
This module is not so much about technical exploits as it is about a general understanding of the structure of web applications and the attack surface that they present. The goal of this lab is to help you understand that attack surface and think creatively about ways to exploit it.

#### Requirements
This lab requires the following THA virtual machines
* Kali
* Vulnerable Client

#### Lab Credentials
Kali VM: root / toor
Vuln Client VM: user / password

#### Setup
The technical labs seem more directly applicable, but this lab is more important in understanding the nature of web application security. Without this understanding, you may be able to use specific exploits, but you won’t be able to find new attack vectors or create advanced exploits. You may not already have the experience or skills necessary to attack the applications, but by getting in the habit of assessing their attack surface, any design flaws or vulnerabilities in new applications you encounter will become glaringly obvious.
1. Boot your THA Vulnerable Client VM.

2. Boot your THA Kali VM and login.

3. Clone this repo on your Kali VM by opening a terminal and issuing the following command:

    ```bash
    git clone git://github.com/madsec/web-application-hacking-basics /root/THA/web-application-hacking-basics
    ```

##### Note
* If the Kali VM network connection continually disconnects please reboot the VM.

#### Start the lab
* Follow the instructions for lab 1 found on your Kali machine at 
  ```
  /root/THA/web-application-hacking-basics/lab1.md
  ```
