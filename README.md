# Runit-Service-Helper

### Usage
```
Service Options:
	link <service>				#Enables service
	unlink <service>			#Disables service
	status <service>			#Just 'sv status'
Other Options:
	help					#Show this help then exit
	list-all				#Lists all services available (/etc/sv)
	list-linked				#Lists all service enabled (/var/service)
```

## Installation
### Clone the repo
```git clone https://github.com/adityavishwakarma69/runit-service-helper.git```
Copy rsvh to /usr/bin or any other location in $PATH
