# Network-Intrusion-Detection-System Web-App

## DATASET:

This data is NSL-KDD data set, which is widely used as one of the few publicly available data sets for network-based anomaly detection systems.  

## BASIC FEATURES OF EACH NETWORK CONNECTION VECTOR:

1) **Duration:** Length of time duration of the connection  
2) **Protocol_type:** Protocol used in the connection  
3) **Service:** Destination network service used  
4) **Flag:** Status of the connection – Normal or Error  
5) **Src_bytes:** Number of data bytes transferred from source to destination in a single connection  
6) **Dst_bytes:** Number of data bytes transferred from destination to source in a single connection  
7) **Land:** If source and destination IP addresses and port numbers are equal, this variable takes value 1; else 0  
8) **Wrong_fragment:** Total number of wrong fragments in this connection  
9) **Urgent:** Number of urgent packets in this connection. Urgent packets are packets with the urgent bit activated  

## Attack Class : Attack Type

1) **DoS:** Back, Land, Neptune, Pod, Smurf, Teardrop, Apache2, Udpstorm, Processtable, Worm (10)  
2) **Probe:** Satan, Ipsweep, Nmap, Portsweep, Mscan, Saint (6)  
3) **R2L:** Guess_Password, Ftp_write, Imap, Phf, Multihop, Warezmaster, Warezclient, Spy, Xlock, Xsnoop, Snmpguess, Snmpgetattack, Httptunnel, Sendmail, Named (16)  
4) **U2R:** Buffer_overflow, Loadmodule, Rootkit, Perl, Sqlattack, Xterm, Ps (7)  

## ATTACK CLASS:

1. **DoS:** Denial of service is an attack category, which depletes the victim’s resources thereby making it unable to handle legitimate requests – e.g., syn flooding. Relevant features: “source bytes” and “percentage of packets with errors”  
2. **Probing:** Surveillance and other probing attacks aim to gain information about the remote victim, e.g., port scanning. Relevant features: “duration of connection” and “source bytes”  
3. **U2R:** Unauthorized access to local superuser (root) privileges. The attacker uses a normal account to log in to a victim system and tries to gain root/administrator privileges by exploiting some vulnerability in the victim, e.g., buffer overflow attacks. Relevant features: “number of file creations” and “number of shell prompts invoked”  
4. **R2L:** Unauthorized access from a remote machine. The attacker intrudes into a remote machine and gains local access to the victim machine, e.g., password guessing. Relevant features: Network-level features – “duration of connection” and “service requested” and host-level features - “number of failed login attempts”  

---

# Pest Detection System

## Team Details:

1. **Macharla Bala rangarao**  
2. **B.V.S.Rama krishna**  
3. **B.V.Srinivasulu**  


## Dataset:

**[NSL-KDD Dataset on Kaggle](https://www.kaggle.com/datasets/hassan06/nslkdd?resource=download)**

## Deployment:

**[Deployment Link - Coming Soon]**
