# Block chain with amount transfers 

All the talk about blockchains made me want to dig into the workings of it. I use Secp265k1 crypto
to sign transfers.
Instead of JavaScript, I implement this in Rust.
 
My key insights:

* It is not so much about the algorithm itself
  * once it has been revealed; one can make multiple chains by copying or modifying the algorithm.

* Desire is mimetic; people desire what others desire.
  * Take part in this or that blockchain does not really matter, unless it is *the one many people wants to be a part of too*. 
  * Once people recognize what others want, to take a stake in a certain blockchain, their own desire for the same is invoked.

* Proof of work is brute force
  * Not as sophisticated as one might think, it is just hash value checking after incrementing a value.

* A private secp265k1 key is pretty safe
  * There is no sophisticated way to solve for the private key. There exists some, but only if the key is used multiple times. One has to resort to brute force, which takes an unreasonable amount of time.
  
  * Even if it was brute forced, values are transferred from key-pair to key-pair, so they move.
