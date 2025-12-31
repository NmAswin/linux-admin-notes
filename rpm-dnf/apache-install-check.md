# Checking Apache Installation (RHEL-based systems)

## Commands Used

```bash
rpm -qa | grep httpd

rpm -qa | grep httpd
redhat-logos-httpd-100.2-1.el10.noarch

#Confirms whether Apache Web Server is installed.
rpm -q httpd
package httpd is not installed

#Common Confusion

Packages like redhat-logos-httpd only provide images/logos.
They do NOT install the Apache web server.
