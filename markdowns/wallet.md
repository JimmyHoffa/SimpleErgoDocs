# Ergo Wallet

An Ergo wallet is in fact, **not a wallet at all**.

###### tl;dr any ergo wallet with the same recovery phrase may access the same blockchain funds, because wallets hold keys, not funds

---
### What?

It's important to understand, there are two things often said about an Ergo wallet:

 - You should have one, and use it to hold your funds
 
 - Your funds, tokens, everything in your wallet, is on the blockchain
 
These two statements cause frequent confusion, because how can my funds be in my wallet and on the blockchain?
Why do I need a wallet?
 
---
### Your funds are on the blockchain

This statement is completely true, and one you can really rely on.

The best way to understand the Ergo blockchain's management of your funds, is to imagine the Ergo
blockchain as a huge self-storage building.

<img src={require("./self-store.jpeg").default} width="399" height="600" alt-text="SAFEW github" />

Now, if you have created a "wallet", you have a space in the Ergo blockchain for your stuff!
That address, or the multiple addresses, which you know go with your "wallet"? Those are addresses
to your storage locker on the blockchain!

---
### If my wallet doesn't hold funds, what does it do?

If you go into a self-storage building, and rent your own storage space, you can't just open 
anyone's locker, right? They all have locks, different locks, which require different keys.

In the Ergo blockchain, it is the same, **a wallet app simply holds a key to your storage space**.

When creating a wallet for Ergo, you are presented with a long string of words and told in 
bold terms **"Don't ever let anyone know this at all!"**, that's because that string of words 
creates the key to your storage space on the Ergo blockchain.

#### With that same string of words, any Ergo wallet can then unlock and access your space on the blockchain

---
### Conclusion and purpose

I wrote this in hopes to help people feel more secure about changing wallets.
It is very common for people to avoid changing wallets, thinking they need to
send funds from one wallet to another. People are frequently unsure about why
they wouldn't have to do this, and when encouraged that they don't have to, are
understably worried, about losing their funds.

I hope in this explanation, I can shine a light on *why* and *how* a wallet works, to
comfort people looking at changing wallets.

---
### What wallet should I use?

There's a hand full available right now! Nautilus and SAFEW have both become very popular, as
they have proven to be very effective, fast, and useful. The Ergo Mobile wallet is also exceptionally
functional and well behaved, built and maintained by someone who's joined the Ergo team! Many of us use
it as well as SAFEW or Nautilus, as described above, they all just hold a key so you can use multiple.
**Though multiple web wallets at the same time may cause oddities in dApp connections, if you use multiple,
disable one at a time**. New developments are coming out all the time though, Ergo community has built more
and will continue to.

**I personally cannot recommend Yoroi, it has fallen into disrepair unfortunately and
due to its poor performance, and spotty behaviour, it tends to leave people thinking
Ergo is disfunctional. I assure you it is not, and sternly suggest not using Yoroi**

 - [Nautilus Quickstart](https://docs.ergodex.io/docs/user-guides/nautilus-quick-start "Nautilus Quickstart") - [<img src={require("./GitHub-Mark-Light-32px.png").default} width="20" height="20" alt-text="Nautilus github"/>](https://github.com/capt-nemo429/nautilus-wallet/)
 - [SAFEW Quickstart](https://www.youtube.com/watch?v=4ZEIcr0udkI "SAFEW Quickstart") - [<img src={require("./GitHub-Mark-Light-32px.png").default} width="20" height="20" alt-text="SAFEW github" />](https://github.com/ThierryM1212/SAFEW/)
 - [Ergo Mobile](https://ergoplatform.org/en/mobile_wallets/)
 - [Minotaur Wallet](https://github.com/minotaur-ergo/minotaur-wallet "Cross-platform wallet")
