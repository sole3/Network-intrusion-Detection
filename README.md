# Classification project
Data science Project one of core element of T5 Boot camp from SDAIA Academy
## Network-ntrusion-Detection
<p align="center" width="100%">
<img src="https://reciprocity.com/wp-content/uploads/2021/06/resource_advanced-persistent-threat-cybersecurity_featured-img_730x270.jpg"/>
</p>

# Problem Statement

The dataset to be audited was provided which consists of a wide variety of intrusions simulated in a military network environment. It created an environment to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. The LAN was focused like a real environment and blasted with multiple attacks. A connection is a sequence of TCP packets starting and ending at some time duration between which data flows to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labelled as either normal or as an attack with exactly one specific attack type. Each connection record consists of about 100 bytes.
For each TCP/IP connection, 41 quantitative and qualitative features are obtained from normal and attack data (3 qualitative and 38 quantitative features) .The class variable has two categories:
- Normal
- Anomalous

# Dataset
 This dataset can be found at [Kaggle](https://www.kaggle.com/sampadab17/network-intrusion-detection).
There is 22545 rows and 42 columns.

# Data Description

 - protocol_type: 
 Protocol used
 - service:
 Service used by destination network
 - flag:
 Status of the connection (Error or Normal)
 - src_bytes:
 Number of data bytes transferred from source to destination
 - dst_bytes:
 Number of data bytes transferred from destination to sourceland**
 - land:
 If source and destination port no. and IP addresses are same thenit will set as 1 otherwise 0
 - wrong_fragment:
 otal number of wrong fragments in a connection
 - urgent:  
 Number of urgent packets (these packets with urgent bit acti-vated)
 - hot:
 Number of ’hot’ indicators means entering in a system directory
 - num_failed_logins:
 Number of failed login attempts
 - logged_in:
 Shows login status (1- successful login, 0- otherwise)
 - num_compromised:
 Number of compromised conditions
 - root_shell:
 Shows root shell status (1-if root shell obtained otherwise 0)
 - su_attempted:
 Set as 1 if ’suroot’ command used otherwise set as 0
 - num_root:
 Number of operations performed as root
 - num_file_creations:
 Number of file creation operations
 - num_shells:
 Number of shell prompts in a connection 
 - num_access_files:
 Number of operations on access control files
 - num_outbound_cmds:
 Number of outbound commands in a ftp session
 - is_host_login:  
 If login as root or admin then this set as 1 otherwise 0
 - is_guest_login:
 Set as 1 if login as guest otherwise 0
 - count:
 Number of connections to the same destination hos
 - srv_count:
 Number of connection to the same service (port number
 - serror_rate:
 Percentage of connections that have activated flag (#4) s0,s1,s2or s3, among the connections aggregated in count (#23)
 - srv_serror_rate: 
 Percentage of connection that have activated flag (#4) s0,s1,s2 ors3, among the connections aggregated in srvcount (#24)
 - rerror_rate:
 Percentage of connections that have activated flag (#4) REJ,among the connections aggregated in count (#23)
 - srv_rerror_rate:   
 Percentage of connections that have activated flag (#4) REJ,among the connections aggregated in srvcount (#24
 - same_srv_rate:
 Percentage of connections that were to the same services, amongthe connections aggregated in count (#23)
 - diff_srv_rate :
 Percentage of connections that were to the different services,among the connections aggregated in count (#23)
 - srv_diff_host_rate:
 Percentage of connections that were to different destination ma-chines among the connections aggregated in srvcount (#24)
 - dst_host_count:
 Number of connections having the same destination host IP ad-dress
 - dst_host_srv_count:
 Number of connections having same port number 
 - dst_host_same_srv_rate:
 Percentage of connections that were to the same service amongthe connections aggregated in dsthostcount (#32
 - dst_host_diff_srv_rate:
 Percentage of connections that were to different service amongthe connections aggregated in dsthostcount (#32
 - dst_host_same_src_port_rate:
 Percentage of connections that were to the same source portamong the connections aggregated in dsthostsrvcount (#33)
 - dst_host_srv_diff_host_rate:
 Percentage of connections that were to different service amongthe connections aggregated in dsthostcount (#32
 - dst_host_serror_rate:
 Percentage of connections that have activated flag (#4) s0,s1,s2or s3, among the connections aggregated in dsthostcount (#32
 - dst_host_srv_serror_rate:
 Percentage of connections that have activated flag (#4) s0,s1,s2or s3, among the connections aggregated in dsthostsrvcount(#33
 - dst_host_rerror_rate:
 Percentage of connections that have activated flag (#4) REJ,among the connections aggregated in dsthostcount (#32
 - dst_host_srv_rerror_rate:
 Percentage of connections that have activated flag (#4) REJ,among the connections aggregated in dsthostsrvcount (#32)
 - class:
 Attack class label
## Tools
There are tools that will be used to achieve the goal of this study, such as: 
- Numpy
- Pandas
- Matplotlib
- Seaborn
- math
- sklearn.preprocessing
- sklearn.model_selection
- LinearRegression
- DecisionTreeRegressor
-  mean_squared_error
The work will be done through Jupyter notebook.

## GOALS
- What is the most Service used by destination network ?
- Are activities normal or anomaly ?
- How many flag based on service?


## Authors 
- [@elaftalal](https://github.com/elaftalal)
- [@MuniraAlzhrani](https://github.com/MuniraAlzhrani)
- [@sole3](https://github.com/sole3)
