---
title: 'No Longer On LinkedIn: A Cautionary Tale'
date: 2026-05-31
permalink: /posts/2026/05/no-longer-on-linkedin-a-cautionary-tale/
tags:
  - cybersecurity
---

If you've seen me on LinkedIn since about early May 2026, it wasn't actually me. My account was taken over and LinkedIn hasn't been very helpful getting back in.

So main take away: Do not try to reach me on LinkedIn, or accept any invite from someone with my name on LinkedIn. It isn't me. Even if it has my resume and seems legit. It's not me behind the keyboard.

I managed to learn what happened before being fully locked out of the account. So I'm sharing this also as a caution to others: check if you have any custom domain emails attached to accounts! And be sure you have 2FA on everything!

What happened seems to be that an attacker gained control of a business email I used to have. It was an email at a domain I owned for a business my partner and I opened years ago. It was primarily for my partner's contracting and consulting work, but since I ran the domain and website, I also added it to my LinkedIn so we could have a business page. The business was closed years ago but I kept paying for the domain for a number of years. Finally last year I decided I didn't want to renew it because I haven't used it and we're not going to reopen the business. So I let the domain expire. I forgot it was still listed on my LinkedIn account because I hadn't used it in so long.

Well, a `whois` shows an attacker bought the domain in early May 2026, and immediately must have used it to get access to the email account name. They did a lost password request, got it sent to the business domain email since it was a backup contact on my account, and used that to change my password. Once in, they removed all my other personal emails and phone number and effectively locked me out. This was surprising me to since I thought I had enabled 2FA on LinkedIn, as I have for all my other accounts. Apparently I didn't. So they were able to lock me out entirely. Quite embarrassing, honestly.

I was actually still logged in on my browser so when I got the notices about the password request, I checked my account and saw everything had been removed. I couldn't add it back because you need the new password to do so, which I didn't have, but it did let me look at the action log. Someone from an out-of-state IP (and eventually an international IP) accessed the account, changed the password via password reset to the business email, and locked me out. I took a screenshot of all this and sent it to LinkedIn support. Creating a support request must have notified the attacker because I was pretty quickly booted from the browser session afterward.

I created a new support request with my personal email notifying LinkedIn support that my account had been compromised. I didn't get a reply. I tried again. Still no reply. I tried instead to verify my identity to get my email added back to the account as a password reset, which seems to have worked as I was sent a password reset link, but by the time I clicked it, the attacker must have seen the notice too because the password link was already expired and wouldn't let me change it. Since they tried to add my email back, I guess LinkedIn's database thinks I'm still there because if I try to do a password reset, it says it will send it to my email but I never receive it. If I try to create an account it says that email is already in use. I tried another email to create an new account so I could notify support, thinking maybe they'd ban the old account in favor of a new account if I first verified my identity on the new account. Despite having the verified identity, after I contacted support, I got a message that they investigated my new account and found it to be impersonating someone and they were banning it to protect my identity of the original profile. Sigh. Ironically, in my case, their policy is protecting the attacker-controlled impersonation and not the actual person! There doesn't seem to be an easy way to get through to someone that understands the situation. I also understand it shouldn't be that easy or it will be abused. It's moreso my fault for not having 2FA. Thankfully, my LinkedIn wasn't actually connected to any business access or anything important, just spam messages. I just don't know if the attacker has tried to use it to impersonate me to send spam or anything. A brief search online suggests attackers mostly try to takeover LinkedIn accounts to leapfrog into more business access, so they didn't get anything from me. Ha-ha.

I'll keep trying to get control of the original LinkedIn account back, but when I do, I suspect I'll simply deactivate the account. LinkedIn hasn't been very useful in some time. It seems to have become AI slop feed of influencers more than actual professional connections.

Contact me via personal email or other sites like GitLab instead.
