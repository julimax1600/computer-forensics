# Activity logs

### Activity logs are files that contain information about the events and activities that occur on the system. These logs are used to identify and fix system problems and also to analyze potential hacker attacks.

---

     /var/log/auth.log

#### This file log events related to the SSH server, such as failed login attempts and established connections. If an attacker tries to access the system via SSH, this will be recorded in these files.

---

     /var/log/syslog and var/log/kern.log

#### These files logs a variety of system events, such as kernel errors, debugging messages, and other important events. If an attacker tries to access protected resources. 

---

     /var/log/apache2/access.log and /var/log/apache2/error.log

#### These files record events related to the Apache web server, such as resource requests and server errors. If an attacker tries to perform a denial of service attack or tries to access protected resources on the web server, this will be recorded in these files.

---

     /var/log/ufw.log
     
#### Firewall logs can provide information about what type of traffic was blocked and when the blocks occurred

---

### It's important to note that while activity logs are a valuable tool for identifying and fixing problems, they're not perfect. Sophisticated attackers may attempt to delete or modify activity logs to hide their activity. Therefore, it is important to have other layers of security, such as firewalls and intrusion detection systems, to complement the information recorded in activity logs.
