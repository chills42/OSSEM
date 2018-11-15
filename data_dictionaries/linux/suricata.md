# Suricata Table

## Description

Suricata network detection

## Event Log Illustration

## Data Dictionary

|	Standard Name	|	Field Name	|	Type	|	Description	|	Sample Value	|
|	----------------	|	----------------	|	----------------	|	----------------	|	----------------	|
|	event_creation_time	|	timestamp	|	TEXT	|	event time	|		|
|	event_type	|	event_type	|	TEXT	|	Directory of file(s)	|		|
|	src_ip	|	src_ip	|	TEXT	|	Source ip address	|		|
|	src_port	|	src_port	|	INTEGER	|	Source ip port	|		|
|	dst_ip	|	dest_ip	|	TEXT	|	Destination ip address	|		|
|	dst_port	|	dest_port	|	INTEGER	|	Destination ip port	|		|
|	ip_proto	|	proto	|	TEXT	|	IP Protocol	|		|
|      | alert | OBJECT | an object described below | |


### Alert section

|	Standard Name	|	Field Name	|	Type	|	Description	|	Sample Value	|
|	----------------	|	----------------	|	----------------	|	----------------	|	----------------	|
|	alert_action	|	action	|	TEXT	|	The action taken by the tool |		|
