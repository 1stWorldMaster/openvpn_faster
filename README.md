Connect using `sudo openvpn --config  101.33.255.244_tcp_443.ovpn` 

we will have the following folder structure 
openvpn -> Will contain all the opnvpn files for he connection that are needed
vpn
check.csv
└── 📁 Japan
         |   check.csv  
         └── 📁 ExpressVPN
               └── tokyo-01.ovpn

every conntry will contain the check.csv file which will have the following information 
udp(faster)
tcp(reliablity)

country, provider, ping, conncetion_type(tcp,udp), username, password

the user will have two options 
1. can create at the time of establishing connection 
2. can connect using the time when the connected to the specific country 

check.csv will also have the info in openvpn folder itself giving the overall fastest server and slowest server

will also contain log.txt file for the updates of the server


# scrape - 
will be used to scrape the data form the specific servers to add them for the users

# connect folder 
will contain the files to implement the logic for the required functionality 

# test
will contain the python file to connect using test some test servers

ALSO I NEED TO UPDATE THIS README FILE ANY SUPPORT IN CODE IS APPRECIATED

THANKYOU 

DEADLINE WILL BE THIS APRIL END GUESS IT WILL WORK HAVING THE EXTRA WORK TO 🙃