<p align="center">
  <img src="static/logo.png" width="100" alt="sigil.png">
</p>

# VoidNote

[README.md](https://github.com/user-attachments/files/23010561/README.md)


VoidNote is a small web project built around encrypted, self destructing “notes.”  <img width="1024" height="1024" alt="sigil" src="https://github.com/user-attachments/assets/e22ffc30-9c28-40e9-87eb-c7c17e429f7b" />

It is simple, private, and built during a one week deep dive after reading *Python Cryptography* by Anish Nath (2018)

### what it is for
honestly it can be anything from passing along a password to letting a friend borrow your Steam account so they can finally play Resident Evil,  
to a private journalist transferring fragile material without leaving a trace.  
use it when you want a message to exist only long enough to do its job, then vanish. >_>

### how it works
you write → it encrypts → it gives you a link → they open it once → it burns.  
you can add a passphrase, require two keys to unlock, or just let the system handle it.

### reminder
if i were you i would not use this for illegal stuff not out of moral policing,  
but because most browsers are packed with trackers and weak extensions that leak data before you even blink.  
(none of this is encouragement for bad behavior, it is just practical advice.)

---

built with flask, curiosity, and a serendipitous desire to learn more about browser client side encryption (yes I had to look up serendipitous in order to use it). ¬_¬
