# reporting_network_attack

I was given a task that I am working as a security analyst for a travel agency that advertises sales and promotions on the company’s website. The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 

One afternoon, I received an automated alert from your monitoring system indicating a problem with the web server. I attempted to visit the company’s website, but received a connection timeout error message in my browser.

I used a packet sniffer to capture data packets in transit to and from the web server. And noticed a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. I suspected the server is under attack by a malicious actor. 

I took the server offline temporarily so that the machine can recover and return to a normal operating status. I also configured the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. I knew that your IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. I needed to alert my manager about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. I would need to be prepared to tell my boss about the type of attack I discovered and how it was affecting the web server and employees.
