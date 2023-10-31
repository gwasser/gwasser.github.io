---
title: 'The GPL Is About User Freedom, Not Developers'
date: 2016-06-19
permalink: /posts/2016/06/gpl-about-user-freedom-not-developers/
tags:
  - free software
---

Recently, in online communities and forums, and even professional organizations like ACM, I've been seeing an argument that the GNU General Public License (GPL) is restrictive, while more liberal licenses like the BSD and MIT licenses are "more free". A [recent column][1] in April 2016's Communications of the ACM repeated this obviously misunderstood statement with a pretty aggressive attack on the GPL.

The GNU GPL is somewhat restrictive, true. However, before anyone goes jumping the gun to call it "less free", consider _what_ the GPL is restricting. The GPL's rules are entirely directed at redistributors, not users of the software. In other words, as a developer or a user, you can do anything you want with the software _in private_. Hack on it, use it for business, whatever. Even when you do redistribute the software, you are not prevented from doing things like commercializing the software (in fact, the GPL encourages you to sell your work!), so long as the end user that receives your software has the same _user_ privileges under the GPL that you do. Anyone that buys the software must also receive the rights and freedoms to run and hack at your code under the GPL. In this sense, GPL code will stay GPL code forever.

When considered this way, the divide over "which license is more free" is easily seen as a difference of philosophies. The debate seems to be over a misunderstanding (or, perhaps, miscommunication) of _who_'s freedoms are at stake.

The BSD and MIT licenses (and other more "liberal" licenses) put _developers_' rights and freedoms first. Developers can do pretty much anything with code under these licenses that they wish, including tucking it away into a proprietary product so that future users cannot change or modify the code -- all that's required is typically an acknowledgment. There is a certain sense why this seems fair; developers, especially ones that contributed to the code, should be allowed to use the code that includes their own contributions for whatever project they want. If a developer forks the code and puts time and effort into extending it, and they want to make the updated code from their effort proprietary, why not? And sometimes this is even what you want; for example, [this article][2] describes how the BSD license might be better suited for reference implementations of protocols to encourage standardization among all code bases even the proprietary ones.

The GNU GPL and other "copyleft" licenses however put _users_' rights and freedoms first. Developers are free to use the code for their own projects, so long as they do not take away a _user_'s right to study, modify, and redistribute that code under the GPL. Developers are not allowed to close off the software from users. You can't tuck GPL code into a proprietary program with a simple acknowledgment; the license requires you must also provide source code for the whole program to your users if you make use of any GPL code. It's a clever "hack" on the copyright laws to ensure that the users' rights to the code persist even long after the developer has retired or gone out of business; a bad actor cannot legally fork GPL code and stop you from studying or modifying that code fork. We slightly restrict _redistribution_ rights, in favor of ensuring _more freedoms for the user_.

I personally prefer the GPL over BSD-style licenses; I want to ensure software I write remains in the community, by legal force if necessary rather than a (possibly naive) hope for continued goodwill from proprietary interests. However, I can see in some scenarios the usefulness of BSD particularly within our current market and legal framework. For example, BSD-licensed standards development makes a lot of sense. Ideally, the software will be free software under the GPL from the beginning, but at a minimum if the proprietary software at least uses an open source standard, that enables interoperability between proprietary implementations, reducing "lock in" for users, and allows compatible GPL-licensed free software to be developed and used -- ultimately giving users more options and, well, freedom.

I hope you will join me in considering and supporting copyleft licenses like the GPL for your own projects whenever possible. If you disagree, that's fine; we have different philosophies. In some scenarios like standards development, BSD or similar makes sense to try to nudge companies toward prioritizing user freedom by enabling interoperability. But please do not continue the falsehood that the GPL is "less free" than other licenses; the licenses have different priorities... and maybe that's OK.

*Author's Note: This is a slightly edited update of a blog post initially posted to Blogger in 2016-06-19.*

[1]: http://cacm.acm.org/magazines/2016/4/200171-gnl-is-not-linux/abstract
[2]: https://www.freebsd.org/doc/en/articles/bsdl-gpl/article.html#bsd-advantages
