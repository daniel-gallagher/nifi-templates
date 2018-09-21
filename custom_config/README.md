# Custom Configurations
Example of a custom configuration and notes on how to get NiFi running.

# Lines Changed
* Core Properties

17 - Change to external folder

19 - Change to external folder

30 - Change to external folder

31 - Change to external folder

32 - Change to external folder

34 - Speed up dashboard refresh rate

36 - Add this line and point to external folder


* State Management
43 - Change to external folder
49 - Set true if clustering
51 - Change to external folder


* H2 Settings
55 - Change to external folder


* FlowFile Repository
60 - Change to external folder


* Content Repository
76 - Change to external folder


* Persistent Provenance Repository Properties
92 - Change to external folder


* Site to Site Properties
125 - FQDN for the node you are configuring
126 - Set true if using SSL
127 - Set port


* Web Properties
134 - "NO SSL" FQDN for the node you are configuring
135 - "NO SSL" Web dashboard port
137 - "WITH SSL" FQDN for the node you are configuring
138 - "WITH SSL" Web dashboard port


* Security Properties
146 - Set sensitive props key
152 - Change to external folder
153 - Set keystore type
154 - Set keystore password
155 - Set key password
156 - Change to external folder
157 - Set truststore type
158 - Set truststore password
161 - Set if using LDAP integration


* Cluster Common Properties
191 - Set true if both clustering and using SSL


* Cluster Node Properties
194 - Set true if clustering
195 - FQDN for the node you are configuring
196 - Set port


* Zookeeper Properties
208 - ZooKeeper string containing FQDN and port for each node in cluster
