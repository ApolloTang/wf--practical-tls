# Anti-Replay and Non-Repudiation



**replay** is an action when client replay a already sent legit message (eg: increase my account by $100 repeatedly).  

**anti-replay** prevent resending of a legit message.  This is achieved by stamping the message with an **unique id** so that the receiver can track if a message has been received before. In order to replay the message, the peretrater must insert a new  unique id into the message, but this is imposible because  TLS/SSL's data integrity guarantee that message cannot been tempered. 

---

**Non-repudiate** means `one can not refuse to have anything to do with`

Non-repudiation **in security context** means `sender cannot later deny having sent a message`.  This is possible because the TLS/SSL guarantee:

- message has not been tempered (data integrity) 
- authenticy of the message (we know the original sender of the message). 

