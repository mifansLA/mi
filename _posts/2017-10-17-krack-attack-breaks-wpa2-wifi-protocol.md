---
title: "Beware! KRACK Attack Breaks WPA2 WiFi Protocol"
excerpt: "This KRACK Attack allowing hackers to decrypt and potentially look at everything people are doing online."
last_modified: "2017-10-21"
header:
 ovelay_image: "https://www.kitguru.net/wp-content/uploads/2017/10/Krack.jpg"
 caption: "krack attack wpa2"
category:
 - security
tags:
 - krack attack
 - wpa2 vulnerabilty
 - wi-fi security
 - miui beta fix krack
---
> **Update!** MIUI 7.10.19 Beta ROM has fixed KRACK : [Detailed Changelog and Download](https://mi.knoacc.org/download-miui-9-global-beta-71019-fastboot-recovery)

It's time to get patching again. Another widespread vulnerability affecting practically everyone and everything that uses Wi-Fi was revealed on Monday, allowing hackers to decrypt and potentially look at everything people are doing online.

Researcher Mathy Vanhoef, from Belgian university KU Leuven, released information on his hack, dubbing it KRACK, for Key Re-installation Attack. Vanhoef's description of the bug on [his KRACK website](https://www.krackattacks.com/) is startling:

> "We discovered serious weaknesses in WPA2, a protocol that secures all modern protected Wi-Fi networks. An attacker within range of a victim can exploit these weaknesses using key re-installation attacks (KRACKs). Concretely, attackers can use this novel attack technique to read information that was previously assumed to be safely encrypted. This can be abused to steal sensitive information such as credit card numbers, passwords, chat messages, emails, photos, and so on. The attack works against all modern protected Wi-Fi networks. Depending on the network configuration, it is also possible to inject and manipulate data. For example, an attacker might be able to inject ransomware or other malware into websites."

What's behind the vulnerability? It affects a core encryption protocol, Wi-Fi Protected Access 2 (WPA2), relied on by most Wi-Fi users to keep their web use hidden and secret from others. More specifically, the KRACK attack sees a hacker trick a victim into reinstalling an already-in-use key. Every key should be unique and not reusable, but a flaw in WPA2 means a hacker can tweak and replay the "handshakes" carried out between Wi-Fi routers and devices connecting to them; during those handshakes, encryption keys made up of algorithmically-generated, one-time-use random numbers are created. It turns out that in WPA2, it's possible for an attacker to manipulate the handshakes so that the keys can be reused and messages silently intercepted.

### Demonstration 

The researchers, who said the attack was particularly severe for Android and Linux users, showed how devastating an attack could be in the demonstration video below:

<!-- 4:3 aspect ratio -->
<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/Oh4WURZoR98"></iframe>
</div>

The attacks on Google's Android are made simpler by a coding error, where an attacker will know the key just by forcing a reinstallation. That's because the operating system uses what's known as an "all-zero encryption key" when the reinstallation is initiated, which is easier to intercept and use maliciously.

As for how widespread the issue was, it appears almost any device that uses Wi-Fi is affected. "The weaknesses are in the Wi-Fi standard itself, and not in individual products or implementations. Therefore, any correct implementation of WPA2 is likely affected. To prevent the attack, users must update affected products as soon as security updates become available. Note that if your device supports Wi-Fi, it is most likely affected. During our initial research, we discovered ourselves that Android, Linux, Apple, Windows, OpenBSD, MediaTek, Linksys, and others are all affected by some variant of the attacks," explained Vanhoef.

### What To Do? Know More!

For that reason, users may want to be wary of using Wi-Fi at all until patches are widely rolled out. For now, it looks as if some manufacturers are pushing out updates, which should go some way to preventing attacks.

Users should keep using encrypted Wi-Fi wherever necessary, such as at home and at work. However, you might want to avoid using the Wi-Fi networks, even password-protected ones, in coffeeshops, hotels, airports and other public places for the time being. Use cellular data or a VPN service instead.

Fortunately, many Wi-Fi router and client-device makers have already or are about to issue patches -- a list of vendors that have already issued patches is at https://www.kb.cert.org/vuls/id/228519 -- so users should update their routers, smartphones and laptops as soon as possible.

Note that devices such as laptops and smartphones will require updates as well as routers. Indeed, Vanhoef said it's more urgent for general users to patch their personal devices, whether phones, PCs or any smart device, be they watches, TVs or even cars. He recommended users get in touch with the relevant vendors to find out when patches are coming.
Given the range of devices affected, it's almost guaranteed patches won't make it to everyone. The US Computer Emergency Response Team (CERT) has [released an advisory](http://www.kb.cert.org/vuls/id/228519), which notes a number of affected vendors, including Cisco, Intel and Samsung, amongst many other major tech providers.

A Google spokesperson wrote in an email to Forbes: "We're aware of the issue, and we will be patching any affected devices in the coming weeks."

**Microsoft** confirmed it had rolled patches out already: "We have released a security update to address this issue. Customers who apply the update, or have automatic updates enabled, will be protected."

**Cisco** also said it had published a [security advisory](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-20171016-wpa) to detail which products are affected, and a blog to help customers better understand the issue. "Fixes are already available for select Cisco products, and we will continue publishing additional software fixes for affected products as they become available," a spokesperson said.

**Intel** confirmed it was "working with its customers and equipment manufacturers to implement and validate firmware and software updates that address the vulnerability." It also released an [advisory](https://security-center.intel.com/advisory.aspx?intelid=INTEL-SA-00101&languageid=en-fr)

### Some Good News and Measures to Protect

There's some good news: truly remote attacks won't be possible with this hack alone. In the most likely attack scenario, the hacker would have to directly connect to the Wi-Fi access point, and so would need to be within physical proximity to the device (possibly up to a few hundred feet away depending on whether they had access to antennas to extend their reach).

"This is the sort of flaw that the security community dreads: it is not about a single vendor having messed up a particular implementation but rather a fundamental flaw in the way the protocol was specified. Even those that have implemented the standard correctly will have baked in this flaw."

For those users whose routers, PCs and smartphones don't yet have updates, there are some measures they can take to protect their online privacy. **A Virtual Private Network (VPN) software could protect them**, as it will encrypt all traffic. Only using HTTPS encrypted websites should also benefit the user, though there are exploits that can remove those protections. Changing the Wi-Fi password won't prevent attacks, but it's advisable once the router has been updated.

### Question & Answer

1. **Do we now need WPA3?** No, luckily implementations can be patched in a backwards-compatible manner. This means a patched client can still communicate with an unpatched access point, and vice versa. In other words, a patched client or access points sends exactly the same handshake messages as before, and at exactly the same moments in time. However, the security updates will assure a key is only installed once, preventing our attacks. So again, update all your devices once security updates are available.
2. **Should I change my Wi-Fi password?** Changing the password of your Wi-Fi network does not prevent (or mitigate) the attack. So you do not have to update the password of your Wi-Fi network. Instead, you should make sure all your devices are updated, and you should also update the firmware of your router. After updating your router, you can optionally change the Wi-Fi password as an extra precaution.
3. **I'm using WPA2 with only AES. That's also vulnerable?** Yes, that network configuration is also vulnerable. The attack works against both WPA1 and WPA2, against personal and enterprise networks, and against any cipher suite being used (WPA-TKIP, AES-CCMP, and GCMP). So everyone should update their devices to prevent the attack!
4. **Is my device vulnerable?** Probably. Any device that uses Wi-Fi is likely vulnerable. Contact your vendor for more information.

Source: https://www.forbes.com, https://www.krackattacks.com
