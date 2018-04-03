---
title: "Change DNS resolver to 1.1.1.1 for Fastest Internet Browsing"
excerpt: "How to Speed Up Your Internet and Protect Your Privacy With Cloudflare's New DNS Service"
header:
 image: "https://dummyimage.com/800x400&text=1.1.1.1"
 teaser: "https://dummyimage.com/600x300&text=Fastest%20DNS"
categories:
 - security
tags:
 - Fastest DNS Resolver
 - 1.1.1.1 or 1.0.0.1
 - OpenDNS or Google DNS
 - Cloudflare DNS
 - Quad9 DNS
---
Cloudflare has launched its own consumer Domain Name System (DNS) service that not only promises to keep your browsing history safe, but appears significantly faster than any other DNS service available.

## Newest yet Fastest DNS Resolver

Cloudflare, known primarily for DDoS mitigation, launched DNS resolver 1.1.1.1 and 1.0.0.1 on Sunday and, at time of writing, analytics show it processing queries at 14.01ms, officially making it in the internet’s fastest DNS resolver.

{% include respo.html %}

## What the Benefits of Changing DNS

DNS services are an essential component of the internet, translating IP addresses into easy-to-remember names like “mi.knoacc.org.” Until yesterday, **OpenDNS was the fastest service** to do this, clocking in at around 20.6 ms per query (global average). The difference between 14 ms and 20 ms might seem negligible, but those fractions of a second add up quickly over time and your workflow will inevitably benefit.

“While being a few milliseconds faster might not seem like a big deal, since DNS is the foundation of everything online, whenever you click on a link, or send an email, or open a mobile app, almost every action you take requires as DNS lookup,” Cloudflare CEO Matthew Prince told Gizmodo. “So those milliseconds add up pretty quickly.”

Screenshot: dnsperf.com

{% include inarticle.html %}

The other true benefit here is that Cloudflare’s perspective on handling user data. Prince said the company views user data as a “toxic asset,” something it strives to either never collect or delete as quickly as possible.

“Just at a policy level, Cloudflare’s business has never been advertising or selling consumer data,” Prince said. “As we started to talk to various browser manufacturers and others about what we were doing, they would come back and say, ‘Well, we don’t want you to retain logs for any longer than a week, we don’t want you selling any of the data.’ And I think they were kind of surprised when we returned back and said, ‘Actually, we prefer never to write any personally identifiable information to disk and guarantee that we’ll wipe all of the transactional logs and bug tracking logs within 24 hours.’”

Prince said Cloudflare will also bring in an external monitor to certify that it is actually taking all of these steps to ensure user privacy.

{% include adsense1.html %}

“The FCC under Chairman Pai changed the rules in the United States for ISPs allowing ISPs to start selling your browsing history to target advertising against you,” Prince said. “I think we’ve spent enough time worrying about how Google and Facebook get all of our data. I don’t want to worry about AT&T and Time Warner and Comcast as well.”

The FCC rule change was a major setback in terms of consumer privacy. Those using the DNS services set by their ISPs can have their browsing history recorded, sold, and analyzed for advertising purposes. There are several ways to prevent this, but most involve using a VPN or the Tor browser, both of which can impact speed. There’s also no guarantee that a VPN service isn’t amassing your data itself. (If you’re looking for a reliable VPN, however, I’d suggest _Private Internet Access_ or _ProtonVPN_.)

## How To Change DNS resolver?

For non-technical users who’ve never changed their DNS settings, it may seem like one of those unfamiliar options you’d rather not mess around with. But it’s actually quite simple and takes only a few seconds—and, as you’ve read, the benefits can be significant. 

{% include adsense2.html %}

Below are instructions on how to change your DNS settings for Windows and Mac, as well as iPhone and Android devices.

### Windows

- Click on the Start menu, then click on Control Panel.
- Click on Network and Internet.Click on Change Adapter Settings.
- Right click on the Wi-Fi network you are connected to, then click Properties.
- Select Internet Protocol Version 4 (or Version 6 if desired).
- Click Properties.Write down any existing DNS server entries for future reference.Click Use The Following DNS Server Addresses.
- Replace those addresses with the 1.1.1.1 DNS addresses: 
  - For IPv4: `1.1.1.1` and `1.0.0.1`
  - For IPv6: `2606:4700:4700::1111` and `2606:4700:4700::1001`

{% include adsense1.html %}

Click OK, then Close.Restart your browser.

### MacOS

- Open System Preferences.
- Search for DNS Servers and select it from the dropdown.
- Click the + button to add a DNS Server and enter 1.1.1.1
- Click + again and enter 1.0.0.1(This is for redundancy.)
- Click Ok, then click Apply.

### iPhone

- From your iPhone’s home screen, open the Settings app.
- Tap Wi-Fi, then tap your preferred network in the list.Tap Configure DNS, then tap Manual.
- If there are any existing entries, tap the - button, and Delete next to each one.
- Tap the + Add Server button, then type 1.1.1.1
- Tap the + Add Server button again, then type 1.0.0.1. (Again, this is for redundancy.)
- Tap the Save button on the top right.

### Android

- Connect to your preferred wireless network.
- Enter your router’s gateway IP address in your browser.
- If prompted, fill in your username and password. This information may be labeled on the router.

- In your router’s configuration page, locate the DNS server settings.
- Write down any existing DNS server entries for future reference.
- Replace those addresses with the 1.1.1.1 DNS addresses: 
  - For IPv4: `1.1.1.1` and `1.0.0.1`
  - For IPv6: `2606:4700:4700::1111` and `2606:4700:4700::1001`
- Save your settings, then restart your browser.

Using a custom DNS on your Android device may require you to use a static IP address. Because of this, Cloudflare recommends changing the DNS settings on your home router instead. To do so, you’ll need to enter your router’s gateway IP, login and adjust the settings from there. If you wanted to use Cloudflare’s DNS on your home network, this would be the way to go anyway. (If you don’t know how to login to your home router, just call your ISP and ask.)

To learn more, simply type 1.1.1.1 into the URL bar of your browser or [click here](//1.1.1.1).
