# Network-Intrusion-Detection-System Web-App


### DATASET: 

This data is KDDCUP’99 data set, which is widely used as one of the few publicly available data sets for network-based anomaly detection systems.  
 
For more about data: http://www.unb.ca/cic/datasets/nsl.html 

### BASIC FEATURES OF EACH NETWORK CONNECTION VECTOR:

1) <b>Duration:</b>  Length of time duration of the connection  
2) <b>Protocol_type:</b> Protocol used in the connection  
3) <b>Service:</b> Destination network service used  
4) <b>Flag:</b> Status of the connection – Normal or Error 
5) <b>Src_bytes:</b> Number of data bytes transferred from source to destination in single connection  
6) <b>Dst_bytes:</b> Number of data bytes transferred from destination to source in single connection  
7) <b>Land:</b> if source and destination IP addresses and port numbers are equal then, this variable takes value 1 else 0  
8) <b>Wrong_fragment:</b> Total number of wrong fragments in this connection  
9) <b>Urgent:</b> Number of urgent packets in this connection. Urgent packets are packets with the urgent bit activated

### Attack Class : Attack Type
              
1) DoS       : Back, Land, Neptune, Pod, Smurf,Teardrop,Apache2, Udpstorm, Processtable, Worm (10) 

2) Probe     : Satan, Ipsweep, Nmap, Portsweep, Mscan, Saint  (6) 

3) R2L       : Guess_Password, Ftp_write, Imap, Phf, Multihop, Warezmaster, Warezclient, Spy, Xlock, Xsnoop, Snmpguess, Snmpgetattack, Httptunnel, Sendmail, Named (16)
 
4) U2R       : Buffer_overflow, Loadmodule, Rootkit, Perl, Sqlattack, Xterm, Ps (7) 

### ATTACK CLASS: 

1. <b>DOS:</b> Denial of service is an attack category, which depletes the victim‟s resources thereby making it unable to handle legitimate requests – e.g. syn flooding. Relevant features: “source bytes” and “percentage of packets with errors”  
2. <b>Probing:</b> Surveillance and other probing attack‟s objective is to gain information about the remote victim e.g. port scanning. Relevant features: “duration of connection” and “source bytes”  
3. <b>U2R:</b> unauthorized access to local super user (root) privileges is an attack type, by which an attacker uses a normal account to login into a victim system and tries to gain root/administrator privileges by exploiting some vulnerability in the victim e.g. buffer overflow attacks. Relevant features: “number of file creations” and “number of shell prompts invoked,” 
4. <b>R2L:</b> unauthorized access from a remote machine, the attacker intrudes into a remote machine and gains local access of the victim machine. E.g. password guessing Relevant features: Network level features – “duration of connection” and “service requested” and host level features - “number of failed login attempts” 
