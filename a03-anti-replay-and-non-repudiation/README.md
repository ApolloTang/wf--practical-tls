# Anti-Replay and Non-Repudiation



**replay** is an action when a client resend an already sent legit message (eg: increase my account by $100 repeatedly).  

**anti-replay** 

- prevent resending of an already sent a legit message.  
- This is achieved by stamping the message with an **unique id** so that the receiver can check if a message with the same id has been received before. 
- In order to replay the message, the pepetrater must set a new unique id in the message, but this is imposible because TLS/SSL's data integrity guarantee that message cannot been tempered. 



---

**Non-repudiate** means `one can not refuse to have anything to do with`

Non-repudiation **in security context** means `sender cannot later deny having sent a message`.  

The TLS/SSL prevent sender deny having sent a message, because we can always trace who the message is from via of authenticy of the message.

