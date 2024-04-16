# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## OUTPUT:
## WHOIS
![Screenshot 2024-04-16 085452](https://github.com/dhinesh00406/InformationGathering/assets/147149471/564699ba-9760-4d2f-b2bd-558ced34aff6)
## IP2LOCATION
![Screenshot (4)](https://github.com/dhinesh00406/InformationGathering/assets/147149471/3fe2b059-00fd-4778-94cf-5c96550e919c)
## WEB ARCHIVE
![Screenshot (3)](https://github.com/dhinesh00406/InformationGathering/assets/147149471/4720ab6e-3a34-4f44-9da8-5d5b4be0de31)
# WEB SERVER FINGERPRINTING
## Netcat:
```
nc 172.17.52.118 80
```
# OUTPUT
![1](https://github.com/Rajkiran0604/InformationGathering/assets/164345543/24f84e6f-6782-4b3b-a985-2c418c7a0868)
## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
# OUTPUT
![2](https://github.com/Rajkiran0604/InformationGathering/assets/164345543/cc41e9fd-3960-4902-8c55-173c654bd424)
## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201

```
# OUTPUT
![3](https://github.com/Rajkiran0604/InformationGathering/assets/164345543/287ba05b-6206-4340-9a81-0dbe50f4b0df)
## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
# OUTPUT
![4](https://github.com/Rajkiran0604/InformationGathering/assets/164345543/61acedb1-8109-49d9-b23e-d027b5a3edd1)
## Tracing the Location:
```
sudo traceroute -T www.saveetha.ac.in
```
# OUTPUT
![5](https://github.com/Rajkiran0604/InformationGathering/assets/164345543/161b5f9d-0a95-4e0d-9ba8-62303fcba8a3)
## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
# OUTPUT
![6](https://github.com/Rajkiran0604/InformationGathering/assets/164345543/daa6dc36-c180-44ec-b3e8-ee0b08ca0e01)
## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
# OUTPUT
![7](https://github.com/Rajkiran0604/InformationGathering/assets/164345543/0540700c-aec8-4e89-9b55-9b9dac8d8f26)



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
