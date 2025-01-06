# CAPSTONE-PROJECT--DSML


## Topic-
### Intrusion Detection System Using Machine Learning with Feature Engineering and PCA for Network Security

## 1.Overview of Problem Statement:
>>>`Cybersecurity is a crucial aspect in today’s digital landscape, where preventing and identifying attacks is of paramount importance. The given dataset contains information about network traffic, and the goal is to build a machine learning model to predict whether a given traffic event is an attack or normal behavior based on its features.`

## 2.Objective:
>>>`To develop a predictive model using machine learning algorithms to classify network traffic events as either normal or malicious (attack).`

## 3.Data Description:

>>>⚫`Source: UNSW Cybersecurity dataset : https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/`

>>>⚫`Datast: https://data.world/victorpuli/useful-unsw-nb15-data`

>>>⚫`Features:`

>>>>>▶ **id** ----------Unique identifier for each record               
>>>>>▶ **dur** --------------Duration of the flow.              
>>>>>▶ **spkts** ------------Source packets in the flow.               
>>>>>▶ **dpkts** -------------Destination packets in the flow.          
>>>>>▶ **sbytes** -------------Source bytes in the flow.             
>>>>>▶ **dbytes** ---------------Destination bytes in the flow.              
>>>>>▶ **rate**  ----------------Transmission rate in bytes per second.            
>>>>>▶ **sttl**  -----------------Source-to-destination time-to-live.             
>>>>>▶ **dttl**  ----------------Destination-to-source time-to-live              
>>>>>▶ **sload** ----------------  Source bits per second.

           
>>>>>▶ **dload**  ------------- Destination bits per second.           
>>>>>▶ **sloss**  ------------- Source packet loss.           
>>>>>▶ **dloss**  ------------- Destination packet loss          
>>>>>▶ **sinpkt** ------------- Source inter-packet arrival time.        
>>>>>▶ **dinpkt** ------------- Destination inter-packet arrival time.           
>>>>>▶ **sjit**  -------------- Source jitter (variation in packet delay).            
>>>>>▶ **djit**  -------------- Destination jitter.            
>>>>>▶ **swin**  -------------- Source TCP window advertisement.              
>>>>>▶ **stcpb** -------------- Source TCP base sequence number.              
>>>>>▶ **dtcpb** -------------- Destination TCP base sequence number.             
>>>>>▶ **dwin**  -------------- Destination TCP window advertisement.               
>>>>>▶ **ackdat** --------------- Acknowledgment data.            
>>>>>▶ **smean**  --------------- Mean of the flow’s packet size from the source.

            
>>>>>▶ **dmean** --------------- Mean of the flow’s packet size from the destination.

           
>>>>>▶ **trans_depth**------------- HTTP transaction depth.

       
>>>>>▶ **response_body_len** ------------ Content size of the HTTP response.



>>>>>▶ **ct_srv_src** ---------------- Number of connections from the same source.       
>>>>>▶ **ct_state_ttl** --------------- Number of connections with the same state and time-to-live.     

>>>>>▶ **ct_dst_ltm** ----------------- Number of connections to the same destination.     
 ▶ **ct_src_dport_ltm** --------------- Number of connections from the same source IP and port.  
 ▶ **ct_dst_sport_ltm** --------------- Number of connections to the same destination IP and port.

>>>>>▶ **ct_dst_src_ltm** ----------------  Number of connections between same source-destination IP pairs.    
▶ **is_ftp_login** ----------------- Whether the FTP session is accessed by user & password.    
▶ **t_ftp_cmd**  ------------------- Number of commands in FTP session.      
▶ **ct_flw_http_mthd** -------------- Number of flows using HTTP methods.  
▶ **ct_src_ltm**   -------------- Number of connections from the same source IP.    
▶ **ct_srv_dst**  -------------- Number of connections to the same service.

      
>>>>>▶ **is_sm_ips_ports**  -------------- If source and destination IP ports are equal.       
▶ **label**   -------------- The target variable indicating whether the flow is normal or malicious.          

## 4.Data Collection:
>>>`Data has been provided and imported. Next, we gained insights into the data distribution and patterns through initial checks and will continue with further analysis.`
