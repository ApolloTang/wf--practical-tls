# Anti-Replay and Non-Repudiation



**replay** is an action when client replay a previous sent legit message (eg: increase my account by $100).  

**anti-replay** is a mechenicm where a message is stamp with a unique id so that the receiver can track if a message has been received before.

anti-replay is built in to TLS/SSL because of its **Integrity** via **hashing** and **Authentication** using **PKI**



Non-repudiate means `one can not refuse to have anything to do with`

Non-repudiation in security context means `sender cannot later deny having sent a message`.  This is possible because the TLS/SSL guarantee:

- message has not been tempered (data integrity) 
- authenticy of the message (we know the original sender of the message). 
  