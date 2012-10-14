Computer security for the lazy
==============================
Shit you need to worry about (in order of importance):
* losing your files
* losing your accounts
* losing your privacy

Losing your files
-----------------
All your photos of family and friends. All your financial records. All your university homework. All that porn you've been stashing. The biggest computer security threat you'll ever have to worry about is losing them. Every hard drive is a ticking time bomb, just waiting to fail. You could accidentally leave your laptop in the back of a taxi and never see it again. Recently there has been a spate of attacks where criminals will gain remote access to your computer, encrypt everything on it, and then demand ransom payment to decrypt it. However it happens the results are the same - you've lost your shit.

Thankfully preventing these problems is easy; back your shit up.

Losing your accounts
--------------------
Your email. Your internet banking. Your Facebook, Twitter and World of Warcraft character. These are all "accounts" and you can lose them. If you choose a shitty password someone can just guess or "brute force" it. If you're tricked into installing malicious software it can log every keystroke you press, recording your passwords. If you are directed to a spoofed version of a trusted website and you try to log in, you've just given the bad guys your password. If you use the same password everywhere you're truly fucked.

Unfortunately there isn't a single easy solution to these threats. The best thing is having a well calibrated "bullshit" detector. Using a password manager and keeping your computer up to date with security patches will also help. Detailed section on all this coming soon.

Losing your privacy
-------------------
Take any private photos of you and your partner? Do you write a pseudonymous blog like "[Belle de Jour](https://en.wikipedia.org/wiki/Belle_de_Jour_%28writer%29)" or at the other end of the sexual activity spectrum, "[Nice Jewish Girl](http://www.shomernegiah.blogspot.com/)"? Don't want someone going through the soppy love poems emailed to your partner? Want to complain about work to a friend over chat / IM without getting fired?

Remember that laptop you left in the back of a taxi? Someone could go through all the files on it. Browsing on an insecure wifi network could give you away to anyone within range. Depending on which country you live in, your ISP could be obliged to log your browsing history, where criminals will undoubtedly hack in and get access to it at some point.

The threat to privacy is a bit more esoteric than losing your files or accounts, because it isn't obvious when it happens. When you lose your hard drive, you know about it. When someone steals money out of your bank account, you know about it. When Facebook gathers information about the websites you visit and sells it to other companies, you're left in the dark.

I'll go through ways to keep your communication and browsing private, stay tuned.

Back your shit up
=================
Threats to your files (in order of likelihood):
* hard drive failure
* losing your laptop
* malicious attacks

You can prevent all of them by keeping proper backups. It's pretty simple:
* Use automated backup software
* Keep a copy at different places, in case your house burns down
* Encrypt your backups so other people can't pry into them

Most of this is taken care of if you use decent backup software like [Crashplan](http://www.crashplan.com/). It keeps incremental backups of your files as you work. It updates itself automatically. You can backup to external hard drives. You can backup to their servers "in the cloud" somewhere for $$$. You can backup to your friends computers over then net for free (as long as they run Crashplan). Your backups are encrypted so that only you can open them up and see the files. It's available for Linux, Mac and Windows and it's dead easy to setup. In a word it is brilliant, stop reading this and start downloading it.

I'm not going to write an in depth guide to get it up and running, I'll let Crashplan's tech support help you with that. The only thing I will add is that you should definitely secure your Crashplan encryption key with a private password, not just leave it at the default settings. With the default settings the friendly staff at Crashplan HQ could have a lot of fun digging through your backups to see those photos you took of yourself naked.

Here's how to secure your backups with a private password:
1. Open Crashplan's desktop application
2. Go to **Settings**
3. Go to the **Security** tab
4. Under archive encryption, select 448-bit (or 128-bit) encryption + password
5. Enter a *different* password, make it long - 20 characters or more
6. **Do not forget this password**

If you forget the password you won't be able to restore backups, defeating the whole point. Read the (as yet unwritten) lazy guide to passwords for help with managing your passwords.

When you are done, perform a backup, and then test that it has worked by pretending that your hard drive has died. Restoring some of the files and check that they are ok. You don't want the first test of your backup system to be when you really need it, because if it doesn't work then, you're fucked.

About this document
===================
This document is licensed under a Creative Commons Attribution-ShareAlike 3.0 Unported License.  
Last changed October 2012  
Authors:  
* [Daniel Kinsman](https://danielkinsman.wordpress.com/)