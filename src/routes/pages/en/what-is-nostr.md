---
title: Censorship-resistant publishing for the web
description: Nostr is a simple, open protocol that enables truly censorship-resistant and global value-for-value publishing on the web.
---

## What is Nostr?

Nostr stands for "Notes and Other Stuff Transmitted by Relays". Like HTTP or TCP-IP, Nostr is a protocol; an open standard upon which anyone can build. Nostr itself is not an app or service that you sign up for.

Nostr is designed for simplicity and enables censorship-resistant and globally decentralized publishing on the web. Let's unpack that a little:

### Simple

The protocol is based on very simple & flexible `Event` objects (which are passed around as plain JSON) and uses standard public-key cryptography for keys & signing. This makes it easy to run relays and build clients and ensures that the protocol can be extended over time.

### Resilient

Because Nostr doesn't rely on a small number of trusted servers for moving or storing data, it's very resilient. The protocol assumes that relays will disappear and allows users to connect & publish to an arbitrary number of relays that they can change over time.

### Verifiable

Because Nostr accounts are based on [public-key cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography) it's easy to verify messages were really sent by the user in question.

### Don't take my word for it

Here's [Uncle Bob](https://primal.net/profile/npub19mun7qwdyjf7qs3456u8kyxncjn5u2n7klpu4utgy68k4aenzj6synjnft) giving a great overview of how Nostr works and why it matters.

<iframe width="650" height="366" src="https://www.youtube-nocookie.com/embed/ssNkOMx2E5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
