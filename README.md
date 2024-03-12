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

## Pen Test Tools Categories:

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:

![1](https://github.com/Prakashmathi2004/InformationGathering/assets/118350045/adf985c7-413a-4abc-8640-b7b23eb0c784)


## Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```ping saveetha.ac.in```

## output:

![2](https://github.com/Prakashmathi2004/InformationGathering/assets/118350045/723e6daf-c4ef-421f-8517-f1aa85261af6)


## Finding Hosting Company:

get further detail by using ip2location.com website.

## output:

![3](https://github.com/Prakashmathi2004/InformationGathering/assets/118350045/6fd782e3-6b40-4344-918e-583eab7de0dd)


## History of the website:

## Output:

![4](https://github.com/Prakashmathi2004/InformationGathering/assets/118350045/a146f239-fac2-4d2c-b3a6-1b54072b0816)

## Webserver Fingerprinting:

## Netcat:

```nc 172.17.52.118 80```

## OUTPUT:

![5](https://github.com/Prakashmathi2004/InformationGathering/assets/118350045/c98a3638-894f-4327-9320-9ae6766d8255)


## nmap:

```nmap -p 21 -sV --script=banner ftp.vim.org```

## OUTPUT:

![6](https://github.com/Prakashmathi2004/InformationGathering/assets/118350045/144d737c-4f5e-4140-8ce5-6dfdb8a98585)


## Whatweb:

```whatweb infosys.com```

```whatweb zoho.com```

```whatweb -v -a 3 172.17.52.201```

## OUTPUT:

![7](https://github.com/Prakashmathi2004/InformationGathering/assets/118350045/b9f24218-4d42-4710-91a2-330fe6831ecc)


## httprint:

```httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more```

## OUTPUT:

![8](https://github.com/Prakashmathi2004/InformationGathering/assets/118350045/95147e07-2f9e-4f66-accb-71306b2fab4a)


## Tracing the Location

## TCP Traceroute:

```sudo traceroute -T www.saveetha.ac.in```

## OUTPUT:

![9](https://github.com/Prakashmathi2004/InformationGathering/assets/118350045/edde51d0-c7da-4dc0-bc7d-de5301e6e6e0)

## UDP Traceroute:

```sudo traceroute -U www.saveetha.ac.in```

## OUTPUT:

![10](https://github.com/Prakashmathi2004/InformationGathering/assets/118350045/7feddd28-0024-4abd-9f17-b040951aa16d)



## ICMP Traceroute:

```sudo traceroute  www.saveetha.ac.in```

## OUTPUT:

![11](https://github.com/Prakashmathi2004/InformationGathering/assets/118350045/8c5dbaca-1bf1-48cc-b984-61aee13d4d48)



## RESULT:

The information gathering techniques tools/procedure were  identified successfully
