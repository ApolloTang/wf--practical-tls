# Anti-Replay and Non-Repudiation



**replay** is when a client resends an already sent legit message (e.g., repeatedly increase my account by $100).  

**anti-replay** 

- prevent resending of an already sent legit message.  
This is achieved by stamping the message with a unique ID so that the receiver can check if a message with the same ID has been received before. 
- In order to replay the message, the perpetrator must set a new unique ID in the message, but this is impossible because TLS/SSL's data integrity guarantees that a message cannot be tempered. 

---

**Non-repudiate** means `one can not refuse to have anything to do with.`

Non-repudiation **in security context** means `sender cannot later deny having sent a message.`  

Due to TLS's authenticity guarantee, the sender cannot deny having sent the message.

