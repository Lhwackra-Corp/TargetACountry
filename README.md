# How to target a whole country?

I was pentesting on a website, And as you know reconaissance is a important step in penetration testing, So as anyone would do. 
I wanted to get some subdomains, There is lot of recon processes to do so for me , always I start with ASN discovery. 
I went to https://bgp.he.net I noticed the ASN number of my ISP, So I clicked on it and it redirect me to another page. 
A big list of CIDR's popped up, So I fired up MassDns and I gave it the list of those CIDR's and it started to grab IP addresses and I was able to grab all the online machines of 4 CIDR's (It will take a lot of time, and I don't have that time) included in thoes IP addresses some of them are not secure. 
With this process you can actually target a whole country's network infrastructure which is actually dangerous.

![alt text](https://i.imgur.com/h37siEA.png)

# How can it be used?

- You can scan for a specific vulnerable service.
- You can face non password security cameras, smart home devices, etc..
- It may used to spread malwares

# NOTE

I know that alot of people that already know it, I just want to write about it, because I find it interesting.

Good luck and stay safe (even if no one is safe).

# RESOURCES:

- https://www.cloudflare.com/learning/network-layer/what-is-an-autonomous-system/
