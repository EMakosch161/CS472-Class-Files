# Assignment 1 - History of the Internet
- Eric Makosch / erm327

# Part 1

| Problem | Solution Proposed / Unaddressed | How we see this today |
| --- | --- | --- |
| How is mobile hotspot able to send packets although the connection is much slower | Flow control: The receiver limits how much data is sent at one time. Slower connections won't get overwhlemed. | When I provide phone hotspot to my laptop, websites still load slowly compared to normal wifi |
| How is data sent from from one network to multiple different networks. | Gateway routing: sends packets through gatewats so they can mvoe between different network | I am able to message someone while I am on cellular when someone at home is still on the wifi. |
| Why can't the protocols automatically dismiss malicious received packets | Not addressed: Security was not primary concern over efficient packet sending and recevial methods. | I see websites or emails that are marked as suspicious, but files can unintentionally be downloaded / installed with no checks without 3rd party blockers. |
| How can apps like tiktok support millions watching a livestream but thousands of people doing something like going to a website sneaker drop crash the website? | Not addressed: It only mentions the idea of congestion rather than millions of user access in the same place. | I have seen big social media applications be able to host live streams consisting of a few million virtual audience members with no latency on either end. |
| How can high-action video games support a large player base all at once? | Sequencing + Fragmentation: The packets are kept in order and missing data is resent when called for | When playing video games, the amount of data being sent back and forth is all hidden, but you can see some details when lag or rubber-banding occurs. |
| How do messages sometimes deliver smaller sized messages compared to larger sized messages like photos | Segmentation: Large message broken into smaller pieces so they can be handled efficiently | When I send my family an image along with a short follow up message, sometimes I see the small follow-up deliver before the image itself. |
| How are continous 'typing' indications get sent as at the '...' bubble in imessages or discord? | Process-to-process communication: applications can send small and/or continous messages. | Most messaging platforms I use, I can see continous typing indications until the message is sent or they delete their entire message. |

# Part 2
- a) I am investigating why social media applications can support livestreams of so many audience members while sites that host events like sneaker drops typically crash. This is row 4 (excluding title row). Specifically, this question highlights the differences of how website traffic is handled different than livestream traffic. 
- b) Questions:
    - How can so much live internet traffic be handled so efficiently with a few million audience members on a platform such as tiktok livestream?
    - How does this compare to a public website event like a sneaker drop where only thousands of people join in, yet the website crashes?
    - If the edge servers for livestreams start to become overloaded, does this effect the streamer or only the viewers? How do the copies of the livestreams being created not overload the system/servers themselves?
    - How did the idea of CDNs develop from the concepts discussed in the 1974 Cerf-Kahn?
- c) 
    - Ideas from the paper that were developed into the modern solution of being able to stream videos to millions of viewers stemmed from the concept of packet-switching networks through gateways which used processes such as sequencing, flow control, and addressing. This gave a foundation to support large quantity communication by allowing livestream data to travel across different networks and reach viewers watching from anywhere in the world. The change made was the creation of CDNs: expanding the idea of one main server into the capability of distributing cached copies through servers closer to viewers location. The creation of CDNs gives the original server an easier workload and allows it to work efficiently. Although the ideas for networking was expanded on and left out of the paper, their concepts is what eventually gave applications and networks the ability for streamers and millions of viewers to watch. 
- d) 
    - My assumption was that the tech companies that build applications like youtube and tiktok were able to pour enough funding into the strongest network systems that allowed streams to be hosted on one server. This led to my knowledge of CRNs and how they work within this system. I also knew nothing about the cached copy distribution process, as I always assumed that live streams that I watched included every viewer's comments / likes being shown at once, rather than just people interacting to the same cached copy as me. To relate to the shoe-drop scenario, I never understood the full complexity of how many requests are going through when someone simply refreshes along with many users trying to compete. 

# Part 3
- I think that the interesting concept I learned from the paper would be how different network speeds are managed and network overload handling. This is because of how relevant it is today when websites, livestreams, and apps are getting more and more popular, which requires strong nework support. The AI investigation opened my eyes to concepts I never heard about such as how CDNs use a distribution process through many servers so every viewer can watch. The shocking part of my investigation was that the problem does not rely in site events like shoe-drops having weaker servers, it is that the purchase process needs to be on one server and that many websites cannot support that much traffic and requests. My understanding shifted as I read about how different the process is for livestreaming apps that use CRNs and many different servers. This process showed me how the paper paved the way for modern problems and solution within network traffic and distribution. 

    
