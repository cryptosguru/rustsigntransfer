# Block chain with amount transfers 

All this talk about blockchains saving the digital world from integrity
problems made me want to dig into the workings of it. I use Secp265k1 crypto
to sign transfers. I was inspired by [SavjeeCoin](https://github.com/Savjee/SavjeeCoin) and 
the YouTube series explaining the basics of how a blockchain works.
Instead of JavaScript, I implement this in Rust.
 
My key insights:

* It is not so much about the algorithm itself
  * once it has been revealed; one can make multiple chains by copying the algorithm.

* Value is mimetic; you want what others want.
  * Take part in this or that blockchain does not really matter, unless it is *the one many people wants to be part of too*. 

* Desire is mimetic
  * Once you recognize what others want, to take a stake in a blockchain, your desire for the same is invoked.

* Proof of work is brute force
  * Not as sophisticated as one might think, it is just hash value checking after incrementing a value.


