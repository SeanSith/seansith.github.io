---
layout: single
title:  "What to Know About: KRACK"
date:   2017-10-16 23:03:38 -0500
categories: blog
excerpt: "A recently announced vulnerability with Wi-Fi security has people wondering what to do. Here's how KRACK affects you."
---
Earlier today, a disclosure embargo was lifted on a vulnerability that affects almost every Wi-Fi installation in the world. [KRACK](https://www.krackattacks.com/) is a key reinstallation attack which allows encrypted traffic between your devices and your router to be decrypted by someone within range of you and your access point/router. While this is a very serious vulnerability (and you should patch your equipment when you are prompted), it's not the end of the world.

# Highlights

- Patching your wireless clients (e.g. phones, tablets, computers, etc.) is key.
- Routers are mostly unaffected unless they are used in mesh networking or range extension setups.
- As of 17 October 2017, Windows OSs are known to be patched assuming you've applied the October updates. Other OSs are coming.
- Sites where you are protected with HTTPS are no less secure than if you were directly wired to your network, and help keep you reasonably safe during this time.

# A Quick History

When Wi-Fi networks first sprung up, it was noted that encryption of the data across the wireless link was necessary. So, in 1997, the ["Wired Equivalent Privacy"](https://en.wikipedia.org/wiki/Wired_Equivalent_Privacy) (WEP) standard was born. Then, in 2005, the FBI showed how easily it could be circumvented in about 3 minutes with standard computer hardware. Fortunately, ["Wi-Fi Protected Access"](https://en.wikipedia.org/wiki/Wi-Fi_Protected_Access) had been introduced in 2001 and had started replacing default WEP configurations. Sadly, WPA was broken in 2010, but WPA2 had come to save the day -- or so we thought.

# How Does this Affect Me?

To be honest, I don't have a simple way of explaining the current attack that really matters. Let's just lead with how I would evaluate your risk. First, if you're famous, infamous, or you really do have people who are technologically savvy and are after you, this article isn't for you. Contact me and we can discuss options further. If you live in a population-dense area, the chances of someone sitting within range of your Wi-Fi network are higher. The attack assumes that the attacker is targeting you or has an immense amount of time on their hands. If you live in a less dense area (i.e. suburbs or rural), it's likely you'll notice an attacker sitting in a car outside your house before this becomes a problem.

Good news, though! Most of the important sites you go to on a regular basis have likely adopted HTTPS to secure your traffic. While HTTPS isn't infallible, in situations like this, it will help to keep your traffic private, even on a compromised network. The adage "you don't have to be faster than the bear, you have to be faster than the other guy" applies here. Unless you're being specifically targeted, most attackers will likely get bored faster. With that said, you should never ignore any HTTPS errors in your browser, as it could be indicative of someone attempting to decrypt your traffic (a man-in-the-middle attack).

# What Should I Do?

All discussions of computer security come down to one thing: patch your system with the latest updates. If anyone tells you anything different, they likely know nothing of which they speak. This is primarily a client-side attack, so your computers, phones, and other smart devices should be patched as soon as updates become available. At this time we know that Microsoft had quietly patched all current versions of Windows prior to the announcement. Apple is currently (as of 2017-10-18 @ 12:06am EDT) testing updated macOS, iOS, tvOS, and watchOS software, and a release is imminent. As for patching Android: my best wishes go with you. Google will certainly release updated versions of Android for consumption, but whether or not your wireless provider allows them is unknown.

Should you patch your router? If it's still supported by the manufacturer, absolutely. If not, it's up to you: likely you may find that you'd benefit from a newer, faster router anyway, but there's no reason to believe that it's going to be patched at this time either.

If you have a slightly more complicated wireless setup where you're using range extenders or an older router/access point to extend coverage from one side of the house to the other, you should absolutely look for updated firmware. Please check with your manufacturer's support page immediately.

# Moving On

My hope is that this high-level article will help to assuage any fears you have about this most recent attack. It's starting to get noticed by news agencies and Facebook. As always, if you have any questions, you can reach me by one of the methods linked here on my blog.

Best wishes!