---
title: (Temporarly) Living in a IPv6 only world
date: "2019-12-11T00:00:00Z"
type: "blog"
---

On the evening of 2nd December, I have noticed something funny - only half of
the internet was working. The other half? Disappeared off the planet. 

<!--more-->

Google - works, Github - gone. My website - empty as always, but here, Slack
- nope. Work VPN - unsuccessful DNS. So thinks were bad, but not horrible.

So what was happening? Quick `ip addr` showed me one thing - no IPv4 addresses
were assigned locally, checked on whatsmyip.com and I was greeted with
`Your IPv4 is: Not Detected`. Our ISP is Virgin Media, and they provide dual
stack to homes now - IPv6 being primary, with IPv4 for fallback. I am quite
happy about it. Loads of cheap VPS providers will give you IPv6 for free, with
IPv4 being available for an extra fee. But you still have that IPv4 just in
case someone refuses to move to the newer standard.

So how is the experience? Good and bad. Wide range of sites down work, but at
least you can see who cares about being a good internet citizen and supporting
latest standards. People at the time of the incident complained about Virgin
Media breaking the internet for them, and while this is correct, it is also up
to websites to add IPv6 functionality, because in most cases its not hard, just
slap a CDN like [Cloudflare] and you are done. The ironic thing is that the
Virgin Media site itself is IPv4 only, making their status page useless.

In the end it turns out it was a bad device on the network. I am not a
networking expert, but it looks like a new switch was reporting that a device
connected to the switch was assigned all IP addresses. Unplugging and plugging
it back in solved the problem. I was suprised however that a single device
would kill IPv4 connectivity, and somehow it was not translated back to IPv4
by the router. I might however just show that I have massive gaps in how this
whole thing works and I need to read up on it more.

__My conclusion: Highly recommended__ (that everybody should switch to IPv6)

[Cloudflare]: https://www.cloudflare.com
