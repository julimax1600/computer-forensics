# Activity logs

### Activity logs are files that contain information about the events and activities that occur on the system. These logs are used to identify and fix system problems and also to analyze potential hacker attacks.

---

     /var/log/auth.log

#### This file logs login attempts and changes to authentication settings. If an attacker tries to log in to the system or tries to modify the authentication settings, this will be logged in the file.

---

     /var/log/syslog

#### This file logs a variety of system events, such as kernel errors, debugging messages, and other important events. If an attacker tries to access protected resources, this will be recorded in this file.

---

     /var/log/apache2/access.log and /var/log/apache2/error.log

#### These files record events related to the Apache web server, such as resource requests and server errors. If an attacker tries to perform a denial of service attack or tries to access protected resources on the web server, this will be recorded in these files.

---

      /var/log/auth.log and /var/log/syslog

#### These files log events related to the SSH server, such as failed login attempts and established connections. If an attacker tries to access the system via SSH, this will be recorded in these files.

---

### It's important to note that while activity logs are a valuable tool for identifying and fixing problems, they're not perfect. Sophisticated attackers may attempt to delete or modify activity logs to hide their activity. Therefore, it is important to have other layers of security, such as firewalls and intrusion detection systems, to complement the information recorded in activity logs.
