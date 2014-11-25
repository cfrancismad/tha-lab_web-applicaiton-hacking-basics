#### WEB APPLICATION DISCOVERY

1. Make a list of the web applications you use every day. Include:
 * News sites
 * Social networking
 * Webmail
 * Intranet applications
 * Others

2. Perform an nmap scan of your local network for web applications.

  ```
  nmap -p http* 192.168.1.1-255
  ```

    * Adjust the above network range to match your own network.
    * Investigate any devices or services that were found.

3. Consider what each of these applications is used for and how its compromise could affect you.
 * How much of your personal information do these applications contain?
 * How heavily do you rely on these applications for everyday functions?
 * What network, hardware, or information resources would these applications provide an attacker?

4. You have completed this lab. You can continue to lab 2 by following the instructions found at 
    ```
    /root/THA/web-application-hacking-basics/lab2.md
    ```