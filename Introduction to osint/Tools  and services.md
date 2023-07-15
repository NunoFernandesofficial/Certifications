
TheHarvester
	
	The harvester is a command-line info gathering tool that utilizes OSINT sources to gather info about the target domain and retreives info such as hostnames, IP Addresses, and much more.
	`**theharvester -d google.com -l 100 -b google**`


Maltego

	Maltego is a high-level data mining and info gathering tool, capable of obtaining real-time data on different types of entities, and representing them graphically through nodes, showing all the connections that the program was able to obtain over the internet, about the subject under investigation.


tweetdeck

Google Dorking
	
	Cyber security filetype:pdf
	site:Facebook.com -site:www.facebook.com (this is used for subdomain enumeation).
	inurl: admin (shows admin login pages)
	https://securitytrails.com/blog/google-hacking-techniques


Defending Against Dorks

	Geofencing and ip whitelisting:
		There are a nuber of ways we can use IP-Based controls to restrict who can access web content, such as unauthorized users or google´s crawlers.
		Geofencing is a method of blocking entire IP ranges associated with countries so that only access from a specific location will be allowed. 
		ip whitelisting works in a similar way, but instead it only allows specified IP addresses to access resources, and blocks everything else. This is great if you have a development environment or site that is present on the internet,but you don´t want anyone accessing it.

Crawler Restrictions

	A very effective method of preventing content being present on google is to block their crawlers from being able to access any of the content present on the internet. This can be achieved by creating a robots.txt file that disallows any crawlers from indexing any part of your website, preventing it from showing on googles search engine.

https://osintframework.com/

Tiny-Eye :

	Reverse image research over all the internet, this can be usefull for evaluating if a profile is fake or not.

Google images:

	Almost the same as tiny-eye we can use google images for the same purposouses.