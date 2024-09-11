# Custom DNS-Server
This Custom DNS Server manages and processes domain names and related IP addresses.When the DNS Server receives a name resolution query, it translates the given domain name into its IP address and returns it to the user.If the DNS Server cannot discover the domain name in its records, it forwards the inquiry to a regular DNS Server.

This project also features a Registration Portal built with Django that allows users to register their own domain names in the DNS Server.


# Setup:
The DNS entries are stored in the host_file, whereas the server.py contains the server's code. To launch the server, run the server.py file with administrative rights (since it has a port 53 binding).

How to run the portal?<br>
First change directory to Registration_portal then run command-<br>
python manage.py runserver

