# BugHunting


# Tools
1. Nmap Host Discovery: <https://nmap.org/book/host-discovery-dns.html> <br>
The key focus of Nmap host discovery is determining which hosts are up and responsive on the network. That narrows down the field of targets, since you can't hack a host which doesn't exist. <br>
<br>
Print the output of your Nmap scan using the -oX command.<br>
Example: nmap -T4 -A -p 1-1000 -oX - scanme.nmap.org<br>
https://nmap.org/book/output-formats-xml-output.html#output-formats-xml<br>
<br>
2. Amass: https://github.com/owasp-amass/amass/blob/master/doc/user_guide.md
